# EVCHARGE

전기차 충전 요금표 · 계산기. 파워큐브, 환경부, 레드이엔지, E-pit, SK일렉링크, 한전 요금을 시간대(경/중간/최대부하)와 충전 속도별로 비교합니다.

- `index.html` — 단일 파일 웹 앱 (브라우저로 열면 바로 동작)
- 입력한 배터리 정보는 브라우저 localStorage에만 저장됩니다.

## 배포

`main` 브랜치에 푸시하면 GitHub Actions(`.github/workflows/pages.yml`)가 GitHub Pages로 배포합니다.
최초 1회: 저장소 Settings → Pages → Build and deployment → Source를 **GitHub Actions**로 설정하세요.
