---
title: "From Model to Message"
subtitle: "Power BI Data Visualization and Analysis — A PL-300 Aligned Course"
description: |
  A pedagogical guide to data visualization in Power BI, aligned to the Visualize-and-Analyze
  and Manage-and-Secure domains of the Microsoft PL-300 certification exam (skills measured
  as of January 15, 2026). Built for community college students who have completed an
  introductory Power BI data preparation and modeling course, with a neurodivergent-friendly
  design throughout.
---

:::{figure} images/cover.png
:label: fig-cover
:alt: From Model to Message cover by Professor Carlos Marquez
:width: 100%
:align: center

*From Model to Message* · Professor Carlos Marquez
:::

# From Model to Message

### Power BI Data Visualization and Analysis — A PL-300 Aligned Course

This book teaches you to build Power BI reports that drive decisions. It is the second course in a two-semester sequence at Miami Dade College. The first course (CAP2791C) built the data model. This course (CAP2743C) builds the report.

The book is also aligned to two of the four domains of the Microsoft **PL-300: Power BI Data Analyst Associate** certification exam — the Visualize-and-Analyze domain and the Manage-and-Secure domain — using the skills measured as of **January 15, 2026**.

---

## Who This Book Is For

You will get the most out of this book if you:

- Have completed an introductory Power BI course covering Power Query, the star schema, relationships, and beginner DAX. At Miami Dade College, that prerequisite is CAP2791C: Power BI Data Preparation and Modeling.
- Are comfortable with Excel formulas and basic SQL (`SELECT`, `JOIN`, `WHERE`).
- Are preparing for the PL-300 exam, or stepping into an entry-level BI analyst role, or both.

If you have never opened Power BI Desktop before, this is not the right starting point. Begin with the prerequisite material first, then come back here.

---

## How This Book Is Different

- **Pedagogical, not reference.** Microsoft Learn documents Power BI. This book teaches it. You will hear a real voice on the page, in second person, with stories and analogies and the kind of warnings a professor gives after teaching the same class ten times.
- **Neurodivergent-friendly design throughout.** Chunked sections of 500–800 words. One-sentence previews and transitions. Five color-coded callout types. View Compass at the top of every chapter. The See-It → Name-It → Find-It → Do-It pattern for every Power BI interaction. Mandatory Take-a-Breath boxes. No content block that runs more than ten minutes without a marker.
- **One dataset, the whole way.** Every example, demo, and case study uses **AdventureWorks_Sales.xlsx** — Microsoft's official PL-300 prep dataset. No dataset switching, no toy data.
- **A South Florida cultural anchor with global data.** The book's recurring cast lives and works in South Florida — Hialeah, Miami Shores, the Port of Miami, hurricane season, cafecito and cortaditos, I-95 traffic. The data they analyze spans six countries and three regions, because AdventureWorks is a global cycling company.
- **Aligned to PL-300 (January 15, 2026).** Chapters 1–6 cover the Visualize-and-Analyze domain (25–30% of the exam). Chapters 7–8 cover the Manage-and-Secure domain (15–20% of the exam). Three skills are flagged as **new** for the January 15, 2026 update and receive explicit, in-depth coverage: Visual Calculations with DAX (Chapter 5), Copilot for narrative visuals and new report pages (Chapters 5 and 6), and Copilot to summarize the semantic model (Chapter 6).

---

## The Cast

You will meet four recurring characters throughout the book. They are not narrative dressing — they are the way the technical material gets taught.

- **Camila Reyes** — Protagonist. Junior BI analyst at AdventureWorks' fictional South Florida regional office. Recent MDC graduate, Cuban-American, from Hialeah. Across the eight chapters she grows from her first nervous Monday-morning meeting to running a deployment pipeline.
- **Marcus Bell** — VP of Sales for the AW South Florida region, and Camila's stakeholder. African-American, former Navy supply officer. Demands clarity. No tolerance for visual noise. Carries an actual paper notebook.
- **Dr. Priya Iyer** — Camila's former MDC professor, now an adjunct and BI consultant. South Asian. The mentor who connects classroom theory to industry practice and surfaces PL-300 exam expertise.
- **Jamal Foster** — Peer in AW's central BI Center of Excellence (the governance side). Haitian-American, from Miami Shores. Appears in cameo through Chapters 1–6, then becomes central in Chapters 7 and 8 when governance takes over.

---

## Table of Contents

### Part 1 — Foundations of Visualization

**Chapter 1.** [From Model to Message — Foundations of Power BI Visualization](chapters/ch01-from-model-to-message.md)
The bridge from the data model you built in CAP2791C to the report you will build here. Anatomy of a Power BI report. Visual encoding 101 — position, length, color, area, and the accuracy hierarchy. Pre-attentive processing. The chain from question to shape of answer to chosen visual. Environment setup, then your first hands-on report from AdventureWorks.

**Chapter 2.** [The Core Visual Toolkit](chapters/ch02-core-visual-toolkit.md)
Bar, column, clustered, and stacked charts for categorical comparisons. Line, area, and ribbon for trends. Pie, donut, and treemap for part-to-whole (and when *not* to use them). Scatter, histogram, and box plot for relationships and distributions. Tables and matrices. Maps. KPI cards, gauges, and multi-row cards.

