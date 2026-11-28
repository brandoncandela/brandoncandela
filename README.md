# Brandon Candela

### Building intelligent financial crime technology

**AI-assisted investigations · Blockchain intelligence · Fintech risk infrastructure**

I build the systems financial crime teams depend on: monitoring rules, entity resolution, blockchain tracing and investigation workflows. Six years inside AML at TD Bank, KPMG, IBM Promontory and Deutsche Bank tell me what the real problem is. I own the architecture, implementation, testing and tradeoffs, and every project documents where it stops.

Senior AML Consultant · TD Bank (contract) · CAMS · PMP · CRISC · English and Spanish

**[Portfolio](https://brandoncandela.github.io/)** · **[Technical case studies](https://brandoncandela.github.io/case-studies/)** · [LinkedIn](https://www.linkedin.com/in/brandon-candela/) · [Email](mailto:Brandon.d.candela@gmail.com) · Open to compliance tech, solutions and implementation roles (remote or New York)

## Flagship builds

| Build | Problem it solves | Result | Links |
| --- | --- | --- | --- |
| **[AML Backlog Command Center](https://github.com/brandoncandela/aml-backlog-command-center)** | 5,343 alerts in three systems with no shared customer ID and a regulator's deadline | All 4,923 automatic matches correct; deadline met with 6 analysts instead of 9 | [Demo](https://brandoncandela.github.io/aml-backlog-command-center/) · [Case study](https://brandoncandela.github.io/case-studies/aml-backlog-command-center.html) |
| **[Crypto Exchange Monitoring Lab](https://github.com/brandoncandela/crypto-exchange-monitoring-lab)** | Which exchange transfers to stop for sanctions exposure and laundering patterns | Six SQL rules against real OFAC wallets and Tron USDT data, 100% recall on every rule | [Demo](https://brandoncandela.github.io/crypto-exchange-monitoring-lab/) · [Case study](https://brandoncandela.github.io/case-studies/crypto-exchange-monitoring-lab.html) |
| **[Fraud Intelligence & Control Lab](https://github.com/brandoncandela/fraud-intelligence-control-lab)** | Changing a fraud control without flooding a queue of 8 daily reviews | 87.5% precision and 100% recall at the chosen threshold, within capacity | [Demo](https://brandoncandela.github.io/fraud-intelligence-control-lab/) · [Case study](https://brandoncandela.github.io/case-studies/fraud-intelligence-control-lab.html) |

## More builds

| Build | What it does | Links |
| --- | --- | --- |
| **[AI SAR Narrative Lab](https://github.com/brandoncandela/ai-sar-narrative-lab)** | Claude drafts SAR narratives where every sentence cites its evidence; plain rules check every amount, date and citation before a person signs off | [Demo](https://brandoncandela.github.io/ai-sar-narrative-lab/) · [Case study](https://brandoncandela.github.io/case-studies/ai-sar-narrative-lab.html) |
| **[Trace Desk](https://github.com/brandoncandela/trace-desk-aml-workspace)** ([v1](https://github.com/brandoncandela/usdt-investigator)) | Ethereum USDT investigations from raw node data to a checksummed case file and QC | [Demo](https://brandoncandela.github.io/trace-desk-aml-workspace/) · [Case study](https://brandoncandela.github.io/case-studies/trace-desk.html) |
| **[Sanctions Review Desk](https://github.com/brandoncandela/sanctions-review-desk)** | OFAC name matches to a QC-ready decision, with the list refreshed hourly by GitHub Actions | [Demo](https://brandoncandela.github.io/sanctions-review-desk/) · [Case study](https://brandoncandela.github.io/case-studies/sanctions-review-desk.html) |
| **[Adverse Media Review Desk](https://github.com/brandoncandela/adverse-media-review-desk)** | Is this news story about your customer? Same triage rules in TypeScript and SQL | [Demo](https://brandoncandela.github.io/adverse-media-review-desk/) · [Case study](https://brandoncandela.github.io/case-studies/adverse-media-review-desk.html) |
| **[SQL Financial Crime Lab](https://github.com/brandoncandela/sql-fincrime-lab)** | Real SQLite in the browser showing what threshold changes cost in missed cases | [Demo](https://brandoncandela.github.io/sql-fincrime-lab/) · [Case study](https://brandoncandela.github.io/case-studies/sql-fincrime-lab.html) |
| **[Payments Strategy Lab](https://github.com/brandoncandela/payments-strategy-lab)** | A tested unit-economics model weighing approvals, fraud loss and review capacity | [Demo](https://brandoncandela.github.io/payments-strategy-lab/) · [Case study](https://brandoncandela.github.io/case-studies/payments-strategy-lab.html) |

## How I build

- **A wrong answer is worse than no answer.** Unsure matches go to a person; stale sanctions data refuses to run; an empty query is never a clean wallet.
- **Every number is traceable.** Amounts stay exact, evidence keeps its source, and scores break down into named parts.
- **Tested at the edges.** Boundary tests, answer keys and deterministic builds, run with one command and no network.
- **Limits are written down.** Each case study ends with what the system does not do and what I would build next.

## Stack

Python · SQL (SQLite, CTEs, window functions) · TypeScript · React · JavaScript · Ethereum JSON-RPC · GitHub Actions · NICE Actimize · LexisNexis · Moody's RDC · CLEAR
