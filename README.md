# moraldeep.github.io

Personal portfolio website for **Moraldeep Sachdeo** — Product Manager with 7+ years of experience in AI products, LLM applications, RAG architectures, and evaluation pipelines.

🔗 **Live site:** [moraldeep.github.io](https://moraldeep.github.io/)

## Sections

- **About** — Background and current role at Microsoft (M365 Copilot fine-tuning & AI evaluation frameworks)
- **Vibe-Coding** — AI/ML project demos including RAG Database Routing, MCP Travel Planner, Voice Support Agent, Meeting Prep Agent, DocSignal, and more
- **Experience** — Career history across Microsoft, Sprinklr, Micron, Western Digital, Beam Solutions, Imarticus Learning, and Mercedes Benz
- **Projects** — Additional work in pedestrian intention detection, supply chain simulation, Tableau dashboards, and go-to-market strategy
- **Education** — MS Operations Research (UC Berkeley), BTech Engineering (VIT Vellore)
- **Publications** — Research published in IEEE and IJLSS
- **Reads** — Curated research papers on RAG evaluation, RLHF, DPO, and conversational AI

## Project Structure

```
├── index.html                  # Main portfolio page
├── 404.html                    # Custom 404 page
├── robots.txt
├── sitemap.xml
├── assets/
│   ├── css/                    # Stylesheets (nav, pub, style)
│   ├── img/                    # Images, logos, project thumbnails
│   └── js/                     # JS utilities (favicon, GitHub stars, Google Scholar citations)
├── projects/                   # Individual project detail pages
├── publications/               # Publications listing page
├── google_scholar_crawler/     # Python script to fetch Google Scholar citation data
│   ├── main.py
│   ├── requirements.txt
│   └── results/                # Cached citation data (JSON)
└── html_source_file/           # Source/template files
```

## Google Scholar Citation Crawler

A Python utility that fetches citation counts from Google Scholar and stores the result as a shields.io-compatible JSON badge.

```bash
cd google_scholar_crawler
pip install -r requirements.txt
python main.py
```

## Local Development

Open `index.html` in a browser, or serve locally:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

This site is deployed via [GitHub Pages](https://pages.github.com/) from the root of the `main` branch. Pushing to `main` automatically publishes updates.

## License

© Moraldeep Sachdeo. All rights reserved.
