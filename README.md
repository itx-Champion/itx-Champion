<p align="center">
  <img src="assets/banner.svg" width="100%" alt="Muhammad Ahmad — AI Engineer & Full-Stack Developer. AI agents, RAG, MCP servers, Next.js, Postgres."/>
</p>

<p align="center">
  <a href="https://savora-six-beta.vercel.app"><img src="https://img.shields.io/badge/Live%20demo-Savora-f2762b?style=for-the-badge&logo=vercel&logoColor=white" alt="Savora live demo"/></a>
  <a href="https://lumora-ai-agent.vercel.app"><img src="https://img.shields.io/badge/Live%20demo-Lumora-8b5cf6?style=for-the-badge&logo=vercel&logoColor=white" alt="Lumora live demo"/></a>
  <a href="https://www.upwork.com/freelancers/~010c610903c61fe4fc"><img src="https://img.shields.io/badge/Upwork-14a800?style=for-the-badge&logo=upwork&logoColor=white" alt="Upwork"/></a>
  <a href="https://www.fiverr.com/mianahmad121921"><img src="https://img.shields.io/badge/Fiverr-1dbf73?style=for-the-badge&logo=fiverr&logoColor=white" alt="Fiverr"/></a>
  <a href="https://www.linkedin.com/in/mian-ahmad-764882262/"><img src="https://img.shields.io/badge/LinkedIn-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:ahmadsharif965@gmail.com"><img src="https://img.shields.io/badge/Email-0b0f17?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

<p align="center">
  I build AI features and full-stack SaaS that hold up in production: tool-calling agents, RAG over real documents,
  <b>MCP servers</b> that let Claude and Cursor act on business data, and the Next.js + Postgres apps around them.
</p>

<br/>

## Featured work

### Savora — a restaurant operating system with an AI copilot and an MCP server

<a href="https://savora-six-beta.vercel.app">
  <img src="https://raw.githubusercontent.com/itx-Champion/savora/main/docs/screenshots/landing.png" width="100%" alt="Savora landing page: a 3D walkthrough of the demo restaurant"/>
</a>

One platform for the whole restaurant — **POS, kitchen display, QR and online ordering, floor plan, reservations, menu and recipe costing, inventory, purchasing, staff rota and timesheets, loyalty, reviews, finance and reports** — with an **AI copilot** that answers from live data through 21 audited tools, and an **MCP server + REST API** that expose the same tools to Claude, Cursor and your own scripts. Multi-tenant and multi-location, six server-enforced roles, every change in the audit log. The landing page is a scroll-driven 3D walkthrough of the demo restaurant built in React Three Fiber, with no 3D assets.

<table>
  <tr>
    <td width="50%"><img src="https://raw.githubusercontent.com/itx-Champion/savora/main/docs/screenshots/pos.png" alt="Savora point of sale" width="100%"/></td>
    <td width="50%"><img src="https://raw.githubusercontent.com/itx-Champion/savora/main/docs/screenshots/copilot.png" alt="Savora AI copilot answering a food-cost question from live data" width="100%"/></td>
  </tr>
  <tr>
    <td align="center"><sub>Tablet-first POS — one order flows to the kitchen display, the floor plan and stock</sub></td>
    <td align="center"><sub>AI copilot: menu engineering on 30 days of sales, every number from a tool call</sub></td>
  </tr>
</table>

