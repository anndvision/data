# can-ai-agents-improve-ai-agents

Baseline rollout traces for the [TensorZero blog post](https://www.tensorzero.com/blog/can-ai-agents-improve-ai-agents/) and its companion starter at [`tensorzero/tensorzero/examples/blog/can-ai-agents-improve-ai-agents/`](https://github.com/tensorzero/tensorzero/tree/main/examples/blog/can-ai-agents-improve-ai-agents).

Stored via Git LFS (`*.jsonl filter=lfs ...` in `.gitattributes`).

## Files

| File | Rows | Size | SHA-256 |
| --- | ---: | ---: | --- |
| `baseline_data/inferences.jsonl` | 1,380 | 98 MiB | `9bac777bcedd790146ed082252ad77d41496f19f1beaecc8acac12cffe55d176` |
| `baseline_data/feedback.jsonl` | 320 | 36 KiB | `e59685147aea4679d6e617e39e12cd8474e052649f0eb48ccca9f6b2a6fe319d` |

## Provenance

A real baseline rollout of the YC Bench Tutorial environment (`yc_bench_tutorial_v0::yc_bench_act`) against the `initial` variant on `openai::gpt-5.4-mini`: 80 unique train tasks + 20 unique test tasks (Codex YC Bench seed 0, 2026-04-23).

These match the artifacts the autopilot-evals harness dumps to `<run_dir>/claude_code/baseline_data/` before invoking the optimizer agent.

## Raw URLs

LFS-backed files use `media.githubusercontent.com/media/...` to fetch actual content (rather than the LFS pointer that `raw.githubusercontent.com` returns):

```
https://media.githubusercontent.com/media/anndvision/data/main/can-ai-agents-improve-ai-agents/baseline_data/inferences.jsonl
https://media.githubusercontent.com/media/anndvision/data/main/can-ai-agents-improve-ai-agents/baseline_data/feedback.jsonl
```
