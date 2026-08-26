<h1 align="center">Awesome n8n Community Nodes</h1>

<p align="center">
  <strong>Community-built integrations and utilities for n8n, organized around what you want to automate.</strong>
</p>

<p align="center">
  <a href="https://awesome.re"><img alt="Awesome" src="https://awesome.re/badge.svg"></a>
  <img alt="n8n community nodes" src="https://img.shields.io/badge/n8n-community%20nodes-ff6d5a">
  <a href="LICENSE"><img alt="CC0 1.0 license" src="https://img.shields.io/badge/license-CC0%201.0-555555"></a>
</p>

Discover community node packages that extend n8n with integrations, triggers, AI tools, data services, and workflow utilities. Each entry links to the package on npm and to its public source repository when one is available.

This is a curated directory, not an endorsement or a security audit. Community nodes run third-party code in your n8n instance. Review the source, release history, permissions, dependencies, and license before installing anything, and test new packages in a non-production environment.

## Contents

- [Install a community node](#install-a-community-node)
- [AI, Agents and Search](#ai-agents-and-search)
- [Browser, Web and Scraping](#browser-web-and-scraping)
- [Communication and Messaging](#communication-and-messaging)
- [Data, Storage and Observability](#data-storage-and-observability)
- [Documents, Media and Productivity](#documents-media-and-productivity)
- [CRM and Sales](#crm-and-sales)
- [Utilities](#utilities)
- [Legend](#legend)
- [Contributing](#contributing)
- [Maintainer](#maintainer)

## Install a community node

Follow n8n's [official installation and management guide](https://docs.n8n.io/integrations/community-nodes/installation/) for the n8n version and hosting mode you use. Copy the exact npm package name from a row below, then read the package's own documentation for credentials, configuration, supported operations, and compatibility.

You can browse the wider ecosystem through npm's [`n8n-community-node-package` search](https://www.npmjs.com/search?q=keywords%3An8n-community-node-package). A package appearing in npm search does not by itself mean that it has been reviewed or is safe to run.

## AI, Agents and Search

| Package | What it adds | Source | Tags |
| --- | --- | --- | --- |
| [`n8n-nodes-a2a`](https://www.npmjs.com/package/n8n-nodes-a2a) | Connect n8n to A2A account transfers and Google Agent2Agent workflows, with file uploads, custom fields, requests, and streaming. | - | `community` `ai-agents` `agent-protocol` |
| [`n8n-nodes-ai-media-generate`](https://www.npmjs.com/package/n8n-nodes-ai-media-generate) | Generate images and videos through multiple AI media providers. | [GitHub](https://github.com/MaskerPRC/n8n-nodes-ai-media-generate) | `community` `ai` `media` |
| [`n8n-nodes-aimlapi`](https://www.npmjs.com/package/n8n-nodes-aimlapi) | Call AIMLAPI for LLM and multimodal chat-completion operations. | [GitHub](https://github.com/D1m7asis/n8n-nodes-aimlapi) | `community` `ai` `llm` |
| [`n8n-nodes-aiscraper`](https://www.npmjs.com/package/n8n-nodes-aiscraper) | Call Parsera's AI scraping API from n8n workflows. | [GitHub](https://github.com/parsera-labs/n8n-parsera) | `community` `ai` `web-scraping` |
| [`n8n-nodes-aistudio`](https://www.npmjs.com/package/n8n-nodes-aistudio) | Use Gemini API operations from n8n workflows. | - | `community` `gemini` `ai` |
| [`@aws/n8n-nodes-agentcore`](https://www.npmjs.com/package/@aws/n8n-nodes-agentcore) | Run Amazon Bedrock AgentCore harnesses with managed memory, isolated browser/code/MCP tools, persistent sessions, and structured agent output. | [GitHub](https://github.com/aws/n8n-nodes-agentcore) | `official` `ai` `agents` |
| [`n8n-nodes-backstage`](https://www.npmjs.com/package/n8n-nodes-backstage) | Query Backstage's software catalog, TechDocs, and service relationships, with selected operations exposed as AI tools through backctl MCP. | [GitHub](https://github.com/jsolana/n8n-nodes-backstage) | `community` `developer-tools` `mcp` |
| [`@brave/n8n-nodes-brave-search`](https://www.npmjs.com/package/@brave/n8n-nodes-brave-search) | Search Brave web, image, news, video, and local results, with spell check, suggestions, and LLM context. | [GitHub](https://github.com/brave/n8n-nodes-brave-search) | `official` `search` `ai` |
| [`n8n-nodes-cognee`](https://www.npmjs.com/package/n8n-nodes-cognee) | Add data to Cognee datasets, build knowledge-graph memory, search it, and delete datasets or items. | [GitHub](https://github.com/topoteretes/cognee-integrations/tree/main/integrations/n8n) | `official` `ai-memory` `knowledge-graph` |
| [`@vorionsys/n8n-nodes-cognigate`](https://www.npmjs.com/package/@vorionsys/n8n-nodes-cognigate) | Apply Cognigate AI-agent trust scoring, capability enforcement, and audit-proof logging through the BASIS standard. | [GitHub](https://github.com/vorionsys/n8n-nodes-cognigate) | `community` `ai-governance` `security` |
| [`n8n-nodes-comfyui-all`](https://www.npmjs.com/package/n8n-nodes-comfyui-all) | Execute ComfyUI workflows with dynamic parameter support. | [GitHub](https://github.com/ksxh0524/n8n-nodes-comfyui-all) | `community` `image-generation` `ai` |
| [`n8n-nodes-dataforseo`](https://www.npmjs.com/package/n8n-nodes-dataforseo) | Automate SERP, keyword, backlink, domain, on-page, content, merchant, app, and business research through DataForSEO APIs. | [GitHub](https://github.com/dataforseo/n8n-nodes-dataforseo) | `official` `seo` `search` |
| [`n8n-nodes-deepseek`](https://www.npmjs.com/package/n8n-nodes-deepseek) | Use DeepSeek through an OpenAI-like n8n AI node. | [GitHub](https://github.com/rubickecho/n8n-deepseek) | `community` `ai` `llm` |
| [`n8n-nodes-duckduckgo-search`](https://www.npmjs.com/package/n8n-nodes-duckduckgo-search) | Search DuckDuckGo web, image, news, and video results, with optional page-text extraction. | [GitHub](https://github.com/samnodehi/n8n-nodes-duckduckgo) | `community` `search` `web` |
| [`@e2b/n8n-nodes-e2b`](https://www.npmjs.com/package/@e2b/n8n-nodes-e2b) | Create and manage E2B cloud sandboxes and snapshots, then run commands from n8n workflows and AI agents. | [GitHub](https://github.com/e2b-dev/n8n-nodes-e2b) | `official` `agents` `sandboxes` |
| [`@elevenlabs/n8n-nodes-elevenlabs`](https://www.npmjs.com/package/@elevenlabs/n8n-nodes-elevenlabs) | Add ElevenLabs text-to-speech, speech-to-text, speech-to-speech, and voice-management operations. | [GitHub](https://github.com/elevenlabs/elevenlabs-n8n) | `official` `ai` `voice` |
| [`@gotohuman/n8n-nodes-gotohuman`](https://www.npmjs.com/package/@gotohuman/n8n-nodes-gotohuman) | Request human reviews and approvals inside AI workflows with gotoHuman. | [GitHub](https://github.com/gotohuman/n8n-nodes-gotohuman) | `community` `human-review` `approvals` |
| [`@langfuse/n8n-nodes-langfuse`](https://www.npmjs.com/package/@langfuse/n8n-nodes-langfuse) | Fetch versioned Langfuse prompts into n8n workflows for cloud or self-hosted Langfuse projects. | [GitHub](https://github.com/langfuse/n8n-nodes-langfuse) | `official` `ai` `prompts` |
| [`n8n-nodes-mcp`](https://www.npmjs.com/package/n8n-nodes-mcp) | Connect n8n to Model Context Protocol servers and use their tools, resources, and prompts. | [GitHub](https://github.com/nerding-io/n8n-nodes-mcp) | `community` `mcp` `agents` |
| [`@mixpeek/n8n-nodes-mixpeek`](https://www.npmjs.com/package/@mixpeek/n8n-nodes-mixpeek) | Process text, web pages, images, video, and files with multimodal inference, semantic search, classification, and clustering. | [GitHub](https://github.com/mixpeek/connectors) | `official` `multimodal` `search` |
| [`n8n-nodes-nilai`](https://www.npmjs.com/package/n8n-nodes-nilai) | Use Nillion nilAI for private OpenAI-compatible LLM inference with local response-signature and TEE-attestation verification. | [GitHub](https://github.com/NillionNetwork/n8n-nodes-nilai) | `official` `private-ai` `security` |
| [`n8n-nodes-openai-structured-outputs`](https://www.npmjs.com/package/n8n-nodes-openai-structured-outputs) | Extract structured JSON from unstructured text with an OpenAI JSON Schema. | [GitHub](https://github.com/crucerlabs/n8n-nodes-openai-structured-outputs) | `community` `openai` `structured-data` |
| [`n8n-nodes-openrouter-official`](https://www.npmjs.com/package/n8n-nodes-openrouter-official) | Use OpenRouter for multimodal actions plus LangChain embeddings and document reranking. | [GitHub](https://github.com/nguyenthieutoan/n8n-nodes-openrouter-official) | `community` `openrouter` `rag` |
| [`n8n-nodes-praisonai`](https://www.npmjs.com/package/n8n-nodes-praisonai) | Run PraisonAI agents and multi-agent workflows from n8n. | [GitHub](https://github.com/MervinPraison/n8n-nodes-praisonai) | `community` `ai-agents` `llm` |
| [`@searchapi/n8n-nodes-searchapi`](https://www.npmjs.com/package/@searchapi/n8n-nodes-searchapi) | Query structured results from Google, Bing, YouTube, Amazon, and other supported engines through SearchApi.io. | [GitHub](https://github.com/SearchApi/n8n-nodes-searchapi) | `community` `search` `serp` |
| [`n8n-nodes-serpapi`](https://www.npmjs.com/package/n8n-nodes-serpapi) | Query SerpApi search engine results from n8n workflows. | [GitHub](https://github.com/serpapi/n8n-nodes-serpapi) | `official` `search` `seo` |
| [`n8n-nodes-siliconflow-ai`](https://www.npmjs.com/package/n8n-nodes-siliconflow-ai) | Use SiliconFlow for chat, vision, embeddings, image, reranking, TTS, speech-to-text, video generation, and LangChain chat models. | [GitHub](https://github.com/nam2009/n8n-nodes-siliconflow-ai) | `community` `multimodal` `ai` |
| [`@tavily/n8n-nodes-tavily`](https://www.npmjs.com/package/@tavily/n8n-nodes-tavily) | Search, extract, crawl, map, and research web content with Tavily. | [GitHub](https://github.com/tavily-ai/tavily-n8n-node) | `official` `search` `research` |
| [`@telnyx/n8n-nodes-telnyx-ai`](https://www.npmjs.com/package/@telnyx/n8n-nodes-telnyx-ai) | Add Telnyx AI and voice capabilities to n8n workflows. | [GitHub](https://github.com/team-telnyx/n8n-nodes-telnyx-ai) | `official` `ai` `voice` |
| [`n8n-nodes-transcript-lol`](https://www.npmjs.com/package/n8n-nodes-transcript-lol) | Transcribe audio and video with Transcript.lol. | [GitHub](https://github.com/transcript-lol/n8n-nodes-transcript-lol) | `community` `transcription` `speech` |

## Browser, Web and Scraping

| Package | What it adds | Source | Tags |
| --- | --- | --- | --- |
| [`@apify/n8n-nodes-apify`](https://www.npmjs.com/package/@apify/n8n-nodes-apify) | Connect n8n workflows to Apify's actors, datasets, and web-automation platform. | [GitHub](https://github.com/apify/n8n-nodes-apify) | `official` `web-scraping` `automation` |
| [`@brightdata/n8n-nodes-brightdata`](https://www.npmjs.com/package/@brightdata/n8n-nodes-brightdata) | Use Bright Data Web Unlocker, Marketplace Dataset, and Web Scraper APIs from n8n, including dataset snapshots and AI-agent use. | [GitHub](https://github.com/brightdata/n8n-nodes-brightdata) | `community` `web-scraping` `datasets` |
| [`n8n-nodes-browserflow`](https://www.npmjs.com/package/n8n-nodes-browserflow) | Automate Browserflow LinkedIn profile checks, scraping, connection invites, chat history, and messages. | [GitHub](https://github.com/Browserflow-io/browserflow-n8n) | `official` `linkedin` `browser` |
| [`n8n-nodes-browserless`](https://www.npmjs.com/package/n8n-nodes-browserless) | Connect n8n workflows to the Browserless browser automation platform. | [GitHub](https://github.com/minhlucvan/n8n-nodes-browserless) | `community` `browser` `web-scraping` |
| [`@mendable/n8n-nodes-firecrawl`](https://www.npmjs.com/package/@mendable/n8n-nodes-firecrawl) | Use Firecrawl's official node for search, map, scrape, crawl, extract, usage, and AI-agent tool operations. | [GitHub](https://github.com/firecrawl/n8n-nodes-firecrawl) | `official` `web-scraping` `ai` |
| [`n8n-nodes-firecrawl`](https://www.npmjs.com/package/n8n-nodes-firecrawl) | Crawl and extract web content with Firecrawl. | [GitHub](https://github.com/minhlucvan/n8n-nodes-firecrawl) | `community` `web-scraping` `content` |
| [`n8n-nodes-puppeteer`](https://www.npmjs.com/package/n8n-nodes-puppeteer) | Automate a browser with Puppeteer, including scraping, screenshots, scripts, and PDF output. | [GitHub](https://github.com/drudge/n8n-nodes-puppeteer) | `community` `browser` `automation` |
| [`n8n-nodes-scrapeless`](https://www.npmjs.com/package/n8n-nodes-scrapeless) | Run Scrapeless web-search and crawler workflows from n8n. | [GitHub](https://github.com/scrapeless-ai/n8n-nodes-scrapeless) | `official` `web-scraping` `search` |
| [`n8n-nodes-scraperapi-official`](https://www.npmjs.com/package/n8n-nodes-scraperapi-official) | Scrape and structure web data with ScraperAPI, including browser rendering, structured endpoints, crawler jobs, and reusable AI parsers. | [GitHub](https://github.com/scraperapi/n8n-nodes-scraperapi-official) | `official` `web-scraping` `structured-data` |
| [`n8n-nodes-webpage-content-extractor`](https://www.npmjs.com/package/n8n-nodes-webpage-content-extractor) | Extract the main content from a URL in a browser-reader style, omitting common page chrome. | [GitHub](https://github.com/Savjee/n8n-nodes-webpage-content-extractor) | `community` `web` `content` |
| [`n8n-nodes-whoisfreaks`](https://www.npmjs.com/package/n8n-nodes-whoisfreaks) | Automate WHOIS, DNS, SSL, subdomain, availability, typo-squat, geolocation, and IP-reputation lookups. | [GitHub](https://github.com/WhoisFreaks/n8n-nodes-whoisfreaks) | `community` `domain-intelligence` `security` |

## Communication and Messaging

| Package | What it adds | Source | Tags |
| --- | --- | --- | --- |
| [`n8n-nodes-alive5`](https://www.npmjs.com/package/n8n-nodes-alive5) | Send Alive5 SMS messages and trigger workflows when new messages arrive, with webhook lifecycle management. | [GitHub](https://github.com/wearealive5/n8n-nodes-alive5) | `official` `sms` `trigger` |
| [`n8n-nodes-chat-data`](https://www.npmjs.com/package/n8n-nodes-chat-data) | Manage Chatdata chatbots, send messages, and retrieve leads from n8n. | [GitHub](https://github.com/chat-data-llc/n8n-nodes-chat-data) | `community` `chatbot` `messaging` |
| [`n8n-nodes-chatwoot`](https://www.npmjs.com/package/n8n-nodes-chatwoot) | Use Chatwoot conversations and customer-support workflows from n8n. | [GitHub](https://github.com/sufficit/n8n-nodes-chatwoot) | `community` `support` `messaging` |
| [`n8n-nodes-evolution-api`](https://www.npmjs.com/package/n8n-nodes-evolution-api) | Connect to Evolution API, a WhatsApp-focused channel hub. | [GitHub](https://github.com/oriondesign2015/n8n-nodes-evolution-api) | `community` `whatsapp` `messaging` |
| [`n8n-nodes-evolution-api-media-downloader`](https://www.npmjs.com/package/n8n-nodes-evolution-api-media-downloader) | Download media from Evolution API message data. | - | `community` `whatsapp` `media` |
| [`n8n-nodes-feishu-lark`](https://www.npmjs.com/package/n8n-nodes-feishu-lark) | Automate Feishu/Lark bots, event triggers, message parsing, streaming, human-in-the-loop waits, and MCP calls. | [GitHub](https://github.com/zhgqthomas/n8n-nodes-feishu-lark) | `community` `feishu` `mcp` |
| [`n8n-nodes-imap`](https://www.npmjs.com/package/n8n-nodes-imap) | Connect to an IMAP server and retrieve email. | [GitHub](https://github.com/umanamente/n8n-nodes-imap) | `community` `email` `trigger` |
| [`n8n-nodes-max`](https://www.npmjs.com/package/n8n-nodes-max) | Send Max messenger messages, receive webhooks, manage attachments, and build interactive bot workflows with the Max Bot API. | [GitHub](https://github.com/pfrankov/n8n-nodes-max) | `community` `messaging` `chatbot` |
| [`n8n-nodes-megaapi`](https://www.npmjs.com/package/n8n-nodes-megaapi) | Automate MegaAPI WhatsApp messaging, groups, media, and webhooks. | - | `community` `whatsapp` `messaging` |
| [`n8n-nodes-notificame-hub`](https://www.npmjs.com/package/n8n-nodes-notificame-hub) | Automate communication across multiple channels through NotificaMe Hub. | [GitHub](https://github.com/oriondesign2015/n8n-nodes-notificame-hub) | `community` `messaging` `multichannel` |
| [`n8n-nodes-pushinator`](https://www.npmjs.com/package/n8n-nodes-pushinator) | Connect n8n workflows to the Pushinator notification service. | [GitHub](https://github.com/appricos/pushinator-n8n) | `community` `notifications` `messaging` |
| [`n8n-nodes-quepasa`](https://www.npmjs.com/package/n8n-nodes-quepasa) | Use Quepasa v4 or later in n8n workflows. | [GitHub](https://github.com/sufficit/n8n-nodes-quepasa) | `community` `whatsapp` `messaging` |
| [`n8n-nodes-resend`](https://www.npmjs.com/package/n8n-nodes-resend) | Send email and manage Resend contacts, domains, templates, broadcasts, webhooks, and events. | [GitHub](https://github.com/resend/n8n-nodes-resend) | `official` `email` `messaging` |
| [`n8n-nodes-stevomanager`](https://www.npmjs.com/package/n8n-nodes-stevomanager) | Connect to the StevoManager WhatsApp-focused channel hub. | - | `community` `whatsapp` `messaging` |
| [`n8n-nodes-tallyforms`](https://www.npmjs.com/package/n8n-nodes-tallyforms) | Trigger workflows when a Tally form receives a new submission and pass the submission data downstream. | [GitHub](https://github.com/tallyforms/n8n-nodes-tallyforms) | `official` `forms` `trigger` |
| [`n8n-nodes-thang-zalo-app`](https://www.npmjs.com/package/n8n-nodes-thang-zalo-app) | Add Zalo integration nodes for n8n workflows. | - | `community` `zalo` `messaging` |
| [`@yuniruyuni/n8n-nodes-twitch`](https://www.npmjs.com/package/@yuniruyuni/n8n-nodes-twitch) | Connect to the Twitch API, including operations and EventSub triggers. | [GitHub](https://github.com/yuniruyuni/n8n-nodes-twitch) | `community` `streaming` `webhooks` |
| [`n8n-nodes-typebot`](https://www.npmjs.com/package/n8n-nodes-typebot) | Manage Typebot chat sessions, bots, results, workspaces, and folders from n8n. | [GitHub](https://github.com/achiya-automation/n8n-nodes-typebot) | `community` `chatbot` `messaging` |
| [`@devlikeapro/n8n-nodes-waha`](https://www.npmjs.com/package/@devlikeapro/n8n-nodes-waha) | Connect n8n to WAHA's WhatsApp HTTP API. | [GitHub](https://github.com/devlikeapro/n8n-nodes-waha) | `community` `whatsapp` `messaging` |
| [`n8n-nodes-webhookrelay`](https://www.npmjs.com/package/n8n-nodes-webhookrelay) | Receive webhooks and inbound email in self-hosted n8n over an outbound WebSocket connection. | [GitHub](https://github.com/webhookrelay/n8n-nodes-webhookrelay) | `official` `webhooks` `email` |
| [`n8n-nodes-wecom`](https://www.npmjs.com/package/n8n-nodes-wecom) | Automate WeCom (WeChat Work) messages, contacts, documents, approvals, and callback triggers. | [GitHub](https://github.com/funcodingdev/n8n-nodes-wecom) | `community` `wechat-work` `messaging` |
| [`n8n-nodes-whatsable`](https://www.npmjs.com/package/n8n-nodes-whatsable) | Use WhatsAble's WhatsApp messaging API from n8n. | [GitHub](https://github.com/Whatsable/n8n-nodes-whatsable) | `community` `whatsapp` `messaging` |
| [`n8n-nodes-wuzapi`](https://www.npmjs.com/package/n8n-nodes-wuzapi) | Connect n8n to the Wuzapi WhatsApp multi-device REST API. | - | `community` `whatsapp` `messaging` |
| [`n8n-nodes-zapi`](https://www.npmjs.com/package/n8n-nodes-zapi) | Use Z-API for WhatsApp messaging workflows. | [GitHub](https://github.com/leandcesar/n8n-nodes-zapi) | `community` `whatsapp` `messaging` |
| [`n8n-nodes-zohozeptomail`](https://www.npmjs.com/package/n8n-nodes-zohozeptomail) | Use Zoho ZeptoMail for transactional email workflows. | [GitHub](https://github.com/zohomail/zoho_zeptomail_n8n) | `official` `email` `transactional` |

## Data, Storage and Observability

| Package | What it adds | Source | Tags |
| --- | --- | --- | --- |
| [`n8n-nodes-actual`](https://www.npmjs.com/package/n8n-nodes-actual) | Automate Actual Budget months, transactions, imports, and category budgets. | [GitHub](https://github.com/TheFehr/n8n-nodes-actual) | `community` `finance` `budgeting` |
| [`n8n-nodes-binance`](https://www.npmjs.com/package/n8n-nodes-binance) | Connect n8n workflows to Binance Exchange operations. | [GitHub](https://github.com/germanynick/n8n-nodes-binance) | `community` `finance` `crypto` |
| [`n8n-nodes-cloudflare`](https://www.npmjs.com/package/n8n-nodes-cloudflare) | Manage Cloudflare DNS, Workers, R2, D1, KV, Pages, Vectorize, Zero Trust, security, analytics, and more. | [GitHub](https://github.com/Automations-Project/n8n-nodes-cloudflare) | `community` `cloudflare` `infrastructure` |
| [`n8n-nodes-cnpj`](https://www.npmjs.com/package/n8n-nodes-cnpj) | Look up Brazilian company details using a CNPJ. | [GitHub](https://github.com/Integreme/integreme-cnpj) | `community` `company-data` `brazil` |
| [`n8n-nodes-datastore`](https://www.npmjs.com/package/n8n-nodes-datastore) | Store and retrieve data within an n8n workflow. | [GitHub](https://github.com/korotovsky/n8n-nodes-datastore) | `community` `storage` `data` |
| [`n8n-nodes-firebird`](https://www.npmjs.com/package/n8n-nodes-firebird) | Query Firebird databases from n8n. | [GitHub](https://github.com/anantanandgupta/n8n-nodes-firebird) | `community` `database` `sql` |
| [`@globalping/n8n-nodes-globalping`](https://www.npmjs.com/package/@globalping/n8n-nodes-globalping) | Run ping, traceroute, MTR, HTTP, and DNS measurements from locations around the world. | [GitHub](https://github.com/jsdelivr/n8n-nodes-globalping) | `official` `networking` `observability` |
| [`@justbrunasso/n8n-nodes-glpi`](https://www.npmjs.com/package/@justbrunasso/n8n-nodes-glpi) | Connect to the GLPI REST API for GLPI 9.x and later. | [GitHub](https://github.com/PhyBruno/n8n-nodes-glpi) | `community` `it-management` `rest` |
| [`n8n-nodes-hostinger-api`](https://www.npmjs.com/package/n8n-nodes-hostinger-api) | Manage Hostinger VPSs, domains/DNS, monitoring, networking, backups, billing, and Reach email marketing. | [GitHub](https://github.com/hostinger/api-n8n-node) | `official` `hosting` `infrastructure` |
| [`n8n-nodes-liveblocks`](https://www.npmjs.com/package/n8n-nodes-liveblocks) | Manage Liveblocks rooms, storage, comments, threads, notifications, AI knowledge, and webhook triggers. | [GitHub](https://github.com/liveblocks/n8n-nodes-liveblocks) | `official` `realtime` `webhooks` |
| [`n8n-nodes-minio`](https://www.npmjs.com/package/n8n-nodes-minio) | Connect n8n workflows to MinIO object storage. | [GitHub](https://github.com/cedricziel/n8n-nodes-minio) | `community` `object-storage` `s3` |
| [`n8n-nodes-mongodb-vector-search`](https://www.npmjs.com/package/n8n-nodes-mongodb-vector-search) | Add MongoDB Atlas vector search, schema-aware AI search, standard queries, and custom aggregations. | [GitHub](https://github.com/DanEvenSegler/n8n-nodes-mongodb-vector-search) | `community` `vector-database` `ai` |
| [`n8n-nodes-powerbi`](https://www.npmjs.com/package/n8n-nodes-powerbi) | Manage Power BI reports, dashboards, datasets, DAX queries, refreshes, exports, gateways, and dataflows. | [GitHub](https://github.com/And-Rochaa/n8n-nodes-powerbi) | `community` `business-intelligence` `microsoft` |
| [`n8n-nodes-pocketbase`](https://www.npmjs.com/package/n8n-nodes-pocketbase) | Work with PocketBase collections and subscribe to create, update, and delete events through its beta trigger. | [GitHub](https://github.com/TheFehr/n8n-nodes-pocketbase) | `community` `backend` `database` |
| [`@probo/n8n-nodes-probo`](https://www.npmjs.com/package/@probo/n8n-nodes-probo) | Automate Probo GRC workflows over GraphQL, including controls, documents, risks, vendors, tasks, and compliance webhooks. | [GitHub](https://github.com/getprobo/probo) | `official` `compliance` `security` |
| [`n8n-nodes-qdrant`](https://www.npmjs.com/package/n8n-nodes-qdrant) | Interface with Qdrant for vector search and data operations. | [GitHub](https://github.com/qdrant/n8n-nodes-qdrant) | `official` `vector-database` `ai` |
| [`n8n-nodes-seats-aero`](https://www.npmjs.com/package/n8n-nodes-seats-aero) | Query seats.aero travel data from n8n workflows. | - | `community` `travel` `search` |
| [`n8n-nodes-synology`](https://www.npmjs.com/package/n8n-nodes-synology) | Automate Synology Drive files and folders plus Note Station content from n8n. | [GitHub](https://github.com/khoazero123/n8n-nodes-synology) | `community` `nas` `storage` |
| [`@biztory/n8n-nodes-tableau-rest-api`](https://www.npmjs.com/package/@biztory/n8n-nodes-tableau-rest-api) | Manage Tableau Server or Cloud workbooks, views, data sources, flows, projects, users, and VizQL queries. | [GitHub](https://github.com/biztory/n8n-nodes-tableau-rest-api) | `community` `business-intelligence` `tableau` |
| [`n8n-nodes-trino`](https://www.npmjs.com/package/n8n-nodes-trino) | Execute SQL queries against Trino and return result rows as n8n items. | [GitHub](https://github.com/Dmsrdnv/n8n-nodes-trino) | `community` `sql` `analytics` |

## Documents, Media and Productivity

| Package | What it adds | Source | Tags |
| --- | --- | --- | --- |
| [`n8n-nodes-adeu`](https://www.npmjs.com/package/n8n-nodes-adeu) | Extract DOCX to Markdown, apply tracked changes, generate diffs, and finalize documents for AI-assisted workflows. | [GitHub](https://github.com/dealfluence/adeu) | `community` `documents` `ai` |
| [`n8n-nodes-assemblyai`](https://www.npmjs.com/package/n8n-nodes-assemblyai) | Transcribe and analyze audio with AssemblyAI speech models, diarization, PII redaction, and speech understanding. | [GitHub](https://github.com/gsharp-aai/n8n-nodes-assemblyai) | `community` `speech-to-text` `ai` |
| [`n8n-nodes-awork`](https://www.npmjs.com/package/n8n-nodes-awork) | Automate project and work-management workflows through the awork API. | [GitHub](https://github.com/awork-io/n8n-nodes-awork) | `community` `project-management` `productivity` |
| [`@blotato/n8n-nodes-blotato`](https://www.npmjs.com/package/@blotato/n8n-nodes-blotato) | Create AI visuals and publish or schedule content across social platforms through Blotato's unified API. | [GitHub](https://github.com/Blotato-Inc/n8n-nodes-blotato) | `official` `social-media` `content` |
| [`@cloudconvert/n8n-nodes-cloudconvert`](https://www.npmjs.com/package/@cloudconvert/n8n-nodes-cloudconvert) | Convert files, create thumbnails, add watermarks, capture websites, merge PDFs, and create archives. | [GitHub](https://github.com/cloudconvert/n8n-nodes-cloudconvert) | `official` `documents` `media` |
| [`n8n-nodes-cloudinary`](https://www.npmjs.com/package/n8n-nodes-cloudinary) | Upload media and update Cloudinary asset tags and metadata. | [GitHub](https://github.com/cloudinary/n8n-nodes-cloudinary) | `official` `media` `storage` |
| [`@custom-js/n8n-nodes-pdf-toolkit`](https://www.npmjs.com/package/@custom-js/n8n-nodes-pdf-toolkit) | Interact with the customjs.space PDF Toolkit API from n8n. | [GitHub](https://github.com/customjs/n8n-nodes-pdf-toolkit) | `community` `pdf` `documents` |
| [`n8n-nodes-diariz`](https://www.npmjs.com/package/n8n-nodes-diariz) | Trigger on Diariz events and manage self-hosted meeting recordings, transcripts, speaker diarization, search, action items, and chat. | [GitHub](https://github.com/kenhayward/Diariz/tree/main/integrations/n8n-nodes-diariz) | `community` `meetings` `transcription` |
| [`@docuseal/n8n-nodes-docuseal`](https://www.npmjs.com/package/@docuseal/n8n-nodes-docuseal) | Create and update DocuSeal signature requests from templates, DOCX, HTML, or PDF, with signing triggers. | [GitHub](https://github.com/docusealco/n8n-nodes-docuseal) | `official` `esignature` `documents` |
| [`n8n-nodes-docx-converter`](https://www.npmjs.com/package/n8n-nodes-docx-converter) | Convert DOCX documents to text. | [GitHub](https://github.com/cre8tiv/n8n-docx-converter) | `community` `docx` `documents` |
| [`n8n-nodes-docx-filler`](https://www.npmjs.com/package/n8n-nodes-docx-filler) | Create and fill DOCX/PDF templates, and extract document content. | - | `community` `docx` `pdf` |
| [`n8n-nodes-document-generator`](https://www.npmjs.com/package/n8n-nodes-document-generator) | Create dynamic document or email content with Handlebars templates. | [GitHub](https://github.com/n8nhackers/n8n-nodes-document-generator) | `community` `documents` `templates` |
| [`n8n-nodes-ffmpeg-command`](https://www.npmjs.com/package/n8n-nodes-ffmpeg-command) | Execute FFmpeg and FFprobe commands without separate binary installation or custom Docker images. | [GitHub](https://github.com/revolabs-io/n8n-nodes-ffmpeg-command) | `community` `video` `audio` |
| [`@firefliesai/n8n-nodes-fireflies`](https://www.npmjs.com/package/@firefliesai/n8n-nodes-fireflies) | Automate Fireflies.ai transcripts, summaries, analytics, meeting recordings, clips, and workspace data. | [GitHub](https://github.com/firefliesai/n8n-nodes-fireflies) | `official` `meetings` `transcription` |
| [`@gammatech/n8n-nodes-gamma`](https://www.npmjs.com/package/@gammatech/n8n-nodes-gamma) | Generate presentations, documents, social posts, and webpages with Gamma, including templates, themes, and async status checks. | [GitHub](https://github.com/gamma-app/n8n-nodes-gamma) | `official` `ai` `content` |
| [`n8n-nodes-htmlcsstoimage`](https://www.npmjs.com/package/n8n-nodes-htmlcsstoimage) | Convert HTML and CSS to images from n8n workflows. | [GitHub](https://github.com/HtmlCssToImg/n8n-nodes-htmlcsstoimage) | `community` `images` `media` |
| [`n8n-nodes-htmlcsstopdf`](https://www.npmjs.com/package/n8n-nodes-htmlcsstopdf) | Create and process PDFs with PDFMunk: HTML/CSS or URL rendering, merge/split/compress, security, structured parsing, and OCR. | [GitHub](https://github.com/PdfMunk/n8n-nodes-htmltopdf) | `community` `pdf` `documents` |
| [`n8n-nodes-hudu`](https://www.npmjs.com/package/n8n-nodes-hudu) | Automate Hudu IT documentation, companies, articles, assets, procedures, relations, filtering, bulk operations, and AI tools. | [GitHub](https://github.com/msoukhomlinov/n8n-nodes-hudu) | `community` `it-documentation` `ai` |
| [`n8n-nodes-instagram-token`](https://www.npmjs.com/package/n8n-nodes-instagram-token) | Use Instagram API operations with access-token authentication. | [GitHub](https://github.com/r-milioli/n8n-nodes-insta-accessToken) | `community` `instagram` `social-media` |
| [`@igabm/n8n-nodes-tiktok`](https://www.npmjs.com/package/@igabm/n8n-nodes-tiktok) | Connect n8n workflows to the TikTok API. | [GitHub](https://github.com/igabm/n8n-nodes-tiktok) | `community` `tiktok` `social-media` |
| [`n8n-nodes-metricool-or`](https://www.npmjs.com/package/n8n-nodes-metricool-or) | Integrate n8n workflows with the Metricool social-media management platform. | [GitHub](https://github.com/kukis2107/n8n-nodes-metricool-or) | `community` `metricool` `social-media` |
| [`n8n-nodes-notionmd`](https://www.npmjs.com/package/n8n-nodes-notionmd) | Transform Markdown into Notion blocks. | [GitHub](https://github.com/minhlucvan/n8n-nodes-notionmd) | `community` `notion` `markdown` |
| [`n8n-nodes-palatine-speech`](https://www.npmjs.com/package/n8n-nodes-palatine-speech) | Transcribe, diarize, summarize, analyze sentiment, and call an OpenAI-compatible chat model through Palatine Speech. | [GitHub](https://github.com/PalatineVision/n8n-nodes-palatine-speech) | `official` `speech` `ai` |
| [`n8n-nodes-pdf-api-hub`](https://www.npmjs.com/package/n8n-nodes-pdf-api-hub) | Use PDF API Hub for 30+ PDF operations including rendering, OCR, table extraction, conversion, signing, compression, and protection. | [GitHub](https://github.com/PdfApiHub/n8n-nodes-pdf-api-hub) | `community` `pdf` `ocr` |
| [`n8n-nodes-pdf-generation`](https://www.npmjs.com/package/n8n-nodes-pdf-generation) | Generate PDFs from text or table data. | [GitHub](https://github.com/pot030321/Custom_Node_List) | `community` `pdf` `documents` |
| [`@pdfgeneratorapi/n8n-nodes-pdf-generator-api`](https://www.npmjs.com/package/@pdfgeneratorapi/n8n-nodes-pdf-generator-api) | Generate PDFs from templates and convert HTML or URLs, with QR codes, watermarks, encryption, optimization, and form fields. | [GitHub](https://github.com/pdfgeneratorapi/n8n-nodes-pdf-generator-api) | `official` `pdf` `documents` |
| [`n8n-nodes-pdfkit`](https://www.npmjs.com/package/n8n-nodes-pdfkit) | Transform images into PDFs with PDFKit. | [GitHub](https://github.com/bramkn/n8n-nodes-pdfkit) | `community` `pdf` `documents` |
| [`n8n-nodes-pdf4me`](https://www.npmjs.com/package/n8n-nodes-pdf4me) | Process PDFs and documents with PDF4ME, including OCR, extraction, conversion, forms, barcodes, signing, and template generation. | [GitHub](https://github.com/pdf4me/n8n-nodes-pdf4me) | `official` `pdf` `documents` |
| [`n8n-nodes-pdfco`](https://www.npmjs.com/package/n8n-nodes-pdfco) | Use PDF.co document and PDF-processing operations in n8n. | [GitHub](https://github.com/pdfdotco/n8n-nodes-pdfco) | `official` `pdf` `documents` |
| [`n8n-nodes-pdforge`](https://www.npmjs.com/package/n8n-nodes-pdforge) | Generate AI-assisted PDF templates and deliver PDFs through the pdforge/PDF Noodle service. | [GitHub](https://github.com/pdfnoodle/n8n-nodes-pdforge) | `community` `pdf` `ai` |
| [`n8n-nodes-sb-render`](https://www.npmjs.com/package/n8n-nodes-sb-render) | Render videos with customizable subtitles, background music, and narration. | [GitHub](https://github.com/choisb87/sb-render) | `community` `video` `rendering` |
| [`n8n-nodes-tesseractjs`](https://www.npmjs.com/package/n8n-nodes-tesseractjs) | Run local Tesseract.js OCR on images and image-based PDFs, returning recognized text, confidence, and bounding boxes. | [GitHub](https://github.com/jreyesr/n8n-nodes-tesseractjs) | `community` `ocr` `documents` |
| [`n8n-nodes-transcribe-audio`](https://www.npmjs.com/package/n8n-nodes-transcribe-audio) | Transcribe WAV audio locally with Whisper via ONNX WebAssembly, without third-party inference APIs. | [GitHub](https://github.com/dioveath/n8n-nodes-transcribe-audio) | `community` `speech-to-text` `local-ai` |
| [`n8n-nodes-upload-post`](https://www.npmjs.com/package/n8n-nodes-upload-post) | Publish content to Upload Post from n8n workflows. | [GitHub](https://github.com/Upload-Post/n8n-nodes-upload-post) | `community` `social-media` `content` |
| [`n8n-nodes-video-downloader`](https://www.npmjs.com/package/n8n-nodes-video-downloader) | Download and process M3U8 streams, video files, and supported social-media videos. | [GitHub](https://github.com/revolabs-io/n8n-nodes-video-downloader) | `community` `video` `media` |
| [`@xberg-io/n8n-nodes-xberg`](https://www.npmjs.com/package/@xberg-io/n8n-nodes-xberg) | Extract text, tables, metadata, and optional OCR from 101 document formats locally inside self-hosted n8n. | [GitHub](https://github.com/xberg-io/xberg) | `official` `documents` `ocr` |

## CRM and Sales

| Package | What it adds | Source | Tags |
| --- | --- | --- | --- |
| [`@asaasbr/n8n-nodes-asaas`](https://www.npmjs.com/package/@asaasbr/n8n-nodes-asaas) | Connect n8n workflows to the Asaas API. | - | `community` `payments` `finance` |
| [`n8n-nodes-autotask`](https://www.npmjs.com/package/n8n-nodes-autotask) | Automate Autotask PSA entities, filters, webhooks, API-threshold checks, and AI-agent tools. | [GitHub](https://github.com/msoukhomlinov/n8n-nodes-autotask) | `community` `psa` `service-management` |
| [`n8n-nodes-lemonsqueezy`](https://www.npmjs.com/package/n8n-nodes-lemonsqueezy) | Manage Lemon Squeezy products, subscriptions, orders, license keys, checkouts, customers, and webhooks. | [GitHub](https://github.com/janmaaarc/n8n-nodes-lemonsqueezy) | `community` `payments` `subscriptions` |
| [`n8n-nodes-kommo`](https://www.npmjs.com/package/n8n-nodes-kommo) | Connect workflows to the Kommo CRM API. | [GitHub](https://github.com/yatolstoy/n8n-nodes-kommo) | `community` `crm` `sales` |
| [`@skriptfabrik/n8n-nodes-moco`](https://www.npmjs.com/package/@skriptfabrik/n8n-nodes-moco) | Automate MOCO business workflows from n8n. | [GitHub](https://github.com/skriptfabrik/n8n-nodes) | `community` `business` `erp` |
| [`n8n-nodes-netsuite-rest`](https://www.npmjs.com/package/n8n-nodes-netsuite-rest) | Connect to NetSuite's SuiteTalk REST API with standard records, custom fields and records, and SuiteQL queries. | [GitHub](https://github.com/entech-code/n8n-nodes-netsuite-rest) | `community` `erp` `rest` |
| [`@outseta/n8n-nodes-outseta`](https://www.npmjs.com/package/@outseta/n8n-nodes-outseta) | Manage Outseta CRM accounts, people, billing plans, subscriptions, and email lists. | [GitHub](https://github.com/outseta/outseta-js) | `official` `crm` `billing` |
| [`n8n-nodes-openpix`](https://www.npmjs.com/package/n8n-nodes-openpix) | Use OpenPix payment and transaction operations from n8n. | [GitHub](https://github.com/open-pix/n8n-nodes-openpix) | `community` `payments` `finance` |
| [`n8n-nodes-rd-station-crm`](https://www.npmjs.com/package/n8n-nodes-rd-station-crm) | Automate RD Station CRM contacts, deals, pipelines, and related records. | [GitHub](https://github.com/PedroHSGuimaraes/n8n-nodes-rd-station-crm) | `community` `crm` `sales` |
| [`n8n-nodes-tomba`](https://www.npmjs.com/package/n8n-nodes-tomba) | Find, enrich, and verify company and professional email data with Tomba's domain, email, company, and finder operations. | [GitHub](https://github.com/tomba-io/n8n-nodes-tomba) | `official` `email-intelligence` `sales` |
| [`n8n-nodes-twenty-dynamic`](https://www.npmjs.com/package/n8n-nodes-twenty-dynamic) | Use Twenty CRM with runtime discovery of custom objects and fields plus bulk CRUD and upsert operations. | [GitHub](https://github.com/Logrui/n8n-nodes-twenty-dynamic) | `community` `crm` `graphql` |

## Utilities

| Package | What it adds | Source | Tags |
| --- | --- | --- | --- |
| [`@bitovi/n8n-nodes-utils`](https://www.npmjs.com/package/@bitovi/n8n-nodes-utils) | Add JSON Schema validation, regex operations, item skipping, and Wikipedia lookups. | [GitHub](https://github.com/bitovi/n8n-nodes-utils) | `community` `utilities` `validation` |
| [`n8n-nodes-confirm8`](https://www.npmjs.com/package/n8n-nodes-confirm8) | Call the Confirm8 API without configuring credentials. | - | `community` `verification` `api` |
| [`n8n-nodes-cronlytic`](https://www.npmjs.com/package/n8n-nodes-cronlytic) | Add Cronlytic advanced cron scheduling to n8n workflows. | [GitHub](https://github.com/Cronlytic/n8n-nodes-cronlytic) | `community` `scheduling` `trigger` |
| [`n8n-nodes-globals`](https://www.npmjs.com/package/n8n-nodes-globals) | Define global constants and reuse them across workflows. | [GitHub](https://github.com/umanamente/n8n-nodes-globals) | `community` `utilities` `configuration` |
| [`n8n-nodes-randomizer`](https://www.npmjs.com/package/n8n-nodes-randomizer) | Randomize data for n8n workflows. | [GitHub](https://github.com/mcnaveen/n8n-nodes-randomizer) | `community` `data` `utilities` |
| [`n8n-nodes-shortio`](https://www.npmjs.com/package/n8n-nodes-shortio) | Work with the short.io URL-shortening service from n8n. | [GitHub](https://github.com/liamdmcgarrigle/n8n-nodes-shortio) | `community` `url-shortening` `utilities` |
| [`@splainez/n8n-nodes-phonenumber-parser`](https://www.npmjs.com/package/@splainez/n8n-nodes-phonenumber-parser) | Normalize and validate phone numbers with country, formatting, validity, and number-type metadata. | [GitHub](https://github.com/splainez/n8n-nodes-phonenumber-parser) | `community` `phone` `data-quality` |
| [`n8n-nodes-signauf`](https://www.npmjs.com/package/n8n-nodes-signauf) | Pause workflows for human approvals and resume them with Signauf's decision payload. | [GitHub](https://github.com/kam-itnn/n8n-nodes-signauf) | `community` `approvals` `human-review` |
| [`n8n-nodes-sirenic`](https://www.npmjs.com/package/n8n-nodes-sirenic) | Verify European suppliers and automate KYB, VAT, sanctions, financial, registry, and company-monitoring checks. | [GitHub](https://github.com/sirenic-eu/n8n-nodes-sirenic) | `official` `compliance` `kyb` |
| [`n8n-nodes-sshv2`](https://www.npmjs.com/package/n8n-nodes-sshv2) | Run SSH, SCP, and SFTP operations with dynamic parameters from n8n. | [GitHub](https://github.com/AhmedElhadidii/N8N-SSH-Tool-Node) | `community` `ssh` `file-transfer` |
| [`n8n-nodes-text-manipulation`](https://www.npmjs.com/package/n8n-nodes-text-manipulation) | Modify text values inside n8n workflows. | [GitHub](https://github.com/lublak/n8n-nodes-text-manipulation) | `community` `text` `utilities` |
| [`n8n-nodes-yaml`](https://www.npmjs.com/package/n8n-nodes-yaml) | Parse YAML text and stringify workflow data for configuration and interchange steps. | [GitHub](https://github.com/pemontto/n8n-nodes-yaml) | `community` `yaml` `utilities` |

## Legend

`official` means the package is published by the service provider or an organization that appears to represent it. `community` means it is maintained independently of the integrated service. Tags describe the primary use case; they are not n8n compatibility guarantees.

Every linked package and provider retains ownership of its name, trademarks, source code, and license. Check the package and source repository before installation. Report broken links, ownership changes, security concerns, or misleading descriptions through an issue or pull request.

Last reviewed: August 25, 2026.

## Contributing

Contributions are welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.

## Maintainer

This directory is maintained as a community project and is dedicated to the public domain under [CC0 1.0 Universal](LICENSE). The n8n name and trademarks belong to their respective owners.
