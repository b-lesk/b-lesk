<div align="center">

# Benjamin Lesko

![Typing](https://readme-typing-svg.demolab.com?font=Inter&weight=700&size=24&duration=3500&pause=900&color=FFC61A&center=true&vCenter=true&width=560&lines=Consultant+at+Accenture;Data+%26+AI+engineer+in+New+Orleans;Founder+of+SipTrack;SQL+pipelines+and+LLM+workflows)

[![Portfolio](https://img.shields.io/badge/Portfolio-b--lesk.github.io-111?style=for-the-badge&logo=githubpages&logoColor=white)](https://b-lesk.github.io/) [![LinkedIn](https://img.shields.io/badge/LinkedIn-benjamin--lesko-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/benjamin-lesko/) [![SipTrack](https://img.shields.io/badge/SipTrack-siptrack.app-FFC61A?style=for-the-badge&logoColor=111)](https://siptrack.app/) [![App Store](https://img.shields.io/badge/App_Store-SipTrack_Happy_Hour-000?style=for-the-badge&logo=apple&logoColor=white)](https://siptrack.app/get)

</div>

<br>

I build SQL and Python pipelines and LLM workflows, and I help business leaders decide what to do with the numbers. By day I'm a Consultant at Accenture supporting Meta's Wearables AI. At night I run SipTrack, a happy-hour finder for 19,000+ bars and restaurants in 690+ US cities.

<br>

## Now

- **Accenture, client Meta.** Consultant, recently promoted from Senior Analyst (May 2025 to now). I sit between the data and the people making product and business calls on Wearables AI, and build what they need to decide. Daily-summary pipelines that cut data scanned 50-fold, a backfill agent that ran 200+ production backfills, privacy cleanup across 120+ tables.
- **SipTrack LLC.** Founder. I run the business side too: pricing, a 60-day pilot for New Orleans bars, and an owner dashboard that shows bars what their deals bring in.
- **Georgia Tech.** M.S. Analytics, in progress. B.S. Statistics from the University of Michigan.

<br>

## SipTrack

<table>
<tr>
<td width="50%" valign="top">

**What it does.** Shows which happy hours are on right now, what they cost and how long is left, on a map and a list.

**How it's built**
- SwiftUI iOS app with Live Activities and widgets
- Next.js on Cloudflare Workers for siptrack.app
- Supabase Postgres with row-level security
- A nightly AI pipeline (Gemini and a local Qwen model) that reads venue websites, then a strict validator checks every price, item and time against the page
- A React dashboard where bar owners see views, taps and deal-code visits

</td>
<td width="50%" valign="top">

**By the numbers**
- 21,800+ live deals
- 19,600+ bars and restaurants
- 690+ cities with their own pages
- 300,000+ venue websites read by the pipeline
- One founder

[siptrack.app](https://siptrack.app/) and the [architecture overview](https://github.com/b-lesk/siptrack-overview)

</td>
</tr>
</table>

<br>

## Other work

| Project | What it is |
|---|---|
| **Backfill agent** | Takes an approved backfill request, submits it, watches it, retries within limits and checks rows landed before closing. Chat, Claude Code skill and web entry points. |
| **Contract search (RAG)** | Azure, OpenAI and Cosmos DB over 60+ statements of work, with a semantic layer for contract value by period. |
| **AI practitioner platform** | Full-stack Next.js platform for a community of 250+: onboarding, project discovery and an assistant. |
| **PaperTrade** | Paper-trading app. FastAPI, SQLAlchemy, strategies written in plain English and parsed by Claude. [papertrade.dev](https://papertrade.dev/) |

<br>

## Tools

<div align="center">

![Stack](https://skillicons.dev/icons?i=py,ts,react,nextjs,postgres,supabase,cloudflare,azure,git&theme=dark)

**Most used:** Python and SQL

**Data:** SQL, Python, Presto, Hive, Snowflake, Airflow, Postgres
**AI:** OpenAI, Gemini, Claude, RAG, vector databases, agents, Ollama
**Apps:** SwiftUI, Next.js, React, Cloudflare Workers, Supabase

</div>
