# NatureAlpha code base

For managing projects and collaborating within NatureAlpha. Please read the guidelines and update the Repository

## Repository Overview

When starting a new repository, you are encouraged to initiative it by choosing the [template structure](https://github.com/naturealphaai/Template) from the dropdown menu.

| Repository | Description | Contact |
|------------|-------------|-------------|
| [app-tnfd](https://github.com/NatureAlphaAI/app-tnfd) | TNFD (Corp/FI) website | Carlos Mimoso |
| [libs-ts](https://github.com/NatureAlphaAI/libs-ts) | TypeScript Libraries | Carlos Mimoso |
| [libs-multiverse](https://github.com/NatureAlphaAI/libs-multiverse) | Nature+industry projects and wide-table metrics pipelines | Jasper Hajonides / Adomas Puzelevicius |
| [libs-web-scrape](https://github.com/NatureAlphaAI/libs-web-scrape) | Code for scraping information from websites | Jasper Hajonides |
| [libs-genai_materiality](https://github.com/NatureAlphaAI/libs-genai_materiality) | Generating Materiality Matrix from Research Documents | Jasper Hajonides |
| [unmanaged risk RAG](https://github.com/naturealphaai/unmanaged-risk) | Scoring of Company information and policies | Jasper Hajonides |
| [unmanaged risk web-scraping](https://github.com/naturealphaai/unmanaged-risk-web-scraping/) | Identification of Company information and policies from the web | Jasper Hajonides |
| [nature index fund](https://github.com/naturealphaai/nature_index_fund) | Using Nature Risk to compose a nature benchmark | Jasper Hajonides |
| [Footprint](https://github.com/naturealphaai/footprint) | Calculating company footprint values | Josh Gregory / Margot van Laar |
| [asset-locator](https://github.com/naturealphaai/asset-locator/tree/main) | Automated asset locator using SERP and OpenAI APIs | Jasper Hajonides / Valerie Song |
| [Revenue Splits](https://github.com/naturealphaai/revenue_splits) | Extracting revenue splits from company documents | Valerie Song |
| [Nature Insights](https://github.com/naturealphaai/NatureInsights) | Frontend for generation of case study data and Deep Research prompt | Jasper Hajonides |
| [Nature Alpha Fundamentals](https://github.com/naturealphaai/nature-alpha-fundamentals) | Set of functions used across modules | Jasper Hajonides |
| [Source of Truth](https://github.com/naturealphaai/nature-alpha-centralised-source-of-truth) | Nature Alpha source tables | Adomas Puzelevicius |
| [Python Repository Template](https://github.com/naturealphaai/Template) | Template for new Python repos | Valerie Song |
| [NatureAlpha Intelligence FRONTEND](https://github.com/naturealphaai/naturealpha-intelligence) | Chatbot frontend | Adomas Puzelevicius / Jasper Hajonides |
| [NatureAlpha Intelligence BACKEND](https://github.com/naturealphaai/naturealpha-intelligence-backend) | Chatbot capabilities backend with agentic framework | Jasper Hajonides |
| [Agentic Framework](https://github.com/naturealphaai/agents_in_action) | LangGraph agentic framework for web and research capabilities | Jasper Hajonides |
| [Nature Risk (core 2.0 generation)](https://github.com/naturealphaai/nature_risk_core_table) | Combine all modules in wide table and calculate Nature Risk | Jasper Hajonides / Adomas Puzelevicius |
| [Supply Chain](https://github.com/naturealphaai/supply_chain_repo) | Extracting supply chain information from company documents | Valerie Song |
| [Subsidiaries](https://github.com/naturealphaai/subsidiaries) | Building subsidiaries file for companies in our universe | Valerie Song |
| [MSA](https://github.com/naturealphaai/MSA_production) | Mean species abundance metric | Jasper Hajonides |
| [AWS Bedrock Credentials](https://github.com/naturealphaai/aws-bedrock-credentials) | CLI tool for managing AWS Bedrock session credentials with MFA | Nikolai Tennant |
| **[ALD Module](#ald-module)** | Asset-Level Data pipeline — 15 repos for discovery, extraction, geocoding, verification. See [detailed breakdown below](#ald-module). | Nikolai Tennant |

---

## ALD Module

**Contact:** Nikolai Tennant (all repos below unless noted)

Asset-Level Data pipeline — discovers, extracts, geocodes, verifies, and validates physical assets for corporate entities.

### Entity Resolution

| Repository | Description |
|---|---|
| [Corp Graph](https://github.com/naturealphaai/corp-graph) | Entity resolution and ownership hierarchy database (~4.6M issuers, securities, relationships) |
| [Corp Profile](https://github.com/naturealphaai/corp-profile) | Build rich company context documents from corp-graph DB or JSON files |
| [Corp Enrich](https://github.com/naturealphaai/corp-enrich) | Corporate entity enrichment (WIP) |
| [Orgchart](https://github.com/naturealphaai/orgchart) | Generate corporate org-chart PNGs from relationships CSV or corp-graph DB |

### Asset Discovery & Extraction

| Repository | Description |
|---|---|
| [Asset Discovery](https://github.com/naturealphaai/asset-discovery) | Orchestrator — 9-stage async pipeline (profile, places, discover, scrape, extract, merge, geocode, verify, QA) |
| [Places Discovery](https://github.com/naturealphaai/places-discovery) | Zero-cost location discovery from All The Places + Overture Maps + Foursquare OS |
| [Store Locator](https://github.com/naturealphaai/store-locator) | Agentic store locator scraper with LLM planner |
| [Web Scraper](https://github.com/naturealphaai/web-scraper) | Spider Cloud API wrapper with batching + proxy |
| [Doc Extractor](https://github.com/naturealphaai/doc-extractor) | LLM structured extraction via instructor |
| [RAG](https://github.com/naturealphaai/rag) | pgvector ingest + Cohere rerank retrieval |

### Geo Processing & Verification

| Repository | Description |
|---|---|
| [Geo Resolve](https://github.com/naturealphaai/geo-resolve) | Provider-agnostic geocoding with persistent cache, rate limiting, and batch support |
| [Geo Verify](https://github.com/naturealphaai/geo-verify) | Multi-signal location verification with CatBoost classifier + agentic LLM correction |

### Validation & Classification

| Repository | Description | Contact |
|---|---|---|
| [ALD Checker](https://github.com/naturealphaai/ald-checker) | Output validation and auto-fix (22 checks) | Nikolai Tennant |
| [Asset Type Assignment](https://github.com/naturealphaai/asset_type_assignment) | Map raw asset types to custom NAICS categories | Jasper Hajonides |

### Legacy (superseded by Asset Discovery)

| Repository | Description |
|---|---|
| [Asset Search](https://github.com/naturealphaai/asset-search) | Earlier 9-stage pipeline — superseded by asset-discovery |
| [Asset Crawler](https://github.com/naturealphaai/asset-crawler) | Earlier 10-stage pipeline — superseded by asset-discovery |

---

### General Guidelines

- **Documentation**:
  - Ensure each repository has a comprehensive `README.md` file.
  - At a minimum, the `README.md` should describe the repository's purpose.
  - If applicable, include instructions on how to run the code, installation steps, usage examples, and any dependencies.

- **Branching, Commits, and Issues**:
  - Write branches, commits, and issues as descriptively as possible.
  - Branches should follow a consistent naming convention, such as `feature/short-description` or `bugfix/short-description`.
  - Commit messages should be meaningful and describe what the commit does. Use the format: `type(scope): message`.
  - Issues should clearly state the problem or feature request, including relevant details and context.
  - Merge requests (MRs) should clearly describe what is being added or changed. They should be issue-specific and not aggregate months of work.
  - Ensure that each MR is focused on a single issue or feature to facilitate easier reviews and integrations.


---

*This document is a living document and will be updated regularly to reflect the current practices and guidelines of the NatureAlphaAI organisation.*
