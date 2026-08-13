## Hi there 👋

I'm Shravani, a senior fullstack engineer working across React/TypeScript on the front and Node/NestJS with PostgreSQL on the back. Most of my work involves making messy domain data trustworthy enough that someone will act on it.

- 🔭 **I'm currently working on** core product at Flywl, a multi-cloud marketplace platform
- 🌱 **I'm currently going deeper on** distributed systems design and backend architecture at scale
- 👯 **I'm looking to collaborate on** developer tooling, especially things that make the tedious parts of engineering smaller
- 💬 **Ask me about** NestJS API design, React performance, or building agents over real production data
- ✍️ **I write** about system design and engineering practice on [Medium](https://medium.com/@skher3318)
- 📫 **How to reach me:** shravanikher9@gmail.com · [LinkedIn](https://www.linkedin.com/in/)

---

### Things I've built

**An insight agent over multi-cloud billing data.** Triggers when a cost usage file lands in S3, compares current and prior periods to flag overage, spend spikes, and under-utilised reserved instances and savings plans, then projects run-rate against commitment and recommends action.

**Enterprise commitment and overage tracking.** Designed the PostgreSQL data model and built the NestJS services computing commitment burn-down, with real-time spend analytics aggregating usage across AWS, Azure, and GCP.

**An AI-assisted event tracking system.** PMs tag @Cursor in Slack with an event spec, which runs against a custom runbook and event dictionary I wrote to generate instrumentation code and raise a PR, removing engineering from the instrumentation loop.

**A custom tagging system for an EHR platform.** Evaluated third-party options, found they were incompatible with the module architecture, and built the custom path across the NestJS API and React interface. Now core workflow across 1,200+ US facilities.

**Billing and insurance claim APIs.** NestJS REST services for clinical billing workflows, where the data contracts had to hold up against real financial and regulatory complexity.

**A ~30% dashboard performance improvement.** Profiling across API and client: payload reduction, re-render elimination, code splitting, memoization, and bundle optimisation.

---

**Stack:** TypeScript · React · Next.js · Node.js · NestJS · PostgreSQL · Redis · GraphQL
