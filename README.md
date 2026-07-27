# LH 철근 스캔 분석 도구 (웹)

LiDAR 점군(PLY)에서 철근을 검출해 3D 모델(USDZ/OBJ)로 내보내는 단일 파일 웹 도구.

- **사용**: https://youngbrain85.github.io/lh-rebar-webtool/
- 소스 원본은 비공개 저장소 `lh-lidar-scan`의 `tools/ply-crop/index.html`이며,
  이 저장소는 GitHub Pages 배포용 사본입니다 (`<!doctype html>` 한 줄만 추가됨).
- 분석은 전부 브라우저 안에서 수행됩니다. 서버(BriconLab) 연동 기능은 HTTP API라서
  HTTPS 페이지에서는 브라우저가 차단하므로, 서버 기능이 필요하면 파일을 내려받아
  로컬에서 여세요.
