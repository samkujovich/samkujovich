# Sam Kujovich

Engineering leader focused on AI products, platform infrastructure, and scaling teams that ship.

Director of Software Engineering at [A Place for Mom](https://www.aplaceformom.com), leading 12 engineers across AI Product and B2B Platform.

## What I'm Building

I lead the team behind **Grace** — a production multi-agent system powering an AI-native senior care marketplace. We shipped a B2C marketplace and an agency-facing B2B portal in back-to-back 8-week sprints.

A few of the architectural decisions I'm most interested in: hexagonal (ports & adapters) so we can swap LLM providers without touching business logic, composable prompt packs with filesystem fallback for resilience, and a two-layer guardrail system — fast pattern matching for known risks, then LLM evaluation with fallback models running synchronously on every turn. Agency matching uses a contextual bandit that learns from real user outcomes rather than static rules.

The bigger strategic problem I'm working on now: moving from "AI team builds all agents" to building an internal platform/SDK with shared guardrails, evaluations, and agent primitives. The goal is enabling product teams to build their own AI capabilities without reinventing safety and observability every time.

## Featured Project

### [prd-decomposer](https://github.com/samkujovich/prd-decomposer)
MCP server that takes a product requirements doc and decomposes it into Jira-ready epics and stories. Built with OpenAI Agents SDK. The part I'm most interested in is the eval suite — how do you measure whether a PRD was "correctly" decomposed? That's a harder problem than the decomposition itself.

## Background

**5 years of engineering leadership**, Manager → Sr Manager → Director across MarTech, Platform, and AI teams. Hired and developed 15+ engineers from IC to Principal level.

**A Place for Mom** — Director of Software Engineering. Present product strategy to CEO and executive leadership. Before the AI initiative, transformed a 21-person platform org: KTLO from 45% to 19%, P0 incidents from ~1/week to 1/year, delivery lead time from 20+ days to 6 days. Rebuilt the leadership team across an 18-month transformation — hired a QA Manager, Sr Manager, 2 Principals, 2 Staff Engineers, and promoted from within.

**Realtor.com** — Manager → Sr Manager across three teams that grew to 18 engineers (Auth, Identity, Notifications, MarTech). Founded the MarTech org from zero. Scaled Notifications from a single-use system to a company-wide platform doing 4B+ quarterly. Led Auth0 migration of 170M user records with zero downtime. Partnered with Data Science to productionalize ML-powered recommendation models.

**Pandora** — Part of a 4-engineer founding team that built the company's distributed message bus from scratch on Kafka. It became the foundation for all future data platform work.

**Lightspeed Venture Partners** — Founded a VC-backed startup through their fellowship. Didn't make it, but learned when to build vs. buy and how to validate before you've built anything.

**Okta** — SDR → AE Emerging → AE Corporate. Deliberately left engineering for enterprise sales to understand how customers evaluate, buy, and adopt platforms. Presidents Club 2019. Came back to engineering and it changed how I build — for adoption, not just technical elegance.

**Technical depth:** AI/ML infrastructure (multi-agent systems, agentic AI, reinforcement learning), distributed systems (Kafka, microservices), platform engineering (Auth, Identity, Notifications, Search). Computer Engineering, Santa Clara University (Dean's Scholar).

## What I'm Thinking About Lately

How to make agent evaluation rigorous when outputs are non-deterministic. The organizational design problem of platformizing AI capabilities (who owns what, where are the boundaries). The bottleneck shift nobody's talking about: AI tooling made our engineers 3-5x faster, but the product/design process couldn't feed them fast enough — so we had to rethink the entire development workflow, not just the engineering part. Whether the current multi-agent pattern is actually the right long-term abstraction or just the best one we have right now.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/samkujovich/)
