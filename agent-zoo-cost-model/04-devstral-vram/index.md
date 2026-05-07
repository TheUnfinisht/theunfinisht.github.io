---
layout: page
title: "Devstral Memory Budget: Why 24GB Is a Bridge"
permalink: /agent-zoo-cost-model/04-devstral-vram/
---

Explain why GPU usefulness depends on usable VRAM after model weights, KV cache, runtime overhead, and context size.

**Status:** Draft scaffold

## Planned content

- Stack: OpenCode / Cline / Aider -> local OpenAI-compatible endpoint -> Devstral Small 2 24B
- Quant sizes: Q4_K_M, Q5_K_M, Q6_K, Q8_0
- Context sizes: 8k, 16k, 32k, 64k
- Why 24GB is a minimum bridge, not a destination
- Why 40-48GB is the first serious workstation target
- Why 96GB is a pro path

## Planned visuals

- Devstral VRAM budget heatmap
- VRAM class ladder: 16GB / 24GB / 32GB / 40GB / 48GB / 96GB

## Open questions

- Which inference runtime should define the baseline overhead?
- How much KV cache headroom should be reserved for practical agent workflows?
- Which quantization levels are useful enough for senior-engineering work?

[Back to The Agent Zoo Cost Model](/agent-zoo-cost-model/)
