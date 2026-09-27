<a href="https://www.endrhq.com">
  <img src="https://raw.githubusercontent.com/endrhq/.github/45283c4133657e8cae91e4edd0657d87e9e10c5f/profile/%5Bendr%5D%5Bassets%5D%5Bgithub%5D/%5Bendr%5D%5Basset%5D%5Bcoastal-tactical-banner-v8%5D.png" alt="endr coastal painting with a subtle tactical grid, terrain contours, and conceptual coordination network." width="100%">
</a>

## 「 01 」「 COMPANY BRIEF 」

endr is a Seattle-based battlefield AI company developing software for human-led mission coordination, assurance, and execution under degraded conditions.

Our engineering approach centers on explicit authority, bounded behavior, and evidence that makes decisions traceable.

## 「 02 」「 MISSION ASSURANCE 」

**Mission Assurance Lab (M.A.L.)** focuses on a core engineering question: does a change to an agent workflow preserve its task requirements and authority limits under defined faults?

Engineering acceptance requires reproducible comparisons, attributable decisions, and an accountable human review.

```mermaid
%%{init: {"theme":"base","themeVariables":{"fontFamily":"Arial, Helvetica, sans-serif","fontSize":"17px","primaryColor":"#161d24","primaryTextColor":"#e6edf3","primaryBorderColor":"#52616b","lineColor":"#91a49a","secondaryColor":"#1b2c25","tertiaryColor":"#0d1117","clusterBkg":"#0d1117","clusterBorder":"#34424d","titleColor":"#adbac4","edgeLabelBackground":"#0d1117"},"flowchart":{"curve":"linear","nodeSpacing":28,"rankSpacing":35,"padding":16}}}%%
flowchart TB
    accTitle: endr — Mission Assurance Lab
    accDescr: Conceptual synthetic research architecture. Matched workflows submit requests to independent authority evaluation. An ordered ledger feeds comparison and replay, then human review. Lost links never expand authority.

    subgraph INPUTS["01 · CONTEXT & AUTHORITY"]
        SCENARIO["Scenario fixture<br/>Tasks · resources · initial state"]
        MANIFEST["Run manifest<br/>Versions · seeds · fault schedule"]
        AUTHORITY["Human authority<br/>Scope · policy · valid approvals"]
    end

    subgraph EVALUATION["02 · CONTROLLED EVALUATION"]
        HARNESS["Scenario & fault harness<br/>Nominal · lost link · recovery"]
        WORKFLOWS["Compared workflows<br/>Baseline · reference · candidate"]
        GATE["Independent authority evaluator<br/>Scope · permission · approval"]
        STATE["Simulated state<br/>Permitted effects only"]
        HARNESS --> WORKFLOWS
        WORKFLOWS -->|Proposed requests| GATE
        GATE --> STATE
    end

    subgraph EVIDENCE["03 · EVIDENCE & REVIEW"]
        LEDGER["Decision ledger<br/>Requests · reasons · effects"]
        REPORT["Comparison report<br/>Criteria by run and condition"]
        REPLAY["Replay<br/>State reconstruction · discrepancies"]
        REVIEW["Human review<br/>Disposition · next-run revisions"]
        LEDGER --> REPORT & REPLAY
        REPORT & REPLAY --> REVIEW
    end

    SCENARIO & MANIFEST --> HARNESS
    AUTHORITY -.->|Rules & approvals| GATE
    GATE -->|Requests & decisions| LEDGER
    STATE -->|Executed effects| LEDGER

    classDef authority fill:#1b2c25,stroke:#98b4a4,color:#edf3ef,stroke-width:1.5px
    classDef evidence fill:#182129,stroke:#70828e,color:#e6edf3
    class AUTHORITY,GATE,REVIEW authority
    class LEDGER,REPORT,REPLAY evidence
```

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
