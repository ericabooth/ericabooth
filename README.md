<h1 align="center">Eric A. Booth</h1>

<p align="center">
  <b>Researcher &middot; Evaluation Specialist &middot; Statistical Programmer</b><br>
  <sub>Monitoring, Evaluation &amp; Learning &nbsp;|&nbsp; Austin, TX &nbsp;|&nbsp; <a href="https://texas2036.org">Texas&nbsp;2036</a></sub><br>
  <sub><i>Alchemizing &#9749; caffeine into Stata code</i></sub>
</p>

<p align="center">
  <img alt="Stata" src="https://img.shields.io/badge/Stata-1a5fb4?style=flat-square&logo=stata&logoColor=white">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="R" src="https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white">
  <img alt="SQL" src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white">
  <img alt="LaTeX" src="https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white">
  <img alt="Shell" src="https://img.shields.io/badge/Shell-121011?style=flat-square&logo=gnubash&logoColor=white">
</p>

<p align="center">
  <a href="https://ericabooth.github.io/code-portfolio/"><img alt="Code portfolio" src="https://img.shields.io/badge/code%20portfolio-48%20commands-0b6b6b?style=flat-square"></a>
  <a href="https://econpapers.repec.org/RAS/pbo536.htm#author-software"><img alt="SSC" src="https://img.shields.io/badge/SSC%20archive-25%20modules-8a6a1f?style=flat-square"></a>
  <a href="https://scholar.google.com/citations?user=dX8xU4UAAAAJ&hl=en"><img alt="Scholar" src="https://img.shields.io/badge/Google%20Scholar-4285F4?style=flat-square&logo=googlescholar&logoColor=white"></a>
  <a href="https://orcid.org/0000-0001-9607-5979"><img alt="ORCID" src="https://img.shields.io/badge/ORCID-A6CE39?style=flat-square&logo=orcid&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/eric-booth-746376a"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
</p>

---

Two decades in **Monitoring, Evaluation and Learning**, working where complex statistical
programming meets applied policy research. I build the evidence base for state, federal and
foundation-funded programs in **education, behavioral health and juvenile justice** — and I build
the tooling that makes that work reproducible. Currently at the non-partisan policy think tank
**Texas 2036**, on data-driven policy for the state.


### Start here

