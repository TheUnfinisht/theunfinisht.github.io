---
layout: page
title: "Decision Rules"
permalink: /agent-zoo-cost-model/08-decision-rules/
---

Summarize practical rules for deciding when to use Web/API, hybrid, or local hardware.

**Status:** Draft scaffold

## Planned content

1. Buy optionality before performance.
2. Do not buy a GPU until measured usage proves the bottleneck.
3. B1 must be useful as a dev-server immediately.
4. 24GB is a bridge, not a destination.
5. 40-48GB is the first serious local AI workstation target.
6. 96GB is a pro path, not a budget path.
7. SXM is not a GPU deal; it is a server-platform decision.
8. Do not optimize for datacenter throughput if the workload is single-user agentic coding.
9. If local models save tokens but burn senior time, they are not cheaper.
10. Ownership beats access only at sufficient utilization.

## Planned visuals

- Decision rules poster
- Final strategy diagram:
  - Web/API frontier models first.
  - B1 dev-server if immediately useful.
  - GPU only after measured usage proves payback.

## Open questions

- Which rules should become hard gates in the model?
- How should measured usage be collected without adding process drag?
- What decision rule best captures the boundary between local and frontier models?

[Back to The Agent Zoo Cost Model](/agent-zoo-cost-model/)
