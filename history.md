# Slide Version History

각 버전으로 돌아가려면: `git checkout <tag>`
현재 최신으로 돌아오려면: `git checkout main`

---

## v1.0 — 초기 버전
- **커밋:** `2fcdced`
- **날짜:** 2026-03-17
- **디자인 톤:** 라이트 베이스 (#f7f7f5), Plus-Ex itoo 참고
- **커버:** 중앙 정렬, 텍스트만
- **인터랙션:** 없음 (스크롤 reveal만)
- **슬라이드:** Session 1 (17장) + Session 2 Farmmorning
- **복원:** `git checkout v1.0`

---

## v1.1 — 그리드 정렬, 레이아웃 개선
- **커밋:** `7807c72`
- **날짜:** 2026-03-17
- **변경:** Problem divider 추가, 14번 시너지 바, 13번 3컬럼 아이콘 카드, 23번 중앙 클로징
- **인터랙션:** 없음
- **복원:** `git checkout v1.1`

---

## v1.2 — DotGrid 커버 인터랙션 + 콘텐츠 보강 (현재)
- **커밋:** `3bd3d2b`
- **날짜:** 2026-03-17
- **디자인 톤:** 커버 다크 (#0a0a12) + DotGrid, 본문 라이트 유지
- **커버 인터랙션:** DotGrid (마우스 근접 반응 + 클릭 충격파)
  - dotSize: 3, gap: 20, baseColor: #271E37, activeColor: #5227FF
  - proximity: 80, shockStrength: 1.2, resistance: 1200
- **주요 변경:**
  - 14번: Platform/Product Designer 통합 그리드 테이블
  - 13번: SVG 아이콘 3컬럼 카드
  - 19번: 그리드 정렬 수정
  - 23번: 중앙 정렬 클로징
  - 전체 align-self:start 감사
  - Nav 다크모드 감지 (커버 대응)
  - 연도 2025 → 2026
- **복원:** `git checkout v1.2`

---

## v2.0 — Full Dark Theme + Interactions (현재)
- **커밋:** `e7345ad`
- **날짜:** 2026-03-17
- **디자인 톤:** reactbits.dev 스타일 다크 (#0a0a12), accent #5227FF
- **커버:** DotGrid 인터랙션 (마우스 근접 반응 + 클릭 충격파)
- **Problem 디바이더 (06,12,17):**
  - WebGL 노이즈 웨이브 배경, 풀스크린
  - 큰 번호 + 솔루션 요약 타이틀
- **인터랙션:**
  - 카드/박스: 호버 lift + glow shadow
  - 메트릭/숫자: easeOutCubic count-up
  - Steps: 순차적 fade-in (120ms delay)
  - 이미지: scroll-triggered scale fade-in
- **주요 변경:**
  - 전체 CSS 다크 테마 전환
  - SVG 다이어그램 다크 팔레트 재색칠
  - 03번: Before/After 통합 그리드, 라인 완화
  - 13번: 3컬럼 통합 그리드 테이블
  - 19번: 통합 그리드 compare 박스
  - 20번: accent 컬러 STEP 03, 의미 맞는 SVG 아이콘 (Save, Git, Users, Zap)
  - 21번: 이미지 높이 280px 크롭 통일
  - 슬라이드 번호: pill badge 스타일
- **복원:** `git checkout v2.0`

---

## v2.1 — Session 2 포트폴리오 PDF 이미지 기반 재구성 (현재)
- **커밋:** `35c6616`
- **날짜:** 2026-03-21
- **Session 2 변경:**
  - 포트폴리오 PDF 페이지 이미지를 그대로 슬라이드에 사용
  - 이미지 크롭 없이 원본 레이아웃 유지
  - p4~p12: STEP1 문제 → 핵심 발견 → 문제 상세 → STEP2 전략 → 실행(다크) → 결과
  - 녹색 accent (#22c55e)로 Session 1(보라)과 시각적 구분
  - 커버: 다크 그린 오로라 그라데이션
  - fm-slide CSS 클래스로 풀블리드 이미지 레이아웃
  - 클로징: 프로젝트 회고 + Thank You (그린 글로우)
- **Session 1:** v2.0과 동일 (다크 테마 + 인터랙션)
- **복원:** `git checkout v2.1`

---

## 참고: 인터랙션 없는 최신 콘텐츠 버전
v1.1이 인터랙션 적용 전 마지막 버전입니다.
콘텐츠는 v1.2가 최신이므로, 인터랙션만 빼고 싶다면 v1.2에서 커버 섹션만 v1.1 스타일로 교체하면 됩니다.
