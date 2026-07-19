# 이진철 — MICE를 다시 설계하다 · Portfolio

MICE 전략가 이진철의 포트폴리오 웹사이트입니다.

## 구성

| 파일 | 내용 |
|---|---|
| `index.html` | **포트폴리오 웹사이트** — 테크 기업 스타일의 원페이지 사이트. 동적 SVG 히어로, 스크롤 리빌, 카운트업 지표, 애니메이션 파이프라인 다이어그램 포함 |
| `deck.html` | **슬라이드 덱 버전** — 원본 PPTX 26장을 좌표 단위로 재현한 웹 슬라이드 (키보드 · 스와이프 · 목차 · 전체화면) |
| `assets/` | 이미지 · 아이콘 리소스 |

빌드나 서버 없이 브라우저에서 바로 열립니다.
GitHub Pages 배포 시 (Settings → Pages → Deploy from a branch → `/ (root)`)
`index.html`이 메인 사이트로, `/deck.html`이 슬라이드 버전으로 서빙됩니다.

## 사이트 특징

- **동적 SVG** — 히어로/컨택트 섹션의 유동 곡선 · 파티클 애니메이션, 모객 BM 4단계 파이프라인의 선 드로잉 · 펄스 노드
- **스크롤 인터랙션** — IntersectionObserver 기반 섹션 리빌, 숫자 카운트업, 타임라인 라인 그로우, 읽기 진행바
- **반응형** — 데스크톱 · 태블릿 · 모바일(햄버거 메뉴, 스와이프 스크롤) 대응
- **접근성** — `prefers-reduced-motion` 준수 (모션 최소화 설정 시 정적 렌더링)
- 폰트: [Pretendard](https://github.com/orioncactus/pretendard) · 컬러: Deep Navy `#0A2540` + Electric Blue `#2962FF`
