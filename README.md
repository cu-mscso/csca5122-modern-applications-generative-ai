# CSCA 5122: Modern Applications of Generative AI

CSCA 5122 · [Generative AI Specialization](https://github.com/cu-mscso/specialization-generative-ai) · CU Boulder MSCS via Coursera

**Instructor:** Bobby Hodgkinson · **Duration:** ~9 hours · **Level:** Intermediate

## Overview

Explores how generative AI behavior is shaped, guided, and extended — from inference-time control through prompting to how models acquire capabilities during training via reinforcement learning and fine-tuning. Progresses from single prompts to structured reasoning, model evaluation, and real-world applications across coding, business, accessibility, and creative domains.

## Modules

| Module | Title | Topics |
|--------|-------|--------|
| 1 | Course Introduction | Generative AI refresher, course framing |
| 2 | Prompting and Control Parameters | Inference-time control, temperature, sampling, prompt structure |
| 3 | Training and Alignment | RLHF, fine-tuning, evaluator models, hallucinations, reward misalignment |
| 4 | Reasoning Scaffolds and Chain-of-Thought | Chain-of-thought prompting, context windows, self-critique, iterative refinement |
| 5 | Ecosystem and Evaluation | Open-source models, MoE architectures, benchmarking, Goodhart's Law, alignment drift |
| 6 | Tools, Memory and Persistence | Tool use, RAG, short-term context, long-term memory, summarization |
| 7 | Applications and Ethics | Code generation, business workflows, accessibility, AI productivity paradox |

## Topics Covered

- Inference-time control vs. training-time intelligence
- Reinforcement Learning from Human Feedback (RLHF)
- Fine-tuning and behavioral alignment
- Chain-of-thought and structured reasoning
- Mixture of Experts (MoE) architectures
- Model benchmarking and evaluation
- Retrieval-Augmented Generation (RAG) and tool use
- Agentic memory and persistence
- Responsible AI and data ethics

## Prerequisites

Completion of CSCA 5112 (Introduction to Generative AI) or equivalent familiarity with GenAI fundamentals.

## Setup

```shell
pyenv virtualenv 3.12 $(basename $PWD)
pyenv local $(basename $PWD)
pip install -r requirements.txt
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, please reach out to [Abdul Mohammed](https://github.com/am368a) or open an issue on GitHub.
