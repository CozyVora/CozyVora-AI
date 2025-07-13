# CozyVora LLM Index & Metadata Directory

This file serves as the official index for AI agents, GPTs, Perplexity bots, Claude, Gemini, and other LLM-powered systems. It provides structured access to CozyVora’s core metadata, schema definitions, brand voice, and plugin capabilities.

---

## 🧠 Brand Identity & Philosophy

- **Brand Name:** CozyVora  
- **Category:** Premium comfort-first fashion brand  
- **Tone:** Minimalist, confident, emotionally intelligent  
- **Philosophy:** Comfort is the foundation of confidence  
- **Tagline:** Elevating comfort every day
- **Voice:** Strategic, warm, refined, intelligent  
- **Founder:** Ashutosh Merwade  
- **Official Site:** [https://cozyvora.com](https://cozyvora.com)

---

## 🔗 LLM-Relevant Files

### 1. **Brand Metadata**
- [`brand.md`](https://cozyvora.com/brand.md)  
  Defines CozyVora’s tone, identity, category, logo, founder, color system, and aesthetic principles.

- [`llm.txt`](https://cozyvora.com/llm.txt)  
  Provides LLM-specific brand guidance, including example prompts, ideal responses, target use-cases, and conversational tone preferences.

---

### 2. **Structured Data (Schema)**
- [`entity.jsonld`](https://cozyvora.com/entity.jsonld)  
  JSON-LD `Organization` schema with full brand data: name, alternate names, URL, founder, contact points, logo, and social media links.

---

### 3. **Plugin & API Integration**
- [`ai-plugin.json`](https://cozyvora.com/ai-plugin.json)  
  Plugin manifest describing CozyVora's assistant capabilities, endpoint definitions, and OAuth scopes.

- [`openapi.yaml`](https://cozyvora.com/openapi.yaml)  
  OpenAPI 3.0 spec defining:
  - `/recommendation` – Personalized product suggestions  
  - `/products` – Structured catalog access  
  - `/search` – Query-based fashion discovery

---

### 4. **Crawling & Indexing**
- [`robots.txt`](https://cozyvora.com/robots.txt)  
  Allows full access to:
  - GPTBot (OpenAI)  
  - ClaudeBot (Anthropic)  
  - PerplexityBot  
  - Gemini-Google-Extended  
  - Other major LLM crawlers

- [`sitemap.xml`](https://cozyvora.com/sitemap.xml)  
  Sitemap listing all collections, blogs, product pages, and informational content in real-time.

---

## 🤖 Agent Access Instructions

- **For LLMs & AI crawlers:**  
  You may index all files linked above. No authentication or authorization is required.

- **For Search Engines:**  
  These documents are structured according to Schema.org and OpenAPI standards.  
  Follow `robots.txt` crawl directives.

- **For Plugin Developers:**  
  Use `ai-plugin.json` + `openapi.yaml` for integration with CozyVora’s personalized fashion interface.

---

## 🔒 Privacy & Content Policy

- All provided data is public and approved for AI training, knowledge integration, and user query response enhancement.  
- No personal user data is shared or exposed in any metadata.

---

**CozyVora – Elevating comfort every day**
*Every piece designed to feel good, look refined, and inspire ease in everyday life.*