<p>
  <img src="https://img.shields.io/badge/Next.js%2016-0b0f17?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js 16"/>
  <img src="https://img.shields.io/badge/React%2019-0b0f17?style=flat-square&logo=react&logoColor=white" alt="React 19"/>
  <img src="https://img.shields.io/badge/TypeScript-0b0f17?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/PostgreSQL-0b0f17?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/Drizzle%20ORM-0b0f17?style=flat-square&logo=drizzle&logoColor=white" alt="Drizzle ORM"/>
  <img src="https://img.shields.io/badge/Vercel%20AI%20SDK-0b0f17?style=flat-square&logo=vercel&logoColor=white" alt="Vercel AI SDK"/>
  <img src="https://img.shields.io/badge/Gemini-0b0f17?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini"/>
  <img src="https://img.shields.io/badge/MCP-0b0f17?style=flat-square" alt="MCP"/>
  <img src="https://img.shields.io/badge/React%20Three%20Fiber-0b0f17?style=flat-square&logo=threedotjs&logoColor=white" alt="React Three Fiber"/>
  <img src="https://img.shields.io/badge/Stripe-0b0f17?style=flat-square&logo=stripe&logoColor=white" alt="Stripe"/>
  <img src="https://img.shields.io/badge/Vitest-0b0f17?style=flat-square&logo=vitest&logoColor=white" alt="Vitest"/>
  <img src="https://img.shields.io/badge/Playwright-0b0f17?style=flat-square&logo=playwright&logoColor=white" alt="Playwright"/>
  <img src="https://img.shields.io/badge/GitHub%20Actions-0b0f17?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
</p>

**23 back-office screens · 51 routes · 123 automated tests · 21 AI & MCP tools · demo seeded with 46 dishes, 2 branches and 30 days of history**

