# Mohamed Aziz Balti

AI engineer. I build LLM agents and document-AI systems that run in production, and I reimplement papers to understand how the models underneath actually work.

## What I'm working on

- **Agents that know when to stop and ask.** A supervisor delegating to 6 specialist agents over 30+ tools. It pauses for a human when a field is missing or an action needs approval, then resumes from a checkpoint, even after a restart. It is validated against a 59-scenario test suite.
- **A tutor that doesn't give the answer away.** Grounded in each lesson's worksheet, transcript and video. A 50+ case regression suite checks that it withholds final answers.
- **PDFs into structured data.** OCR on vLLM plus LLM extraction and validation: a worksheet page in 1–3 minutes instead of up to an hour by hand.

These run at work, so the code is private.

## From papers to code

I learn a model by rebuilding it:

- [**LLM watermarking**](https://github.com/mohamedazizbalti/LLM-Watermark-Paper-Implementation): Kirchenbauer et al. (2023) on Qwen3-0.6B. 1,000 watermarked tokens score 72.5% green (z = 14.2).
- [**GPT-2**](https://github.com/mohamedazizbalti/GPT-2-Paper-Implementation), [**GPT-1 with a byte-level BPE tokenizer**](https://github.com/mohamedazizbalti/GPT-implementation), [**BERT**](https://github.com/mohamedazizbalti/BERT-implementation) and [**the original Transformer**](https://github.com/mohamedazizbalti/Transformer-Implementation), implemented from the papers in PyTorch.

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/balti-mohamed-aziz-bbb8ba154/) · [azizbalti50@gmail.com](mailto:azizbalti50@gmail.com)
