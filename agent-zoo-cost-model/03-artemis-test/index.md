---
layout: page
title: "The Artemis Test: Cheap VRAM Is Not Usable VRAM"
permalink: /agent-zoo-cost-model/03-artemis-test/
---

Convert external hardware-sourcing notes into a technical acceptance checklist.

**Status:** Draft scaffold

## Planned content

- Artemis as the hardware market reality-check layer
- Cheap GPU price vs usable GPU path
- PCIe vs SXM
- CUDA vs non-CUDA
- Single-user agentic coding vs multi-user inference throughput
- Required proof before a GPU enters the model:
  - exact part number
  - PCIe or SXM
  - nvidia-smi proof
  - VRAM total
  - ECC status
  - temperature and power limit
  - cooling requirements
  - return path
  - full platform cost, not just module cost

## Planned visuals

- Artemis Test checklist
- GPU acceptance matrix

## Open questions

- Which marketplace claims should be excluded until verified?
- What minimum evidence is enough for a used GPU to enter the model?
- How should return risk and platform mismatch risk be priced?

[Back to The Agent Zoo Cost Model](/agent-zoo-cost-model/)
