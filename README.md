<p align="center">
  <img src="./assets/casebook-cover-v1.svg" alt="Engineering casebook" width="100%" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/abhisec-tech/">LinkedIn</a>
  &nbsp;·&nbsp;
  <a href="mailto:abhisec.tech@gmail.com">Email</a>
  &nbsp;·&nbsp;
  <a href="https://exploreai.tools/">ExploreAI</a>
</p>

I work end-to-end — product surface, backend, data, deployment, and the parts that get uncomfortable once software meets production.

## open a case

<details open>
<summary><strong>01 — How do you keep VPN state consistent across Flutter, Android and iOS?</strong></summary>
<br/>

**Zylo Browser / Zylo VPN** · `building`

The UI was never the hard part. The interesting work is keeping connection state, native SDK behavior, providers, reconnects and platform bridges aligned while the product still feels simple.

`Flutter` · `Android/iOS native bridges` · `AtomSDK / PureWL` · `Node.js`

</details>

<details>
<summary><strong>02 — What should happen when the AI model fails?</strong></summary>
<br/>

**INDRA / ExploreAI AI systems** · `research + production work`

I treat model failure as normal rather than exceptional: classify the task, route it, fall back when needed, verify the output, and keep the rest of the system independent from one provider or model.

`classification` · `routing` · `fallback` · `verification` · `OpenRouter`

</details>

<details>
<summary><strong>03 — What actually breaks when a production database changes?</strong></summary>
<br/>

**Advocate Matrimony** · `live`

A MySQL → MongoDB migration changed more than storage: plugin startup, data shape, deployment behavior and backend assumptions all became part of the migration.

`Fastify` · `MongoDB` · `deployment` · `migration`

</details>

<details>
<summary><strong>04 — How much browser context is useful before it becomes invasive?</strong></summary>
<br/>

**Zylo / Loki DMP + Companion** · `building / prototype`

The moment browsing context changes recommendations, personalization becomes a privacy architecture problem. The system has to separate useful intent from unnecessary observation.

`events` · `intent` · `segmentation` · `recommendation` · `privacy boundaries`

</details>

---

## project index

<sub>55 projects across 8 areas. States are explicit: <code>live</code>, <code>building</code>, <code>private</code>, <code>prototype</code>, <code>research</code>, <code>concept</code>, <code>archive</code>.</sub>

<br/>

<a id="browser"></a>
<details>
<summary><strong>01 / browser · privacy · intelligence</strong> &nbsp; <code>06</code></summary>
<br/>

| Project | State | Notes |
|---|---|---|
| **Zylo VPN** | `building` | Flutter VPN, subscriptions, server inventory, AtomSDK/PureWL, backend services |
| **Zylo Browser** | `building` | GeckoView/Chromium, privacy, VPN, ad blocking, search, contextual AI |
| **Zylo / Loki DMP** | `building` | events, profiles, segmentation, intent, recommendation and prediction infrastructure |
| **Zylo Suggestive Ads** | `prototype` | product-intent understanding and better-value commerce recommendations |
| **Zylo Companion** | `prototype` | contextual assistant around browsing behavior and product discovery |
| **LokiVPN Tracker** | `private` | tracking and product utilities around the VPN ecosystem |

</details>

<details>
<summary><strong>02 / ExploreAI ecosystem</strong> &nbsp; <code>05</code></summary>
<br/>

