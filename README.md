# Papa Diadji BOYE

**AI / ML Engineer ** | Building, evaluating and making LLM systems reliable

I build AI systems end to end, from model design to production, and I care about one question: does it actually work, and how do we know?

- **Devoteam Research & Innovation**: RAG / GraphRAG systems and a query classifier , deployed as an API with Docker and CI/CD
- **INRAE**: explainability for computer vision; benchmarked Grad-CAM, Integrated Gradients, LIME and RISE, adapted D-RISE and D-CLOSE to object detection
- NVIDIA DLI certified: Adding Knowledge to LLMs, Rapid Application Development with LLMs, Efficient Workflows

---

## Tech Stack

**Languages & ML**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

**LLM & Evaluation**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge)
![Ragas](https://img.shields.io/badge/Ragas-6C5CE7?style=for-the-badge)
![DeepEval](https://img.shields.io/badge/DeepEval-4B32C3?style=for-the-badge)

**Engineering & Deployment**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab%20CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)


## Featured Projects

### [LLM Inference Benchmark](https://github.com/Diadji23/llm-inference-benchmark)
How much speed, memory and quality does quantization really trade? Reproducible benchmark with llama.cpp on 3 models (FP16, 8-bit, 4-bit).
- Decoding is memory-bandwidth bound: 4-bit gives 1.7–2.3x faster decoding and half the memory
- Quality checked with perplexity, KL divergence and MMLU (McNemar tests): stable accuracy can hide 20% of flipped answers
- Pre-registered hypotheses, interleaved randomized runs, 20 unit tests

### [reliable-tool-agent](https://github.com/Diadji23/Reliable-tool-agent)
A customer-support agent built as a complete system, not a demo.
- Tools served over MCP with Pydantic-validated outputs; the customer identity comes from the session, never from the model
- Human approval before refunds and cancellations, guardrails against prompt injection and out-of-scope requests
- Evaluation on the final database state rather than the wording of the answer, with tracing and cost tracking

### [RAG Assistant — Research Papers](https://github.com/Diadji23/RAG-Assistant-Computer-Vision-Papers)
Question answering with citations over 965 chunks of computer vision papers.
- Same pipeline runs locally (Mistral via Ollama, ChromaDB) or on Azure (Azure OpenAI, hybrid search) by configuration
- Retries, cost alerts, Docker, pytest and GitHub Actions

### [Explain-RAG](https://github.com/Diadji23/Explainable-RAG)
Makes RAG answers verifiable: links every generated sentence to its source and measures faithfulness by passage ablation.

### Other projects
- [LangGraph Support Agent](https://github.com/Diadji23/langgraph-support-agent): tool-using agent that checks the reliability of its own answer and escalates to a human when in doubt
- [DPO from Scratch](https://github.com/Diadji23/DPO): Direct Preference Optimization loss implemented from scratch in PyTorch, with unit tests
- [Speech-to-Text API](https://github.com/Diadji23/Speech-to-Text-API): Whisper served over REST and WebSocket (FastAPI), WER/CER evaluation, Docker
- [Amazon Review Prediction](https://github.com/Diadji23/amazon-review-prediction-nlp): 525k reviews, TF-IDF vs BiLSTM vs fine-tuned BERT (94.7% accuracy), Dockerized API
- [Explainability in Deep Learning](https://github.com/Diadji23/Explainability-in-deep-Learning-): XAI methods for classification and object detection

---


---

## Contact

[LinkedIn](https://www.linkedin.com/in/papadiadji/) · papediadji123@gmail.com · Open to AI / ML Engineer roles in France and Europe
