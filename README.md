# Scientific Calc

브라우저에서 실행되는 공학용 계산기 (HTML/CSS/JS + Math.js v15.2.0).

## 주요 기능
- 사칙연산, 괄호, 거듭제곱, 제곱근, 로그, 팩토리얼, 백분율
- DEG/RAD 전환이 가능한 삼각함수 및 역삼각함수
- Ans, π, e, 지수 표기(E), 계산 기록(브라우저 로컬 저장소)
- 모바일/데스크톱 반응형 UI, 키보드 입력

## 실행
`index.html` 파일을 브라우저에서 엽니다. Math.js는 외부 CDN에서 제공되므로 인터넷 연결이 필요합니다.

## GitHub Pages 배포
1. GitHub에서 **Public** 저장소 `scientific-calculator`를 만듭니다.
2. 압축파일을 해제한 다음, `index.html`, `README.md`, `.nojekyll` 파일을 저장소 최상위에 업로드하고 커밋합니다. ZIP 자체를 업로드하면 안 됩니다.
3. **Settings > Pages > Build and deployment**에서 **Deploy from a branch**를 선택합니다.
4. Branch **main**, folder **/(root)**를 선택해 **Save**합니다.
5. 페이지에 표시되는 **Visit site** 버튼으로 접속합니다. 기본 URL은 `https://<username>.github.io/scientific-calculator/` 형태입니다.

## 주의
- 계산기 코드는 사용자 브라우저에서 실행됩니다. 별도 백엔드나 데이터베이스가 없습니다.
- 계산 기록은 사용자의 브라우저에만 저장됩니다.
- 입력 길이와 사용 가능한 함수가 제한되어 있지만, 공개 사용자가 임의 수식을 입력하는 경우 추가 보안 및 성능 검토를 권장합니다.
- 인터넷 연결이 끊기면 Math.js CDN을 불러오지 못할 수 있습니다.
- 일반 계산 용도이며 안전·품질·인증 업무에서는 별도로 검증된 계산기를 사용하세요.

## 사용 라이브러리
- Math.js 15.2.0 (Apache-2.0): https://mathjs.org/
- GitHub Pages 문서: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