| Project | State | Notes |
|---|---|---|
| **[ExploreAI.tools](https://exploreai.tools/)** | `live` | AI-tool discovery, categories, search, comparison, content and programmatic SEO |
| **ExploreAI Backend** | `private` | APIs, ingestion, categories, search, SEO data and content infrastructure |
| **ExploreAI Dashboard** | `private` | admin control plane for tools, models, pages, SEO and generated content |
| **ExploreAI AI SEO Engine** | `private` | OpenRouter model selection/fallback for metadata, schemas and page generation |
| **ExploreAI Agent V2** | `building` | agent-oriented frontend/backend evolution of ExploreAI |

</details>

<a id="ai-research"></a>
<details>
<summary><strong>03 / AI · research · generative systems</strong> &nbsp; <code>07</code></summary>
<br/>

| Project | State | Notes |
|---|---|---|
| **INDRA / Multi-Model Orchestrator** | `research` | classifier → scorer → orchestrator → specialized models → verifier |
| **VectorSeed / TinySVG** | `research` | lightweight model research for structured, editable SVG generation |
| **RepoMind** | `prototype` | repository-aware engineering agent with controlled modification and verification loops |
| **Offline / Personalized AI Engine** | `research` | local context, intent classification, recommendation and privacy-aware personalization |
| **[Hive](https://github.com/Invens/hive)** | `prototype` | public software/AI experimentation |
| **[OpenClaw](https://github.com/Invens/openclaw)** | `prototype` | public agent/software exploration |
| **[LLM Chat App Template](https://github.com/Invens/llm-chat-app-template)** | `prototype` | LLM application architecture and chat-system experimentation |

</details>

<a id="products"></a>
<details>
<summary><strong>04 / products · SaaS · applications</strong> &nbsp; <code>11</code></summary>
<br/>

| Project | State | Notes |
|---|---|---|
| **SocialHub** | `building` | AI generation, review, scheduling, publishing and analytics workflows |
| **Fluencerz** | `private` | influencer marketing, creators, brands, campaigns, chat and admin workflows |
| **LokiSurf** | `building` | gaming discovery, frontend, search, themes, SEO, dashboard and AI content |
| **DhanWise** | `concept` | personal-finance intelligence, reconciled ledger and assistant workflows |
| **CleanMyBG** | `private` | background-removal SaaS, auth, subscriptions, credits, payments and usage controls |
| **Advocate Matrimony** | `live` | Android product, Fastify/MongoDB backend, migration and deployment work |
| **IndiTeppich** | `private` | e-commerce storefront, backend, catalog and administrative workflows |
| **GrowwPaisa** | `private` | finance/product web application with frontend and backend work |
| **Social Impact Platform** | `concept` | discovery and documentation platform for social and humanitarian work |
| **CoupleUp** | `archive` | relationship/matching application with frontend and backend systems |
| **Job Portal** | `prototype` | employment marketplace and backend workflow project |

</details>

<a id="adtech"></a>
<details>
<summary><strong>05 / adtech · affiliate · commerce</strong> &nbsp; <code>12</code></summary>
<br/>

| Project | State | Notes |
|---|---|---|
| **AdStudioz Platform** | `private` | advertising/publisher ecosystem and campaign platform components |
| **AdStudioz Tracking** | `private` | event, attribution and conversion-tracking infrastructure |
| **Publisher.AdStudioz** | `private` | publisher-facing advertising platform |
| **Affiliate Website Platform** | `building` | product/comparison content, affiliate links, SEO, dashboard and Impact integration |
| **Affiliate Blog Engine** | `private` | automated affiliate-content frontend/backend/dashboard stack |
| **DealskyPro** | `archive` | products, reviews, deals and buying-guide platform |
| **EasyShopPrice** | `private` | product discovery, price comparison and affiliate commerce system |
| **Amazon Affiliate Automation** | `prototype` | affiliate product and publishing automation |
| **Trivogames / Trackier Signup Tracking** | `private` | click-ID capture, attribution, signup pixel and campaign tracking integration |
| **DSP** | `prototype` | demand-side advertising experiment |
| **Ads Tester** | `prototype` | advertising integration/testing utilities |
| **Tracking Code** | `prototype` | small attribution and tracking utility work |

</details>

<details>
<summary><strong>06 / media · content automation</strong> &nbsp; <code>02</code></summary>
<br/>

| Project | State | Notes |
|---|---|---|
| **CS Explainer Video Engine** | `prototype` | topic → script → scenes → voice → captions → Remotion render pipeline |
| **Cat Grooming / Rescue Shorts Engine** | `building` | repeatable 3-clip Veo storytelling and visual-continuity workflow |

</details>

<a id="systems-infra"></a>
<details>
<summary><strong>07 / infrastructure · DevOps · enterprise</strong> &nbsp; <code>03</code></summary>
<br/>

| Project | State | Notes |
|---|---|---|
| **Lightweight Coolify-style Server Manager** | `concept` | minimal Docker website/API management on Ubuntu |
| **Multi-Server Coolify Infrastructure** | `private` | Ubuntu, Docker, Coolify, remote servers and multi-service deployments |
| **Alonsa Group AI / Odoo System** | `concept` | Odoo workflows plus AI-assisted OCR, catalog content and publishing pipeline |

</details>

<a id="archive"></a>
<details>
<summary><strong>08 / earlier builds</strong> &nbsp; <code>09</code></summary>
<br/>

| Project | State | Notes |
|---|---|---|
| **Wedding Manage** | `archive` | wedding/event-management application |
| **Fashion** | `archive` | earlier fashion application project |
| **FashionApp** | `archive` | mobile fashion application iteration |
| **DesignIndianHomes** | `archive` | home/design platform and dashboard iterations |
| **Boots & Crampons** | `archive` | commercial/e-commerce frontend and backend work |
| **Tally9** | `archive` | business/accounting-oriented application |
| **Gamora / Gamora.world** | `archive` | web/application platform across multiple iterations |
| **GreenLantern** | `archive` | earlier public software project |
| **AR Instant App** | `archive` | augmented-reality/mobile experiment |

</details>

---

<details>
<summary><strong>tools I use often</strong></summary>
<br/>

`Python` · `TypeScript` · `JavaScript` · `Dart` · `Node.js` · `Fastify` · `Flutter` · `PyTorch` · `MySQL` · `MongoDB` · `Redis` · `Linux` · `Docker` · `Nginx` · `Coolify`

</details>

<br/>

<p align="center">
  <a href="https://www.linkedin.com/in/abhisec-tech/">LinkedIn</a> · <a href="mailto:abhisec.tech@gmail.com">abhisec.tech@gmail.com</a>
</p>