### Part 2 — Design and Interaction

**Chapter 3.** [Formatting, Conditional Logic, and Custom Visuals](chapters/ch03-formatting-conditional-custom-visuals.md)
Themes (built-in, customized, JSON). Conditional formatting with color scales, rules, and field-value drivers. Small multiples. Custom visuals from AppSource and the security trade-offs. R and Python visuals when the built-ins aren't enough. Accessibility design (alt text, tab order, contrast, screen readers).

**Chapter 4.** [Interactive Storytelling — Filters, Navigation, and Drill-Through](chapters/ch04-interactive-storytelling.md)
The three-layer filter hierarchy (visual, page, report). Slicers and sync slicers. Bookmarks and navigation buttons. Custom tooltips and tooltip pages. Editing interactions. Drill down, drill through, cross-filter. The Selection pane. Sorting strategies.

### Part 3 — Analytics and AI

**Chapter 5.** [Insights That Tell a Story — Analytics, Statistics, and Visual Calculations](chapters/ch05-analytics-statistics-visual-calculations.md)
The Analyze feature. Top N analysis two ways. The Analytics pane (reference lines, error bars, forecasting). Quick Insights. Smart Narrative and narrative visuals with Copilot **(new for 2026)**. Visual Calculations with DAX **(new for 2026)**. Play Axis.

**Chapter 6.** [AI-Powered Analysis — Patterns, Anomalies, and Copilot](chapters/ch06-ai-patterns-anomalies-copilot.md)
Grouping, binning, and clustering. Outlier and anomaly detection. The Key Influencers visual. The Decomposition Tree. The Q&A visual. AI Insights. Copilot for new report pages **(new for 2026)**. Copilot to summarize the semantic model **(new for 2026)**. The ethics of AI-assisted analysis.

### Part 4 — Distribution and Production

**Chapter 7.** [Beyond the Report — Dashboards, Mobile, and Distribution](chapters/ch07-dashboards-mobile-distribution.md)
Dashboards vs. reports vs. apps. Building a dashboard, pinning tiles, dashboard Q&A. Mobile-optimized layouts. Data alerts and subscriptions. Paginated reports. Automatic page refresh. Exporting to Excel. Personalize Visuals.

**Chapter 8.** [Production-Ready BI — Workspaces, Security, and Governance](chapters/ch08-workspaces-security-governance.md)
Workspaces (purpose, roles, configuration). Publishing, versioning, and workspace apps. Sensitivity labels. Promoting and certifying content. Item-level access. Row-Level Security with roles. Scheduled and incremental refresh. Gateways. Deployment pipelines. A PL-300 exam strategy capstone.

---

## How to Use This Book

Each chapter follows the same structure:

1. **Opening image** that captures the chapter's narrative arc.
2. **Title** and chapter position banner.
3. **Power BI View Compass** naming which views you will use in this chapter.
4. **Opening hook** — a story, a question, or a stake.
5. **Learning objectives** (3–5 things you will be able to do by the end).
6. **Chapter roadmap** in one paragraph.
7. **5–8 named subchapters** of conceptual and hands-on material.
8. **1–2 short stories** with technical-connection footers.
9. **Minimum 2 Take-a-Breath cognitive-reset markers.**
10. **A case study** near the end of the conceptual content.
11. **Chapter closing**: Key Takeaways, Concept Map, Vocabulary Review, Bridge to the Next Chapter, 5 Self-Check Questions with answers, and a Reflection Prompt.

You will see five callout box types throughout. Each has a consistent color and meaning:

- 💡 **Blue · WHY ARE WE DOING THIS?** — Rationale and context.
- ✅ **Green · DO THIS** — Action steps.
- 🛑 **Red · STOP AND CHECK** — Verification of expected screen state.
- ⚠️ **Yellow · COMMON MISTAKE** — Frequent errors and how to fix them.
- 💜 **Purple · TAKE A BREATH** — Cognitive reset point.

---

## Prerequisites and Setup

Before you start Chapter 1, you should have:

1. **Power BI Desktop** installed (Windows; Mac users use lab machines or VMs).
2. **A Microsoft 365 account** with a Power BI Service license. MDC provides one to every student.
3. **The AdventureWorks_Sales.xlsx file** from the course GitHub repository.

Chapter 1, Section 1.6 walks you through each of these step by step.

---

## A Note on Tone and Difficulty

Some sections of this book will feel hard. Power BI has corners that trip up professional developers, never mind students. Where a section is genuinely difficult, the book says so up front. Struggle here is normal and expected — it is part of the work, not a sign you are doing something wrong.

The book also acknowledges where Microsoft's terminology, defaults, or naming has changed over the years (the **Fields Pane** is now the **Data Pane**, and so on). The current name is used in instructions; older names are flagged the first time so that your search results from older tutorials still make sense.

---

## License

This book is published under the **Creative Commons Attribution 4.0** license. You are free to share, remix, and adapt the material, including for commercial purposes, with attribution.

Source code, datasets, and chapter files are in the [GitHub repository](https://github.com/c-marq/power-bi-data-viz-pl300). Issues, corrections, and pull requests are welcome.
