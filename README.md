## Hi there 👋

I'm Shravani, a Full-Stack + AI Engineer. I build production AI agents end to end with LangGraph and LangChain in Python, on NestJS and PostgreSQL backends with React frontends.

I care about the unglamorous parts that make agents reliable: evals, guardrails, cost control, and recovering from failure.

- 🔭 **I'm currently building** a multi-agent system that turns Jira tickets into reviewed GitHub pull requests
- 💬 **Ask me about** agent orchestration, evals for LLM systems, NestJS API design, or React performance
- ✍️ **I write** about system design and engineering practice on [Medium](https://medium.com/@skher3318)
- 🌍 **Open to** remote roles in AI engineering and full-stack + AI
- 📫 **How to reach me:** shravanikher9@gmail.com · [LinkedIn](https://www.linkedin.com/in/shravani-kher-0875281b6/)

---

### Things I've built

**Multi-Agent Dev Team (personal project).** AI agents that read a Jira ticket, plan the work, write the code and tests in a sandbox, review it, and open a pull request. Built on a LangGraph pipeline with Postgres checkpoints, a code map that finds the files a ticket touches, a verify step (lint, typecheck, tests, secret scan), and golden-ticket evals. A full run costs about ₹9.46 (~$0.11).

**A natural-language workflow agent.** Users describe a process in plain words, and a LangGraph agent plans the steps, picks integrations and tools, and generates an executable workflow for review. Per-user integration auth, structured outputs, guardrails on every step, and prompt caching. Holds a ~84% eval pass rate.

**An insight agent over multi-cloud billing data.** Triggers when a cost usage file lands in S3, compares current and prior periods to flag overage, spend spikes, and under-used reserved instances and savings plans, then projects run-rate against commitment and recommends action.

**Enterprise commitment and overage tracking.** Designed the PostgreSQL data model and built the NestJS services for commitment burn-down, with real-time spend analytics across AWS, Azure, and GCP.

**An AI-assisted event tracking system.** PMs tag @Cursor in Slack with an event spec. It runs against a custom runbook and event dictionary I wrote, generates the instrumentation code, and raises a PR, so engineers are no longer needed in that loop.

**A custom tagging system for an EHR platform.** Third-party options didn't fit the module architecture, so I built a custom one across the NestJS API and React interface. It is now a core workflow across 1,200+ US facilities.

**Performance work.** Designed 10+ NestJS and PostgreSQL REST APIs with role-based access control, cutting average response time from ~340ms to under 100ms through query optimisation and caching. Cut frontend page load from ~4s to under 2s and bundle size by ~35% through render optimisation, code splitting, and memoization.

---

**AI:** Python · LangGraph · LangChain · LLM evals · RAG · Prompt engineering · FastAPI

**Full-stack:** TypeScript · React · Next.js · Node.js · NestJS · PostgreSQL · Redis · GraphQL · Docker
