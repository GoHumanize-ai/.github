# GoHumanize

**[gohumanize.ai](https://gohumanize.ai)** turns AI-generated text into writing that reads naturally, keeping the meaning, the facts and the author's intent.

## Open work

We publish part of our work in the open so developers and researchers can learn how a text-humanization system is built:

**GoHumanize Open Humanizer** is a small open model (Qwen3-4B fine-tune, Apache-2.0) trained on 2,000 pairs built from 47 public-domain books, published with its dataset, training pipeline, evaluation and a paper-style write-up of every step and service used.

| Resource | Link |
| --- | --- |
| Project page and browser demo | [gohumanize.ai/open-model](https://gohumanize.ai/open-model) |
| Model weights, LoRA adapter, GGUF builds | [gohumanize/gohumanize-open-humanizer](https://huggingface.co/gohumanize/gohumanize-open-humanizer) |
| Dataset, 2,200 pairs (CC-BY 4.0) | [gohumanize/gohumanize-open-humanizer-dataset](https://huggingface.co/datasets/gohumanize/gohumanize-open-humanizer-dataset) |
| Code and full pipeline | [gohumanize-open-humanizer](https://github.com/GoHumanize-ai/gohumanize-open-humanizer) |
| Write-up: every step, service and result | [docs/paper.md](https://github.com/GoHumanize-ai/gohumanize-open-humanizer/blob/main/docs/paper.md) |
| Archived release, citable DOI | [10.5281/zenodo.22843083](https://doi.org/10.5281/zenodo.22843083) |
| Python client and CLI | [pypi.org/project/gohumanize-open-humanizer](https://pypi.org/project/gohumanize-open-humanizer/) |
| MCP server for AI assistants | [npm](https://www.npmjs.com/package/gohumanize-open-humanizer-mcp) · [source](https://github.com/GoHumanize-ai/gohumanize-open-humanizer-mcp) |

Try it in one line:

```bash
pip install gohumanize-open-humanizer && open-humanizer "It is worth noting that the committee reached a consensus."
```

The open model is an educational release. It is separate from the production models behind gohumanize.ai and makes no claim about AI detectors.

## Contact

hello@gohumanize.ai
