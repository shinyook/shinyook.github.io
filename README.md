# Shinyook blog

Astro personal blog published at https://shinyook.github.io.

## 글쓰기

1. https://app.pagescms.org 에서 GitHub로 로그인합니다.
2. Pages CMS GitHub App에 이 저장소만 접근하도록 허용합니다.
3. shinyook/shinyook.github.io 저장소의 main 브랜치를 선택합니다.
4. 글 관리에서 새 글을 작성하고 블로그에 공개를 켠 뒤 저장합니다.
5. GitHub Actions 배포가 완료되면 사이트에 반영됩니다.

**공개 저장소이므로 공개 여부가 꺼진 글과 이미지도 GitHub에서 볼 수 있습니다. 민감한 비공개 초안은 별도 개인 문서에 보관하세요.**

## 개발

Node 22 이상, `pnpm install`, `pnpm run dev`. 배포 빌드는 `pnpm run build`.

## 한국어 / English

한국어는 `/`, 영어는 `/en/`입니다. 홈 첫 방문에서 브라우저의 첫 번째 선호 언어가 한국어면 한국어, 그 외는 영어를 표시합니다. 상단 언어 버튼으로 선택한 언어를 기억합니다. 위치/IP는 수집하지 않습니다.

Pages CMS에는 한국어 글과 English posts가 분리되어 있습니다. 번역 글은 두 언어에서 파일 이름을 같게 지정하면 언어 버튼으로 서로 연결됩니다. 번역이 없으면 해당 언어의 홈으로 이동합니다. 새 글이 자동 번역되는 것은 아닙니다.
