<img src="./banner-animated.svg" alt="hi there, I'm Sanskar;" width="100%">

I build web apps, APIs and small tools, from a tech news feed to a local video converter.

I work mostly in TypeScript, React, Node.js and Python. I also send fixes upstream and write about what I learn.

## Projects

| Project | What it does |
| --- | --- |
| **[IMA](https://github.com/MaybeSomeone-arc18/Ima-)** | Pulls the latest tech news into one feed, so you can keep up without the FOMO. |
| **[Voino](https://github.com/MaybeSomeone-arc18/voino)** | Turns meetings into editable, interactive notes and a visual board. Prototype. |
| **[Saartheye](https://github.com/MaybeSomeone-arc18/saartheye-ai)** | A prototype I built with the vision of helping blind people use their phones to navigate. Not a validated navigation aid. |
| **[FacCheck.ai](https://github.com/MaybeSomeone-arc18/fac-Check.ai)** | A predictive-maintenance dashboard prototype for machine health and alerts. Uses CSV replay and simulated metrics, not real factory results. |
| **[TaskFlow AI](https://github.com/MaybeSomeone-arc18/taskflow-ai)** | Helps people arrange tasks and projects, collaborate with others and use AI for planning. |
| **[mov2mp4](https://github.com/MaybeSomeone-arc18/mov2mp4)** | Helps editors convert MOV videos to MP4 for free, on their own machine. |

## Open source

7 merged PRs and 5 open ones in other people's projects. Open does not mean accepted. The full list with links and current status is in [OPEN-SOURCE.md](./OPEN-SOURCE.md).

- **[pgAdmin](https://github.com/pgadmin-org/pgadmin4/pull/10451)** - fixed pgpass handling in the Change Server Password dialog, with regression tests, and [made the Database properties panel show real default privileges](https://github.com/pgadmin-org/pgadmin4/pull/10502). Both squashed into master by the maintainer. A [fix for multi-byte characters in the Dashboard logs](https://github.com/pgadmin-org/pgadmin4/pull/10526) is open and has had a maintainer review.
- **Notify-Chain** - four merged PRs, including [database reconnection with bounded backoff](https://github.com/Core-Foundry/Notify-Chain/pull/858) and [API contract tests with CI coverage](https://github.com/Core-Foundry/Notify-Chain/pull/862).
- **[ZecHub wiki](https://github.com/ZecHub/zechub-wiki/pull/990)** - made the keyboard work in the 404 page search, with tests. Merged.

## Tools I use

<img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,nodejs,express,py,fastapi,postgres,mongodb,redis,docker,java" alt="TypeScript, JavaScript, React, Next.js, Node.js, Express, Python, FastAPI, PostgreSQL, MongoDB, Redis, Docker, Java">

## Tripwire: library and technical report

[Tripwire](https://github.com/MaybeSomeone-arc18/tripwire-guardrails) checks text going into and out of LLM apps for prompt injection, secrets and personal data, with plain rules and an optional Gemma judge.

**[Tripwire catches the override, not the intent](https://zenodo.org/records/23117097)** - a rules-only failure analysis of indirect prompt-injection screening. Technical report on Zenodo, not peer reviewed. It measures text screening, not whether an agent was protected from an attack.

## Notes from building

I write about the parts that took longer than expected, what broke and what I'd change: **[dev.to/sansk_ya](https://dev.to/sansk_ya)**.

One place to start: [what I learned shipping a tiny FFmpeg desktop app](https://dev.to/sansk_ya/what-i-learned-shipping-a-tiny-ffmpeg-desktop-app-1hng).
