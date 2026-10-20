# interview-prep

면접 단계가 실제로 무엇을 보는지 정하고, 그 단계에서 **반드시 나올 질문부터** 준비하는 Claude 스킬입니다. 면접이 끝나면 복기를 쌓아 여러 면접에 걸친 패턴을 찾습니다.

- **단계 판단** — 회사가 붙인 단계 이름이 아니라 면접관이 누구인지로 (실무 / 기능 검증 / 원칙·가치 / 임원·최종)
- **반드시 나올 질문 3개** — role-match에서 넘어온 빈 곳 중 이 단계가 볼 만한 것
- **답의 뼈대** — 외울 문장이 아니라 30초 / 2분 키워드와 순서
- **실무 연습** — 공고가 도구·분석을 직접 요구하면 가상 문제와 채점 포인트
- **역질문 4축** — 어떻게 일하나 / 어떤 문제 / 고객의 가장 큰 니즈 / 무엇으로 재나
- **복기** — 질문 원문, 분류, 여러 면접 누적 패턴 (`debrief_log.md`에 누적)

## 설치
- **claude.ai**: [Releases](https://github.com/findot-ai/career-ai-skills/releases)에서 `interview-prep.zip`을 받아 스킬로 업로드
- **Claude Code**: 이 폴더를 `~/.claude/skills/interview-prep/`에 복사

## 사용
```
/interview
[공고] [면접 단계·면접관·형식]
[role-match 결과, 사례 은행 — 있으면]
```
면접 후에는 기억나는 질문을 붙여 넣고 "복기"라고 하면 됩니다.

## 규칙 파일
- [예상 질문과 역질문](references/01_questions.md)
- [답의 뼈대와 실무 연습](references/02_answers.md)
- [복기](references/03_debrief.md)

MIT License — 저장소 루트의 [LICENSE](../LICENSE)