**[Live demo](https://savora-six-beta.vercel.app)** — try it as the owner, the head chef, a server or the host, no sign-up · **[Source](https://github.com/itx-Champion/savora)** · [Architecture notes](https://github.com/itx-Champion/savora/blob/main/docs/ARCHITECTURE.md)

<br/>

### Lumora — AI agent, CRM and help desk

<a href="https://lumora-ai-agent.vercel.app">
  <img src="https://raw.githubusercontent.com/itx-Champion/lumora/main/docs/screenshots/17-pulse.png" width="100%" alt="Lumora: AI briefing, KPIs and risk signals across pipeline and support"/>
</a>

An AI agent that answers from company documents **with citations** and acts on a multi-tenant Postgres CRM: a support inbox with SLAs, auto-triage and knowledge-grounded AI replies, a drag-and-drop pipeline with weighted forecast, explainable lead scores and an AI morning briefing. Admins get five server-enforced roles, "view as" impersonation, no-code automations and an audit log. A REST API and an **MCP server** let Claude or Cursor work with the CRM using scoped API keys.

<table>
  <tr>
    <td width="50%"><img src="https://raw.githubusercontent.com/itx-Champion/lumora/main/docs/screenshots/22-agent-crm.png" alt="Lumora agent acting on the CRM" width="100%"/></td>
    <td width="50%"><img src="https://raw.githubusercontent.com/itx-Champion/lumora/main/docs/screenshots/18-inbox.png" alt="Lumora help desk inbox" width="100%"/></td>
  </tr>
  <tr>
    <td align="center"><sub>The agent finds a contact and creates a follow-up task through tool calls</sub></td>
    <td align="center"><sub>Help desk with SLAs, auto-triage and AI replies grounded in the knowledge base</sub></td>
  </tr>
</table>

<p>
  <img src="https://img.shields.io/badge/Next.js%2016-0b0f17?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js 16"/>
  <img src="https://img.shields.io/badge/PostgreSQL-0b0f17?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/Drizzle%20ORM-0b0f17?style=flat-square&logo=drizzle&logoColor=white" alt="Drizzle ORM"/>
  <img src="https://img.shields.io/badge/Vercel%20AI%20SDK-0b0f17?style=flat-square&logo=vercel&logoColor=white" alt="Vercel AI SDK"/>
  <img src="https://img.shields.io/badge/RAG-0b0f17?style=flat-square" alt="RAG"/>
  <img src="https://img.shields.io/badge/MCP-0b0f17?style=flat-square" alt="MCP"/>
  <img src="https://img.shields.io/badge/Gemini-0b0f17?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini"/>
  <img src="https://img.shields.io/badge/RBAC-0b0f17?style=flat-square" alt="RBAC"/>
  <img src="https://img.shields.io/badge/Vitest-0b0f17?style=flat-square&logo=vitest&logoColor=white" alt="Vitest"/>
  <img src="https://img.shields.io/badge/GitHub%20Actions-0b0f17?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
</p>

**[Live demo](https://lumora-ai-agent.vercel.app)** — every visitor gets a private sandbox workspace · **[Source](https://github.com/itx-Champion/lumora)**

<br/>

### Cyber Store — a production-style e-commerce storefront

<table>
  <tr>
    <td width="62%"><a href="https://cyber-e-commerce-blond.vercel.app"><img src="https://raw.githubusercontent.com/itx-Champion/cyber-e-commerce/master/docs/screenshots/03-catalog.png" alt="Cyber Store catalog with URL-synced filters" width="100%"/></a></td>
    <td width="38%" valign="top">
      Electronics storefront with URL-synced filters, <kbd>Ctrl</kbd> <kbd>K</kbd> search, a cart drawer, validated guest checkout and order history, CI-tested.<br/><br/>
      <img src="https://img.shields.io/badge/Next.js%2016-0b0f17?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js 16"/>
      <img src="https://img.shields.io/badge/TypeScript-0b0f17?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
      <img src="https://img.shields.io/badge/Zustand-0b0f17?style=flat-square" alt="Zustand"/>
      <img src="https://img.shields.io/badge/Zod-0b0f17?style=flat-square&logo=zod&logoColor=white" alt="Zod"/><br/><br/>
      <b><a href="https://cyber-e-commerce-blond.vercel.app">Live demo</a></b> · <a href="https://github.com/itx-Champion/cyber-e-commerce">Source</a>
    </td>
  </tr>
</table>

> Savora and Lumora are my own products, built to production standards and documented as case studies. The companies, staff, guests and reviews inside the demos are fictional.

<br/>

## What I build

| | |
|---|---|
| 🤖 **AI agents & LLM integrations** | Tool-calling agents and multi-step workflows (OpenAI, Claude, Gemini), RAG and knowledge-base assistants over your documents, AI copilots inside existing apps |
| 🔌 **MCP servers & AI APIs** | MCP servers that connect Claude, Cursor and ChatGPT to internal APIs and databases, with scoped keys, permissions and audit logs; the same tools exposed over REST |
| 🧱 **Full-stack SaaS** | MVPs, dashboards, admin panels and internal tools; Next.js / React in TypeScript; Node.js APIs; PostgreSQL, MongoDB and Supabase; auth, roles, billing, multi-tenancy |
| ⚙️ **Automation & CRM** | API, webhook and third-party integrations; lead capture, qualification, routing and follow-ups; AI content and reporting pipelines; BullMQ job queues |
| 🎙️ **Voice AI** | Voice agents and real-time voice features with ElevenLabs, LiveKit and GoHighLevel |
| 🛠️ **Debugging & rescue** | Fixing broken integrations, failing AI features, and slow or unstable Node.js / Next.js apps |

Day to day I also work on a multi-tenant construction-management SaaS (Node.js/Express, MongoDB, Redis/BullMQ, React/TypeScript), where I build MCP servers and tools that let AI agents act on real business data, integrate agent frameworks, work with vector search, and build real-time voice features with LiveKit.

<br/>

## How I work

- **Start from the business problem** — what should happen, for whom, and how we will know it works. AI goes only where it pays off.
- **Production habits from day one** — typed code, server-side authorization, tests that run in CI, error handling and retries instead of silent failures.
- **Clear scope and milestones** — regular progress updates and a working demo before handoff.
- **Documentation and a proper handover** — architecture notes and setup instructions so your team can run and extend what I build.

<br/>

## Toolbox

<p>
  <img src="https://img.shields.io/badge/OpenAI-0b0f17?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI"/>
  <img src="https://img.shields.io/badge/Claude-0b0f17?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude"/>
  <img src="https://img.shields.io/badge/Gemini-0b0f17?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Gemini"/>
  <img src="https://img.shields.io/badge/Vercel%20AI%20SDK-0b0f17?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel AI SDK"/>
  <img src="https://img.shields.io/badge/MCP-0b0f17?style=for-the-badge" alt="MCP"/>
  <img src="https://img.shields.io/badge/RAG%20%26%20vector%20search-0b0f17?style=for-the-badge" alt="RAG and vector search"/>
</p>
<p>
  <img src="https://img.shields.io/badge/React-0b0f17?style=for-the-badge&logo=react&logoColor=white" alt="React"/>
  <img src="https://img.shields.io/badge/Next.js-0b0f17?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js"/>
  <img src="https://img.shields.io/badge/TypeScript-0b0f17?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/Tailwind%20CSS-0b0f17?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS"/>
  <img src="https://img.shields.io/badge/Three.js-0b0f17?style=for-the-badge&logo=threedotjs&logoColor=white" alt="Three.js"/>
  <img src="https://img.shields.io/badge/GSAP-0b0f17?style=for-the-badge&logo=greensock&logoColor=white" alt="GSAP"/>
</p>
<p>
  <img src="https://img.shields.io/badge/Node.js-0b0f17?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/Express-0b0f17?style=for-the-badge&logo=express&logoColor=white" alt="Express"/>
  <img src="https://img.shields.io/badge/PostgreSQL-0b0f17?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/MongoDB-0b0f17?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/>
  <img src="https://img.shields.io/badge/Supabase-0b0f17?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase"/>
  <img src="https://img.shields.io/badge/Redis-0b0f17?style=for-the-badge&logo=redis&logoColor=white" alt="Redis"/>
  <img src="https://img.shields.io/badge/GraphQL-0b0f17?style=for-the-badge&logo=graphql&logoColor=white" alt="GraphQL"/>
  <img src="https://img.shields.io/badge/Drizzle-0b0f17?style=for-the-badge&logo=drizzle&logoColor=white" alt="Drizzle ORM"/>
</p>
<p>
  <img src="https://img.shields.io/badge/ElevenLabs-0b0f17?style=for-the-badge&logo=elevenlabs&logoColor=white" alt="ElevenLabs"/>
  <img src="https://img.shields.io/badge/LiveKit-0b0f17?style=for-the-badge&logo=livekit&logoColor=white" alt="LiveKit"/>
  <img src="https://img.shields.io/badge/GoHighLevel-0b0f17?style=for-the-badge" alt="GoHighLevel"/>
  <img src="https://img.shields.io/badge/Stripe-0b0f17?style=for-the-badge&logo=stripe&logoColor=white" alt="Stripe"/>
  <img src="https://img.shields.io/badge/GitHub%20Actions-0b0f17?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
  <img src="https://img.shields.io/badge/Vercel-0b0f17?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel"/>
  <img src="https://img.shields.io/badge/Vitest-0b0f17?style=for-the-badge&logo=vitest&logoColor=white" alt="Vitest"/>
  <img src="https://img.shields.io/badge/Playwright-0b0f17?style=for-the-badge&logo=playwright&logoColor=white" alt="Playwright"/>
</p>

<br/>

## Let's build something

**Good fit:** founders building an MVP or SaaS, product teams adding AI to an existing app, agencies that need a dependable developer, and businesses automating lead handling or internal workflows.

Send me a short message with what you're building (or what's broken), your stack and your timeline.

<p>
  <a href="mailto:ahmadsharif965@gmail.com"><img src="https://img.shields.io/badge/Get%20in%20touch-ahmadsharif965%40gmail.com-f2762b?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Muhammad Ahmad"/></a>
  <a href="https://www.upwork.com/freelancers/~010c610903c61fe4fc"><img src="https://img.shields.io/badge/Hire%20on-Upwork-14a800?style=for-the-badge&logo=upwork&logoColor=white" alt="Hire on Upwork"/></a>
  <a href="https://www.fiverr.com/mianahmad121921"><img src="https://img.shields.io/badge/Hire%20on-Fiverr-1dbf73?style=for-the-badge&logo=fiverr&logoColor=white" alt="Hire on Fiverr"/></a>
</p>
