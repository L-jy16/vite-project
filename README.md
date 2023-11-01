# vite를 이용한 포트폴리오 사이트 만들기

## vite를 사용하는 이유
Vite는 JavaScript 애플리케이션을 개발하고 위한 빠르고 경량화된 도구입니다.
Vite는 빠른 개발 속도, ES 모듈 사용, 다중 언어 지원, 플러그인 확장, Vue.js 및 React 지원, 테스트 환경, 코드 스플릿팅, 간단한 설정으로 인해 인기 있는 JavaScript 개발 도구입니다.
[vite](https://ko.vitejs.dev/guide/)

1. 빠른 개발 속도: Vite는 빠른 개발 속도를 제공합니다. 개발 서버가 모듈 기반 빌드를 지원하며, 코드 변경이 발생할 때 필요한 모듈만 다시 빌드하므로 개발 환경에서 빠른 리로드를 가능하게 합니다.

2. ES 모듈 사용: Vite는 기본적으로 ES 모듈(ESM)을 사용하며, 이는 브라우저에서 모듈을 로딩할 때 사용되는 표준 방법입니다. 이를 통해 모듈을 더 효과적으로 관리하고 코드 번들의 크기를 줄일 수 있습니다.

3. 다중 언어 지원: Vite는 다양한 언어(JavaScript, TypeScript, CSS, JSON, HTML 등)를 지원하며, 이러한 언어들을 하나의 애플리케이션에서 함께 사용하는 것이 쉽습니다.

4. 플러그인 생태계: Vite는 다양한 플러그인을 지원하며, 이를 통해 프로젝트에 필요한 기능을 확장할 수 있습니다. 예를 들어, CSS 전처리기 지원, 이미지 최적화, 번들 최적화 등을 플러그인으로 추가할 수 있습니다.

5. Vue.js 및 React 지원: Vite는 Vue.js와 React와 같은 인기 있는 프론트엔드 프레임워크를 지원하며, 이러한 프레임워크와 함께 사용할 때 뛰어난 성능을 제공합니다.

6. 테스트 환경: Vite는 테스트 환경을 지원하며, Jest, Mocha, 등 다양한 테스트 러너와 통합할 수 있습니다.

7. 코드 스플릿팅: Vite는 코드를 자동으로 스플릿팅하여 페이지 로딩 시간을 최소화하고 초기 번들 크기를 줄일 수 있습니다.

8. 가볍고 간단한 설정: Vite는 간단한 설정 파일을 가지고 있으며, 초기 설정을 빠르게 구성할 수 있습니다.

## 트러블 슈팅
<details>
<summary>git 업로드 버그</summary>
권한으로 인한 업로드 버그 현상이 생김 > 해결
- git 업로드 설정 : 
1. The requested URL returned error: 403 Pushing to ... 에러 내용
2. git remote -v
3. git remote set-url origin https://[Your-Name]@github.com/[Your-Name][repo-name].git
    예제. git remote set-url origin h나의 ttps://L-jy16@github.com/L-jy16/vite-project.git
나의 4. git remote -v
h나의 ttps://[Your-Name]@github.com/[Your-Name][repo-name].git 나의 리스트가 뜨는지 확인
5. git push -u origin master
6. 패스워드 입력하라는창이 나오면 패스워드 입력
7. VS code 재시작하고 다시 push하기
</details>