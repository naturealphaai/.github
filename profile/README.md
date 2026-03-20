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
| **ALD Module** | | |
| ↳ [Asset Discovery](https://github.com/naturealphaai/asset-discovery) | Multi-stage pipeline for discovering physical assets using LLM agents and web scraping | Nikolai Tennant |
| ↳ [ALD Checker](https://github.com/naturealphaai/ald-checker) | ALD output validation and auto-fix (22 checks) | Nikolai Tennant |
| ↳ [RAG](https://github.com/naturealphaai/rag) | pgvector ingest + Cohere rerank retrieval | Nikolai Tennant |
| ↳ [Doc Extractor](https://github.com/naturealphaai/doc-extractor) | LLM structured extraction via instructor | Nikolai Tennant |
| ↳ [Web Scraper](https://github.com/naturealphaai/web-scraper) | Spider Cloud API wrapper with batching + proxy | Nikolai Tennant |
| ↳ [Corp Profile](https://github.com/naturealphaai/corp-profile) | Build company context documents from corp-graph DB or JSON files | Nikolai Tennant |
| ↳ [Geo Resolve](https://github.com/naturealphaai/geo-resolve) | Provider-agnostic geocoding with persistent cache, rate limiting, and batch support | Nikolai Tennant |
| ↳ [Geo Verify](https://github.com/naturealphaai/geo-verify) | Multi-signal location verification with CatBoost classifier | Nikolai Tennant |
| ↳ [Places Discovery](https://github.com/naturealphaai/places-discovery) | Multi-source location discovery (ATP + Overture Maps + Foursquare) | Nikolai Tennant |
| ↳ [Orgchart](https://github.com/naturealphaai/orgchart) | Generate corporate org-chart PNGs from relationships CSV or corp-graph DB | Nikolai Tennant |
| ↳ [Store Locator](https://github.com/naturealphaai/store-locator) | Agentic store locator scraper with LLM planner | Nikolai Tennant |
| ↳ [AWS Bedrock Credentials](https://github.com/naturealphaai/aws-bedrock-credentials) | CLI tool for managing AWS Bedrock session credentials with MFA | Nikolai Tennant |
| ↳ [Corp Enrich](https://github.com/naturealphaai/corp-enrich) | Corporate entity enrichment (WIP) | Nikolai Tennant |
| ↳ [Corp Graph](https://github.com/naturealphaai/corp-graph) | Corporate entity resolution and ownership hierarchy database | Nikolai Tennant |
| ↳ [Asset Type Assignment (custom naics)](https://github.com/naturealphaai/asset_type_assignment) | convert raw asset types to our custom naics categories | Jasper Hajonides |




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
