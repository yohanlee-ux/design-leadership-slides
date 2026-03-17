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

## 참고: 인터랙션 없는 최신 콘텐츠 버전
v1.1이 인터랙션 적용 전 마지막 버전입니다.
콘텐츠는 v1.2가 최신이므로, 인터랙션만 빼고 싶다면 v1.2에서 커버 섹션만 v1.1 스타일로 교체하면 됩니다.
