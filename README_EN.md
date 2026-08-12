# PaperScope

<p align="center">
  <strong>English</strong> | <a href="README.md">中文</a>
</p>

> A desktop literature search assistant for research discovery, paper filtering, citation tracing, and AI-assisted reading workflows.

<p align="center">
  <img alt="Release" src="https://img.shields.io/github/v/release/Daniel123jia/PaperScope?label=release">
  <img alt="Platform" src="https://img.shields.io/badge/platform-Windows%20%7C%20macOS-blue">
  <img alt="Source Code" src="https://img.shields.io/badge/source%20code-not%20included-lightgrey">
  <img alt="Trial" src="https://img.shields.io/badge/trial-available-green">
</p>

**PaperScope** is a local desktop app that searches online academic data sources. It helps researchers, students, teachers, and engineers discover papers, filter results, trace citations, and organize reading candidates.

This repository only provides compiled Windows and macOS packages. **Source code is not included.**

## Download

Recommended version: [PaperScope v1.8](https://github.com/Daniel123jia/PaperScope/releases/tag/v1.8).

All versions are available on [GitHub Releases](https://github.com/Daniel123jia/PaperScope/releases).

| Version | Trial | Windows | Intel Mac | Apple Silicon Mac | Highlights |
| --- | ---: | :---: | :---: | :---: | --- |
| [v1.8](https://github.com/Daniel123jia/PaperScope/releases/tag/v1.8) | 10 days | Yes | Yes | Yes | Added AI Paper Radar, top venue archives, research topic maps, citation-context analysis, more themes, default deep search, and an improved smart journal shortcut |
| [v1.7](https://github.com/Daniel123jia/PaperScope/releases/tag/v1.7) | 10 days | Yes | Yes | Yes | Added ordinary / deep search, title direction categories, smart journal finder, classified citing-paper analysis, paper email delivery, manual subscriptions, safer PDF downloading, and stronger source routing / deduplication |
| [v1.6](https://github.com/Daniel123jia/PaperScope/releases/tag/v1.6) | 10 days | Yes | Yes | Yes | Improved journal / conference filtering, added official proceedings sources, and strengthened multi-source search stability |
| [v1.5](https://github.com/Daniel123jia/PaperScope/releases/tag/v1.5) | 10 days | Yes | Yes | Yes | Redesigned result page, paper-analysis templates, AI title-copy workflow, and search stability improvements |
| [v1.4](https://github.com/Daniel123jia/PaperScope/releases/tag/v1.4) | 7 days | Yes | Yes | Yes | Citing-paper workflow, CAS partition filtering, CCF and English UI improvements |
| [v1.3](https://github.com/Daniel123jia/PaperScope/releases/tag/v1.3) | 20 days | Yes | Yes | Yes | Chinese / English UI, multi-source search orchestration, multiple interface backgrounds |
| [v1.2](https://github.com/Daniel123jia/PaperScope/releases/tag/v1.2) | 7 days | Yes | Yes | Yes | First release with Windows, Intel Mac, and Apple Silicon Mac packages |
| [v1.1](https://github.com/Daniel123jia/PaperScope/releases/tag/v1.1) | 7 days | Yes | No | No | Windows EXE and portable ZIP |

Different versions may provide 7-day, 10-day, or 20-day trials because PaperScope is updated regularly with new features. Each version keeps the trial duration configured at the time of its release.

## What's New in v1.8

- **AI Paper Radar**: a dedicated entry for focused tracking across AI topics, keywords, authors, years, open-access status, PDF availability, and top venues.
- **Top venue archive library**: browse archived papers from CVPR, ICCV, ECCV, NeurIPS, ICML, ICLR, ACL, AAAI, IJCAI, TPAMI, IJCV, TGRS, TMI, Nature / Science venues, and more.
- **Research topic maps**: organize papers by task, modality, learning paradigm, method family, and application area to understand representative works and trends.
- **High-value paper signals**: archive views can show best-paper, best-student-paper, oral-presentation, and similar labels when available.
- **Citation-context analysis**: the citing-paper workflow can separate highly related works, method improvements, surveys, and low-relevance follow-ups, making AI-assisted citation review easier.
- **Smart journal shortcut**: the main search panel can jump from current results into journal recommendations faster.
- **Default deep search**: the main search flow now prefers deeper retrieval and automatically applies a recent 10-year scope when no explicit year is selected.
- **Interface improvements**: the top navigation now highlights AI Paper Radar, paper subscriptions, and paper access; new themes include scholar blue, paper, ocean, midnight, and AI purple.
- **Release packaging**: v1.8 provides Windows, Intel Mac, and Apple Silicon Mac packages with a 10-day trial.

## What's New in v1.7

- **Ordinary and deep search modes**: ordinary search stays fast for daily use, while deep search provides broader coverage with progress, coverage reports, and cancellation.
- **Title direction categories**: search results are grouped by research directions inferred from titles; the sidebar can filter by direction, and paper cards show direction tags.
- **Smart journal finder**: generates candidate journals from the current result set and analysis range, using partitions, impact factors, hit distribution, and local venue matching.
- **Classified citing-paper analysis**: the citing-paper view can organize follow-up works by title direction, source, and citation information, making it easier to understand later method improvements, application extensions, and related-topic expansion.
- **Better source routing and deduplication**: PaperScope chooses more relevant providers based on the topic and selected venues, and deduplicates more strictly by DOI, arXiv ID, PMID, PMCID, and other stable identifiers.
- **Paper email delivery**: configure SMTP and send selected paper results to yourself or another recipient.
- **Manual paper subscriptions**: save current search conditions, set a time range, delivery frequency, and maximum number of papers, then track new papers over time.
- **Safer PDF downloading**: PDF links are validated more strictly to avoid unsafe redirects and private-network targets.
- **AI provider settings**: added common AI provider configuration entries to support smoother title-copy and citation-copy analysis workflows.

## Highlights

- **Advanced search conditions**: keywords, exact phrases, exclusion words, title-only search, AND / OR logic, and grouped conditions.
- **School and institution filtering**: filter by Chinese names, English names, abbreviations, and common aliases.
- **Journal and conference filtering**: CAS partitions, CCF categories, disciplines, venue names, and journal / conference switching.
- **Partition-aware result browsing**: quickly prioritize papers by partition, source, open-access status, and PDF availability.
- **Title direction categories**: infer research directions from paper titles and filter the current result set by direction.
- **Smart journal finder**: generate candidate journal lists from the current search results for submission planning and source prioritization.
- **Copy titles for AI analysis**: copy paper titles and paste them into ChatGPT, Claude, or other LLMs with your own analysis prompt template.
- **Classified citing-paper analysis and AI workflow**: open the citing-paper workflow, organize follow-up works by direction/source/citation signals, copy titles, and ask an LLM to summarize research trends, improvements, and possible gaps.
- **v1.8 AI Paper Radar and archives**: track top AI venues, browse venue archives, inspect research topic maps, use high-value paper labels, and analyze citation context.
- **v1.7 search and subscription workflow**: ordinary / deep search modes, coverage reports, paper email delivery, manual subscriptions, and safer PDF downloading for long-term research tracking.
- **v1.6 official proceedings and filtering upgrades**: improved the journal / conference filtering panel, added supplementary official proceedings search for AAAI OJS, NeurIPS Proceedings, ACL, EMNLP, ICML, COLT, IJCAI, and improved multi-source deduplication, statistics, and timeout fallback.
- **v1.5 result-page and template upgrades**: clearer result layout, simple / detailed paper-analysis prompt templates, better repeated-search caching, and clearer citation-count handling.

## Example Workflow

Example: search for `few-shot`, set the year to `2026`, and choose `IEEE Transactions on Pattern Analysis and Machine Intelligence` as the journal. PaperScope aggregates public academic data sources and presents results with partition, source, open-access, and PDF-availability information. In this example, search time dropped from about `24 seconds` to `8.32 seconds`.

<p align="center">
  <img src="assets/paperscope-ai-workflow.png" alt="PaperScope few-shot results and AI analysis workflow" width="100%">
</p>

1. Filter papers by year, source, partition, open-access status, and PDF availability.
2. Use **Copy Title** to send paper titles to ChatGPT or Claude for quick paper analysis.
3. Open **Citing Papers**, copy titles of follow-up works, and use an LLM to understand how later studies extend or improve the original paper.

## Screenshots

<table>
  <tr>
    <td width="50%" valign="top">
      <strong>Keyword Search</strong><br>
      <sub>Use keywords, exact phrases, exclusion words, title-only search, AND / OR, and grouped logic.</sub><br><br>
      <img src="assets/paperscope-keywords.png" alt="PaperScope keyword filtering" width="100%">
    </td>
    <td width="50%" valign="top">
      <strong>School / Institution Filtering</strong><br>
      <sub>Filter papers by universities, research institutions, English names, abbreviations, and aliases.</sub><br><br>
      <img src="assets/paperscope-school.png" alt="PaperScope school filtering" width="100%">
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <strong>Journal / Conference Filtering</strong><br>
      <sub>Use CAS partitions, CCF categories, disciplines, and venue-name filtering.</sub><br><br>
      <img src="assets/paperscope-venues.png" alt="PaperScope venue filtering" width="100%">
    </td>
    <td width="50%" valign="top">
      <strong>Author Filtering</strong><br>
      <sub>Filter by author names and use the recommended scholar library to follow research communities.</sub><br><br>
      <img src="assets/paperscope-authors.png" alt="PaperScope author filtering" width="100%">
    </td>
  </tr>
</table>

## Notes

- PaperScope requires internet access for literature search.
- Metadata, PDF links, and citation data depend on public academic data sources.
- Each release includes SHA-256 checksum files for download verification.
- For formal literature reviews, grant applications, or final manuscript checks, please cross-check with authoritative databases and publisher websites.

## Contact

Feedback, feature requests, and bug reports are welcome through GitHub Issues. You can also scan the QR code below to connect on WeChat.

<p align="center">
  <img src="assets/wechat-contact.jpg" alt="PaperScope WeChat contact QR code" width="220"><br>
  <sub>Scan to connect on WeChat</sub>
</p>

## Disclaimer

PaperScope aggregates paper metadata, links, citation information, and venue classifications from public academic data sources. The information is for research discovery and auxiliary analysis only.
