### Software engineer working across product, backend, AI, browsers and infrastructure

I build and operate software end-to-end: product surface, application logic, backend services, data, deployment, and the failure cases that appear after release.

[LinkedIn](https://www.linkedin.com/in/abhisec-tech/) · [Email](mailto:abhisec.tech@gmail.com) · [ExploreAI](https://exploreai.tools/)

---

## Selected work

| System | State | Engineering scope |
|---|---|---|
| **Zylo Browser + VPN** | `building` | Privacy-focused browser and VPN stack spanning Flutter, GeckoView/Chromium work, native mobile SDK bridges, subscriptions, server inventory and backend services. |
| **[ExploreAI.tools](https://exploreai.tools/)** | `live` | AI discovery platform with search, structured content, programmatic SEO, backend ingestion, admin tooling and model-assisted content generation. |
| **SocialHub** | `building` | Social publishing system covering generation, review, scheduling, platform formatting, publishing and analytics workflows. |
| **INDRA / Multi-Model Orchestrator** | `research` | Classifier → scorer → orchestrator → specialized models → verifier architecture for cost-aware multi-model execution. |
| **VectorSeed / TinySVG** | `research` | Lightweight generative-model work for structured, editable SVG output with custom tokenization, validation and candidate ranking. |
| **Advocate Matrimony** | `live` | Production mobile/backend work including Fastify, MongoDB, deployment and a MySQL → MongoDB migration. |

---

## Engineering focus

I tend to spend most of my time on problems that sit between features and production:

- **State consistency** — especially across Flutter, native mobile SDKs, browsers and backend services.
- **Failure handling** — retries, fallback models, provider failure, reconnects and verification paths.
- **System boundaries** — keeping product logic, data, integrations and infrastructure independently replaceable.
- **Migrations** — treating schema, data shape, startup behavior and deployment as one change rather than separate tasks.
- **Operational simplicity** — reducing moving parts where complexity does not buy reliability or product value.

### Typical system boundary

```text
product surface
      ↓
application / client state
      ↓
API + services
      ↓
data / queues / external providers
      ↓
infrastructure + observability
```

AI is another component in that graph when it is useful; I do not treat it as the architecture by default.

---

## Public work

- **[ExploreAI.tools](https://exploreai.tools/)** — AI discovery product
- **[Hive](https://github.com/Invens/hive)** — software / AI experimentation
- **[OpenClaw](https://github.com/Invens/openclaw)** — agent / software exploration
- **[LLM Chat App Template](https://github.com/Invens/llm-chat-app-template)** — LLM application architecture experiments

A large part of my production and client work is private, so the public repository graph is only part of the engineering history below.

---

## Project catalog

<sub>55 projects across 8 areas. States are explicit: <code>live</code>, <code>building</code>, <code>private</code>, <code>prototype</code>, <code>research</code>, <code>concept</code>, <code>archive</code>.</sub>

<br/>

<details>
<summary><strong>01 · Browser · Privacy · Intelligence</strong> &nbsp;&nbsp;<code>6 projects</code></summary>
<br/>

| Project | State | Scope |
|---|---|---|
| **Zylo VPN** | `building` | Flutter VPN, subscriptions, server inventory, AtomSDK/PureWL and backend services |
| **Zylo Browser** | `building` | GeckoView/Chromium work, privacy, VPN, ad blocking, search and contextual AI |
| **Zylo / Loki DMP** | `building` | Events, profiles, segmentation, intent, recommendation and prediction infrastructure |
| **Zylo Suggestive Ads** | `prototype` | Product-intent understanding and better-value commerce recommendations |
| **Zylo Companion** | `prototype` | Contextual assistant around browsing behavior and product discovery |
| **LokiVPN Tracker** | `private` | Tracking and product utilities around the VPN ecosystem |

</details>

<details>
<summary><strong>02 · ExploreAI Ecosystem</strong> &nbsp;&nbsp;<code>5 projects</code></summary>
<br/>

| Project | State | Scope |
|---|---|---|
| **[ExploreAI.tools](https://exploreai.tools/)** | `live` | AI-tool discovery, categories, search, comparison, content and programmatic SEO |
| **ExploreAI Backend** | `private` | APIs, ingestion, categories, search, SEO data and content infrastructure |
| **ExploreAI Dashboard** | `private` | Admin control plane for tools, models, pages, SEO and generated content |
| **ExploreAI AI SEO Engine** | `private` | OpenRouter model selection/fallback for metadata, schemas and page generation |
| **ExploreAI Agent V2** | `building` | Agent-oriented frontend/backend evolution of ExploreAI |

</details>

<details>
<summary><strong>03 · AI · Research · Generative Systems</strong> &nbsp;&nbsp;<code>7 projects</code></summary>
<br/>

| Project | State | Scope |
|---|---|---|
| **INDRA / Multi-Model Orchestrator** | `research` | Classifier → scorer → orchestrator → specialized models → verifier |
| **VectorSeed / TinySVG** | `research` | Lightweight model research for structured, editable SVG generation |
| **RepoMind** | `prototype` | Repository-aware engineering agent with controlled modification and verification loops |
| **Offline / Personalized AI Engine** | `research` | Local context, intent classification, recommendation and privacy-aware personalization |
| **[Hive](https://github.com/Invens/hive)** | `prototype` | Public software / AI experimentation |
| **[OpenClaw](https://github.com/Invens/openclaw)** | `prototype` | Public agent / software exploration |
| **[LLM Chat App Template](https://github.com/Invens/llm-chat-app-template)** | `prototype` | LLM application architecture and chat-system experimentation |

</details>

<details>
<summary><strong>04 · Products · SaaS · Applications</strong> &nbsp;&nbsp;<code>11 projects</code></summary>
<br/>

| Project | State | Scope |
|---|---|---|
| **SocialHub** | `building` | AI generation, review, scheduling, publishing and analytics workflows |
| **Fluencerz** | `private` | Influencer marketing, creators, brands, campaigns, chat and admin workflows |
| **LokiSurf** | `building` | Gaming discovery, frontend, search, themes, SEO, dashboard and AI content |
| **DhanWise** | `concept` | Personal-finance intelligence, reconciled ledger and assistant workflows |
| **CleanMyBG** | `private` | Background-removal SaaS, auth, subscriptions, credits, payments and usage controls |
| **Advocate Matrimony** | `live` | Android product, Fastify/MongoDB backend, migration and deployment work |
| **IndiTeppich** | `private` | E-commerce storefront, backend, catalog and administrative workflows |
| **GrowwPaisa** | `private` | Finance/product web application with frontend and backend work |
| **Social Impact Platform** | `concept` | Discovery and documentation platform for social and humanitarian work |
| **CoupleUp** | `archive` | Relationship/matching application with frontend and backend systems |
| **Job Portal** | `prototype` | Employment marketplace and backend workflow project |

</details>

<details>
<summary><strong>05 · AdTech · Affiliate · Commerce</strong> &nbsp;&nbsp;<code>12 projects</code></summary>
<br/>

| Project | State | Scope |
|---|---|---|
| **AdStudioz Platform** | `private` | Advertising/publisher ecosystem and campaign platform components |
| **AdStudioz Tracking** | `private` | Event, attribution and conversion-tracking infrastructure |
| **Publisher.AdStudioz** | `private` | Publisher-facing advertising platform |
| **Affiliate Website Platform** | `building` | Product/comparison content, affiliate links, SEO, dashboard and Impact integration |
| **Affiliate Blog Engine** | `private` | Automated affiliate-content frontend/backend/dashboard stack |
| **DealskyPro** | `archive` | Products, reviews, deals and buying-guide platform |
| **EasyShopPrice** | `private` | Product discovery, price comparison and affiliate commerce system |
| **Amazon Affiliate Automation** | `prototype` | Affiliate product and publishing automation |
| **Trivogames / Trackier Signup Tracking** | `private` | Click-ID capture, attribution, signup pixel and campaign tracking integration |
| **DSP** | `prototype` | Demand-side advertising experiment |
| **Ads Tester** | `prototype` | Advertising integration/testing utilities |
| **Tracking Code** | `prototype` | Small attribution and tracking utility work |

</details>

<details>
<summary><strong>06 · Media · Content Automation</strong> &nbsp;&nbsp;<code>2 projects</code></summary>
<br/>

| Project | State | Scope |
|---|---|---|
| **CS Explainer Video Engine** | `prototype` | Topic → script → scenes → voice → captions → Remotion render pipeline |
| **Cat Grooming / Rescue Shorts Engine** | `building` | Repeatable 3-clip Veo storytelling and visual-continuity workflow |

</details>

<details>
<summary><strong>07 · Infrastructure · DevOps · Enterprise</strong> &nbsp;&nbsp;<code>3 projects</code></summary>
<br/>

| Project | State | Scope |
|---|---|---|
| **Lightweight Coolify-style Server Manager** | `concept` | Minimal Docker website/API management on Ubuntu |
| **Multi-Server Coolify Infrastructure** | `private` | Ubuntu, Docker, Coolify, remote servers and multi-service deployments |
| **Alonsa Group AI / Odoo System** | `concept` | Odoo workflows plus AI-assisted OCR, catalog content and publishing pipeline |

</details>

<details>
<summary><strong>08 · Earlier Builds</strong> &nbsp;&nbsp;<code>9 projects</code></summary>
<br/>

| Project | State | Scope |
|---|---|---|
| **Wedding Manage** | `archive` | Wedding/event-management application |
| **Fashion** | `archive` | Earlier fashion application project |
| **FashionApp** | `archive` | Mobile fashion application iteration |
| **DesignIndianHomes** | `archive` | Home/design platform and dashboard iterations |
| **Boots & Crampons** | `archive` | Commercial/e-commerce frontend and backend work |
| **Tally9** | `archive` | Business/accounting-oriented application |
| **Gamora / Gamora.world** | `archive` | Web/application platform across multiple iterations |
| **GreenLantern** | `archive` | Earlier public software project |
| **AR Instant App** | `archive` | Augmented-reality/mobile experiment |

</details>

---

## Stack

`Python` · `TypeScript` · `JavaScript` · `Dart` · `Node.js` · `Fastify` · `Flutter` · `PyTorch` · `MySQL` · `MongoDB` · `Redis` · `Linux` · `Docker` · `Nginx` · `Coolify`

The stack changes with the problem; architecture and operational trade-offs matter more to me than tool loyalty.

---

If something here overlaps with what you are building: [email](mailto:abhisec.tech@gmail.com) · [LinkedIn](https://www.linkedin.com/in/abhisec-tech/)