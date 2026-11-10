# skills

외부 GitHub 저장소의 스킬을 복사하지 않고 원본 저장소를 직접 가리키는 Claude 플러그인 마켓플레이스입니다.
업데이트하면 각 원작자 저장소의 최신 버전을 받아옵니다.

| 플러그인 | 원본 | 스킬 |
| --- | --- | --- |
| interfaces | jakubkrehel/skills | better-* 7종, interface-review, explain-interface, break, build-design, teardown, state-machine, variant, afk |
| cyclomatic-complexity | saurabhkumar8112/cyclomatic-complexity-skill | cyclomatic-complexity |
| eli5 | dreambigou/eli5 | eli5 |
| archify | tt-a1i/archify | archify |
| lieflat-charts | larashero3-dotcom/lieflat-charts | lieflat-charts |
| amicro | Subhan-code/Amicro--Micro-transitions- | amicro-design-system |
| sepia | Nanako0129/sepia | sepia, sepia-write, sepia-review, sepia-refactor, sepia-recreate, sepia-hemingway |
| yomiyasu | nanaism/yomiyasu | yomiyasu |
| mattpocock-skills | mattpocock/skills | tdd, diagnosing-bugs, code-review, grilling 등 (저장소 설정 그대로) |
| cursor-team-kit-picks | cursor/plugins (cursor-team-kit) | thermo-nuclear-code-quality-review, weekly-review, what-did-i-get-done, check-compiler-errors, verify-this, run-smoke-tests, make-pr-easy-to-review, get-pr-comments |

## 스킬 추가하기

`.claude-plugin/marketplace.json`의 `plugins`에 항목을 추가합니다.

- 저장소에 `.claude-plugin/`이 있으면 `source`만 적습니다.
- 없으면 `"strict": false`와 함께 `skills`에 SKILL.md가 들어 있는 폴더 경로를 적습니다.
