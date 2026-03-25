# Sam Kujovich

Engineering leader focused on AI tooling, platform infrastructure, and scaling teams that ship.

Engineering Manager at [Arcade.dev](https://arcade.dev), leading the Tools and Growth teams. Arcade is building the platform that lets AI agents actually do things — tackling auth, permissions, security, and connecting to the systems we've spent decades building. I lead the teams responsible for what those tools are, and how developers discover and use them.

## What I'm Building

At Arcade, I'm focused on the infrastructure that makes AI agents useful in the real world. Not just chat — actual tool use with real auth, real permissions, and real security. The Tools team builds what agents can do; the Growth team makes sure developers can find and use it.

Previously at A Place for Mom, I led the team behind **Grace** — a production multi-agent system powering an AI-native senior care marketplace. Key architectural decisions: hexagonal architecture for LLM provider flexibility, composable prompt packs with filesystem fallback, and a dual-layer guardrail system combining pattern matching with LLM evaluation.

## Featured Project

### [prd-decomposer](https://github.com/samkujovich/prd-decomposer)
MCP server that takes a product requirements doc and decomposes it into Jira-ready epics and stories. Built with OpenAI Agents SDK. The part I'm most interested in is the eval suite — how do you measure whether a PRD was "correctly" decomposed? That's a harder problem than the decomposition itself.

## Background

**5+ years of engineering leadership**, Manager → Sr Manager → Director across MarTech, Platform, and AI teams. Hired and developed 15+ engineers from IC to Principal level.

**Arcade.dev** — First Engineering Manager. Leading Tools and Growth teams, building the platform that connects AI agents to real-world systems with proper auth, permissions, and security.

**A Place for Mom** — Director of Software Engineering. Led 12 engineers across AI Product and B2B Platform. Presented product strategy to CEO and executive leadership. Transformed a 21-person platform org: KTLO from 45% to 19%, P0 incidents from ~1/week to 1/year, delivery lead time from 20+ days to 6 days. Rebuilt the leadership team across an 18-month transformation — hired a QA Manager, Sr Manager, 2 Principals, 2 Staff Engineers, and promoted from within.

**Realtor.com** — Manager → Sr Manager across three teams that grew to 18 engineers (Auth, Identity, Notifications, MarTech). Founded the MarTech org from zero. Scaled Notifications from a single-use system to a company-wide platform doing 4B+ quarterly. Led Auth0 migration of 170M user records with zero downtime. Partnered with Data Science to productionalize ML-powered recommendation models.

**Pandora** — Part of a 4-engineer founding team that built the company's distributed message bus from scratch on Kafka. It became the foundation for all future data platform work.

**Lightspeed Venture Partners** — Founded a VC-backed startup through their fellowship. Didn't make it, but learned when to build vs. buy and how to validate before you've built anything.

**Okta** — SDR → AE Emerging → AE Corporate. Deliberately left engineering for enterprise sales to understand how customers evaluate, buy, and adopt platforms. Presidents Club 2019. Came back to engineering and it changed how I build — for adoption, not just technical elegance.

**Technical depth:** AI/ML infrastructure (multi-agent systems, agentic AI, reinforcement learning), distributed systems (Kafka, microservices), platform engineering (Auth, Identity, Notifications, Search). Computer Engineering, Santa Clara University (Dean's Scholar).

## What I'm Thinking About Lately

How to make AI agents actually useful beyond chat — the auth, permissions, and security problems nobody wants to solve. How to make agent evaluation rigorous when outputs are non-deterministic. The bottleneck shift nobody's talking about: AI tooling made our engineers 3-5x faster, but the product/design process couldn't feed them fast enough — so we had to rethink the entire development workflow, not just the engineering part. Whether the current multi-agent pattern is actually the right long-term abstraction or just the best one we have right now.
