**[개발 환경 설정]**

**크롬 브라우저**  
**아톰(Atom) 텍스트 에디터**  

- 아톰 테마
	- Win: File > Settings / Mac: Atom > Preferences 
	- install 탭
	- Themes 버튼
	- `seti-ui` / `atom-material-syntax-dark` 검색. 설치.
	- Themes 탭 UI Theme 드롭 다운 박스 클릭. Seti 선택.
	- 확인: html, css, js 파일 생성 > 확장자별 아이콘 확인.
	- Syntax Theme 도 마찬가지.

- 아톰 패키지
	- Win: File > Settings / Mac: Atom > Preferences
	- Packages 탭
	- `language-vue` 설치
	- 확인: tem 입력 후 template (Vue Component) 자동 완성 기능 확인
	- 처음 설치 시 에디터 종료 후 재실행
	- 이 외의 여러 가지 유용한 패키지. (구글: 아톰 필수 플러그인)

**노드제이에스(Node.js)**  

서버 사이드 자바스크립트 실행 환경.  
뷰 CLI 를 이용하여 쉽게 뷰 프로젝트를 구성하기 위함.  
LTS(Long Term Support), 라이브러리 호환성 관점에서 더 도움이 됨.  
[nodejs.org](nodejs.org)  
설치 파일을 설치하면 노드 패키지 매니저(NPM) 이 함께 설치됨.

- NPM: 전 세계의 자바스크립트 라이브러리르 모아놓은 공개 저장소

확인: `node -v`

**뷰 개발자 도구(Vue.js devtools, 크롬 확장 플러그인)**  

뷰로 만든 웹 앱. 디버깅/분석 용.  
크롬/파이어폭스/사파리 모두 지원.  

- vue.js devtools 검색 / CHROME에 추가
- Download the Vue Devtools extension for a better development experience:
  https://github.com/vuejs/vue-devtools, 뷰 크롬 익스텐션 다운로드 로그.
  - 서버에서 띄운 것이 아닌 파일 시스템에서 접근하여 브라우저로 실행한 파일에 뜸.
  - `file://` 로 접근한 파일과 `http://`로 접근한 파일에 대해서 뷰 개발자 도구가 각기 다른 설정을 적용하기 때문.
  - 크롬 브라우저 설정 버튼 > 도구 더보기 > 확장 프로그램 > 파일 URL에 대한 액세스 허용
  - 확인: 사라짐
- You are running Vue in development mode.
  Make sure to turn on production mode when deploying for production.
  See more tips at https://vuejs.org/guide/deployment.html
  - 현재 개발자 모드에서 뷰를 실행하고 있으니 상용화된 서비스를 하는 경우에는 상용화 모드로 전환하라는 로
  
**뷰 개발자 도구 사용 방법**

컴포넌트(상세내용/검/inspect_개발자도구 Elements 에서 html 태그로 확인)/Vuex 속성/Events/Refresh

