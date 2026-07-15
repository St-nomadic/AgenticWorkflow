---
description: "애니메이션/모션 코드 리뷰 — review-animations 스킬 단축 호출"
---

Skill tool로 `review-animations` 스킬을 즉시 호출하세요. (이 스킬은 `disable-model-invocation: true`라 이 커맨드가 유일한 자동 진입점입니다.)

- 인자: $ARGUMENTS
- 인자가 없으면 현재 diff(`git diff` + staged)의 애니메이션·모션 코드를 리뷰 대상으로 삼으세요.
- 출력은 스킬이 요구하는 형식(Before/After/Why 테이블 + Block/Approve 판정)을 그대로 따르세요.
