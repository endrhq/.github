<a href="https://www.endrhq.com">
  <img src="https://raw.githubusercontent.com/endrhq/.github/45283c4133657e8cae91e4edd0657d87e9e10c5f/profile/%5Bendr%5D%5Bassets%5D%5Bgithub%5D/%5Bendr%5D%5Basset%5D%5Bcoastal-tactical-banner-v8%5D.png" alt="endr coastal painting with a subtle tactical grid, terrain contours, and conceptual coordination network." width="100%">
</a>

## 「 01 」「 COMPANY BRIEF 」

endr is a Seattle-based battlefield AI company developing software for human-led mission coordination, assurance, and execution under degraded conditions.

Our engineering approach centers on explicit authority, bounded behavior, and evidence that makes decisions traceable.

## 「 02 」「 MISSION ASSURANCE 」

**Mission Assurance Lab (M.A.L.)** focuses on a core engineering question: does a change to an agent workflow preserve its task requirements and authority limits under defined faults?

Engineering acceptance requires reproducible comparisons, attributable decisions, and an accountable human review.

**Systems research / Mission Assurance Lab**

```mermaid
%%{init: {"theme":"base","themeVariables":{"fontFamily":"Arial, Helvetica, sans-serif","fontSize":"18px","primaryColor":"#19242c","primaryTextColor":"#e9edf0","primaryBorderColor":"#5a6a76","lineColor":"#9aada5","clusterBkg":"#111920","clusterBorder":"#384852","titleColor":"#c2ccd2","edgeLabelBackground":"#0d1117"},"htmlLabels":false,"flowchart":{"htmlLabels":false,"curve":"stepAfter","nodeSpacing":24,"rankSpacing":32,"padding":16,"subGraphTitleMargin":{"top":12,"bottom":20}}}}%%
flowchart TB
    accTitle: endr — Systems research architecture
    accDescr: Three layers show experiment setup, the evaluation harness, and evidence with human review. Requests are evaluated independently against human-defined authority. Synthetic requests, decisions, and observed effects feed comparison and replay.

    subgraph SETUP["01 / EXPERIMENT SETUP"]
        direction LR
        SCENARIO["Scenario fixture<br/>Tasks / state / faults"] ~~~ MANIFEST["Run manifest<br/>Versions / seeds"] ~~~ AUTHORITY["Human authority<br/>Bounds / approvals"]
    end

    subgraph HARNESS["02 / EVALUATION HARNESS"]
        direction LR
        subgraph WORKFLOWS["WORKFLOWS"]
            direction TB
            BASELINE["Baseline"]
            REFERENCE["Reference"]
            CANDIDATE["Candidate"]
        end
        EVALUATOR["Authority evaluator<br/>Independent boundary"]
        STATE["Synthetic state<br/>Isolated per run"]
        BASELINE & REFERENCE & CANDIDATE --> EVALUATOR
        EVALUATOR -->|Authorized requests| STATE
    end

    subgraph EVIDENCE["03 / EVIDENCE & REVIEW"]
        direction LR
        LEDGER["Decision ledger<br/>Decisions / observed effects"] --> ANALYSIS["Comparison + replay<br/>Criteria / state"] --> REVIEW["Human review<br/>Next-run disposition"]
    end

    SETUP --> HARNESS
    HARNESS --> EVIDENCE

    classDef boundary fill:#a8b9a8,stroke:#cfdbcb,color:#142119,stroke-width:1.5px
    class EVALUATOR boundary
    style WORKFLOWS fill:#17221e,stroke:#62756a,color:#c8d6cc
```

The harness compares baseline, reference, and candidate workflows under matched synthetic scenarios and declared faults. Human authority defines the evaluator’s bounds. Requests, decisions, and observed effects feed comparison and replay; human review determines the next run.

*Conceptual research architecture · Synthetic scenarios · Lost links never expand authority.*

## 「 03 」「 COMMAND PRINCIPLES 」

- **Human authority.** People define scope and retain responsibility for consequential decisions.
- **Bounded behavior.** Degraded communications must never expand permissions.
- **Attributable decisions.** Actions and interventions must leave evidence that can be reconstructed.

## 「 04 」「 RESEARCH AND ENGINEERING 」

Mission assurance, distributed coordination, and edge intelligence shape endr’s research. Our work examines agent behavior under faults, authority across system boundaries, and decision reconstruction in constrained environments.

## 「 05 」「 CONTACT 」

For engineering collaboration and research inquiries.

<p>
  <a href="https://www.endrhq.com" title="endr website"><img src="https://github.com/endrhq/.github/raw/fc58ff67b485a2be229b8ab74943773f10bc318f/profile/%5Bendr%5D%5Bassets%5D%5Bgithub%5D/%5Bendr%5D%5Basset%5D%5Blink-website-v1%5D.svg" alt="endr website" width="32" height="32"></a> &nbsp;&nbsp;
  <a href="mailto:us@endrhq.com" title="Email endr"><img src="https://github.com/endrhq/.github/raw/fc58ff67b485a2be229b8ab74943773f10bc318f/profile/%5Bendr%5D%5Bassets%5D%5Bgithub%5D/%5Bendr%5D%5Basset%5D%5Blink-email-v1%5D.svg" alt="Email endr" width="32" height="32"></a> &nbsp;&nbsp;
  <a href="https://x.com/endrhq" title="endr on X"><img src="https://github.com/endrhq/.github/raw/fc58ff67b485a2be229b8ab74943773f10bc318f/profile/%5Bendr%5D%5Bassets%5D%5Bgithub%5D/%5Bendr%5D%5Basset%5D%5Blink-x-v1%5D.svg" alt="endr on X" width="32" height="32"></a>
</p>
