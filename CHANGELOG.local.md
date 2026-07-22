# CHANGELOG (local)
<!-- upstream CHANGELOG.md는 건드리지 않는다. 포크 커스텀 변경 이력만 여기에 기록. -->

| 변경시점 | 구분 | 범위 | 상세내역 | 변경사유/목적 |
|---------|------|------|---------|-------------|
| 2026-07-22 17:56 KST | fix | pnpm-policy | preinstall 가드가 pnpm 자신을 차단하던 버그 수정 — npm_execpath 폴백 검사 추가 | npm_config_user_agent 미설정 실행 경로에서 pnpm이 오차단되어 신규 설치 불가 |
| 2026-07-22 17:07 KST | chore | pnpm-policy | packageManager를 pnpm@11.0.9로 고정하고 preinstall 가드와 allowBuilds(esbuild) 설정 추가 | pnpm store v11 일괄전환에 따른 정책 통일, npm 혼용 차단 |
