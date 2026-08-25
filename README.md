# Visual Analytics with Tableau - Supplementary Material

[![CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](LICENSE)
[![Companion Website](https://img.shields.io/badge/Companion%20Site-alexloth.com-blue)](https://alexloth.com/tableau-book/)
[![Follow on X](https://img.shields.io/twitter/follow/VisAnalyticsNYC?style=social)](https://x.com/VisAnalyticsNYC)
[![R, Python & MATLAB](https://img.shields.io/badge/R%2C_Python_%26_MATLAB-Chapter_7-E97627)](chapter07)

> Official companion repository for ***Visual Analytics with Tableau*** by **Alexander Loth** (Wiley). This repo contains the Tableau Workbooks (`.twbx`) and Tableau Prep flows (`.tfl`) used throughout the book so you can follow along, experiment, and adapt the examples to your own data.

<p align="center">
  <img src="https://alexloth.com/wp-content/uploads/2021/05/3d-hard-1024x944.png" alt="Book cover: Visual Analytics with Tableau by Alexander Loth" width="420" />
</p>

**Buy the book:** [alexloth.com/tableau-book](https://alexloth.com/tableau-book/) · also at [Wiley](https://www.wiley.com/en-us/Visual+Analytics+with+Tableau-p-9781119560227) and [Amazon](https://www.amazon.com/-/de/dp/1119560209/)

---

## Who this is for

* **Business professionals** who make data-informed decisions.
* **Analysts & developers** building dashboards for teams and stakeholders.
* **Data scientists** doing rapid visual exploration before modeling.
* **Anyone** with access to data and a desire to understand it—no prior math or coding required.

## Quick start

1. **Get Tableau**

   * Use **Tableau Desktop** (free trial) or **Tableau Public** (free).
   * **Tableau Prep Builder** is required for Chapter 10 flows.
2. **Download examples**

   * Click the green **`<> Code`** button → **Download ZIP**.
   * Unzip and open the `.twbx` workbooks directly in Tableau (they are packaged with data where applicable).
3. **Follow along with the book**

   * Open the matching chapter folder and work through the examples step-by-step.

> **Tip:** If Tableau prompts you to upgrade a workbook created with an older version, accept the upgrade; save under a new filename to keep the originals untouched.

## Chapter overview

| Chapter | Title                                       | Key Topics |
| :------ | :------------------------------------------ | :--------- |
| 🚀 1    | [Introduction & Getting Started with Tableau](chapter01/) | App suite, UI, data prep basics, first viz, saving & sharing |
| 🔌 2    | Adding Data Sources in Tableau              | Connectors, joins, unions, extracts vs. live, metadata |
| 📊 3    | [Creating Data Visualizations](chapter03/)  | Bars, scatter, lines, highlight tables, heatmaps, bullet & waterfall |
| 🧮 4    | [Aggregations, Calculations & Parameters](chapter04/) | Aggregates, text/date/logical functions, what-if with parameters |
| 📈 5    | [Table Calcs & LOD Expressions](chapter05/) | Quick calcs, custom (bump), dual-axis, LOD (FIXED / INCLUDE / EXCLUDE) |
| 🗺️ 6    | [Maps](chapter06/)                         | Symbol, filled & density maps, layers, dual-axis, Viz in Tooltip, spatial data |
| 🔬 7    | [Advanced Analytics](chapter07/)            | Trend lines, forecasting, clustering, R / Python / MATLAB integration |
| 🎨 8    | [Interactive Dashboards](chapter08/)        | Layout, containers, filter / highlight / URL actions |
| 🌐 9    | Sharing Insights                            | Publish to Online / Server / Public, Ask Data, Mobile, embedding |
| 🛠️ 10   | [Data Prep with Tableau Prep](chapter10/)   | Connect, clean, split, group, join, output flows |

> **Why no folders for Chapters 2 & 9?** These chapters are concept-focused and don’t produce standalone workbooks.

## Detailed contents by chapter

### `chapter01/`

* **`First-Visualization.twbx`** – Build your first bar chart (Sales by Category) with Profit on color.

### `chapter03/`

* **`Bar-Chart-Example.twbx`** – Basic bar chart with color encoding for Profit.
* **`Waterfall-Chart.twbx`** – Cumulative Sales by Sub-Category (pages 73–77 in the book).

### `chapter04/`

* **`Calculated-Field-Profit-Ratio.twbx`** – Sales & Profit margin calculation (cf. Figure 4.4).
* **`Searchable-Customer-List.twbx`** – Parameter-driven text search (pages 100–103).

### `chapter05/`

* **`Bump-Chart.twbx`** – Visualize ranking changes over time with a dual axis.
* **`Adjustable-Moving-Average.twbx`** – Moving average with a tunable window parameter.

### `chapter06/`

* **`Symbol-Map-Sales-Profit.twbx`** – City-level map; size = Sales, color = Profit.
* **`Undersea-Cables-Map.twbx`** – Spatial-data example using undersea cable geometry (pages 148–152).

### `chapter07/`

* **`Trend-Line-Example.twbx`** – Polynomial trend line with confidence bands.
* **`Customer-Segmentation-Clusters.twbx`** – K‑means–style clustering on Sales & Profit.

### `chapter08/`

* **`Sales-Dashboard.twbx`** – Interactive dashboard with filter, highlight, and URL actions.

### `chapter10/`

* **`Superstore-Prep-Flow.tfl`** – End‑to‑end cleaning/shaping/joining in Tableau Prep.

## FAQ

**Do I need the book to use these files?**
You’ll get the most value pairing the workbooks with the book’s walkthroughs. The files are still useful as standalone references.

**Which Tableau version is required?**
Workbooks are packaged (`.twbx`) and generally open in current Tableau versions. If Tableau asks to upgrade the file, proceed and save a copy.

**Where’s the data?**
Most `.twbx` files are packaged with data (e.g., **Sample – Superstore**). If a workbook references an external file, Tableau will prompt you to locate it.

**Can I use Tableau Public?**
Yes—most examples open in **Tableau Public**. Features that require Desktop/Prep are noted in the book.

**Why are there no folders for Chapters 2 and 9?**
They’re conceptual and focus on process (connecting/publishing), not on discrete workbooks.

## Troubleshooting

* **Broken file paths / missing data** → When prompted, point Tableau to the correct data location; then **Extract → Refresh** and **save**.
* **Locale or date format issues** → Check *Data Source* settings and field types after opening; adjust date parsing if needed.
* **Performance** → If a workbook feels slow, reduce mark count (filters), switch to extracts, or aggregate to a higher level.

## How to cite

If you reference the book or materials, please use the following BibTeX entry to cite the book:

```bibtex
@book{loth2019tableau,
  title      = {Visual Analytics with {Tableau}},
  shorttitle = {Visual Analytics},
  author     = {Loth, Alexander},
  year       = {2019},
  publisher  = {Wiley},
  address    = {Hoboken, NJ, USA},
  isbn       = {978-1-119-56020-3},
  url        = {https://alexloth.com/tableau-book/},
  urldate    = {2026-08-25}
}
```

You can also link the companion site: [https://alexloth.com/tableau-book/](https://alexloth.com/tableau-book/).

GitHub also reads `CITATION.cff` in this repository, so the **Cite this repository** button in the sidebar produces the same reference with the author ORCID attached.

## Contributing

Contributions that enhance the learning experience are welcome! Use our issue templates:

* 📖 **[Report an Erratum](https://github.com/aloth/tableau-book-resources/issues/new?template=erratum.yml)** — errors in the book
* ❓ **[Ask a Question](https://github.com/aloth/tableau-book-resources/issues/new?template=question.yml)** — questions about chapters or examples
* 💻 **[Report a Code Issue](https://github.com/aloth/tableau-book-resources/issues/new?template=code-issue.yml)** — problems with companion files

## About the author

**Alexander Loth** is a Data Scientist and Digital Strategist with over 15 years of experience in AI, Data & Cloud.  
His career began at CERN and includes leadership roles at Microsoft, Tableau, and SAP. Today, he advises companies and organizations on their digital transformation journeys and is the author of several bestselling books.

[![Website](https://img.shields.io/badge/Website-alexloth.com-blue?style=flat-square)](https://alexloth.com/)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0003--9327--6865-green?style=flat-square&logo=orcid)](https://orcid.org/0009-0003-9327-6865)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-aloth-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/aloth/)
[![X (Twitter)](https://img.shields.io/badge/Follow-@xlth-black?style=flat-square&logo=x)](https://x.com/xlth)
[![Tableau Public](https://img.shields.io/badge/Tableau%20Public-Alexander%20Loth-orange?style=flat-square&logo=tableau)](https://public.tableau.com/profile/alexander.loth#!/)

## 📚 More books by the author

Companion repositories for the other books:

| Book | Publisher |
|:---|:---|
| [Content Creation mit generativer KI](https://github.com/aloth/Generative-KI-Buch-Begleitmaterialien) | mitp 2026 |
| [KI für Content Creation](https://github.com/aloth/KI-Buch-Begleitmaterialien) | mitp 2024 |
| [Microsoft Power BI: Das Praxisbuch](https://github.com/aloth/Power-BI-Fabric-Copilot-Buch-Begleitmaterialien) | mitp 2026 |
| [Datenvisualisierung mit Power BI](https://github.com/aloth/Power-BI-Buch-Begleitmaterialien) | mitp 2022 |
| [Datenvisualisierung mit Tableau](https://github.com/aloth/Tableau-Buch-Begleitmaterialien) | mitp 2021 |
| [Teach Yourself VISUALLY Power BI](https://github.com/aloth/power-bi-book-resources) | Wiley 2023 |
| [Decisively Digital](https://github.com/aloth/decisively-digital-book-resources) | Wiley 2021 |

**Note:** [Datenvisualisierung mit Tableau](https://github.com/aloth/Tableau-Buch-Begleitmaterialien) is the German-language Tableau book.

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License](LICENSE).

[![CC BY 4.0](https://i.creativecommons.org/l/by/4.0/88x31.png)](LICENSE).

## Acknowledgments

Thanks to **John Wiley & Sons** and the technical editors whose feedback improved the book and examples: **Florian Ramseger**, **Mark Bradbourne**, **Brahim Salem**, and **Srilalitha Jammalamadaka**. And thanks to the Tableau community for continued inspiration and contributions.

---

> ⭐ If these resources help you, consider **starring** the repo and following the social links above to get updates and share your work!
> 

[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
