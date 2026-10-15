# Memory Poisoning and Behavioral Drift in LLM-Based Agents

> A systematic review investigating how memory-poisoning mechanisms influence the behavior of large language model (LLM)-based agents over time and what evidence exists regarding the persistence of these effects across interactions and tasks.

## Problem & Users

LLM-based agents increasingly use memory mechanisms to retain information from previous interactions, personalize responses, and perform multi-step tasks. However, malicious or misleading information introduced into an agent's memory may influence its future decisions and behavior.

Although memory-related security risks are receiving increasing attention, evidence concerning the duration, persistence, and transferability of memory-poisoning effects across interactions and tasks requires systematic examination.

**Target Audience:**
- Researchers working on AI agent security and safety.
- Students investigating LLM vulnerabilities and memory systems.
- Developers building memory-enabled AI applications.
- Professionals interested in trustworthy and secure AI systems.

## Features / Solution

This project uses a systematic literature review methodology to examine existing research on memory poisoning and behavioral changes in LLM-based agents.

Key activities include:

- **Literature Search:** Identify relevant research papers using academic databases and scholarly repositories.
- **Study Screening:** Apply predefined inclusion and exclusion criteria to select relevant studies.
- **Mechanism Classification:** Categorize memory-poisoning techniques and attack vectors.
- **Evidence Extraction:** Record experimental settings, observed behavioral changes, and evaluation methods.
- **Persistence Analysis:** Examine whether reported effects persist across subsequent interactions, sessions, or tasks.
- **Research Gap Identification:** Identify limitations in existing evidence and opportunities for future research.

## Architecture

The review follows a structured research workflow:

```text
Research Question
       |
       v
Search Strategy Development
       |
       v
Literature Identification
       |
       v
Title and Abstract Screening
       |
       v
Full-Text Eligibility Assessment
       |
       v
Data Extraction and Quality Assessment
       |
       v
Evidence Synthesis
       |
       v
Research Gaps and Conclusions
```

The review will follow appropriate systematic review reporting practices, including PRISMA 2020 where applicable.

## Prerequisites

- Access to academic literature databases and scholarly repositories.
- A defined research question and review protocol.
- A reference manager or spreadsheet for organizing papers.
- A screening and data-extraction template.
- Familiarity with LLM-based agents, memory architectures, and AI security concepts.

## Installation

This repository primarily contains research documentation and does not require software installation.

Clone the repository:

```bash
git clone https://github.com/Yashwanth-1237/memory-poisoning-systematic-review.git
```

Navigate to the project directory:

```bash
cd memory-poisoning-systematic-review
```

Open the repository in your preferred editor to review the research documentation.

## Quick Start / Usage

The repository is intended to organize and document the systematic review process.

1. Review the research question and scope.
2. Consult the search strategy and selected academic databases.
3. Record identified papers and screening decisions.
4. Extract relevant evidence from eligible studies.
5. Compare findings across attack mechanisms, agent architectures, and evaluation settings.
6. Synthesize the evidence and document research gaps.

**Primary Research Question:**

How do memory-poisoning mechanisms affect the behavior of LLM-based agents over time, and what evidence exists regarding the persistence of these effects across interactions and tasks?

## Example Output

The review aims to produce the following research artifacts:

- A documented search strategy and search log.
- A screened collection of eligible research papers.
- A study-selection flow diagram.
- A structured evidence-extraction matrix.
- A synthesis of reported behavioral effects and their persistence.
- A discussion of limitations and future research directions.

Illustrative evidence-extraction fields:

| Field | Description |
|---|---|
| Study | Author and publication year |
| Attack mechanism | How malicious information enters memory |
| Agent architecture | Memory type and agent configuration |
| Behavioral effect | Observed change in decisions or responses |
| Persistence | Duration or recurrence of the reported effect |
| Evaluation setting | Interactions, sessions, or tasks tested |
| Evidence strength | Experimental support and study limitations |

No review findings or conclusions are assumed in advance; results will be reported after the literature has been screened and analyzed.

## Data / Model (for AI projects)

This project does not train or deploy a new AI model. Its primary data consists of published research studies concerning memory poisoning, persistent behavioral changes, and the security of LLM-based agents.

Potential evidence sources include Google Scholar, IEEE Xplore, ACM Digital Library, Scopus, and arXiv. The final database selection and search strings will be documented in the review protocol.

The review will distinguish experimentally demonstrated effects from conceptual arguments, proposed attacks, and claims that have not been independently validated.

## Limitations

- Available evidence may be limited by the novelty of memory-enabled AI agents.
- Studies may use different agent architectures, memory mechanisms, benchmarks, and evaluation methods.
- Persistence may be measured inconsistently across studies.
- Results from simulated environments may not generalize to real-world deployments.
- Publication bias and incomplete reporting may affect the conclusions.
- A systematic review can synthesize available evidence but cannot establish effects that existing studies have not tested.

## Contributing · License · Contact

**Contributing:** Research team members can contribute through literature screening, evidence extraction, methodology review, and manuscript preparation. Changes to the review protocol should be documented.

**License:** To be determined by the research team. Any reuse of published research must respect the original sources' copyright and licensing conditions.

**Contact:** Gavini Yashwanth — [GitHub Profile](https://github.com/Yashwanth-1237)

**Project Type:** Academic Systematic Literature Review

**Status:** Research planning and literature review.
