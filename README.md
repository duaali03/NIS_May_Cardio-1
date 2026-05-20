# AliFam Nerds Research Repository

AliFam Nerds is a team of medical doctors and biostatisticians working together at the **Research Council of Pakistan (RCOP)**. We maintain this repository to share code, analyses, and documentation for our research projects. Our aim is to produce high-quality, reproducible work that advances medical knowledge while helping each other grow as early-career investigators.

Visit [rcop.pk](https://rcop.pk) to learn more about RCOP's mission and initiatives.

![R Version](https://img.shields.io/badge/R-4.5%2B-blue)
![Quarto](https://img.shields.io/badge/Quarto-enabled-brightgreen)
![License](https://img.shields.io/badge/license-restricted-lightgrey)

---

## Table of Contents

- [AliFam Nerds Research Repository](#alifam-nerds-research-repository)
  - [Table of Contents](#table-of-contents)
  - [Repository Structure](#repository-structure)
  - [Getting Started](#getting-started)
  - [Contributing](#contributing)
  - [License](#license)
  - [About AliFam Nerds](#about-alifam-nerds)
    - [Our Core Values](#our-core-values)
  - [Contact](#contact)

---

## Repository Structure

Each project directory typically includes:

- `data/` – Raw or processed data files. These are **not tracked in Git** due to data use restrictions.
- `scripts/` – R scripts for data cleaning, modeling, and visualization.
- `quarto/` – Quarto documents (`.qmd`) used to generate reports or manuscripts.
- `renv/` and `renv.lock` – Files used by the **renv** package to manage project-specific R dependencies.

Additional folders such as `documents/` or `plots/` may appear if the project includes supplementary materials like posters, slides, handouts, or figures.

---

## Getting Started

1. Install **R** (version 4.5 or later) and optionally [RStudio](https://posit.co/download/rstudio-desktop/) or [Positron](https://positron.posit.co/).
2. Install the [Quarto CLI](https://quarto.org/docs/get-started/) if you plan to render `.qmd` documents.
3. Navigate to a project directory and run `renv::install()` to install the packages listed in `renv.lock`.
4. Execute scripts in `scripts/` or render Quarto documents from `quarto/` to reproduce analyses.

> **Note**: This repository does not include raw datasets. To reproduce most analyses, access to external datasets (e.g., CDC WONDER, the Nationwide Inpatient Sample (NIS), or the Nationwide Readmissions Database (NRD)) is required. These may require institutional approval. Please consult the respective data providers for access instructions.

---

## Contributing

This repository is used internally by RCOP and by collaborators within the AliFam Nerds group. If you're part of the team:

- Feel free to open issues or submit pull requests.
- When adding a new project, follow the established directory layout.
- Include a short `README.md` in each project folder describing the study’s aim and workflow.

---

## License

All content is © Ali Salman. Redistribution or reuse without explicit permission is prohibited. See [`LICENSE.md`](LICENSE.md) for more information.

---

## About AliFam Nerds

AliFam Nerds began in 2023 as a small mentorship circle founded by [**Ali Salman**](https://github.com/AliSalman-et-al), who now serves as Head Research Analyst at RCOP. After entering Dow Medical College in 2022, Ali sought ways to combine his lifelong interest in computing with the field of medicine. An introductory RCOP workshop on research sparked his interest in applying biostatistics and data science to academic medicine.

He embarked on a self-taught journey using resources such as the Open Source Society University (OSSU) curriculum, Coursera, OpenCourseWare, and EdX, alongside a wide range of textbooks in statistics, mathematics, and programming. Through this path, he developed practical skills in reproducible research, statistical programming, and scientific communication.

Encouraged by [RCOP leadership](https://rcop.pk/our-team/), Ali began mentoring his peers and building what would eventually become a collaborative network of like-minded researchers.

Today, this community has grown into a dedicated team of Research Analysts at RCOP working on high-impact, data-driven projects. This repository serves as their shared workspace for refining analyses, ensuring reproducibility, and developing as scientific investigators.

---

### Our Core Values

- **Collaboration and generous support** – We openly exchange knowledge and help one another grow.
- **Professionalism and respect** – A collegial environment is expected at all times.
- **Confidentiality** – All project code and discussions remain within the team.
- **Mutual trust** – We protect the space that protects our growth.

---

## Contact

For any questions or collaboration inquiries, feel free to contact [Ali Salman](mailto:alisalman.md@outlook.com), Head Research Analyst at RCOP.
