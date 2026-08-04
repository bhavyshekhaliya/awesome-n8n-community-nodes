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
| [`n8n-nodes-duckduckgo-search`](https://www.npmjs.com/package/n8n-nodes-duckduckgo-search) | Search DuckDuckGo web, image, news, and video results, with optional page-text extraction. | [GitHub](https://github.com/samnodehi/n8n-nodes-duckduckgo) | `community` `search` `web` |
| [`n8n-nodes-mcp`](https://www.npmjs.com/package/n8n-nodes-mcp) | Connect n8n to Model Context Protocol servers and use their tools, resources, and prompts. | [GitHub](https://github.com/nerding-io/n8n-nodes-mcp) | `community` `mcp` `agents` |
| [`n8n-nodes-openai-structured-outputs`](https://www.npmjs.com/package/n8n-nodes-openai-structured-outputs) | Extract structured JSON from unstructured text with an OpenAI JSON Schema. | [GitHub](https://github.com/crucerlabs/n8n-nodes-openai-structured-outputs) | `community` `openai` `structured-data` |
| [`n8n-nodes-serpapi`](https://www.npmjs.com/package/n8n-nodes-serpapi) | Query SerpApi search engine results from n8n workflows. | [GitHub](https://github.com/serpapi/n8n-nodes-serpapi) | `official` `search` `seo` |
| [`@telnyx/n8n-nodes-telnyx-ai`](https://www.npmjs.com/package/@telnyx/n8n-nodes-telnyx-ai) | Add Telnyx AI and voice capabilities to n8n workflows. | [GitHub](https://github.com/team-telnyx/n8n-nodes-telnyx-ai) | `official` `ai` `voice` |

## Browser, Web and Scraping

| Package | What it adds | Source | Tags |
| --- | --- | --- | --- |
| [`@apify/n8n-nodes-apify`](https://www.npmjs.com/package/@apify/n8n-nodes-apify) | Connect n8n workflows to Apify's actors, datasets, and web-automation platform. | [GitHub](https://github.com/apify/n8n-nodes-apify) | `official` `web-scraping` `automation` |
| [`n8n-nodes-firecrawl`](https://www.npmjs.com/package/n8n-nodes-firecrawl) | Crawl and extract web content with Firecrawl. | [GitHub](https://github.com/minhlucvan/n8n-nodes-firecrawl) | `community` `web-scraping` `content` |
| [`n8n-nodes-puppeteer`](https://www.npmjs.com/package/n8n-nodes-puppeteer) | Automate a browser with Puppeteer, including scraping, screenshots, scripts, and PDF output. | [GitHub](https://github.com/drudge/n8n-nodes-puppeteer) | `community` `browser` `automation` |

## Communication and Messaging

| Package | What it adds | Source | Tags |
| --- | --- | --- | --- |
| [`n8n-nodes-chatwoot`](https://www.npmjs.com/package/n8n-nodes-chatwoot) | Use Chatwoot conversations and customer-support workflows from n8n. | [GitHub](https://github.com/sufficit/n8n-nodes-chatwoot) | `community` `support` `messaging` |
| [`n8n-nodes-evolution-api`](https://www.npmjs.com/package/n8n-nodes-evolution-api) | Connect to Evolution API, a WhatsApp-focused channel hub. | [GitHub](https://github.com/oriondesign2015/n8n-nodes-evolution-api) | `community` `whatsapp` `messaging` |
| [`n8n-nodes-imap`](https://www.npmjs.com/package/n8n-nodes-imap) | Connect to an IMAP server and retrieve email. | [GitHub](https://github.com/umanamente/n8n-nodes-imap) | `community` `email` `trigger` |
| [`@devlikeapro/n8n-nodes-waha`](https://www.npmjs.com/package/@devlikeapro/n8n-nodes-waha) | Connect n8n to WAHA's WhatsApp HTTP API. | [GitHub](https://github.com/devlikeapro/n8n-nodes-waha) | `community` `whatsapp` `messaging` |
| [`n8n-nodes-zapi`](https://www.npmjs.com/package/n8n-nodes-zapi) | Use Z-API for WhatsApp messaging workflows. | [GitHub](https://github.com/leandcesar/n8n-nodes-zapi) | `community` `whatsapp` `messaging` |
| [`n8n-nodes-zohozeptomail`](https://www.npmjs.com/package/n8n-nodes-zohozeptomail) | Use Zoho ZeptoMail for transactional email workflows. | [GitHub](https://github.com/zohomail/zoho_zeptomail_n8n) | `official` `email` `transactional` |

## Data, Storage and Observability

| Package | What it adds | Source | Tags |
| --- | --- | --- | --- |
| [`@globalping/n8n-nodes-globalping`](https://www.npmjs.com/package/@globalping/n8n-nodes-globalping) | Run ping, traceroute, MTR, HTTP, and DNS measurements from locations around the world. | [GitHub](https://github.com/jsdelivr/n8n-nodes-globalping) | `official` `networking` `observability` |
| [`n8n-nodes-qdrant`](https://www.npmjs.com/package/n8n-nodes-qdrant) | Interface with Qdrant for vector search and data operations. | [GitHub](https://github.com/qdrant/n8n-nodes-qdrant) | `official` `vector-database` `ai` |

## Documents, Media and Productivity

| Package | What it adds | Source | Tags |
| --- | --- | --- | --- |
| [`n8n-nodes-cloudinary`](https://www.npmjs.com/package/n8n-nodes-cloudinary) | Upload media and update Cloudinary asset tags and metadata. | [GitHub](https://github.com/cloudinary/n8n-nodes-cloudinary) | `official` `media` `storage` |
| [`n8n-nodes-notionmd`](https://www.npmjs.com/package/n8n-nodes-notionmd) | Transform Markdown into Notion blocks. | [GitHub](https://github.com/minhlucvan/n8n-nodes-notionmd) | `community` `notion` `markdown` |
| [`n8n-nodes-pdfco`](https://www.npmjs.com/package/n8n-nodes-pdfco) | Use PDF.co document and PDF-processing operations in n8n. | [GitHub](https://github.com/pdfdotco/n8n-nodes-pdfco) | `official` `pdf` `documents` |

## CRM and Sales

| Package | What it adds | Source | Tags |
| --- | --- | --- | --- |
| [`n8n-nodes-kommo`](https://www.npmjs.com/package/n8n-nodes-kommo) | Connect workflows to the Kommo CRM API. | [GitHub](https://github.com/yatolstoy/n8n-nodes-kommo) | `community` `crm` `sales` |
| [`n8n-nodes-rd-station-crm`](https://www.npmjs.com/package/n8n-nodes-rd-station-crm) | Automate RD Station CRM contacts, deals, pipelines, and related records. | [GitHub](https://github.com/PedroHSGuimaraes/n8n-nodes-rd-station-crm) | `community` `crm` `sales` |

## Utilities

| Package | What it adds | Source | Tags |
| --- | --- | --- | --- |
| [`n8n-nodes-globals`](https://www.npmjs.com/package/n8n-nodes-globals) | Define global constants and reuse them across workflows. | [GitHub](https://github.com/umanamente/n8n-nodes-globals) | `community` `utilities` `configuration` |

## Legend

`official` means the package is published by the service provider or an organization that appears to represent it. `community` means it is maintained independently of the integrated service. Tags describe the primary use case; they are not n8n compatibility guarantees.

Every linked package and provider retains ownership of its name, trademarks, source code, and license. Check the package and source repository before installation. Report broken links, ownership changes, security concerns, or misleading descriptions through an issue or pull request.

Last reviewed: August 4, 2026.

## Contributing

Contributions are welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.

## Maintainer

This directory is maintained as a community project and is dedicated to the public domain under [CC0 1.0 Universal](LICENSE). The n8n name and trademarks belong to their respective owners.
