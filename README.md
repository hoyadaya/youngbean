# Youngbin Kim · Minimal Academic Homepage

간결한 영문 연구자 개인 홈페이지입니다. 프로필, 연구 관심 분야, 최근 소식, 논문 및 학력/경력 정보를 한 페이지로 제공합니다.

## GitHub Pages에 공개하기

1. GitHub에서 `<GitHub-사용자이름>.github.io`라는 **Public** 저장소를 생성합니다.
2. ZIP을 압축 해제하고 `index.html`, `style.css`, `assets/` 등 **내용물 전체**를 저장소의 최상위(root)에 업로드합니다. ZIP 파일 자체를 업로드하면 홈페이지가 표시되지 않습니다.
3. GitHub 저장소의 **Settings → Pages → Build and deployment**에서 **Deploy from a branch → main → /(root)**를 선택합니다.
4. 배포가 완료되면 `https://<GitHub-사용자이름>.github.io/`로 접속합니다.

### 원하는 주소가 `youngbean.github.io`인 경우

GitHub Pages 사용자 홈페이지 주소는 계정 이름에 따라 결정됩니다. 현재 GitHub 계정이 `hoyadaya`라면 `youngbean.github.io`는 **Custom domain** 입력란으로 변경할 수 없습니다. `youngbean`이라는 사용자 이름으로 계정을 변경할 수 있는지 먼저 확인하고, 해당 이름을 사용할 수 있다면 저장소 이름을 **`youngbean.github.io`**로 맞춰야 합니다.

계정 이름을 유지하고 싶은 경우에는 `hoyadaya.github.io`라는 저장소를 만들면 `https://hoyadaya.github.io/`로 공개할 수 있습니다.

## 홈페이지 내용 수정하기

- 프로필, 연구 관심 분야, 소식, 논문, 학력 및 경력: `index.html`
- 레이아웃, 글자 크기, 색상, 모바일 디자인: `style.css`
- 프로필 사진: `assets/profile.webp`
- 논문 그림: `assets/scv.webp`, `assets/astra.webp`, `assets/awm_tmm_fig4.png`, `assets/party.webp`, `assets/domain.webp`
- 최신 이력서: `assets/Youngbin_Kim_CV.pdf`

별도 설치나 빌드 없이 `index.html`을 직접 열어 확인할 수 있습니다. 수정한 파일을 GitHub 저장소에 다시 업로드하면 자동으로 반영됩니다.

## 공개 전 주의

이 ZIP에는 프로필 사진, 기관 이메일, CV 및 논문 그림이 포함되어 있습니다. 인터넷에 공개할 자료인지 확인한 뒤 업로드하세요. IEEE TMM 논문은 사용자 요청에 따라 Figure 4 이미지만 포함하며 논문 PDF 본문은 포함하지 않습니다.
