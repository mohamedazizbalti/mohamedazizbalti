# Mohamed Aziz Balti

**AI Engineer · LLM Agents · Document AI**

I build LLM systems that run in production: multi-agent copilots with human-in-the-loop control, grounded tutoring agents, and OCR-to-structured-data pipelines. I work end to end, from LangGraph orchestration and prompts to vLLM serving, tracing and regression tests. Software Engineering graduate of INSAT (Tunis, 2026).

## What I work on

- **AI tutoring.** A math tutor grounded in each lesson's worksheet, transcript and video, which guides students without giving away answers.
- **Document AI.** A worksheet digitization pipeline (DeepSeek-OCR on vLLM, LLM extraction and validation) that turns a PDF page into an interactive worksheet in 1–3 minutes instead of up to an hour by hand, and a LangGraph classifier that re-categorized ~3.3M legacy worksheets.
- **Multi-agent copilot.** A LangGraph supervisor delegating to 6 specialist agents over 30+ tools, with human-in-the-loop interrupts, MongoDB checkpointing and permissions enforced by construction.
- **LLM security.** A fine-tuned prompt-injection classifier served with FastAPI.

This work is private. The repositories below are my public projects.

## Public projects

| Project | What it is |
|---|---|
| [LLM watermarking](https://github.com/mohamedazizbalti/LLM-Watermark-Paper-Implementation) | The green-list watermark of Kirchenbauer et al. (2023) on Qwen3-0.6B, as a logits processor with a z-test detector |
| [GPT-2 from scratch](https://github.com/mohamedazizbalti/GPT-2-Paper-Implementation) | Decoder-only transformer with training, inference and preprocessing |
| [GPT-1 + optimized BPE](https://github.com/mohamedazizbalti/GPT-implementation) | "Improving Language Understanding by Generative Pre-Training", with a byte-level BPE tokenizer (max-heap, linked-list merges, trie encoding) |
| [BERT from scratch](https://github.com/mohamedazizbalti/BERT-implementation) | Encoder-only pre-training and a training loop |
| [Transformer from scratch](https://github.com/mohamedazizbalti/Transformer-Implementation) | "Attention Is All You Need" with causal and cross attention |
| [Semantic FAQ (RAG)](https://github.com/mohamedazizbalti/semantic-faq) | FastAPI + React FAQ assistant with Qdrant semantic search and Redis caching |

## Stack

**LLMs & agents:** LangGraph, LangChain, RAG, LiteLLM, OpenRouter, Azure OpenAI
**Document AI & vision:** DeepSeek-OCR, VLMs, YOLO, speech-to-text
**Serving & MLOps:** vLLM, RunPod, Ollama, FastAPI, Docker, Langfuse
**ML:** PyTorch, Hugging Face Transformers, scikit-learn
**Data & cloud:** MongoDB, Redis, Qdrant, FAISS, AWS (S3, ECS), Azure
**Languages:** Python, TypeScript, SQL

## Contact

[LinkedIn](https://www.linkedin.com/in/balti-mohamed-aziz-bbb8ba154/) · [azizbalti50@gmail.com](mailto:azizbalti50@gmail.com)
