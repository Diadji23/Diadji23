# Papa Diadji BOYE

**AI / ML Engineer ** | Building, evaluating and making LLM systems reliable

I build AI systems end to end, from model design to production, and I care about one question: does it actually work, and how do we know?

- **Devoteam Research & Innovation**: RAG / GraphRAG systems and a query classifier , deployed as an API with Docker and CI/CD
- **INRAE**: explainability for computer vision; benchmarked Grad-CAM, Integrated Gradients, LIME and RISE, adapted D-RISE and D-CLOSE to object detection
- NVIDIA DLI certified: Adding Knowledge to LLMs, Rapid Application Development with LLMs, Efficient Workflows

---

## Featured Projects

### [LLM Inference Benchmark](https://github.com/Diadji23/llm-inference-benchmark)
How much speed, memory and quality does quantization really trade? Reproducible benchmark with llama.cpp on 3 models (FP16, 8-bit, 4-bit).
- Decoding is memory-bandwidth bound: 4-bit gives 1.7–2.3x faster decoding and half the memory
- Quality checked with perplexity, KL divergence and MMLU (McNemar tests): stable accuracy can hide 20% of flipped answers
- Pre-registered hypotheses, interleaved randomized runs, 20 unit tests

### [RAG Assistant — Research Papers](https://github.com/Diadji23/RAG-Assistant-Computer-Vision-Papers)
Question answering with citations over 965 chunks of computer vision papers.
- Same pipeline runs locally (Mistral via Ollama, ChromaDB) or on Azure (Azure OpenAI, hybrid search) by configuration
- Retries, cost alerts, Docker, pytest and GitHub Actions

### [Explain-RAG](https://github.com/Diadji23/Explainable-RAG)
Makes RAG answers verifiable: links every generated sentence to its source and measures faithfulness by passage ablation.

### [LangGraph Support Agent](https://github.com/Diadji23/langgraph-support-agent)
Tool-using agent that checks the reliability of its own answer and escalates to a human when in doubt.

### [DPO from Scratch](https://github.com/Diadji23/DPO)
Direct Preference Optimization loss implemented from scratch in PyTorch, with unit tests.

### Other projects
- [Speech-to-Text API](https://github.com/Diadji23/Speech-to-Text-API): Whisper served over REST and WebSocket (FastAPI), WER/CER evaluation, Docker
- [Amazon Review Prediction](https://github.com/Diadji23/amazon-review-prediction-nlp): 525k reviews, TF-IDF vs BiLSTM vs fine-tuned BERT (94.7% accuracy), Dockerized API
- [Explainability in Deep Learning](https://github.com/Diadji23/Explainability-in-deep-Learning-): XAI methods for classification and object detection

---

## Stack

**ML / LLMs:** Python, PyTorch, TensorFlow, Hugging Face, LangChain, LangGraph, llama.cpp
**Evaluation:** Ragas, DeepEval, LLM-as-judge, statistical testing
**Engineering:** FastAPI, Docker, Kubernetes, CI/CD, Azure, Git, Linux

---

## Contact

[LinkedIn](https://www.linkedin.com/in/papadiadji/) · papediadji123@gmail.com · Open to AI / ML Engineer roles in France and Europe
