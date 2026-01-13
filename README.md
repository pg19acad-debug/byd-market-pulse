# BYD Market Pulse Engine

Sentiment analysis pipeline for BYD electric vehicle market signals (YouTube comments, news articles).

**Goal:** Build a Gradio dashboard + personas + A/B creatives from real market data.

## Quick Start (3 steps)

### 1. Clone & Setup Environment
\`\`\`bash
git clone https://github.com/[your-username]/byd-market-pulse.git
cd byd-market-pulse
cp .env.template .env
# Edit .env with real API keys (do NOT commit .env file)
\`\`\`

### 2. Populate Data (Signal Scout + APIs team)
- Curate 4 YouTube videos → upload URLs to `data/youtube_log.csv`
- Extract 400+ comments → save as `data/comments.csv`
- Fetch 5+ articles → save as `data/articles.csv`

### 3. Launch Dashboard (App Developer + Colab)
- Open Colab notebook → [link here]
- Run all cells
- Share Gradio public link

## Team Roles & Responsibilities

| Role | Deliverable | GitHub Path |
|------|------------|-------------|
| Signal Scout | YouTube curation log | `data/youtube_log.csv` |
| APIs & Scraping | Comment extraction script | `scripts/fetch_youtube_comments.py` |
| DB & Supabase | Schema validation report | `docs/schema_validation.md` |
| App Developer | Colab notebook | `notebooks/BYD_Pulse_Dashboard.ipynb` |
| Strategy Leads | Personas + A/B specs | `assets/personas.md`, `assets/promo_specs.md` |

## Key Links

- **Supabase Project:** [SUPABASE_PROJECT_URL]
- **Colab Notebook:** [COLAB_NOTEBOOK_URL]
- **Gradio Dashboard:** [GRADIO_LIVE_URL] (generated after launch)
- **Master Spec:** See `docs/master_spec.md`

## Documentation

- `docs/schema.md` – Supabase table structure
- `docs/signal_collection_guide.md` – How to curate videos & scrape comments
- `docs/colab_setup.md` – Installation & environment setup

## Status Tracker

- [ ] GitHub repo created
- [ ] Supabase project live
- [ ] 4 YouTube videos curated
- [ ] 400+ comments extracted
- [ ] 5+ articles sourced
- [ ] Colab notebook deployed
- [ ] Gradio dashboard live
- [ ] 3 personas written
- [ ] A/B creatives finalized
- [ ] Strategic verdict completed

---

**Last Updated:** [Date]  
**Team:** [Your names]
