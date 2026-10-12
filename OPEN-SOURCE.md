# Open source

Contributions to other people's projects, grouped by status. Status comes from GitHub and is updated when a PR changes state. An open PR is not an accepted one. Course and team projects are not listed.

Last updated: 2026-10-12

**6 merged, 6 open, 2 waiting on assignment.**

## Merged

| Project | PR | What it does |
| --- | --- | --- |
| pgAdmin | [#10451](https://github.com/pgadmin-org/pgadmin4/pull/10451) | Honours the pgpass file in the Change Server Password dialog, with regression tests. Squashed into master by the maintainer. |
| Notify-Chain | [#846](https://github.com/Core-Foundry/Notify-Chain/pull/846) | Repairs a mangled docstring that broke the build on main. |
| Notify-Chain | [#856](https://github.com/Core-Foundry/Notify-Chain/pull/856) | Bounded worker pool for scheduled notification delivery. |
| Notify-Chain | [#858](https://github.com/Core-Foundry/Notify-Chain/pull/858) | Automatic database reconnection with bounded backoff. |
| Notify-Chain | [#862](https://github.com/Core-Foundry/Notify-Chain/pull/862) | API contract tests with CI coverage. |
| ZecHub wiki | [#990](https://github.com/ZecHub/zechub-wiki/pull/990) | Keyboard selection in the 404 page search, with tests. |

## Open

| Project | PR | What it does | State |
| --- | --- | --- | --- |
| pgAdmin | [#10526](https://github.com/pgadmin-org/pgadmin4/pull/10526) | Dashboard log reads no longer fail when a multi-byte character is split across a chunk boundary. Known limit: EUC and GBK encodings can still garble one character at a boundary. | Maintainer reviewed, changes pushed, waiting on his merge decision. |
| pgAdmin | [#10502](https://github.com/pgadmin-org/pgadmin4/pull/10502) | Database properties panel shows the real default privileges instead of empty values. | No maintainer review yet. |
| DIPY | [#4222](https://github.com/dipy/dipy/pull/4222) | API summaries include functions and classes listed in `__all__`. AI assistance was used for the implementation and tests, as the PR says. | No review yet. |
| zulip-terminal | [#1657](https://github.com/zulip/zulip-terminal/pull/1657) | Esc on message search returns focus to the column it started from. | No review yet. |
| Notify-Chain | [#861](https://github.com/Core-Foundry/Notify-Chain/pull/861) | Events API validates query params and returns clear 400 errors. | No review yet. |
| fastapi-react | [#13](https://github.com/testdrivenio/fastapi-react/pull/13) | `add_todo` returned a Python set instead of a string. | No review yet. |

## Waiting on assignment

| Project | Issue | Note |
| --- | --- | --- |
| Talawa API | [#5037](https://github.com/PalisadoesFoundation/talawa-api/issues/5037) | Assignment requested. Talawa needs an assignment before any code, so nothing is written yet. |
| Talawa API | [#5038](https://github.com/PalisadoesFoundation/talawa-api/issues/5038) | Same. |

## Closed without merging

- BasedHardware/omi [#16869](https://github.com/BasedHardware/omi/pull/16869), [#16870](https://github.com/BasedHardware/omi/pull/16870)
- ZecHub/zechub [#2217](https://github.com/ZecHub/zechub/pull/2217)
- Pi-Defi-world/acbu-backend [#1082](https://github.com/Pi-Defi-world/acbu-backend/pull/1082)
- checkstyle/checkstyle [#21533](https://github.com/checkstyle/checkstyle/pull/21533)
