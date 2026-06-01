# Tondreka Robles

I design AI-assisted document review, application preparation, requirement extraction, and decision-support workflows for business, insurance, compliance, and service operations.

I am currently pursuing a Master's in Applied AI & Business Analytics at the University of Rochester. My portfolio focuses on practical AI workflow prototypes that turn intake data, documents, and business requirements into structured outputs for human review.

## Portfolio Direction

My current flagship direction is **Business Review / PaperworkPro**: an AI-assisted document review and application-prep workflow that helps business users prepare insurance and business applications, decode COI and contract insurance requirements, identify missing information, generate summaries, create checklists, draft emails, and keep outputs source-aware, auditable, and human-reviewed.

These are portfolio prototypes, not production systems and not legal, insurance, compliance, underwriting, or certificate issuance advice.

## What I Focus On

- AI-assisted document review and application preparation
- Requirement extraction from contracts, COIs, intake notes, and business documents
- Decision-support workflows with human review gates
- Missing-information detection and review checklists
- Business-ready summaries, draft emails, and structured JSON outputs
- Insurance, compliance, customer success, implementation, and service operations workflows
- Practical prototypes that connect technical logic with real business processes

## Featured Project

### Business Review / PaperworkPro

[Business Review AI Orchestration](https://github.com/Tondie-HSPI/business-review-ai-orchestration) is a portfolio prototype for AI-assisted document review, application preparation, requirement extraction, and decision-support workflows.

**Business problem:** Business, insurance, compliance, and service teams often need to turn intake data, contracts, COI requirements, and application forms into accurate review packets. Manual review can lead to missed requirements, incomplete applications, rework, and unclear handoffs.

**Solution:** PaperworkPro takes an initial request and creates a submission-ready application draft for human review. It identifies missing information, infers likely application answers from fake intake data, flags complex wording, creates CSR certificate request drafts, and requires review before save/export.

**What it demonstrates:**

- Restaurant insurance application prep from fake intake data
- COI and contract insurance requirement decoding
- Missing-information checklists
- Draft email output for CSR or business follow-up
- Human-in-the-loop review gates and audit-friendly outputs
- Source-aware answers with evidence and rep double-check notes
- Next.js frontend and Python workflow logic

**Sample input:** A fake restaurant/bar quote request with general liability, liquor liability, property coverage, operations, sales, security, entertainment, certificate wording, additional insured, waiver of subrogation, and primary/noncontributory requests.

**Sample output:** A structured review packet with application sections, inferred answers, target field mappings, quote-impacting flags, CSR certificate request draft, missing-information checklist, and downloadable JSON.

**Status:** Portfolio prototype. Uses fake/sample data only. Not legal, insurance, compliance, underwriting, certificate issuance, or production advice. Requires human review.

## Legacy / Earlier Prototype

### Compliance Explained

Compliance Explained was an earlier prototype focused on turning complex insurance and compliance text into structured checklists. I am retiring it as a standalone flagship brand and treating it as a legacy concept that informed the broader Business Review / PaperworkPro direction.

## Features Demonstrated Across My Portfolio

- **Business-friendly AI workflows:** Projects are framed around operational problems, not just technical experiments.
- **Decision-support logic:** Workflows are designed to help users review information, identify gaps, and choose next actions.
- **Human-in-the-loop design:** AI output is treated as support for human review, especially in higher-risk domains.
- **Structured communication:** Documentation explains the business problem, intended user, solution, sample inputs, sample outputs, and project status.
- **Implementation thinking:** Projects show how an idea can move from problem framing to a usable prototype.

## How to Review or Run Projects Locally

This profile repository itself is a GitHub landing page and does not need to be run locally.

For runnable portfolio projects, open the linked project repository and look for:

```text
README.md          Project overview and setup steps
.env.example       Placeholder environment variables, if needed
src/ or app/       Main application or workflow logic
data/              Sample or demonstration data, if included
outputs/           Sample structured review outputs, if included
docs/              Architecture, business case, or evaluation notes
tests/             Basic validation or workflow tests, if included
```

Typical local setup for a project may look like:

```bash
git clone <project-repository-url>
cd <project-folder>
npm install
npm run dev
```

or, for Python-based projects:

```bash
git clone <project-repository-url>
cd <project-folder>
python -m venv .venv
pip install -r requirements.txt
python app.py
```

Each project README should be treated as the source of truth for its specific setup commands.

## Project Structure

This profile repository is intentionally simple:

```text
.
|-- README.md      GitHub profile and portfolio overview
`-- .gitignore     Keeps local caches, secrets, and generated files out of git
```

Individual project repositories contain the source code, setup instructions, and project-specific documentation.

## Future Improvements

- Add screenshots or short demo walkthroughs to featured project repositories.
- Standardize README sections across projects for easier hiring-manager review.
- Add sample datasets that avoid private, sensitive, or regulated information.
- Expand tests around scoring, checklist generation, field mapping, and workflow logic where applicable.
- Add concise architecture notes for AI workflow and API orchestration decisions.

## Connect

- LinkedIn: [www.linkedin.com/in/tondreka-robles-888b84140](https://www.linkedin.com/in/tondreka-robles-888b84140)
- GitHub: [Tondie-HSPI](https://github.com/Tondie-HSPI)
