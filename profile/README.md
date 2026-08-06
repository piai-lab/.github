# πAI Lab

**Open intelligence infrastructure for scientific discovery.**

πAI Lab is a public research and open-technology initiative based at 广东智慧医学国际研究院 in Guangzhou, the international executive headquarters of the [π-HuB program](https://kjj.gz.gov.cn/xwlb/yw/content/post_10776038.html). We start from real biomedical research and build scientific capabilities that can remain useful across models, agents, projects, and disciplines.

Our work spans the research process: finding questions worth investigating, grounding them in evidence, accessing scientific data, invoking methods under explicit conditions, sustaining long-running work, and creating scientific outputs that remain inspectable and editable. We develop these as distinct but composable capabilities—not as a closed, all-in-one agent.

> **Development status:** Every direction below is under development. This page describes research scope and intended relationships; it does not imply public release, production readiness, adoption, or scientific, clinical, legal, or regulatory validation.

## A capability system for the research process

### Scientific data and methods

- **OmniData:** agent-native scientific data access that preserves semantics, versions, quality, permissions, updates, and provenance.
- **OmniEngine:** reusable scientific methods with explicit inputs, applicability conditions, environments, validation, resource costs, and failure returns.

### Evidence and research intelligence

- **OmniScholar:** scientific literature, full text, figures, citations, retrieval, and claim-to-evidence relationships.
- **OmniPatent:** a direction alongside OmniScholar for patent evidence and patent-oriented research workflows.
- **AI4SNews:** a source-linked research-intelligence stream across papers, open models, technical advances, industry developments, and scientific communities.

### Continuous and governed research

- **OmniHarness:** governed execution across long-running scientific work, including tools, permissions, observability, verification, recovery, and handoff.
- **OmniMind:** a continuous research workbench for maintaining questions, hypotheses, evidence, analysis, and task state while coordinating agents and scientific capabilities.

### Scientific communication and editable artifacts

- **OmniPlotter:** a shared scientific plotting system across agent and interactive workflows, with data-aware generation, refinement, quality control, and verifiable export.
- **OmniSketch:** editable scientific illustration combining agent-driven generation with object-level editing, local revision, versioning, and high-quality export.
- **OmniSlide:** presentation generation and editing with explicit contracts for reading, safe editing, export, task state, history, validation, and failure handling.
- **OmniOffice:** a family of reliable file capabilities comprising **OmniDoc**, **OmniSheet**, and **PPT Skill**, with safe editing, independent validation, real rendering, versioning, and failure recovery.

### Question formation and domain research

- **OmniSage:** a research direction on how worthwhile, testable scientific questions can be formed from evidence gaps, competing explanations, and explicit validation paths.
- **Drug discovery:** an applied research program connecting domain data, scientific methods, and agent workflows across target and pocket analysis, molecular search and generation, synthesis planning, evaluation, prioritization, evidence tracing, and reporting.

### Evaluation and reproducibility

- **Evaluation and reproducibility:** cross-cutting research on benchmarks, provenance, failure analysis, recovery, reproducible environments, and validation in real research settings.

## How the system connects

These directions have different scientific jobs and are intended to remain independently reusable. Their shared design goal is composability: a researcher or agent should be able to move across evidence, data, methods, execution, and scientific artifacts without silently losing provenance, conditions, state, or failure information.

OmniMind is one environment in which these capabilities are intended to converge around a continuing research question. It does not own them or make itself their exclusive gateway; the underlying capabilities are intended to remain reusable by other agents and research platforms through open, explicit interfaces.

- **Researchers and experiments remain the decision layer** across question selection, interpretation, validation, and release.
- **OmniHarness is cross-cutting execution infrastructure**, not one step in a linear workflow.
- **Evaluation and reproducibility apply to every capability**, not only to a separate benchmark project.

Drug discovery is intended to provide a demanding biomedical setting in which this capability system can be developed and evaluated without creating a separate demonstration stack.

## How we work

- **Evidence before confidence.** Claims remain traceable to data, sources, or explicit assumptions.
- **Reproducibility by design.** Inputs, environments, methods, outputs, and limitations should remain inspectable.
- **Human scientific accountability.** Researchers retain responsibility for direction, interpretation, validation, and release.
- **Open, composable interfaces.** Capabilities should be reusable beyond one model, agent, product, or research task.
- **Shared scientific foundations.** Research, engineering, products, and evaluation should use the same underlying capabilities and versioned evidence.

## Leadership

**[Zaoqu Liu (刘灶渠)](https://github.com/Zaoqu-Liu)** — Lead

## Collaborate

We welcome research collaborations around scientific data and methods, evidence systems, agent architecture, scientific communication, evaluation and reproducibility, biomedical research, and cross-disciplinary transfer. For organization-level collaboration, contact [liuzaoqu@163.com](mailto:liuzaoqu@163.com).

Public projects enter πAI Lab only when they have a clear scientific purpose, accountable maintainers, reproducible entry points, explicit licensing, documented evidence boundaries, and a credible maintenance path.

Read our [governance](../GOVERNANCE.md), [project policy](../PROJECT_POLICY.md), [contribution guide](../CONTRIBUTING.md), [security policy](../SECURITY.md), and [support policy](../SUPPORT.md).

---

## 中文摘要

**πAI Lab · 面向科学发现的开放智能基础设施**

πAI Lab 是设在广东智慧医学国际研究院的公共研究与开放技术计划；该研究院是 [π-HuB 计划国际执行总部](https://kjj.gz.gov.cn/xwlb/yw/content/post_10776038.html)。我们从真实生物医学研究出发，计划建设可以跨模型、跨 Agent、跨课题持续复用的开放科学能力，而不是一个封闭的端到端科研智能体。

我们计划围绕完整科研过程建设以下方向：OmniData 与 OmniEngine 面向可追溯的数据和可验证的方法；OmniScholar、OmniPatent 与 AI4SNews 面向文献、专利、证据和科研动态；OmniHarness 与 OmniMind 面向可靠执行和持续研究；OmniPlotter、OmniSketch、OmniSlide 与 OmniOffice 面向绘图、科学示意图、演示文稿、文档和表格等可编辑科研产物；OmniSage 研究值得验证的科学问题如何形成；药物发现承担真实生物医学领域验证。评测、溯源、失败分析与可复现性贯穿所有方向。

这些方向各自承担独立的科学任务，目标是未来通过开放接口彼此组合。OmniMind 是它们可以汇聚的一种持续科研工作环境，但不是其他能力的所有者或唯一入口。科学家始终负责研究方向、证据判断、实验验证和最终结论。

以上方向均处于建设中。列入本页不代表已经公开发布、达到生产状态、获得规模采用，或通过科学、临床、法律与监管验证。

科研合作请联系：[liuzaoqu@163.com](mailto:liuzaoqu@163.com)
