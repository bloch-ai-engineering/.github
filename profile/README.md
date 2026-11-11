# AI Engineering

Hands-on projects across the modern AI engineering stack: **LLM evaluation, RAG, agents, inference serving, observability and distributed training.** Built during the Nebius Academy *AI Performance Engineering* program, each project is a working system with measured results and an honest write-up of what did and didn't work.

## Projects

| Project | What it is | Stack |
|---|---|---|
| [**text2sql-observability**](https://github.com/bloch-ai-engineering/text2sql-observability) | Text-to-SQL service tuned from a P95 of 84 s to 4.4 s at 11.8 RPS on 1× H100, with no accuracy loss | vLLM · LangGraph · Langfuse · Prometheus/Grafana |
| [**data-analyst-agent**](https://github.com/bloch-ai-engineering/data-analyst-agent) | Conversational data-analyst agent: LLM router + ReAct over typed tools, persistent memory, 95% routing accuracy | LangGraph · Pydantic · MCP · Streamlit |
| [**fin-rag**](https://github.com/bloch-ai-engineering/fin-rag) | RAG over SEC filings (FinanceBench) evaluated on correctness, faithfulness and hit-rate, with improvement cycles | LangChain · FAISS · RAGAS |
| [**llm-copywriter-eval**](https://github.com/bloch-ai-engineering/llm-copywriter-eval) | LLM content generation with a human rubric, LLM-as-a-judge, and judge–human agreement analysis | OpenAI SDK · Pydantic · Nebius |
| [**skypilot-ddp-training**](https://github.com/bloch-ai-engineering/skypilot-ddp-training) | Multi-node PyTorch DDP on Kubernetes H100s, with a 1→4 GPU NCCL communication-overhead analysis | PyTorch DDP · SkyPilot · mk8s |
| [**seq-models-nlp**](https://github.com/bloch-ai-engineering/seq-models-nlp) | Subword tokenization → Word2Vec → MLP news classifier (91%), and a char-level LSTM language model | PyTorch · gensim · 🤗 tokenizers |
| [**torch-optim-lab**](https://github.com/bloch-ai-engineering/torch-optim-lab) | SGD, Momentum, AdaGrad and Adam from scratch, plus numerical stability and L1 sparsity | PyTorch |

## Maintainers

- **Nathanael Bloch**: [@nbloch](https://github.com/nbloch)
- **Tomer Porat**: [@analytics972](https://github.com/analytics972)
