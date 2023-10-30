# <img src="https://lilinwang.github.io/image/tigerLabLogo.png" height="24px" style="padding-top:4px"/>TigerLab - Open Source LLM Toolkit
<br/>
<div align="center">
    <img src="https://lilinwang.github.io/image/TigerLab.png" width="80%"  style="padding: 40px"/>
</div>
<br/>
<p align="center">
  🐅🚀<em>LLM Toolkit: RAG + FineTune + ?</em>🚀🐅
</p>
<div align="center">
    <a href="https://discord.gg/GnwH2STv">
    <img src="https://img.shields.io/badge/discord-join%20chat-blue.svg?style=for-the-badge" alt="Join our Discord" height="20">
    </a>
    <a href="https://twitter.com/TigerLabAI">
    <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/TigerLabAI?style=for-the-badge" height="20">
    <a href="https://github.com/tigerlab-ai/tiger">
    <img alt="GitHub" src="https://img.shields.io/github/stars/tigerlab-ai/tiger?style=for-the-badge&color=gold" height="20">
    </a>
    <a href="https://github.com/tigerlab-ai/tiger/commits/main">
    <img alt="GitHub" src="https://img.shields.io/github/last-commit/tigerlab-ai/tiger/main?style=for-the-badge" height="20">
    </a>
    <a href="https://github.com/tigerlab-ai/tiger/blob/main/README.md" target="_blank">
    <img src="https://img.shields.io/static/v1?label=license&message=MIT&color=green&style=for-the-badge" alt="License" height="20">
    </a>
</div>

A significant gap has arisen between general Large Language Models (LLMs) and the vector stores that provide them with contextual information. Bridging this gap is a crucial step towards grounding AI systems in efficient and factual domains, where their value lies not only in their generality but also in their specificity and uniqueness.

In pursuit of this goal, we are thrilled to introduce the Tiger toolkit (TigerRag, TigerTune, TigerDA, TigerArmor) as an open-source resource for developers to create AI models tailored to their specific needs.

We believe that our efforts will play a pivotal role in shaping the next phase of language modeling. This phase involves organizations customizing AI systems to align with their unique intellectual property and safety requirements, ushering in a new era of AI customization and precision.

## ✨ Demo
Find more demos at [TigerLab.ai](https://www.tigerlab.ai/)

### Demo 1 - Enhanced Search Capabilities, w/ EBR, RAG and GAR
https://github.com/tigerlab-ai/tiger/assets/4805931/e7c35117-269a-437d-99ab-10407a901cc5

### Demo 2 - Fine-tuning Llama2 and DistilBERT
https://github.com/tigerlab-ai/tiger/assets/3810505/2e379c99-ef0c-485a-853e-ef41c4d1b775




## 🔬 Tech stack
<div align="center">
    <img src="https://lilinwang.github.io/image/diagram.png" width="100%"  style="padding: 20px"/>
</div>

- **TigerRag**: Use embeddings-based retrieval (EBR), retrieval-augmented generation (RAG), and generation-augmented retrieval (GAR) to fulfill search queries. The demo used `BERT` for embedding, `FAISS` for indexing, `text-davinci-003` for generation.
- **TigerTune**: Python SDK to finetune, make inference, and evaluate Text Generation models and Text Classification models. The notebook demo finetuned `Llama2` and `DistilBERT`.
- **TigerDA**: Data Augmentation Toolkit. Coming soon!

## 👨‍🚀 Prerequisites

Before you begin setting up this project, please ensure you have completed the following tasks:

### 0. Setup Tutorial

- [Tutorial - YouTuBe](https://youtu.be/0v0Qe-cbvRs?si=ON-ni2yLeVpB0Yco)

### 1. LLM -  OpenAI API Token
<details><summary>👇click me</summary>
This application utilizes the OpenAI API to access its powerful language model capabilities. In order to use the OpenAI API, you will need to obtain an API token.

To get your OpenAI API token, follow these steps:

1. Go to the [OpenAI website](https://beta.openai.com/signup/) and sign up for an account if you haven't already.
2. Once you're logged in, navigate to the [API keys page](https://beta.openai.com/account/api-keys).
3. Generate a new API key by clicking on the "Create API Key" button.
4. Copy the API key and store it safely.
5. Add the API key to your environment variable, e.g. `export OPENAI_API_KEY=<your API key>`

</details>

## 💿 Installation
- **Step 1**. Clone the repo
   ```sh
   git clone https://github.com/tigerlab-ai/tiger.git
    ```
- **Step 2**. Install TigerRag
    - Install all Python requirements
      
    ```sh
    cd tiger/TigerRag 
    pip install -r tigerrag/requirements.txt
    ```
    Demo:
    ```
    cd tigerrag/demo/movie_recs
    python demo.py
    ```
- **Step 3**. Install TigerTune
    - Install all Python requirements
    ```sh
    cd tiger/TigerTune
    pip install -r tigertune/requirements.txt
    pip install --upgrade -e .
    ```
    Demo:
    ```
    python tigertune/finetuning/llm/example.py 
    ```


## 📍 Roadmap
- [x] Launch v0.0.1
- [ ] Release TigerDA
- [ ] Release TigerArmor
- [ ] Add additional model support in TigerTune
- [ ] VectorDB for TigerRag
- [ ] Release TigerArmor for AI safety
- [ ] WebApp

## 🫶 Contribute to TigerLab
Please check out our [Contribution Guide](contribute.md)!

## 💪 Contributors
<a href="https://github.com/tigerlab-ai/tiger/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=tigerlab-ai/tiger" />
</a>

## 🎲 Community
- Join us on [Discord](https://discord.gg/GnwH2STv)
