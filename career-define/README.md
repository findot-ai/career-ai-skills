# career-define

질문으로 내 경력의 원재료를 끌어내는 Claude 스킬입니다. 경력기술서만 주고 "고쳐 줘"라고 하면 AI는 일반론을 돌려줍니다. 이 스킬은 반대로, 숫자의 기준·직접 한 일·실패까지 질문으로 채워 다른 스킬이 쓸 재료를 만듭니다.

- **사례 은행** — 주도한 일 단위의 사례 카드 (문제 → 내가 한 것 → 결과와 기준 → 실패)
- **고정 프로필** — 역할 성격 비중, 근거 있는 기능 / 근거 없는 기능
- **지향 한 문장** — 반문으로 좁힌 근원 가치와, 가고 싶은 자리 / 피할 자리를 가르는 기준

성과 숫자는 지원자에게서만 받습니다. 모르면 '미확인'으로 둡니다.

## 설치
- **claude.ai**: [Releases](https://github.com/findot-ai/career-ai-skills/releases)에서 `career-define.zip`을 받아 스킬로 업로드
- **Claude Code**: 이 폴더를 `~/.claude/skills/career-define/`에 복사

## 사용
```
/define
[경력기술서 첨부]
```
질문은 한 번에 3개 이하로 옵니다. 결과는 `case_bank.md`, `profile.md`, `direction.md` 파일로 남겨 다음에 이어 씁니다.

## 이어지는 스킬
결과는 [role-match](../role-match/), [business-brief](../business-brief/), [interview-prep](../interview-prep/)의 입력이 됩니다.

MIT License — 저장소 루트의 [LICENSE](../LICENSE)
