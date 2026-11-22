<!--
  Profile README for github.com/Tulsee
  Banner and chart are hand-made SVGs in /assets, each with a dark and a light version.
  The contribution snake is redrawn daily by .github/workflows/snake.yml.
-->

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/hero-light.svg">
  <img alt="Shankar Ghimire. Reliable deep learning under uncertainty, multimodal fusion when inputs go missing, and retrieval that knows when not to answer." src="assets/hero-light.svg" width="100%">
</picture>

<p align="center">
  <a href="https://orcid.org/0009-0002-1877-0268"><img alt="ORCID 0009-0002-1877-0268" src="https://img.shields.io/badge/ORCID-0009--0002--1877--0268-A6CE39?style=flat-square&logo=orcid&logoColor=white"></a>
  <a href="https://doi.org/10.5281/zenodo.20199049"><img alt="First-author preprint on Zenodo" src="https://img.shields.io/badge/Preprint-Zenodo-1682D4?style=flat-square&logo=zenodo&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/shankar-ghimire/"><img alt="LinkedIn shankar-ghimire" src="https://img.shields.io/badge/LinkedIn-shankar--ghimire-0A66C2?style=flat-square"></a>
  <a href="mailto:ghimire.shankar1996@gmail.com"><img alt="Email ghimire.shankar1996@gmail.com" src="https://img.shields.io/badge/Email-ghimire.shankar1996-EA4335?style=flat-square&logo=gmail&logoColor=white"></a>
</p>

## About

I'm a software engineer in Kathmandu and an MSc candidate in Data Science and Computational Intelligence at Coventry University. One question runs through my work: **how can a learned model tell when its evidence is too weak to answer?** I build systems that answer only when they should, then measure whether they really do.

