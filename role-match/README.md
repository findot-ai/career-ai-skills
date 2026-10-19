# role-match

공고 하나와 내 경력을 놓고, **그 자리가 실제로 보는 포인트 3개**에 내 사례가 얼마나 맞는지 점검하는 Claude 스킬입니다.

키워드 매칭률은 쓰지 않습니다. 키워드가 많이 겹쳐도 자리가 정체성으로 요구하는 일에 근거가 없으면 서류에서 떨어지기 때문입니다.

- **포인트 3개** — 회사의 지금 상황 × 자리 정체성(포지션명 + 주요업무 1번)
- **매칭** — 포인트마다 내 사례 하나, 강 / 번역 필요 / 없음
- **결격 점검** — 결격 / 경계 / 확인 필요를 JD 원문 인용과 함께
- **번역 문장** — 경력기술서 첫머리와 면접 첫 답변에 쓰는 한 문장
- **예측 기록** — 지원 전 판정을 남기고 결과와 대조

합격 확률은 말하지 않습니다. 근거가 있는 곳과 빈 곳을 말합니다.

## 설치
- **claude.ai**: [Releases](https://github.com/findot-ai/career-ai-skills/releases)에서 `role-match.zip`을 받아 스킬로 업로드
- **Claude Code**: 이 폴더를 `~/.claude/skills/role-match/`에 복사

## 사용
```
/match
[채용 공고 붙여넣기 또는 URL]
[career-define 결과 또는 경력기술서]
```

## 규칙 파일
- [포인트 도출과 매칭](references/01_points.md)
- [결격 조건 점검](references/02_screening.md)
- [예측 기록과 대조](references/03_log.md)

MIT License — 저장소 루트의 [LICENSE](../LICENSE)
