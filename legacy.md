# Portfolio - 이전 직장 프로젝트

## [[2017] 뉴키 - Comic Viewer Renewal](https://github.com/thesoncriel/php.mvc/tree/master/ui-etype)
(주) 제이웨이의 ActiveX 뷰어를 웹표준으로 변경 시킨 것.  
웹표준 모드와 플래시 모드를 자체적으로 갖추어 최신 브라우저부터 구형 브라우저까지 폭넓게 지원한다.  
웹런처와 통합되어 있다.

### 사용기술
- PHP 5.3
- MySQL 5.7
- knockout
- jQuery
- SASS (IE css hack 포함)
- HTML5 - FileAPI (DRM 해석용)
- FLEX3 (DRM 해석용)
- Grunt (빌드 및 최적화)

![](https://github.com/thesoncriel/php.mvc/blob/master/screenshots/comicviewer.png)


## [[2016] VODS - Web Launcher UI](https://github.com/thesoncriel/php.mvc/tree/master/ui-etype)
(주) 제이웨이의 웹UI를 SPA 방식으로 새로 만들어 최적화 시킨 것.  
기본적으론 외부 C++ Windows Application과 통신하여 동영상 플레이어를 제어 한다.  
유지보수와 속도를 위해 모듈화와 Promise 패턴을 적용 시키고 Grunt 를 통해 빌드하고 압축(minify) 하는 일련의 작업을 할 수 있도록 구성 하였다.  
또 한 Allat 및 쿠폰 결제 시 이용되던 ActiveX도 웹표준 방식으로 바꾸어 사용자 환경과의 호환성을 높였다.  
백엔드는 자체적으로 만든 MVC 라이브러리를 적용 하였다.

### 사용기술
- PHP 5.3
- MySQL 5.7
- requireJS (AMD 적용 - 단, build 하면 js가 하나의 파일로 합쳐지기에 순수 모듈 관리 용으로 쓰임)
- knockoutJS
- sammyJS (클라이언트 측 RESTful 적용. 일부 확인된 버그 수정)
- jQuery
	- tinyscrollbar (우측 스크롤 기능으로 사용. 일부 확인된 버그 수정)
- placeholders (input 요소의 placeholder 기능을 IE8 이하에서 적용되도록 지원)
- swfobject 
	- FLEX3 (코믹 뷰어의 Image Component 적용. IE9 이하 전용)
- SASS (compiler: koala)
	- Background Image Sprite 적용
	- IE Hack 적용
- Grunt (프로젝트 빌드 및 이용 파일 복사, 테스트 시 watch로 업로드 병행)
- node.js (패키지 관리용)

![](https://github.com/thesoncriel/php.mvc/blob/master/screenshots/003.png)
![](https://github.com/thesoncriel/php.mvc/blob/master/screenshots/004.png)
![](https://github.com/thesoncriel/php.mvc/blob/master/screenshots/005.png)


## [[2016] MNG - VODS 관리자 사이트](https://github.com/thesoncriel/php.mvc/tree/master/mng)
(주) 제이웨이의 VODS UI 서버 관리를 위한 것.  
원래 여러기의 서버가 운영되며 각기 별도의 DB와 웹소스를 지녀서 관리가 불편했던 점을 개선하기 위해 만들어졌다.  
등록된 가맹점 검색과 옵션 설정, 캐시관리 등의 기능이 포함되어 있다.

### 사용기술
- PHP 5.3
- MySQL 5.7
- AngularJS & UI-Router
- jQuery
- Bootstrap
- LoDash (상영내역조회 에서 자료 요약 시 쓰임)

![](https://github.com/thesoncriel/php.mvc/blob/master/screenshots/011.png)
![](https://github.com/thesoncriel/php.mvc/blob/master/screenshots/012.png)
![](https://github.com/thesoncriel/php.mvc/blob/master/screenshots/014.png)


## [[2016] ONS - Mobile](https://github.com/thesoncriel/java.mvc/tree/master/mb/spa)
(주) 제이웨이의 지사 업무용 모바일 사이트다.  
자체 MVC 라이브러리를 만들어 필요에 따라 사용하였으며 AngularJS를 통한 SPA로 구동되게끔 하였다.

### 사용기술
- JAVA 1.5
- Oracle 10G
- AngularJS & UI-Router
- jQuery
- Bootstrap

![](https://github.com/thesoncriel/java.mvc/blob/master/screenshots/002.png)
![](https://github.com/thesoncriel/java.mvc/blob/master/screenshots/004.png)
![](https://github.com/thesoncriel/java.mvc/blob/master/screenshots/005.png)
![](https://github.com/thesoncriel/java.mvc/blob/master/screenshots/007.png)


## [[2015] ITM - Mobile](https://github.com/thesoncriel/itm.mobile)
캐럿글로벌에서 B2B 업무에 이용되는 ITM 솔루션을 모바일 버전으로 SPA 방식으로 리뉴얼 작업 한 것.  
전체적인 업무는 크게 강사(Tutor)와 학생(Member)로 나뉘며 이 둘은 클래스 목록, 상세 및 그에 따른 세부 정보와 출결 정보를 보여줄 수 있도록 하였으며, 클래스 커뮤니티(Class Community)라 불리는 일종의 게시판을 클래스마다 별도로 운영하기에 이에 대한 링크 및 부가 기능이 담겨 있다.

### 사용기술
- PHP 5.3
- Oracle 10G
- jQuery
- AngularJS & UI-Router
- AmChart

![](https://github.com/thesoncriel/itm.mobile/blob/master/screenshots/001.png)
![](https://github.com/thesoncriel/itm.mobile/blob/master/screenshots/002.png)
![](https://github.com/thesoncriel/itm.mobile/blob/master/screenshots/003.png)


## [[2015] IELTS](https://github.com/thesoncriel/ielts-ci)
캐럿글로벌에서 제작했으며, 아이엘츠라 불리는 영어 시험을 간단하게 수행하고 그 결과를 출력해 주는 사이트.  
이전에 만들다 만 것을 이어서 작업하라는 요청이었지만, 도저히 이어할 수 있는 수준의 퀄리티가 아니라서 아예 CI 및 Bootstrap 기반으로 다시 만들었다.

### 사용기술
- PHP 5.5
- CodeIgniter 3
- jQuery
- Bootstrap
- requireJS
- MediaElementJS (IE8 이하에서 audio 태그 적용을 위함)

![](https://github.com/thesoncriel/ielts-ci/blob/master/screenshots/001.png)
![](https://github.com/thesoncriel/ielts-ci/blob/master/screenshots/002.png)


## [[2014] 시대고시 모바일 사이트](https://github.com/thesoncriel/sdmobile/tree/master/src)
Frontend Framework 인 KnockoutJS를 접목 시켜 보았다.  
더불어 Client 측 RESTful 환경을 구축하고 requireJS를 통하여 JS 모듈화를 본격적으로 적용시켰으며 SASS를 함께 활용하는 등 Frontend 개발자로서의 역량이 본격적으로 시작된 의미있는 프로젝트 였다.

### 사용기술
- PHP 5.3
- MySQL 5.1
- jQuery
- Bootstrap
- knockoutJS
- Sammy (RESTful 용도)
- RequireJS (AMD 용)
- SASS

![](https://github.com/thesoncriel/sdmobile/blob/master/screenshots/001.png)
![](https://github.com/thesoncriel/sdmobile/blob/master/screenshots/002.png)
![](https://github.com/thesoncriel/sdmobile/blob/master/screenshots/003.png)
![](https://github.com/thesoncriel/sdmobile/blob/master/screenshots/005.png)


## [[2014] 강의출결평가](https://github.com/thesoncriel/hanlecture/tree/master/WebContent)
한양대학교 재활의학과 의뢰로 제작 되었으며, 회원/강의 관리 기능과 원격 강의 출석/평가 및 그 데이터를 이용한 통계를 출력 해 주는 기능을 포함하고 있다.  
교수측이 출석을 진행 하기 전엔 학생측에선 출석이 불가하며, 평가되는 질문 내용을 설문지처럼 임의 설정이 가능하도록 하였다.  
사내 프레임워크 2.0을 기반으로 제작.

### 사용기술
- Java 1.6
- Struts2 & myBatis
- jQuery & jQuery-Mobile
- MySQL 5.5

![](https://github.com/thesoncriel/hanlecture/blob/master/screenshots/001.png)
![](https://github.com/thesoncriel/hanlecture/blob/master/screenshots/002.png)
![](https://github.com/thesoncriel/hanlecture/blob/master/screenshots/003.png)


## [[2013] POB Mall](https://github.com/thesoncriel/pobmall/tree/master/WebContent)
모바일 스피커 케이스인 POB 의 쇼핑몰 사이트다.  
사내 프레임워크 2.0을 기반으로 제작 되었으며 media-query를 이용하여 모바일 및 태블릿 기기에도 잘 보일 수 있도록 하였다.

### 사용기술
- Java 1.6
- Struts2 & myBatis
- jQuery & jQuery-UI
- MySQL 5.5
- CSS3: media query 적용
- 카드 및 계좌이체등 결제 모듈 적용

![](https://github.com/thesoncriel/pobmall/blob/master/screenshots/001.png)
![](https://github.com/thesoncriel/pobmall/blob/master/screenshots/002.png)
![](https://github.com/thesoncriel/pobmall/blob/master/screenshots/003.png)


## [[2013] 힐링업 365 (K-Wellness)](https://github.com/thesoncriel/heal365/tree/master/WebContent)
(주)네안플러스의 운동영상 스트레칭 기획을 바탕으로 제작된 헬스케어 솔루션 이다.  
의료기관, 회원, 영상 및 조합영상 관리 기능이 있으며, 이를 바탕으로 운동 처방전을 내려 환자가 영상을 따라하며 자가 진단/치료를 할 수 있도록 도와준다.  
사내 자체 프레임워크를 만들어 적용 하였다.

### 사용기술
* Java 1.6
* Struts2 & myBatis
* jQuery & jQuery-UI
* MySQL 5.5
* MediaElementJS 적용
	- HTML5의 Video Tag를 IE8 이하에서도 지원 하기 위함.
* TrimPath
	- 클라이언트 측 템플릿을 이용할 목적으로 쓰임. JavaScript Library.
	
![](https://github.com/thesoncriel/heal365/blob/master/screenshots/001.png)
![](https://github.com/thesoncriel/heal365/blob/master/screenshots/002.png)
![](https://github.com/thesoncriel/heal365/blob/master/screenshots/003.png)
![](https://github.com/thesoncriel/heal365/blob/master/screenshots/004.png)


## [[2012] 국시원 영문 홈페이지](https://github.com/thesoncriel/kuksiwon)
국시원에서 웹표준 및 웹접근성을 준수하는 영문 홈페이지 제작 의뢰를 받아 만들게 된 것.  

### 사용기술
* C#.NET
* ASP.NET
* 보안 관계상 DB Access가 불가하여 게시판이 필요한 부분엔 XML로 대체함.
* IE8 이하에서 디자인 시안과 동일한 출력을 하기 위해 CSS3 PIE 를 이용함.
	- CSS3의 Rounded-Corner 및 Gradient 출력
	
![](https://github.com/thesoncriel/kuksiwon/blob/master/screenshots/001.png)
![](https://github.com/thesoncriel/kuksiwon/blob/master/screenshots/002.png)


## [[2012] 동반성장위원회 홈페이지](https://github.com/thesoncriel/winwin)
메인 페이지를 리뉴얼하고 각종 컨텐츠 페이지를 정리하는 작업을 하였다.  

### 사용기술
* Java 1.5
* Spring
* iBatis
* jQuery

![](https://github.com/thesoncriel/winwin/blob/master/screenshots/001.png)
![](https://github.com/thesoncriel/winwin/blob/master/screenshots/002.png)


## [[2012] Ilhwa TM - 파이프 생성 라인 관리기](https://github.com/thesoncriel/ilhwa.tm/tree/master/Ilhwa_TM_Renewal)
Ilhwa Stainless 의 파이프 생성 공정 라인에서 쓰이는 프로그램을 새로 만든 것.  
이전 버전의 SW는 한 곳(View) 에서 다수의 테이블 내용을 끌어다 썼기 때문에 느린건 둘째치고 코드가 상당히 복잡 했다.  
그래서 자체적으로 MVC 및 SQL Mapper를 만들어서 적용하고 이것으로도 넘치는 추가 요청사항이 많아서 중간에 엑셀(xls) 파일에 Model 측 설정 기능을 넣어 엄청나게 추상화를 시켰었다.

### 사용기술
* C#.NET 3.5 WinForm (GDI+)
* MVC Pattern 적용
* 자체 SQL Mapper (Query Info) 제작 및 적용
* MS-SQL
* 바코드 출력 기능 (Serial Port & 템플릿 코드 분리)
* 각종 설정 기능 (레지스트리, 엑셀, XML, ini 텍스트 등)
* 터치스크린 UI 최적화 (ex: 버튼 크게 만들기 등)

![](https://github.com/thesoncriel/ilhwa.tm/blob/master/screenshots/001.png)
![](https://github.com/thesoncriel/ilhwa.tm/blob/master/screenshots/002.png)


## [[2012] Insight Viewer Renewal](https://github.com/thesoncriel/insight-viewer/tree/master/source)
기존 장비의 MS-SQL 자료와 신규 장비의 Firebird 자료를 동시에 처리하여 타 부서에서 활용할 수 있는 엑셀 자료료 출력 해 주는 프로그램.  
당시 운영 장비가 2가지가 되어 두 자료를 비교 분석할 수 있는 새로운 프로그램이 필요하게 되어 제작하게 됨.

### 사용기술
* Delphi EX2
* Fire Monkey Library
* MS-SQL Server
* Firebird 2.1
* 그래프 출력 가능

![](https://github.com/thesoncriel/insight-viewer/blob/master/screenshots/001.jpg)
![](https://github.com/thesoncriel/insight-viewer/blob/master/screenshots/002.jpg)


## [[2011] Shutter Test](https://github.com/thesoncriel/shutter-test/tree/master/source)
셔터 테스트 프로그램.  
도가니의 View Port 를 자동으로 여닫으며 설치된 카메라를 통해 출력되는 외부 프로그램과 함께 스크린샷을 남긴다.  
셔터 설정등은 지정된 Recipe 를 통해 변경 가능.

### 사용기술
* Delphi2007
* I700 Series 통신 모듈

![](https://github.com/thesoncriel/shutter-test/blob/master/screenshots/001.jpg)
