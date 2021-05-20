#### 작업예정.
- 1달간은 UI 계속진행(vS code) 하면서,
- 피곤할때 자바|스프링 - (이클립스-egov전자정부프레임워크개발환경) 기본언어실습진행.
- 피곤할때, 오라클DB(SQL디벨러퍼개발환경) Ansi-SQL(표준SQL)기본언어실습진행CRUD.
-2달째부터, 주로 스프링으로 실습이 진행 (납품용-이력서포트폴리오용).

#### 20210520(목) 작업.
- 메인페이지 시간이 걸리는 부분(프런트엔드): 메뉴처리, 슬라이딩처리OK.
- 메인페이지 시간이 걸리는 부분(백엔드): 최근갤러리, 공지사항 DB데이터를 출력하는 부분
- 보통 1주일정도 걸립니다.
- 카멜표기법(낙타등표기법 예, bbsListTbl),_표기법(예, .bbs_title) 
- href: hypertext referance (웹문서 참조)
- 정적(static) 콘텐츠: html, css, js
- 동적(dynamic) 콘텐츠: jsp(java스프링), py(python장고), PHP, C#(닷넷), Nodejs(익스프레스)
- 오후에 자바(스프링) 개발환경 설치예정.(이클립스:전자정부표준프레임워크의 개발환경을 설치)
- 모바일 서브페이지 CSS 스타일처리
- 테블릿+PC용 CSS 스타일처리
- 테블릿+PC용 CSS 스타일처리
- 모바일 게시판페이지(CRUD) CSS 처리
- 모바일+테블릿+PC 댓글 CSS+jQuery+부트스트렙 처리
- AdminLTE(부트스트렙기반템플릿-반응형)를 이용해서 관리자단 디자인 만들기
- UI디자인 끝 ------------------------------------------
- UI구현 시작 --------------- 스프링프로젝트 시작(자바+이클립스+오라클+스프링)
- UI구현 ..... 위 에서 제작한 UI디자인 이용해서 프로그램을 입히게 됩니다.

#### 20210518(화)작업

- 테블릿 메인 CSS 스타일처리, PC용 메인 CSS 스타일처리
- 반응형 페이지의 핵심기술은 미디어쿼리 명령어 사용 + 가로크기를 % 로 지정(px고정크기가 아닌 비율로 내부 컨텐츠 크기를 지정하는 방법)
- 미디어(PC화면, 스마트폰화면, 테블릿화면) + 쿼리(질의어-질문)
- @medie 미디어타입(screen, print 등등=all) and (min-width: 801px) {구현내용}
- 배치1: jQuery코어 임포트 이후 에 사용자가 지정한 js 배치를 해야함.
- 배치2: reset.css, mobile.css 임포트 이후에 tablet.css, pc.css 배치해야 레이아웃이 깨지지 않습니다.

#### 20210517(월) 작업
#### 작업예정 : jQuery 제이쿼리 JSON 데이터 파싱
- 외부 data.js 파일에서 json데이터를 저장한 후 html에서 불러와서 파싱.
- 외부 사이트에서 제공하는 (RestAPI서버)json데이터를 html에서 불러와 파싱.
- RestAPI서버 중 코로나19 확진자데이터를 받아서 html에서 파싱(데이터를 분해해서 화면에 뿌려주는 작업) 
- ResAPI서버주소(빅데이터): http://coroname.me/getdata
- 수업시작전, jsonData 파싱부분에서 append 사용에 2번 반복되는 부분 확인OK.
- 메인페이지에 자바스크립트(jQuery)적용.(VS code+HTML5+CSS+jQuery)
- 제이쿼리적용부분: 메뉴, 슬라이드이미지3개 처리 : 모바일 메인페이지만 마무리
- 보통 이니지 슬라이드 처리는 외부 라이브러리(Lib) 사용(니보슬라이드, 캐러셀슬라이드)
- 외브Lid 사용않하고, 우리가 만들어 봅니다.Ok


#### 20210514(금) 작업
- 구분오류 : syntex 신텍스(사인텍스)오류(문법오류)
- CSS3, HTML : 검사기준입니다.
- 사용자단 모바일 메인페이지 footer영역 CSS입히기.
- top상단이동 OK.
- 과제를 제출 준비
- jQuery Json 데이터 피싱 실습
- 8교시에 과제물 다음카페로 제출

