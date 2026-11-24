# DEMO

51WORK 프로그램 데모 모음. 주소는 `www.51work.bid/demo/<폴더>`.

- `stock/` : 안전용품 재고관리(Safety Stock) 30초 데모 — 주소 `www.51work.bid/demo/stock/`

## 구조

- 이 저장소는 Cloudflare Pages로 배포합니다(빌드 없이 정적 파일 그대로).
- 주소 연결은 재고관리 Worker(aibulapia/stock, `src/index.js`의 `handleDemo`)가 `/demo` 요청을 이 Pages 사이트로 넘기면서 처리합니다.
- 새 데모는 폴더를 만들고 같은 방식으로 추가합니다 (Worker 쪽 연결은 필요 시 따로 수정).
