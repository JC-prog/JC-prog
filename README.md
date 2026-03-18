# Jeffrey Chong

Software developer based in Singapore. I work across machine learning, computer vision, and full-stack development, mostly building tools where AI handles something that would otherwise require a lot of tedious manual work.

A lot of my projects follow a similar thread: find a domain where data exists but the extraction or analysis process is slow and manual, then automate the hard part. That's pulled me in a few different directions — processing clinical eye reports for ophthalmology workflows, predicting pedestrian intent from video for autonomous driving research, and monitoring financial news at scale with agent pipelines. I also build conventional web applications and backend services when that's what the problem calls for.

**What I work with**

AI and ML:

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-000000?style=flat&logo=langchain&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-FF7C00?style=flat&logo=gradio&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)

Web and backend:

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=spring-boot&logoColor=white)

**Selected projects**

[finax](https://github.com/JC-prog/finax) — A multi-agent pipeline that monitors financial news on a daily schedule, scores each article as bullish, bearish, or neutral using Gemini, and sends a formatted digest to Telegram or email. The three agents (Scout, Analyst, Alert) are orchestrated with LangGraph. The goal was to make it trivial to stay on top of market sentiment for a specific set of tickers without reading through news manually.

[pedsense-ai](https://github.com/JC-prog/pedsense-ai) — Computer vision framework for predicting whether a pedestrian is about to cross the road, trained on the JAAD dataset. Benchmarks three architectures: a YOLO end-to-end detector, a ResNet-50 + LSTM classifier over 16-frame windows, and a hybrid that combines the two. Includes a Gradio demo and model registry integration with Hugging Face Hub.

[visual-field-insight](https://github.com/JC-prog/visual-field-insight) — OCR pipeline for Humphrey Visual Field reports used in ophthalmology. Extracts numerical values and field maps from clinical PDFs and exports structured CSV or JSON. Ships as a portable offline Windows build for clinics that can't rely on internet access. Supports single file, batch, and a browser-based template editor for tweaking extraction regions.

[AudioBench](https://github.com/JC-prog/AudioBench) — Gradio interface for benchmarking audio-to-text APIs side by side. Built because testing different transcription providers usually means writing throwaway scripts each time — this makes it a repeatable, visual process.

[F1-Regs-RAG](https://github.com/JC-prog/F1-Regs-RAG) — RAG system built on Formula 1 regulations. Lets you ask natural language questions against the official rulebook instead of digging through PDFs. A smaller project, but a useful exercise in building retrieval pipelines over dense, structured documents.

**Find me**

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat&logo=vercel&logoColor=white)](https://jeffrey-chong-dev.vercel.app/)
