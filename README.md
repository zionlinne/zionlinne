# Lin Sen (Zion)

**Independent Researcher | Multi-Agent Systems · AI Reliability · Executable Oversight**

I study how LLM-based multi-agent systems can preserve requirements and remain verifiable as tasks are decomposed, delegated, and handed off between agents. My work focuses on **programmatic constraints, host-side acceptance checks, context and requirement preservation, and trace-based reliability evaluation**.

I develop open-source research prototypes and investigate their failure modes through execution audits, fault injection, and controlled experiments.

## Research

### Formalize or Lose It: What Executable Constraints Control in an Agent Swarm (2026)

**Collaborative research preprint** developed during the Apart Research Swarm Alignment Hackathon.

We investigated whether coordination requirements remain enforceable after a multi-agent system distributes work. In a recorded Feasibility Scheduler (FBS) execution, all 125 black-box tests passed even though some coordination requirements were not covered by executable checks. A supervision audit identified 39 prompt-only rules among 84 rules; subsequent fault-injection experiments evaluated which failures the host could reject. A separate requirement-relay study examined context compression, reviewer information loss, and an executable requirement ledger.

- [Preprint (Zenodo)](https://zenodo.org/records/24292369)
- [Experimental data and analysis](https://github.com/nimayshah123/dar-executable-constraints)
- [FBS research snapshot and run records](https://github.com/zionlinne/fbs-functional-planning)

## Open-source research projects

| Project | Focus |
| --- | --- |
| [Feasibility Scheduler (FBS)](https://github.com/zionlinne/feasibility-scheduler) | Research prototype for feasibility-gated multi-agent orchestration, task dependencies, responsibility boundaries, and host-side validation. |
| [FBS Functional Planning](https://github.com/zionlinne/fbs-functional-planning) | Reproducibility materials, implementation snapshots, execution records, and tests supporting the FBS research. |
| [phi-core](https://github.com/zionlinne/phi-core) | Work in progress toward a reusable feasibility and evidence-validation component for agent systems. |

## Current research interests

- **Multi-agent reliability:** task decomposition, handoffs, coordination failures, and independent acceptance.
- **Executable oversight:** translating requirements into traceable host-side checks without prescribing every model decision.
- **Context integrity:** studying what is lost during summarization and repeated agent-to-agent transfers.
- **Agent evaluation:** reproducible benchmarks, fault injection, controlled comparisons, and failure attribution.
- **AI governance and ethics:** lifecycle auditing and decision-making under moral uncertainty.

I am interested in research collaborations, reproducibility, and technical feedback on these questions.

## Contact

For research collaboration, technical feedback, or academic correspondence, please email **[zion990214@gmail.com](mailto:zion990214@gmail.com)**.

---

*Research outputs are linked with their underlying code and evidence where available. Ongoing prototypes and future research directions are distinguished from completed experimental results.*
