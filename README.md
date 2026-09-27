<a href="https://www.endrhq.com">
  <img src="https://raw.githubusercontent.com/endrhq/.github/45283c4133657e8cae91e4edd0657d87e9e10c5f/profile/%5Bendr%5D%5Bassets%5D%5Bgithub%5D/%5Bendr%5D%5Basset%5D%5Bcoastal-tactical-banner-v8%5D.png" alt="endr coastal painting with a subtle tactical grid, terrain contours, and conceptual coordination network." width="100%">
</a>

## 「 01 」「 COMPANY BRIEF 」

endr is a Seattle-based battlefield AI company developing software for human-led mission coordination, assurance, and execution under degraded conditions.

Our engineering approach centers on explicit authority, bounded behavior, and evidence that makes decisions traceable.

## 「 02 」「 MISSION ASSURANCE 」

**Mission Assurance Lab (M.A.L.)** focuses on a core engineering question: does a change to an agent workflow preserve its task requirements and authority limits under defined faults?

Engineering acceptance requires reproducible comparisons, attributable decisions, and an accountable human review.

**Evaluation & evidence flow**

```mermaid
%%{init: {"theme":"base","themeVariables":{"fontFamily":"Arial, Helvetica, sans-serif","fontSize":"18px","primaryColor":"#eceeea","primaryTextColor":"#202824","primaryBorderColor":"#77817b","lineColor":"#9ba59f","edgeLabelBackground":"#0d1117"},"block":{"padding":18}}}%%
block-beta
    columns 5
    CONFIG["Scenario & run contract"]:2 space AUTHORITY["Human authority"]:2
    space:5
    RUNS["Matched workflows"]:2 space BOUNDARY["Authority boundary"]:2
    space:5
    LEDGER["Decision ledger"]:2 space STATE["Simulated state"]:2
    space:5
    REPORT["Comparison report"]:2 space REPLAY["State replay"]:2
    space:5
    REVIEW["Human review / next-run decisions"]:5

    CONFIG --> RUNS
    AUTHORITY --> BOUNDARY
    RUNS --> BOUNDARY
    BOUNDARY --> STATE
    BOUNDARY --> LEDGER
    STATE --> LEDGER
    LEDGER --> REPORT
    LEDGER --> REPLAY
    REPORT --> REVIEW
    REPLAY --> REVIEW

    classDef boundary fill:#c9d8cd,stroke:#7d9b87,stroke-width:2px,color:#18271e
    class BOUNDARY boundary
```

Matched workflows compare baseline, reference, and candidate under the same scenario inputs and declared fault schedules. The authority boundary evaluates proposed requests independently; the ledger records requests, decisions, and permitted simulated effects. Comparison and replay support human decisions for the next run.

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
