# Open source

Contributions to other people's projects, grouped by status. Status comes from GitHub and is updated when a PR changes state. An open PR is not an accepted one. Course and team projects are not listed.

Last updated: 2026-10-28

**14 merged, 5 open, 3 waiting on assignment.**

## Merged

| Project | PR | What it does |
| --- | --- | --- |
| pgAdmin | [#10451](https://github.com/pgadmin-org/pgadmin4/pull/10451) | Honours the pgpass file in the Change Server Password dialog, with regression tests. Squashed into master by the maintainer. |
| pgAdmin | [#10502](https://github.com/pgadmin-org/pgadmin4/pull/10502) | Database properties panel shows the real default privileges instead of empty values. Squashed and merged by the maintainer as 641173d0f. |
| pgAdmin | [#10526](https://github.com/pgadmin-org/pgadmin4/pull/10526) | Dashboard log reads no longer fail when a multi-byte character is split across a chunk boundary. Squashed and merged by the maintainer as e02150e. |
| pgAdmin | [#10565](https://github.com/pgadmin-org/pgadmin4/pull/10565) | Moves the 'Returns a set?' option to the Definition tab in the Function dialog, next to the return type. Squashed and merged by the maintainer as 5515b54d5. |
| pgAdmin | [#10596](https://github.com/pgadmin-org/pgadmin4/pull/10596) | Preserves explicit 24-hour mode in Time and DateTime picker popups, with regression tests. Squashed and merged as 5063c76a0; the maintainer removed an unused test import and excluded the clock setting from DatePicker. |
| Django | [#22179](https://github.com/django/django/pull/22179) | Emits 'none' for a CSP source-list directive left empty by an unused nonce, instead of silently dropping it (Trac #37395). Merged into main by a maintainer as 549605d. |
| Notify-Chain | [#846](https://github.com/Core-Foundry/Notify-Chain/pull/846) | Repairs a mangled docstring that broke the build on main. |
| Notify-Chain | [#856](https://github.com/Core-Foundry/Notify-Chain/pull/856) | Bounded worker pool for scheduled notification delivery. |
| Notify-Chain | [#858](https://github.com/Core-Foundry/Notify-Chain/pull/858) | Automatic database reconnection with bounded backoff. |
| Notify-Chain | [#862](https://github.com/Core-Foundry/Notify-Chain/pull/862) | API contract tests with CI coverage. |
| ZecHub wiki | [#990](https://github.com/ZecHub/zechub-wiki/pull/990) | Keyboard selection in the 404 page search, with tests. |
| Liquifact | [#1416](https://github.com/Liquifact/Liquifact-frontend/pull/1416) | Paginated funders table for on-chain invoices. |
| Liquifact | [#1417](https://github.com/Liquifact/Liquifact-frontend/pull/1417) | Shows spendable balance and trustline status on the fund form. |
| Liquifact | [#1423](https://github.com/Liquifact/Liquifact-frontend/pull/1423) | Validates escrow contributions against on-chain funding constraints. |

## Open

| Project | PR | What it does | State |
| --- | --- | --- | --- |
| zulip-terminal | [#1657](https://github.com/zulip/zulip-terminal/pull/1657) | Esc on message search returns focus to the column it started from. | Reviewer tested the updated fix and said it looks good; maintainer merge pending. |
| Notify-Chain | [#861](https://github.com/Core-Foundry/Notify-Chain/pull/861) | Events API validates query params and returns clear 400 errors. | Open; maintainer review or merge pending. |
| fastapi-react | [#13](https://github.com/testdrivenio/fastapi-react/pull/13) | `add_todo` returned a Python set instead of a string. | Open; maintainer review or merge pending. |
| pgAdmin | [#10635](https://github.com/pgadmin-org/pgadmin4/pull/10635) | Index Create Script preserves opclass options (e.g. gist_trgm_ops(siglen=32)) and every storage parameter, with regression tests. | Open; maintainer review or merge pending. |
| pgAdmin | [#10636](https://github.com/pgadmin-org/pgadmin4/pull/10636) | Makes the OpenAI LLM provider work with OpenAI-compatible servers and reasoning models. | Open; maintainer review or merge pending. |

## Waiting on assignment

| Project | Issue | Note |
| --- | --- | --- |
| Talawa API | [#5037](https://github.com/PalisadoesFoundation/talawa-api/issues/5037) | Assignment requested. Talawa needs an assignment before any code, so nothing is written yet. |
| Talawa API | [#5038](https://github.com/PalisadoesFoundation/talawa-api/issues/5038) | Same. |
| DIPY | [#3119](https://github.com/dipy/dipy/issues/3119) | Assignment requested after the first PR was closed for being sent before assignment. No new PR until assigned. |

## Closed without merging

- BasedHardware/omi [#16869](https://github.com/BasedHardware/omi/pull/16869), [#16870](https://github.com/BasedHardware/omi/pull/16870)
- ZecHub/zechub [#2217](https://github.com/ZecHub/zechub/pull/2217)
- Pi-Defi-world/acbu-backend [#1082](https://github.com/Pi-Defi-world/acbu-backend/pull/1082)
- checkstyle/checkstyle [#21533](https://github.com/checkstyle/checkstyle/pull/21533)
- dipy/dipy [#4222](https://github.com/dipy/dipy/pull/4222) - closed by the maintainer because the issue was not assigned first
