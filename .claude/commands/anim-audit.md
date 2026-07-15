---
description: "코드베이스 모션 감사 + 개선 계획 생성 — improve-animations 스킬 단축 호출"
---

Skill tool로 `improve-animations` 스킬을 즉시 호출하세요.

- 인자: $ARGUMENTS (예: `quick`, `deep`, `performance`, `plan <설명>`, `execute <plan>`, `reconcile` — 스킬의 Invocation Variants 그대로 전달)
- 인자가 없으면 `standard` 강도로 전체 워크플로우(recon → audit → vet → confirm → plans)를 실행하세요.
- 소스 코드는 절대 수정하지 말 것 — 산출물은 `plans/` 아래에만 생성.
