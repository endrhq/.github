<a href="https://www.endrhq.com">
  <picture>
    <source media="(max-width: 600px)" srcset="https://raw.githubusercontent.com/endrhq/.github/3bff025a4d02aec931c46436278a360b6e470c68/profile/%5Bendr%5D%5Bassets%5D%5Bgithub%5D/%5Bendr%5D%5Basset%5D%5Bprofile-hero-mobile%5D.svg">
    <img src="https://raw.githubusercontent.com/endrhq/.github/3bff025a4d02aec931c46436278a360b6e470c68/profile/%5Bendr%5D%5Bassets%5D%5Bgithub%5D/%5Bendr%5D%5Basset%5D%5Bprofile-hero%5D.svg" alt="endr — Mission autonomy. Bounded by design." width="100%">
  </picture>
</a>

<p align="center">
  <a href="https://www.endrhq.com">「 WEBSITE 」</a> &nbsp;
  <a href="https://github.com/orgs/endrhq/repositories">「 REPOSITORIES 」</a> &nbsp;
  <a href="https://x.com/endrhq">「 X 」</a> &nbsp;
  <a href="mailto:us@endrhq.com">「 CONTACT 」</a>
</p>

## 「 01 」「 COMPANY BRIEF 」

endr is a Seattle-based defense-autonomy software company developing a vendor-neutral platform for mission-autonomy agents across heterogeneous unmanned systems. We are a legally formed limited liability company, building through a research and simulation-first program.

Our direction is portable mission software: translate operator intent into bounded tasks, coordinate agents with different capabilities, enforce local constraints, and preserve the evidence needed to explain their decisions.

## 「 02 」「 PLATFORM ARCHITECTURE 」

The intended platform connects mission definition, agent development, simulation, edge execution, coordination, and assurance through typed interfaces. Mission logic is designed to remain separate from platform-specific adapters, so each integration can be evaluated against an explicit contract.

| BUILD & SIMULATE | EDGE EXECUTION | COORDINATION & ASSURANCE |
| :--- | :--- | :--- |
| **Python** — planned tools for mission contracts, reference agents, deterministic scenarios, and baseline evaluation. | **Rust** — planned runtime for bounded tasks, local policy enforcement, resource limits, and health monitoring. | **Mission coordination & assurance** — planned peer coordination, attributable events, and replay across typed adapters. |

Ground, aerial, maritime, and space portability is the long-term objective. Each supported domain and integration will require its own evidence.

## 「 03 」「 COMMAND PRINCIPLES 」

- **Humans retain command.** Consequential decisions require human authority; agents operate within an explicit mission envelope.
- **Lost links never expand authority.** Communications degradation must preserve policy limits and predefined behavior.
- **Decisions leave evidence.** Task assignments, interventions, policy decisions, and state changes must be attributable and replayable.

## 「 04 」「 VALIDATION OBJECTIVE 」

The first planned experiment is a deterministic, non-kinetic simulation with two to four unarmed agents representing different platform capabilities.

One reproducible scenario is intended to test capability-aware task assignment, eligible reassignment, delayed or lost communications, and a simulated platform failure. Operator approval, pause, redirect, and abort controls belong in that same experiment.

The proof target is a documented comparison with a simple scripted or centralized baseline, supported by scenario configuration, seeds, event traces, and replay. Simulation evidence comes before hardware consideration.

## 「 05 」「 DEVELOPMENT STATUS 」

**Active software development · mission platform in design**

As reviewed **September 4, 2026**, internal web software, a local task dashboard, and repository tooling are implemented, with local checks recorded. Mission-platform architecture and MVP specifications exist; mission runtime, SDK, and coordination implementation evidence and reproducible mission-simulation results were not located in the reviewed sources.

These internal artifacts are distinct from the intended mission platform. Fielded, certified, production-ready, or operationally validated mission capabilities are not claimed. [Read the public development status](https://github.com/endrhq/.github/blob/main/%5Bendr%5D%5Brepository%5D%5Bprofile-status%5D.md).

The **SENITEL** repository preserves superseded concept documentation from an earlier direction. It is historical context, not the current product thesis or evidence of current platform capability.

## 「 06 」「 CONTACT 」

We welcome non-confidential conversations with autonomy and robotics engineers, research groups, and test teams about heterogeneous-system integration, degraded-network evaluation, and attributable autonomy behavior.

<a href="mailto:us@endrhq.com">「 CONTACT 」</a> &nbsp; <a href="https://www.endrhq.com">「 WEBSITE 」</a> &nbsp; <a href="https://x.com/endrhq">「 X 」</a>
