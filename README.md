<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/computational-lab-dark.svg" />
  <img src="assets/computational-lab-light.svg" width="100%" alt="Vasilij Epishkin — Bioinformatics, Cheminformatics, Data Science and AI Engineering" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=17&duration=3100&pause=1100&color=22D3EE&center=true&vCenter=true&width=800&height=44&lines=Sequence+data+%E2%86%92+reproducible+pipelines;Chemical+names+%E2%86%92+molecular+representations;Research+papers+%E2%86%92+retrieval+%26+reasoning" />
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=17&duration=3100&pause=1100&color=087E91&center=true&vCenter=true&width=800&height=44&lines=Sequence+data+%E2%86%92+reproducible+pipelines;Chemical+names+%E2%86%92+molecular+representations;Research+papers+%E2%86%92+retrieval+%26+reasoning" width="90%" alt="Sequencing workflows, molecular data and research-focused AI" />
</picture>

</div>

### Scientific systems

A selection of projects at the intersection of computational biology, chemical data and AI engineering.

<table>
<tr>
  <td width="50%" valign="top">
    <a href="https://github.com/VasilijEpishkin/bcr-assembler">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="assets/projects/bcr-assembler.dark.svg" />
        <img src="assets/projects/bcr-assembler.light.svg" width="100%" alt="BCR sequencing simulation and assembler evaluation workflow" />
      </picture>
    </a>
  </td>
  <td width="50%" valign="top">
    <a href="https://github.com/VasilijEpishkin/iupac2smiles">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="assets/projects/iupac2smiles.dark.svg" />
        <img src="assets/projects/iupac2smiles.light.svg" width="100%" alt="IUPAC chemical names to SMILES fallback cascade" />
      </picture>
    </a>
  </td>
</tr>
<tr>
  <td width="50%" valign="top">
    <a href="https://github.com/VasilijEpishkin/EnzymeInfoCollector">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="assets/projects/EnzymeInfoCollector.dark.svg" />
        <img src="assets/projects/EnzymeInfoCollector.light.svg" width="100%" alt="Protein, reaction and compound evidence processing" />
      </picture>
    </a>
  </td>
  <td width="50%" valign="top">
    <a href="https://github.com/VasilijEpishkin/alzheimer-rag-agent">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="assets/projects/alzheimer-rag-agent.dark.svg" />
        <img src="assets/projects/alzheimer-rag-agent.light.svg" width="100%" alt="Biomedical literature retrieval and evidence-focused RAG architecture" />
      </picture>
    </a>
  </td>
</tr>
</table>

<sub>Click a system diagram to open its source repository. Diagrams describe implemented workflows, not performance claims.</sub>

### Research & engineering

| Computational biology & chemistry | Data science & AI |
| :--- | :--- |
| Sequence reconstruction, enzyme and reaction evidence, molecular representations and reproducible data workflows. | Applied ML/NLP, retrieval and reranking, research tooling, Python automation and AI-assisted analysis. |

### Technical stack

**Scientific computing & machine learning**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![RDKit](https://img.shields.io/badge/RDKit-00838F?style=flat-square)

**Tooling & reproducibility**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-222222?style=flat-square&logo=linux&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

### Evidence & reproducibility

[![iupac2smiles CI](https://github.com/VasilijEpishkin/iupac2smiles/actions/workflows/ci.yml/badge.svg)](https://github.com/VasilijEpishkin/iupac2smiles/actions/workflows/ci.yml)
[![EnzymeInfoCollector Python tests](https://github.com/VasilijEpishkin/EnzymeInfoCollector/actions/workflows/tests.yml/badge.svg)](https://github.com/VasilijEpishkin/EnzymeInfoCollector/actions/workflows/tests.yml)

- **[IUPAC → SMILES: benchmarking](https://github.com/VasilijEpishkin/iupac2smiles#benchmark)** — documented reference-based evaluation procedure.
- **[BCR assembly: comparison report](https://github.com/VasilijEpishkin/bcr-assembler/blob/main/docs/evaluation_history/assembler_comparison_report.md)** — experiment setup, metrics and assembler comparison.
- **[Enzyme graph: evidence and provenance](https://github.com/VasilijEpishkin/EnzymeInfoCollector/blob/main/docs/architecture/graph_export.md)** — source assertions, identifiers, releases and graph export.
- **[Biomedical RAG: acceptance criteria](https://github.com/VasilijEpishkin/alzheimer-rag-agent/blob/main/docs/ACCEPTANCE.md)** — tests and remaining evaluation requirements, including incomplete validation.

<details>
<summary><strong>Explore the enzyme evidence-graph schema</strong></summary>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/projects/evidence-network.dark.svg" />
  <img src="assets/projects/evidence-network.light.svg" alt="Synthetic evidence graph with protein, reaction, resolved and unresolved ChEBI compounds" width="100%" />
</picture>

This visualization reproduces the **synthetic demo structure** bundled with
[EnzymeInfoCollector's local explorer](https://github.com/VasilijEpishkin/EnzymeInfoCollector/tree/main/explorer).
It is **not experimental biological evidence**. In real data, a `CATALYZES` edge requires a direct source annotation;
sharing an EC classification never establishes catalysis. Unresolved compounds remain explicit.

</details>

### GitHub activity · Development telemetry

<div align="center">

<a href="https://gitcard-studio.creativecode.com.co/">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://gitcard-studio.creativecode.com.co/api/stats?username=VasilijEpishkin&amp;theme=dark&amp;locale=en" />
    <img src="https://gitcard-studio.creativecode.com.co/api/stats?username=VasilijEpishkin&amp;theme=light&amp;locale=en" width="470" alt="Live GitHub statistics" />
  </picture>
</a>

</div>

**Contribution landscape** · An isometric view of the past year's activity.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/activity/contributions.dark.svg" />
  <img src="assets/activity/contributions.light.svg" width="100%" alt="Isometric 3D contribution calendar generated from GitHub activity" />
</picture>

<details>
<summary><strong>Commit cadence · Weekday × hour heatmap</strong></summary>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/activity/cadence.dark.svg" />
  <img src="assets/activity/cadence.light.svg" width="100%" alt="Heatmap of authored commits by weekday and hour, with timing distributions" />
</picture>

</details>

<sub>Graphs are generated from GitHub activity each day; the cadence chart covers commits visible to the generator, not all work performed offline.</sub>
