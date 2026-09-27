---
layout: default
title: Portfolio
---

## Portfolio

---

## Projects

### MSc Dissertation: RAG for Statistical Reasoning in Large Language Models
**Tech:** Python, LangChain, FAISS, Ollama, Pandas, SciPy, Scikit-learn
Designed and implemented a complete RAG pipeline to evaluate whether large language models can reason about statistics. Built a 215-chunk knowledge base from academic PDF documents with empirically validated relevance thresholds (0.65, 0.70, 0.75), and evaluated three open-source LLMs — LLaMA 3, Mistral, and DeepSeek-R1 — under base and RAG conditions across 90 benchmark questions spanning hypothesis testing, regression, and probability. Built an LLM-as-judge evaluation framework calibrated against human annotations using Kendall tau, achieving inter-rater agreement of 0.701 for LLaMA 3 and 0.797 for Mistral. Identified specific LLM failure modes including overconfident incorrect outputs on multi-step numerical reasoning, with findings documented in a formal academic submission.
[View project on GitHub]([https://github.com/Arav810](https://github.com/Arav810/llm-rag-statistics-evaluation))

---

### RAG Pipeline Benchmarking Suite
**Tech:** Python, LangChain, FAISS, Qdrant, Neo4j, FastAPI, Docker, Git
Implemented three distinct RAG architectures — baseline dense retrieval, hybrid dense/sparse retrieval, and Graph RAG using Neo4j — and produced a structured comparative analysis of latency, accuracy, and data quality trade-offs across all three. Documented all architectures with full README files, inline comments, requirements files, and notebook walkthroughs to support reproducibility and reuse.
[View project on GitHub](https://github.com/Arav810/types-of-rag)

---

### Full-Stack Multimodal RAG Chatbot
**Tech:** LangChain, LangGraph, FastAPI, Streamlit, Docker, Groq, vector databases
Built an end-to-end RAG-based chatbot with a FastAPI backend and Streamlit frontend, enabling document-aware, multimodal queries and responses. Containerised the system with Docker Compose to make deployment and experimentation straightforward.
[View project on GitHub](https://github.com/Arav810/Chat-bot-using-RAG/tree/Qdrant)

---

### LLM Integration with ML Model
**Tech:** Python, Hugging Face Transformers, Scikit-learn, NumPy
Enhanced a Random Forest classifier on tabular data by generating LLM-based embeddings for categorical features and clustering them before classification. Achieved around 87% accuracy, a 6% gain over the baseline ML-only model, demonstrating the impact of representation learning on traditional pipelines.
[View project on GitHub](https://github.com/Arav810/GTD-Multi-classification-of-gname-LLM-integration)

---

### Time Series Forecasting Pipeline
**Tech:** Python, XGBoost, Scikit-learn, Pandas, Seaborn
Built an end-to-end forecasting pipeline covering data ingestion, outlier detection, temporal feature engineering including lag features and time-based cross-validation splits, and systematic comparison of multiple XGBoost configurations against out-of-sample accuracy metrics to identify the optimal modelling approach.
[View project on GitHub]([https://github.com/Arav810](https://github.com/Arav810/Time-Series-Forecasting-))

---

### Terrorist Group Prediction (Global Terrorism Database)
**Tech:** Python, Pandas, Scikit-learn, Matplotlib, Seaborn
Developed a multiclass classification model to predict terrorist groups from the Global Terrorism Database, with extensive data cleaning, encoding, and feature engineering. Used feature importance, correlation analysis, and hyperparameter tuning to reach strong performance and provide interpretable insights.
[View project on GitHub](https://github.com/Arav810/Global-Terrorism-Database-Multi-classifier)

---

### Facial Emotion Recognition with CNN
**Tech:** TensorFlow/Keras, Python, Pandas, NumPy, Seaborn
Built and trained a convolutional neural network to classify facial emotions from images, including thorough EDA and image preprocessing — normalisation and augmentation — for robust generalisation. Evaluated performance with appropriate metrics and visualisations to understand model behaviour across emotion classes.
[View project on GitHub](https://github.com/Arav810/Multi-class-Facial-recognition)

---

## Contact

If you'd like to discuss opportunities, collaborations, or get more details about any project:

- 📧 Email: [arav.chauhan0123@gmail.com](mailto:arav.chauhan0123@gmail.com)
- 🔗 LinkedIn: [linkedin.com/in/arav-chauhan-453164266](https://www.linkedin.com/in/arav-chauhan-453164266)
