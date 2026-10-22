# CareerDNA 진로 로드맵

교육 프로그램 기획자를 꿈꾸는 대학교 1학년 학생을 위한 진로 로드맵 웹페이지입니다.
CareerDNA 강점에 맞춘 4년·8학기 계획과 진행 상황을 저장하는 첫 30일 체크리스트를 제공합니다.

## 로컬에서 확인하기

저장소 루트에서 아래 명령을 실행하고 `http://localhost:8000`을 여세요.

```sh
python3 -m http.server 8000
```

별도 패키지 설치 없이 정적 페이지로 동작합니다. 체크리스트 상태는 현재 브라우저의 로컬 저장소에 저장됩니다.

## GitHub Pages 배포

`.github/workflows/deploy-pages.yml`은 `main` 브랜치에 반영되면 `index.html`과 `reference/`를 Pages용 정적 사이트로 배포합니다. 원문 자료도 웹사이트에서 공개하기로 선택했으므로, 배포 전에 `reference/`의 내용과 개인정보를 확인하세요.

GitHub 저장소의 **Settings → Pages → Build and deployment**에서 **GitHub Actions**를 배포 소스로 선택하세요. GitHub CLI 인증이 설정된 환경에서는 `gh auth login` 후 Actions 실행과 Pages 주소를 확인할 수 있습니다.