**[→ The code portfolio](https://ericabooth.github.io/code-portfolio/)** — every tool I maintain,
searchable by the problem it solves, with a gallery of what ten of the packages actually produce.

### Packages

**Recent work**

| Package | What it does | Install |
|---|---|---|
| `mergemap` <sub>v0.5.6</sub> | Maps every join in a do-file and what each did to the row count | [GitHub](https://github.com/ericabooth/mergemap-stata-public) |
| `surveymap` <sub>v0.8.4</sub> | Survey flow maps that count answers, refusals and skips separately | [GitHub](https://github.com/ericabooth/surveymap-stata-public) |
| `datadeposit` <sub>v0.1.1</sub> | Archive-ready copies of a dataset for Stata, R and Python in one step | [GitHub](https://github.com/ericabooth/datadeposit) |
| `peerpick` <sub>v0.1.2</sub> | Picks a comparison group for one unit, then tests how much it mattered | [GitHub](https://github.com/ericabooth/peerpick-stata-public) |
| `ercotapi` <sub>v1.0.2</sub> | Pulls ERCOT grid data — prices, load, generation — straight into Stata | [GitHub](https://github.com/ericabooth/ercotapi-stata-public) |
| `sparkta2` <sub>v0.8.13</sub> | Interactive small-multiple and county maps, charts and dashboards | [GitHub](https://github.com/ericabooth/sparkta2-stata-public) |

**Build &amp; publish**

| Package | What it does | Install |
|---|---|---|
| `dashboardbuilder` <sub>v1.3.4</sub> | Self-contained interactive HTML dashboards, written from a do-file | `ssc install dashboardbuilder` |
| `statashiny` <sub>v1.5.4</sub> | Shiny-style widgets that recompute in the browser | `ssc install statashiny` |
| `webdoc2` <sub>v1.1.6</sub> | Turns the do-file that made the numbers into the page that reports them | [GitHub](https://github.com/ericabooth/webdoc2-stata-public) |
| `googlechart` <sub>v0.1.7</sub> | Google Charts and dashboards driven straight from Stata | `ssc install googlechart` |
| `statplot` <sub>v1.3.0</sub> | Plots of summary statistics, by category *(with Nicholas J. Cox)* | `ssc install statplot` |

**Data plumbing &amp; workflow**

| Package | What it does | Install |
|---|---|---|
| `googlesheets` <sub>v0.1.7</sub> | Read, write and format Google Sheets without leaving Stata | `ssc install googlesheets` |
| `webapi` <sub>v0.1.4</sub> | Fetches an authenticated JSON web API into Stata as a dataset | `ssc install webapi` |
| `datadictionary` <sub>v1.0.2</sub> | Over-time-ready codebooks across survey waves | `ssc install datadictionary` |
| `reshapehelper` <sub>v1.0.1</sub> | Diagnoses the data and suggests the reshape before you run it | `ssc install reshapehelper` |
| `srctag` <sub>v2.0.1</sub> | Stamps variables with source lineage, then searches that provenance | [GitHub](https://github.com/ericabooth/srctag-stata-public) |
| `projectbuilder` <sub>v2.1.2</sub> | Scaffolds a project folder with a numbered do-file pipeline | `ssc install projectbuilder` |

<sub>Version numbers are current as of the latest release; the full set lives in the <a href="https://ericabooth.github.io/code-portfolio/">code portfolio</a>.</sub>


<details>
<summary><b>Demo sites &amp; galleries</b></summary>

<br>

| Gallery | What it shows |
|---|---|
| [mergemap](https://ericabooth.github.io/code-portfolio/galleries/mergemap/) | Every `mergemap` output from one pipeline: the receipt, the map as SMCL / HTML / PNG / mermaid / DOT, and run mode with observed counts |
| [surveymap](https://ericabooth.github.io/code-portfolio/galleries/surveymap/) | Survey flow maps and response braids, with answers, refusals and skips counted separately |
| [Webdoc2](https://ericabooth.github.io/Webdoc2_Example_Site/) | Interactive websites generated from Stata do-files |
| [Sparkta2](https://ericabooth.github.io/Sparkta2_Example_Site/) | Interactive small-multiple and county maps from Stata |
| [StataShiny](https://ericabooth.github.io/StataShiny_Example_Site/) | Simulations, interactive visualizations and web tables written from Stata |
| [GoogleChart](https://ericabooth.github.io/GoogleChart_Example_Site/) | Google Charts and Google Sheets driven from Stata |
| [DashboardBuilder](https://ericabooth.github.io/dashboardbuilder_Example_Site/) | HTML/JS dashboards built from do-files; embeds webdoc2, sparkta2 and statashiny output |

</details>

<details>
<summary><b>Background &amp; expertise</b></summary>

<br>

**Now:** Texas 2036 — data modernization and advanced analytics for state policy.

**Previously:** Senior Director of Research and President at Far Harbor, LLC (promoted from
Sr. Statistician, 2020) · Research Faculty at the Texas A&amp;M Public Policy Research Institute ·
Lecturer in Health Policy &amp; Management at Texas A&amp;M, teaching graduate research methods and
statistical programming · Senior Research Scientist at Gibson Consulting Group. Affiliated
researcher with the Texas Education Research Center and the Southwest Regional Education
Laboratory (REL).

**Selected impact.** Published in the *Journal of Developmental Education*, *Party Politics*,
*American Journal of Public Health* and the *Journal of Applied Research on Children*; co-author of
a book from Teachers College Press; 80+ technical and evaluation reports. The CSG-sponsored study
*Breaking Schools' Rules* provided statewide longitudinal analysis of school discipline and juvenile
justice placement that informed state and federal legislative change, and was cited as a motivating
study for President Obama's *My Brother's Keeper* initiative.

**Core expertise**
- **Statistical programming** — expert-level Stata (active SSC contributor) and Python; working R, SAS and NVivo.
- **Complex modeling** — multilevel models, panel data, sampling weights, nonresponse bias sensitivity; LASSO and related ML.
- **Workflow automation** — reproducible end-to-end pipelines, from raw data to analytic dataset to deliverable.
- **Study design** — lead investigator on large longitudinal studies and RCTs, including designs built for messy collection and hard-to-retain participants.

**Teaching.** Workshops on applied evaluation, including AI-assisted methods — most recently the
NSF-funded *Research in Excellence* workshop at Prairie View A&amp;M and the Texas Evaluation Network
annual meeting.

**Data advocacy.** State-level data modernization and data-rescue work: harmonization,
machine-readability and transparency in public reporting.

</details>

---

- **Website:** [www.eric-booth.com](https://sites.google.com/site/ericabooth/cv/mycv)
- **Email:** [eric.a.booth@gmail.com](mailto:eric.a.booth@gmail.com)
- **RePEc / SSC:** [software and papers](https://econpapers.repec.org/RAS/pbo536.htm#author-software)
- **OSF:** [osf.io/2n4k7](https://osf.io/2n4k7/)
- **Statalist:** [active member and contributor](https://www.statalist.org/)
