# 부산 자율신경실조증 홈페이지

순수 HTML/CSS 정적 홈페이지입니다. 별도 설치나 빌드 없이 사용할 수 있습니다.

## 파일 구성

- `index.html`: 본문, 검색용 제목·설명·구조화 데이터
- `style.css`: PC·모바일 반응형 디자인
- `assets/theanesium.webp`: 제품 이미지
- `favicon.svg`: 사이트 아이콘
- `robots.txt`: 검색 수집 안내
- `sitemap.xml`: 사이트맵
- `.nojekyll`: GitHub Pages에서 정적 파일 그대로 제공

## GitHub 업로드

1. ZIP 파일을 압축 해제합니다.
2. GitHub 저장소를 만들고, 이 폴더 안의 파일과 assets 폴더를 저장소 루트에 업로드합니다.
3. `index.html`이 저장소 최상위에 있는지 확인합니다. 상위 폴더 자체를 업로드하지 마세요.

기존에 게시한 홈페이지의 소스 사본이며, 기존 사이트의 Git 기록이나 호스팅 설정, 인증 정보는 포함하지 않습니다.

## 다른 주소에 게시할 때

현재 검색용 주소는 기존 게시 주소 `https://busan-autonomic-guide.tinybirch1.chatgpt.site`로 설정되어 있습니다.
새 주소를 최종 운영 주소로 사용할 경우 다음 파일의 주소를 실제 공개 주소로 바꿔 주세요.

- `index.html`: canonical 링크, og:url, 구조화 데이터의 url
- `robots.txt`: Sitemap 주소
- `sitemap.xml`: loc 주소

GitHub Pages의 저장소별 주소에는 저장소 이름 경로가 포함될 수 있습니다. 예: `https://사용자명.github.io/저장소명/`.
이미지와 CSS 링크는 저장소 경로에서도 동작하도록 상대 경로로 구성했습니다.

robots.txt는 도메인 루트에 있어야 검색로봇에 적용됩니다. 저장소별 Pages 하위 경로에서는 이 파일만으로 도메인 루트 설정을 바꿀 수 없습니다.

## 내용 수정

문구와 판매처 링크는 `index.html`, 색상과 배치는 `style.css`에서 수정합니다.
제품 정보가 바뀌면 본문과 자료 확인 날짜를 함께 업데이트하세요.
