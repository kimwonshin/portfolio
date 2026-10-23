# 신유원 포트폴리오

AI · Computer Vision 포트폴리오 정적 웹사이트입니다.

## 사이트 수정 및 배포

사이트 주소: https://kimwonshin.github.io/portfolio/

`dist/` 안의 HTML, CSS와 이미지를 수정한 뒤 변경을 커밋하고 아래 명령으로 배포합니다.

```sh
git push origin main
git subtree push --prefix dist origin gh-pages
```

저장소의 **Settings → Pages → Build and deployment → Source**는 **Deploy from a branch**, 브랜치는 **gh-pages**, 폴더는 **/ (root)**로 설정합니다.

별도 빌드 과정이나 패키지 설치는 필요하지 않습니다. 로컬 확인 시 `dist/`를 정적 웹 서버로 실행합니다.