#### 20210513(목) 작업내역
- 픽사베이에서 받은 이미지 3개: 로고1, 슬라이드 이미지1, NoImage 1 받고, 경로 적어놓기
- 로고: https://pixabay.com/ko/photos/%EA%B0%9C%EC%9A%94-%EC%95%84%ED%8A%B8-%EC%98%88%EC%88%A0-%EC%98%88%EC%88%A0-%EC%9E%91%ED%92%88-2675672/
- 슬라이드이미지: https://pixabay.com/ko/photos/%EB%B3%B4%EA%B8%B0-bergsee-%EC%9D%80%ED%96%89-%EA%B0%9C-1844110/
-no_img: https://pixabay.com/ko/vectors/%ED%94%8C%EB%9E%98%EA%B7%B8-%EB%8C%80%ED%95%9C%EB%AF%BC%EA%B5%AD-%EA%B5%AD%EA%B8%B0-%EB%8C%80%ED%95%9C%EB%AF%BC%EA%B5%AD-3029663/ 
- 작업폴더를 나누는 이유: 시청(관공서), 대학, 기업의 웹프로그램(사이트)
  제작 할때, 1년간 무상 유지보수 이후 보통 2천, 리뉴얼 4천 비용이 책정
- home폴더 기존작업률, 리뉴얼 home에 덮어쓰는 방식이 아니고,
- 리뉴얼 할떄 home2022 폴더에 작업을 하시게 됩니다.
- 제이쿼리 코어 다운받기: min버전(압축-속도up), 일반버전(개발-속도Normal)
- jQuery 미처리 작업은 다음주하고,
- 오늘부터는 모바일 메인페이지 1개 만들어서 과제물로 제출 -> 스프링에서
  프로그램 입히는 소스로 사용하게 됩니다.
- 애니데스크(독일산): 팀뷰어(독일산) 사용하는 대신에 애니데스크를 사용.
- html5.html, css.html, js.html 여기까지
- jQuery 기본구조만 실습했습니다.

#### 20210512(수) 작업내역
- git clone 으로 프로젝트를 가져온 경우 아래 내용을 추가해 주셔야합니다.
- git config --list 확인에서 user.name, user.email 
- 터미널에서 아래 2가지 실행
- git config --local user.name 영문이름
- git config --local user.email 영문이메일
- 프로젝트를 1명이 제작하는 경우가 없기 때문에, 2명일때 소스 수정한 사람 확인용 정보보기

#### 20210511(화) 작업내역
- 로렘 입숨 한글URL:
- 로렘 입숨 영어URL:
- URL경로(path)://test/htmls.html
- html5의 레이아웃 구조 제작합니다.
- 서버(응답하는프로그램=response) = 아파치서버, 톰캣서버
- 클라이언트(요청하는프로그램request) = 웹브라우저
- html은 마크업이 태그로 구성됩니다. <의미있는문자>...</의미있는문자>
  http//127.0.0.1:80[8080][9000][5500][6500]
- pc의 네트워크 내부주소(공통):127.0.0.1 == localhost
- yahoo.com(도메인) == 74.6.143.25(IP주소) == 주민번호
- IP주소버전: IPv4, IPv6
- html도 버전: html5, html4.01(old)


#### 20210510(월) 작업내역
- 업로드절차: 1. 커밋(commit) 2. 푸시(push)<br>
- 다운로드절차: 1. 풀(full) : 교실에서 작업한 결과를 집에서 이어서
  작업할 상황<br>
- 레포지토리(저장소) 초기화: git init<br>
  개발PC(html) 와 깃 저장소와 연결시킵니다.<br>
- 포트(port): 포트번호로 서비스를 만드는것이 트렌드<br>
- 이전에는 80포트에 모든 서비스 묶어놓았습니다.<br>
- 모든서비스를 개별로 분라하는 트렌드가 있습니다.:<br>
  마이크로서비스라고 합니다. == RestAPI로 구현이 됩니다.<br>
- 도메인(hrrps://naver.com:1451241/네이버 인증서비스 개발)<br>
- 외부 인원(네이버직원아닌) 위 포트기준으로 제작한 서비스를 갖다가 사용<br>
- html : Hyter Text MarkUP Language 태그를 사용하는 언어<br>
- md : MarkDown Language 태그를 사용하지 않는 언어<br>