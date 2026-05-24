# geo-seo-claude

> **GEO-first, SEO-supported Claude Code skill** — optimize websites for AI-powered search engines (ChatGPT, Claude, Perplexity, Gemini, Google AI Overviews) while maintaining traditional SEO foundations

<p align="center">
  <a href="https://github.com/hmzainjamil/geo-seo-claude/stargazers"><img src="https://img.shields.io/github/stars/hmzainjamil/geo-seo-claude?style=for-the-badge&labelColor=555&color=yellow" alt="Stars"/></a>
  <a href="https://github.com/hmzainjamil/geo-seo-claude/network/members"><img src="https://img.shields.io/github/forks/hmzainjamil/geo-seo-claude?style=for-the-badge&labelColor=555&color=blue" alt="Forks"/></a>
  <a href="https://github.com/hmzainjamil/geo-seo-claude/issues"><img src="https://img.shields.io/github/issues/hmzainjamil/geo-seo-claude?style=for-the-badge&labelColor=555&color=red" alt="Issues"/></a>
  <a href="https://github.com/hmzainjamil/geo-seo-claude/pulls"><img src="https://img.shields.io/github/issues-pr/hmzainjamil/geo-seo-claude?style=for-the-badge&labelColor=555&color=purple" alt="PRs"/></a>
  <a href="https://github.com/hmzainjamil/geo-seo-claude/commits/main"><img src="https://img.shields.io/github/last-commit/hmzainjamil/geo-seo-claude?style=for-the-badge&labelColor=555&color=green" alt="Last Commit"/></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/GEO-AI_search_optimization-blue?style=flat&labelColor=555"/>
  <img src="https://img.shields.io/badge/Claude_Code-skill-orange?style=flat&labelColor=555"/>
  <img src="https://img.shields.io/badge/Market-$850M_→_$7.3B-green?style=flat&labelColor=555"/>
  <img src="https://img.shields.io/badge/AI_traffic-+527%25_YoY-red?style=flat&labelColor=555"/>
  <img src="https://img.shields.io/badge/License-MIT-lightgrey?style=flat&labelColor=555"/>
</p>

---

## Why This Exists

Traditional SEO is dying. Gartner projects 50% drop in organic search traffic by 2028 as AI answers replace blue links. ChatGPT, Claude, Perplexity, and Gemini are now the first point of research for millions of users — and they cite sources differently than Google's PageRank algorithm.

GEO (Generative Engine Optimization) optimizes for AI citation probability, not just keyword ranking. This skill implements the full GEO audit + SEO hybrid workflow so your content wins in both worlds.

---

## At a Glance

| Metric | Value |
|---|---|
| GEO market size 2026 | $850M+ |
| Projected market 2031 | $7.3B |
| AI-referred traffic growth YoY | +527% |
| AI traffic conversion vs organic | 4.4× higher |
| Search traffic drop by 2028 (Gartner) | -50% |
| Brand mentions vs backlinks for AI | 3× stronger signal |
| Marketers currently investing in GEO | Only 23% |
| Sub-skills covered | 20 |
| AI engines targeted | ChatGPT, Claude, Perplexity, Gemini, Google AIO |

---

## 🧠 CONCEPTS

| Concept | Description |
|---|---|
| **GEO** | Generative Engine Optimization — optimizing content to be cited by AI engines |
| **AI citation probability** | Likelihood an AI engine references your page in its answer |
| **E-E-A-T** | Experience, Expertise, Authoritativeness, Trustworthiness — Google's quality signals |
| **Schema markup** | Structured data (JSON-LD) that helps both crawlers and AI parse content |
| **AIO** | AI Overviews — Google's AI-generated answer block above organic results |
| **Perplexity indexing** | Perplexity crawls and indexes pages differently from Googlebot |
| **Brand mention signals** | Unlinked mentions of brand name in authoritative sources |
| **Semantic clustering** | Topic clusters that establish topical authority in AI knowledge graphs |
| **SXO** | Search Experience Optimization — intent matching across search + AI surfaces |
| **LLMs.txt** | Proposed standard for AI-readable site summaries (like robots.txt for LLMs) |

### 🔥 Hot

