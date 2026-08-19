# Bots of Executive / Strategy  (docx S5 candidate menu)

These are the **Major sub-functions** of Executive / Strategy from the spec. Each is a bot — a
child decision system that can be instantiated to do the actual work.

## Install flow (matches the Orientation Protocol)
1. **Orient** — the agent runs the Kojiki Orientation Protocol (name / industry /
   jurisdiction / siblings).
2. **Research** — the agent researches the field and decides which sub-functions this
   specific org needs.
3. **Install** — instantiate only the chosen bots:
   ```bash
   cd bots
   python3 install_bots.py brand growth performance-marketing
   ```
   (use the slugs listed below; omit args to install all). Each installed bot becomes a
   full decision system under `bots/<slug>/` with README + AGENT.md + schemas + a stub
   decision record, and registers under this department's group_id for handoffs.

Total candidates: 8.

- `corporate-strategy` — **Corporate Strategy**  ·  titles: CEO, Chief Strategy Officer, VP Strategy, Head of Strategy, Strategy Director, Strategic Planning Manager, Competitive Intelligence Manager, Strategy Analyst
- `strategic-planning` — **Strategic Planning**  ·  titles: CEO, Chief Strategy Officer, VP Strategy, Head of Strategy, Strategy Director, Strategic Planning Manager, Competitive Intelligence Manager, Strategy Analyst
- `market-intelligence` — **Market Intelligence**  ·  titles: CEO, Chief Strategy Officer, VP Strategy, Head of Strategy, Strategy Director, Strategic Planning Manager, Competitive Intelligence Manager, Strategy Analyst
- `competitive-intelligence` — **Competitive Intelligence**  ·  titles: CEO, Chief Strategy Officer, VP Strategy, Head of Strategy, Strategy Director, Strategic Planning Manager, Competitive Intelligence Manager, Strategy Analyst
- `portfolio-strategy` — **Portfolio Strategy**  ·  titles: CEO, Chief Strategy Officer, VP Strategy, Head of Strategy, Strategy Director, Strategic Planning Manager, Competitive Intelligence Manager, Strategy Analyst
- `resource-allocation` — **Resource Allocation**  ·  titles: CEO, Chief Strategy Officer, VP Strategy, Head of Strategy, Strategy Director, Strategic Planning Manager, Competitive Intelligence Manager, Strategy Analyst
- `strategic-initiatives` — **Strategic Initiatives**  ·  titles: CEO, Chief Strategy Officer, VP Strategy, Head of Strategy, Strategy Director, Strategic Planning Manager, Competitive Intelligence Manager, Strategy Analyst
- `scenario-planning` — **Scenario Planning**  ·  titles: CEO, Chief Strategy Officer, VP Strategy, Head of Strategy, Strategy Director, Strategic Planning Manager, Competitive Intelligence Manager, Strategy Analyst