- **Now:** an MSc thesis on multimodal deep learning that fuses volumetric MRI features with clinical metadata to classify Alzheimer's disease
- **Building:** [SupportIQ](https://github.com/Tulsee/supportIQ), a help desk whose assistant answers, asks, escalates or declines depending on its evidence
- **Next:** doctoral research on reliable and multimodal deep learning

## Research interests

<table>
  <tr>
    <td width="33%" valign="top">
      <b>Uncertainty and abstention</b><br>
      <sub>Selective prediction, deferral to people, and guarantees on the errors a model still makes</sub>
    </td>
    <td width="33%" valign="top">
      <b>Robust multimodal learning</b><br>
      <sub>Combining imaging and clinical data when one input is missing or unreliable</sub>
    </td>
    <td width="33%" valign="top">
      <b>Trustworthy retrieval</b><br>
      <sub>Hybrid search, evidence checks, and evaluation that others can reproduce</sub>
    </td>
  </tr>
</table>

## Featured: SupportIQ

<p>
<a href="https://github.com/Tulsee/supportIQ">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/supportiq-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/supportiq-light.svg">
    <img alt="Dumbbell chart comparing an always-answer baseline with evidence-gated answering on 29 held-out questions. Answered when it should not have: 8 of 13 versus 0 of 13. Behaviour matched the label: 72% (95% CI 54 to 85) versus 93% (78 to 98). Answerable questions answered correctly: 16 of 16 versus 15 of 16." src="assets/supportiq-light.svg" width="100%">
  </picture>
</a>
</p>

An open-source help desk whose assistant checks its evidence before it replies: it answers with citations, asks a clarifying question, escalates when documents disagree, or declines. Hybrid BM25 and dense retrieval with cross-encoder reranking reaches MRR@10 0.96, invented citations are removed, a contradiction scanner flags conflicting documents, and the whole system runs on a laptop CPU. The chart shows the trade-off honestly: one answerable question fewer, in exchange for no unwarranted answers.

**[Code](https://github.com/Tulsee/supportIQ)** · **[Evaluation](https://github.com/Tulsee/supportIQ#evaluation)**

## More work

<table>
  <tr>
    <td width="50%" valign="top">
      <b><a href="https://github.com/Tulsee/ann">Alzheimer's MRI classification</a></b><br>
      VGG16 and ResNet50 compared in PyTorch with sensitivity, not accuracy, as the main criterion, because a missed early-stage case costs more than a false alarm.<br>
      <sub>PyTorch · transfer learning · medical imaging · <a href="https://doi.org/10.5281/zenodo.20199049">preprint</a></sub>
    </td>
    <td width="50%" valign="top">
      <b><a href="https://github.com/Tulsee/rag_chatbot">Local RAG chatbot</a></b><br>
      Private question answering over your own PDFs, with hybrid dense and sparse retrieval, source-page citations, and a harness that checks whether retrieved passages hold the evidence each answer needs.<br>
      <sub>Qdrant · BM25 · Ollama · LangChain</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b><a href="https://github.com/Tulsee/automated_hiring_process">Local AI hiring agent</a></b><br>
      Explainable candidate scoring that reports matched and missing skills, with a human-in-the-loop pause before any hiring decision. In progress.<br>
      <sub>FastAPI · LangGraph · Qdrant · MongoDB</sub>
    </td>
    <td width="50%" valign="top">
      <b><a href="https://github.com/bettercollected/bettercollected">Bettercollected</a></b> <sub>open-source contributor</sub><br>
      Built Discord, Slack and Google Sheets integrations for an open-source forms platform and resolved community-reported issues.<br>
      <sub>FastAPI · Next.js · MongoDB</sub>
    </td>
  </tr>
</table>

## Preprints

- **Sensitivity-prioritized comparative evaluation of VGG16 and ResNet50 deep learning architectures for early-stage Alzheimer's disease detection from brain MRI**<br>
  <sub>**S. Ghimire**, B. Thapa Magar, N. Adhikari, S. Neupane, S. Maharjan · Zenodo · 2026 · [doi:10.5281/zenodo.20199049](https://doi.org/10.5281/zenodo.20199049)</sub>
- **When reward is not grammar: A reward-action validity audit of deep reinforcement learning for English inflection**<br>
  <sub>N. Adhikari, **S. Ghimire**, S. Neupane · Research Square · 2026 · [doi:10.21203/rs.3.rs-10755274/v1](https://doi.org/10.21203/rs.3.rs-10755274/v1)</sub>
- **Transparent context-aware retrieval for mental health and substance use service navigation**<br>
  <sub>N. Adhikari, **S. Ghimire** · Research Square · 2026 · [doi:10.21203/rs.3.rs-10862112/v1](https://doi.org/10.21203/rs.3.rs-10862112/v1)</sub>
- **Demand forecasting for internet bandwidth using machine learning to enhance resource management in Nepal**<br>
  <sub>S. Maharjan, **S. Ghimire** · Research Square · 2026 · [doi:10.21203/rs.3.rs-10747280/v1](https://doi.org/10.21203/rs.3.rs-10747280/v1)</sub>

## Toolbox

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=py,pytorch,sklearn,matlab,fastapi,postgres,redis,mongodb,docker,githubactions,linux,aws,gcp,ts,nextjs&theme=dark">
  <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=py,pytorch,sklearn,matlab,fastapi,postgres,redis,mongodb,docker,githubactions,linux,aws,gcp,ts,nextjs&theme=light">
  <img alt="Python, PyTorch, scikit-learn, MATLAB, FastAPI, PostgreSQL, Redis, MongoDB, Docker, GitHub Actions, Linux, AWS, Google Cloud, TypeScript, Next.js" src="https://skillicons.dev/icons?i=py,pytorch,sklearn,matlab,fastapi,postgres,redis,mongodb,docker,githubactions,linux,aws,gcp,ts,nextjs&theme=light">
</picture>

<sub>Also: Qdrant, LangGraph, LangChain, Ollama, Celery, pandas, NumPy, PySpark</sub>

## Contributions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Tulsee/Tulsee/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Tulsee/Tulsee/output/github-snake.svg">
  <img alt="A snake eating the squares of the contribution graph" src="https://raw.githubusercontent.com/Tulsee/Tulsee/output/github-snake.svg" width="100%">
</picture>