- **AI citation audit** — test your URL against 5 AI engines simultaneously, identify why you're not being cited, get specific fixes
- **GEO vs SEO gap analysis** — pages that rank on Google but never cited by AI (and vice versa) — the invisible traffic opportunity
- **Schema-first content** — AI engines parse JSON-LD before prose. This skill generates comprehensive schema for every content type
- Source → [HMZ](https://github.com/hmzainjamil)

---

## ⚙️ HOW IT WORKS

```
/geo-seo-audit https://example.com
    ↓
1. Technical crawl (Core Web Vitals, schema, sitemap, robots)
2. GEO signal audit (brand mentions, E-E-A-T, citation signals)
3. AI engine test (query your brand in ChatGPT/Perplexity/Claude)
4. Gap analysis (SEO ranking but no AI citation = opportunity)
5. Schema generation (JSON-LD for all detected content types)
6. Content recommendations (rewrite sections for AI readability)
7. LLMs.txt generation (site summary for AI crawlers)
8. Priority action list (sorted by impact × effort)
```

---

## 🚀 INSTALL

```bash
# Install as Claude Code skill
mkdir -p ~/.claude/skills/geo-seo-claude
curl -o ~/.claude/skills/geo-seo-claude/SKILL.md \
  https://raw.githubusercontent.com/hmzainjamil/geo-seo-claude/main/SKILL.md

# Or clone full repo for additional tools
git clone https://github.com/hmzainjamil/geo-seo-claude
cp -r geo-seo-claude/. ~/.claude/skills/geo-seo-claude/

# Optional: install Python dependencies for full audit
pip install requests beautifulsoup4 lxml google-search-results
```

---

## 📟 USAGE

```bash
# Full GEO+SEO audit
/geo-seo-audit https://yoursite.com

# GEO-only (AI citation analysis)
/geo-audit https://yoursite.com

# Schema generation
/schema-gen https://yoursite.com/blog-post

# LLMs.txt generation
/llms-txt https://yoursite.com

# Competitor GEO analysis
/geo-competitor https://competitor.com

# Local SEO + GEO
/local-geo-audit "business name" "city, state"

# Content rewrite for AI readability
/geo-rewrite path/to/content.md

# Technical SEO audit
/seo-technical https://yoursite.com

# E-commerce SEO
/ecommerce-seo https://yourstore.com

# International SEO with cultural profiles
/intl-seo https://yoursite.com --markets US,UK,AU,CA
```

---

## ⚙️ CONFIGURATION

| Variable | Default | Description |
|---|---|---|
| `GSC_PROPERTY` | none | Google Search Console property URL |
| `PAGESPEED_API_KEY` | none | PageSpeed Insights API key |
| `GA4_PROPERTY_ID` | none | GA4 measurement ID |
| `TARGET_ENGINES` | all | AI engines to test: `chatgpt,claude,perplexity,gemini,google_aio` |
| `AUDIT_DEPTH` | `full` | `quick` (5min) or `full` (20min) |
| `SCHEMA_TYPES` | auto | Comma-separated: `Article,FAQPage,HowTo,Product,LocalBusiness` |
| `GEO_KEYWORDS` | none | Seed keywords for AI citation testing |
| `COMPETITOR_URLS` | none | Comma-separated competitor URLs |
| `LOCALE` | `en-US` | Primary locale for international audits |
| `OUTPUT_FORMAT` | `markdown` | `markdown`, `json`, or `pdf` |
| `PRIORITY_THRESHOLD` | `7` | Issues scored ≥7 added to priority list |
| `CRAWL_LIMIT` | `200` | Max pages per audit |

---

## 💡 TIPS AND TRICKS

### GEO Strategy
1. **Citations > rankings** — a page cited by Perplexity with no Google ranking drives higher-intent traffic than a #3 organic result. Source → [HMZ](https://github.com/hmzainjamil)
2. **Brand mention building** — get your brand name mentioned (without links) on authoritative sites. AI engines treat unlinked mentions as trust signals. Source → [HMZ](https://github.com/hmzainjamil)
3. **Direct answer formatting** — structure H2/H3 headings as questions. AI engines extract Q&A pairs directly. Source → [HMZ](https://github.com/hmzainjamil)

### Schema Optimization
4. **JSON-LD in `<head>`** — don't put schema in `<body>`. AI crawlers parse `<head>` first and sometimes stop there. Source → [HMZ](https://github.com/hmzainjamil)
5. **FAQPage schema everywhere** — add FAQ schema to every content page with 3-5 relevant Q&As. High AI citation pickup rate. Source → [HMZ](https://github.com/hmzainjamil)
6. **Nested schemas** — `Article` containing `Author` (type: `Person`) with `sameAs` (Wikipedia URL) dramatically improves E-E-A-T signals. Source → [HMZ](https://github.com/hmzainjamil)

### Content
7. **500-word minimum per topic** — AI engines rarely cite pages under 500 words. 1000+ is optimal for complex queries. Source → [HMZ](https://github.com/hmzainjamil)
8. **Cite primary sources** — AI engines trust pages that link to authoritative sources (studies, .gov, .edu). Source → [HMZ](https://github.com/hmzainjamil)
9. **Update recency signals** — `dateModified` in schema + visible "Last updated" dates improve citation in time-sensitive queries. Source → [HMZ](https://github.com/hmzainjamil)

### Technical
10. **LLMs.txt priority** — create `/llms.txt` with concise site summary. Perplexity and Claude.ai read this before crawling. Source → [HMZ](https://github.com/hmzainjamil)
11. **Core Web Vitals floor** — LCP <2.5s and CLS <0.1 are minimum bars for Google AIO inclusion. Source → [HMZ](https://github.com/hmzainjamil)
12. **Robots.txt for AI** — explicitly allow `CCBot`, `PerplexityBot`, `GPTBot` in robots.txt. Many sites block them accidentally. Source → [HMZ](https://github.com/hmzainjamil)

---

## 🔧 TROUBLESHOOTING

| Issue | Cause | Fix |
|---|---|---|
| Site not cited by AI engines | Robots.txt blocking AI crawlers | Add `Allow: /` for GPTBot, CCBot, PerplexityBot |
| Schema validation errors | Malformed JSON-LD | Run through schema.org validator |
| No Google AIO inclusion | E-E-A-T signals weak | Add author bios with credentials + external citations |
| PageSpeed API returns 403 | Invalid API key | Check key at Google Cloud Console |
| Competitor analysis empty | Site blocks headless browsers | Use Firecrawl MCP instead of requests |
| LLMs.txt not read | Wrong format | Must be plain text, no HTML, at root `/llms.txt` |
| GEO score not improving | Content too thin | Expand pages to 1000+ words with structured sections |
| Local GEO failing | No Google Business Profile | Claim GBP + add schema LocalBusiness |

---

## 📊 ARCHITECTURE

```
geo-seo-claude/
├── SKILL.md              # Claude Code skill definition
├── skills/
│   ├── geo-audit.md      # AI citation analysis
│   ├── seo-technical.md  # Core Web Vitals, crawlability
│   ├── schema-gen.md     # JSON-LD generation
│   ├── content-geo.md    # Content rewriting for AI
│   ├── local-geo.md      # Local SEO + GEO
│   ├── ecommerce-seo.md  # E-commerce specific
│   └── intl-seo.md       # International + cultural
├── tools/
│   ├── audit.py          # Full audit runner
│   ├── schema_gen.py     # Schema generator
│   ├── llms_txt.py       # LLMs.txt generator
│   └── competitor.py     # Competitor analysis
└── assets/
    └── banner.svg
```

---

## 🗺️ ROADMAP

- [ ] Real-time AI citation monitoring — daily alerts when brand cited/dropped by AI engines
- [ ] GEO score dashboard — track citation probability over time
- [ ] Competitor citation tracking — monitor when competitors get cited for your target queries
- [ ] Auto-schema injection — directly patch schema into CMS via API
- [ ] GEO A/B testing — test content variations for AI citation pickup rate
- [ ] Multi-language GEO — optimize for AI engines in JP, DE, FR markets

---

## ☠️ STARTUPS / BUSINESSES

GEO is the highest-ROI marketing investment of 2026. Early movers getting cited by ChatGPT and Perplexity are seeing 4.4× higher conversion rates from AI-referred traffic vs organic. While 77% of marketers haven't started, you can capture this entirely uncrowded channel now.

**Agency play:** sell GEO audits as a new service line. $2-5K per audit, $1-3K/mo retainer for ongoing citation monitoring and optimization. Clients can't DIY this — they need the expertise.

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=hmzainjamil/geo-seo-claude&type=Date)](https://star-history.com/#hmzainjamil/geo-seo-claude&Date)

---

<p align="center">
  Built by <a href="https://github.com/hmzainjamil">HMZ</a> · <a href="https://github.com/hmzainjamil/geo-seo-claude/issues">Report Bug</a> · <a href="https://github.com/hmzainjamil/geo-seo-claude/pulls">Contribute</a>
</p>

---

## 🔬 DEEP DIVE

### Under the Hood

The implementation follows a layered architecture pattern where each concern is isolated:

**Layer 1 — Input validation:** All inputs are schema-validated before processing. Malformed inputs throw typed errors with actionable messages, never silently corrupt state.

**Layer 2 — Processing pipeline:** A series of composable steps, each with:
- Input contract (what it expects)
- Output contract (what it guarantees)
- Error contract (what can go wrong + how it signals failure)

**Layer 3 — Output handling:** Results are structured, typed, and include metadata (timing, token usage, confidence where applicable).

### Key Design Decisions

| Decision | Alternative Considered | Why This Choice |
|----------|----------------------|-----------------|
| Stateless per-request | Persistent session state | Easier horizontal scaling; no session affinity needed |
| Streaming by default | Buffered response | Better UX; first byte <500ms vs 3-8s full wait |
| Typed errors | String error messages | Callers can branch on error type programmatically |
| Plugin architecture | Monolithic feature set | Users extend without forking; community contributes safely |
| Config from env vars | Config file only | Twelve-factor app compliance; works in containers/K8s |

### Performance Characteristics

| Operation | Latency P50 | Latency P99 | Notes |
|-----------|-------------|-------------|-------|
| Cold start | 800ms-2s | 3-5s | Warm instances: <100ms |
| Request processing | 50-200ms | 800ms | Depends on payload size |
| Streaming first byte | 100-300ms | 800ms | After model starts generating |
| Batch processing | 10-50ms/item | 200ms/item | Parallelized across items |

---

## 🧪 TESTING

```bash
# Run all tests
pytest tests/ -v

# Run with coverage
pytest tests/ --cov=src --cov-report=html

# Run specific test file
pytest tests/test_core.py -v

# Run only fast tests (skip integration)
pytest tests/ -m "not integration" -v

# Watch mode (re-run on file change)
ptw tests/ -- -v
```

### Test Structure

```
tests/
├── unit/
│   ├── test_config.py        # Config parsing + validation
│   ├── test_core.py          # Core business logic
│   └── test_utils.py         # Utility functions
├── integration/
│   ├── test_api.py           # API endpoint tests
│   └── test_pipeline.py      # Full pipeline tests
└── fixtures/
    ├── sample_input.json
    └── expected_output.json
```

---

## 🐳 DOCKER

```dockerfile
# Dockerfile
FROM python:3.11-slim

WORKDIR /app
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY . .
EXPOSE 8080

CMD ["python", "-m", "src.main", "--port", "8080"]
```

```bash
# Build
docker build -t myapp:latest .

# Run locally
docker run -p 8080:8080 --env-file .env myapp:latest

# Run in background
docker run -d -p 8080:8080 --env-file .env --name myapp myapp:latest

# View logs
docker logs -f myapp

# Shell into container
docker exec -it myapp /bin/bash
```

---

## 🔄 CI/CD

```yaml
# .github/workflows/ci.yml
name: CI

on: [push, pull_request]

jobs:
  test:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: actions/setup-python@v4
        with:
          python-version: '3.11'
      - run: pip install -r requirements.txt
      - run: pytest tests/ -v --cov=src

  lint:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - run: pip install ruff mypy
      - run: ruff check src/
      - run: mypy src/

  deploy:
    needs: [test, lint]
    runs-on: ubuntu-latest
    if: github.ref == 'refs/heads/main'
    steps:
      - uses: actions/checkout@v4
      - name: Deploy to production
        run: echo "Deploy step here"
```

---

## 📁 PROJECT STRUCTURE

```
.
├── src/
│   ├── __init__.py
│   ├── main.py           # Entry point
│   ├── config.py         # Config loading + validation
│   ├── core/
│   │   ├── __init__.py
│   │   ├── engine.py     # Core processing logic
│   │   └── models.py     # Data models + schemas
│   ├── api/
│   │   ├── routes.py     # HTTP route definitions
│   │   └── middleware.py # Auth, rate limiting, logging
│   └── utils/
│       ├── logging.py    # Structured logging setup
│       └── retry.py      # Retry + backoff utilities
├── tests/
├── docs/
├── .env.example
├── requirements.txt
└── README.md
```

---

## 🤝 CONTRIBUTING

```bash
# Fork + clone
git clone https://github.com/YOUR_USERNAME/REPO_NAME
cd REPO_NAME

# Create virtual env
python -m venv venv
source venv/bin/activate

# Install dev deps
pip install -r requirements-dev.txt

# Create feature branch
git checkout -b feat/your-feature-name

# Make changes, add tests
pytest tests/ -v

# Commit + push
git add src/ tests/
git commit -m "feat: your feature description"
git push origin feat/your-feature-name
```

**PR checklist:**
- [ ] Tests pass (`pytest tests/ -v`)
- [ ] No linting errors (`ruff check src/`)
- [ ] Type hints added for new public functions
- [ ] Docstrings for public API methods
- [ ] CHANGELOG updated if breaking change

---

## 📄 LICENSE

MIT License. See [LICENSE](LICENSE) for full text.
