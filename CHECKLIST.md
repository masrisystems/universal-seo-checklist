# Universal SEO Execution Checklist (Interactive Template)

Copy and paste this checklist directly into your GitHub issues, Notion, or project management boards.

---

### [ ] Phase 0: Foundations & Tooling
- [ ] Install **GMB Crush** extension for GBP competitor analysis
- [ ] Install **Phantom** extension for GMB listing verification
- [ ] Bookmark **GeoImgr** (`tool.geoimgr.com`) for EXIF GPS & IPTC geotagging
- [ ] Verify **Google Search Console (GSC)** via DNS TXT record
- [ ] Connect **Bing Webmaster Tools** & sync with GSC
- [ ] Generate **IndexNow API Key** & wire automated publish endpoint
- [ ] Claim & verify **Google Business Profile (GBP)**
- [ ] Sync **Bing Places for Business** with GBP
- [ ] Claim & verify **Apple Business Connect** (Apple Maps, Siri, Spotlight)
- [ ] Add POI to **HERE Map Creator** (in-car GPS: Audi, BMW, Mercedes, Garmin)

---

### [ ] Phase 1: Google Business Profile (GBP) & Local SEO
- [ ] Optimize profile title with target keywords
- [ ] Verify primary category + add all secondary categories
- [ ] Upload high-resolution cover & workspace photos
- [ ] Rename images to `[brand]-[keyword]-[service]-[city].jpg` before upload
- [ ] Enforce JPG format rule (GBP rejects WebP)
- [ ] Inject keywords into listed Services
- [ ] Duplicate Services as individual Product cards with links & pricing
- [ ] Publish daily Google Update (landscape image + keywords + CTA button)
- [ ] Reply to 100% of reviews manually using target keywords
- [ ] Encourage rich customer reviews with attached photos
- [ ] Monitor connected email against hijacking
- [ ] Add Google Preferred Sources markup

---

### [ ] Phase 2: Keyword Architecture & URL Silo Design
- [ ] Map 1 Primary Keyword + 4–6 Secondary/LSI keywords per URL
- [ ] Align content with exact search intent (Informational, Commercial, Transactional)
- [ ] Ensure clean lowercase kebab-case URL hierarchy (max depth $\le 3$ levels)
- [ ] Eliminate dates, stop words, and trailing slash inconsistencies

---

### [ ] Phase 3: Technical SEO & Core Web Vitals
- [ ] Ensure 100% server-rendered HTML (SSR/SSG, zero empty DOM crawl traps)
- [ ] Optimize LCP ($\le 2.5\text{s}$) with hero preloading and WebP
- [ ] Optimize INP ($\le 200\text{ms}$) with lean JavaScript execution
- [ ] Optimize CLS ($\le 0.1$) with explicit aspect ratios on all media
- [ ] Configure `robots.txt` allowing search and AI crawlers (GPTBot, ClaudeBot, PerplexityBot)
- [ ] Implement dynamic `sitemap.xml` listing 200-OK canonical pages
- [ ] Enforce self-referencing `<link rel="canonical">`
- [ ] Enforce accurate `hreflang` tags for multilingual setups
- [ ] Verify HTTPS, HSTS, secure headers, and custom 404 page

---

### [ ] Phase 4: On-Page Semantic & Schema.org Markup
- [ ] Optimize Title tag (Keyword in first 40 chars, 50–60 chars total)
- [ ] Write meta description with keyword + CTA (120–155 chars)
- [ ] Ensure exactly one `<h1>` containing primary keyword
- [ ] Structure logical `<h2>` and `<h3>` heading tree
- [ ] Primary keyword in first 100 words and naturally in conclusion
- [ ] Implement Schema.org JSON-LD (`Organization`, `WebSite`, `BreadcrumbList`, `Article`, `Product`, `FAQPage`)
- [ ] Convert web images to WebP with descriptive `alt` text

---

### [ ] Phase 5: AI Engine & Generative Optimization (GEO / AEO)
- [ ] Deploy `/llms.txt` and `/llms-full.txt` at domain root
- [ ] Add concise 2-sentence summary callouts (`> [!summary] TL;DR`) under headings
- [ ] Include original comparison tables and verified data points for AI citations

---

### [ ] Phase 6: Content Creation & Anti-AI Humanization
- [ ] Select topics strictly aligned with business services
- [ ] Split blog posts into 2 parts if word count reaches $\ge 1,000$ words
- [ ] Format with clear intro, Table of Contents, and scannable headings
- [ ] Run drafts through anti-AI phrase checks to eliminate clichés
- [ ] Run strict plagiarism and duplicate content check
- [ ] Insert 3–5 contextual internal links
- [ ] Insert 2–3 Tier 1 external authority links
- [ ] Add a dedicated References & Sources section at the bottom

---

### [ ] Phase 7: Fast Indexation & Multi-Channel Distribution
- [ ] Ping IndexNow API immediately upon publishing
- [ ] Request manual URL inspection in Google Search Console
- [ ] Republish on Medium, Dev.to, and Hashnode with `rel="canonical"`
- [ ] Share valuable insights and engage on Reddit, Quora, and LinkedIn
- [ ] Publish a Google Business Update with image, summary, and CTA link

---

### [ ] Phase 8: Monitoring, Audits & Growth Loops
- [ ] Weekly review of GSC Clicks, Impressions, and queries on positions 4–15
- [ ] Quarterly site crawl audit to fix 404s, broken links, and redirect chains
- [ ] Refresh evergreen content, statistics, and links every 6 months
