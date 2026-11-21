# Changelog

## 2026-11 — 테스트 결과 반영
`claude plugin eval`(케이스당 3회, 스킬 있음/없음 비교)에서 나온 문제를 고쳤습니다.

- **role-match**: 호출 설명에 "합격 확률 몇 %", "붙을까?", "될 것 같아?" 추가 / 절대 원칙 7~9 추가(포인트는 공고만 보고 먼저 · 결과 숫자 없으면 최대 '번역 필요' · 짧은 답 요구에도 references 점검)
- **business-brief**: 파일로 낼 때도 채팅 요약의 숫자마다 출처 유형 · 자료로 새로 계산한 값은 `추정` + 계산식
- **evals/ 추가**: 4개 스킬 각 3케이스(정상 · 함정 · 경계). 스킬 폴더에서 `claude plugin eval .`로 실행
  - interview-prep: 역질문 4축, 복기 → 사례 은행 갱신 채점 추가
  - business-brief: 주장 vs 데이터 표, 30·60·90 채점 추가
- `.gitignore`: `claude plugin eval`이 만드는 `evals/results/` 보고서는 저장소에 넣지 않음
