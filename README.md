<div align="center">
    <h1>Awesome Totally Open Chatgpt</h1>
    <a href="https://github.com/sindresorhus/awesome"><img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg"/></a>
</div>

ChatGPT is GPT-3.5 finetuned with RLHF (Reinforcement Learning with Human Feedback) for human instruction and chat.

Alternatives are projects featuring different instruct finetuned language models for chat.
Projects are **not** counted if they are:

* Alternative frontend projects which simply call OpenAI's APIs.
* Using language models which are not finetuned for human instruction or chat.

Tags:

* Bare: only source code, no data, no model's weight, no chat system
* Standard: yes data, yes model's weight, bare chat via API
* Full: full yes data, yes model's weight, fancy chat system including TUI and GUI
* Complicated: semi open source, not really open source, based on closed model, etc...

Other revelant lists:

* [yaodongC/awesome-instruction-dataset](https://github.com/yaodongC/awesome-instruction-dataset) ⭐ 1,154 | 🐛 4 | 📅 2024-01-04: A collection of open-source dataset to train instruction-following LLMs (ChatGPT,LLaMA,Alpaca)

# Table of Contents

1. [The template](#The-template)
2. [The list](#The-list)
   * [lucidrains/PaLM-rlhf-pytorch](#lucidrainsPaLM-rlhf-pytorch)
   * [togethercomputer/OpenChatKit](#togethercomputerOpenChatKit)
   * [oobabooga/text-generation-webui](#oobaboogatext-generation-webui)
   * [KoboldAI/KoboldAI-Client](#KoboldAIKoboldAI-Client)
   * [LAION-AI/Open-Assistant](#LAION-AIOpen-Assistant)
   * [tatsu-lab/stanford\_alpaca](#tatsu-labstanford_alpaca)
     * [Other LLaMA-derived projects](#other-llama-derived-projects)
   * [BlinkDL/ChatRWKV](#BlinkDLChatRWKV)
   * [THUDM/ChatGLM-6B](#THUDMChatGLM-6B)
   * [bigscience-workshop/xmtf](#bigscience-workshopxmtf)
   * [carperai/trlx](#carperaitrlx)
   * [databrickslabs/dolly](#databrickslabsdolly)
   * [LianjiaTech/BELLE](#lianjiatechbelle)
   * [ethanyanjiali/minChatGPT](#ethanyanjialiminchatgpt)
   * [cerebras/Cerebras-GPT](#cerebrascerebras-gpt)
   * [TavernAI/TavernAI](#tavernaitavernai)
   * [Cohee1207/SillyTavern](#cohee1207sillytavern)
   * [h2oai/h2ogpt](#h2oaih2ogpt)
   * [mlc-ai/web-llm](#mlc-aiweb-llm)
   * [Stability-AI/StableLM](#stability-aistablelm)
   * [clue-ai/ChatYuan](#clue-aichatyuan)
   * [OpenLMLab/MOSS](#openlmlabmoss)

# Awesome The template with stars

Append the new project at the end of file

```markdown
## [{owner}/{project-name}]{https://github.com/link/to/project}

Description goes here

Tags: Bare/Standard/Full/Complicated
```

# The list

## [lucidrains/PaLM-rlhf-pytorch](https://github.com/lucidrains/PaLM-rlhf-pytorch) ⭐ 7,867 | 🐛 20 | 🌐 Python | 📅 2026-07-27

Implementation of RLHF (Reinforcement Learning with Human Feedback) on top of the PaLM architecture. Basically ChatGPT but with PaLM

Tags: Bare

## [togethercomputer/OpenChatKit](https://github.com/togethercomputer/OpenChatKit) ⭐ 8,982 | 🐛 92 | 🌐 Python | 📅 2024-04-09

OpenChatKit provides a powerful, open-source base to create both specialized and general purpose chatbots for various applications.

Related links:

* [spaces/togethercomputer/OpenChatKit](https://huggingface.co/spaces/togethercomputer/OpenChatKit)

Tags: Full

## [oobabooga/text-generation-webui](https://github.com/oobabooga/text-generation-webui) ⭐ 47,555 | 🐛 833 | 🌐 Python | 📅 2026-08-17

A gradio web UI for running Large Language Models like GPT-J 6B, OPT, GALACTICA, LLaMA, and Pygmalion.

Tags: Full

## [KoboldAI/KoboldAI-Client](https://github.com/KoboldAI/KoboldAI-Client) ⭐ 3,938 | 🐛 120 | 🌐 Python | 📅 2025-01-16

This is a browser-based front-end for AI-assisted writing with multiple local & remote AI models. It offers the standard array of tools, including Memory, Author’s Note, World Info, Save & Load, adjustable AI settings, formatting options, and the ability to import existing AI Dungeon adventures. You can also turn on Adventure mode and play the game like AI Dungeon Unleashed.

Tags: Full

## [LAION-AI/Open-Assistant](https://github.com/LAION-AI/Open-Assistant) ⭐ 37,407 | 🐛 296 | 🌐 Python | 📅 2024-08-17

OpenAssistant is a chat-based assistant that understands tasks, can interact with third-party systems, and retrieve information dynamically to do so.

Related links:

* [huggingface.co/OpenAssistant](https://huggingface.co/OpenAssistant)
* [r/OpenAssistant/](https://www.reddit.com/r/OpenAssistant/)

Tags: Full

## [tatsu-lab/stanford\_alpaca](https://github.com/tatsu-lab/stanford_alpaca) ⭐ 30,241 | 🐛 186 | 🌐 Python | 📅 2024-07-17

This is the repo for the Stanford Alpaca project, which aims to build and share an instruction-following LLaMA model.

Tags: Complicated

### Other LLaMA-derived projects:

* [ggerganov/llama.cpp](https://github.com/ggerganov/llama.cpp) ⭐ 124,797 | 🐛 2,136 | 🌐 C++ | 📅 2026-08-20 Ports for inferencing LLaMA in C/C++ running on CPUs, supports alpaca, gpt4all, etc.
* [nomic-ai/gpt4all](https://github.com/nomic-ai/gpt4all) ⭐ 77,406 | 🐛 772 | 🌐 C++ | 📅 2025-05-27 Demo, data and code to train an assistant-style large language model with \~800k GPT-3.5-Turbo Generations based on LLaMA.
* [hpcaitech/ColossalAI#ColossalChat](https://github.com/hpcaitech/ColossalAI/tree/main/applications/Chat) ⭐ 41,438 | 🐛 505 | 🌐 Python | 📅 2026-08-17 An open-source solution for cloning ChatGPT with a complete RLHF pipeline.
* [lm-sys/FastChat](https://github.com/lm-sys/FastChat) ⭐ 39,512 | 🐛 1,038 | 🌐 Python | 📅 2026-05-01 An open platform for training, serving, and evaluating large language model based chatbots.
* [tloen/alpaca-lora](https://github.com/tloen/alpaca-lora) ⭐ 18,908 | 🐛 365 | 🌐 Jupyter Notebook | 📅 2024-07-29 Code for rproducing the Stanford Alpaca results using low-rank adaptation (LoRA).
* [setzer22/llama-rs](https://github.com/setzer22/llama-rs) ⚠️ Archived Rust port of the llama.cpp project.
* [Lightning-AI/lit-llama](https://github.com/Lightning-AI/lit-llama) ⭐ 6,084 | 🐛 107 | 🌐 Python | 📅 2025-07-01 Implementation of the LLaMA language model based on nanoGPT.
* [nsarrazin/serge](https://github.com/nsarrazin/serge) ⚠️ Archived A web interface for chatting with Alpaca through llama.cpp. Fully dockerized, with an easy to use API.
* [juncongmoo/chatllama](https://github.com/juncongmoo/chatllama) ⭐ 1,201 | 🐛 3 | 🌐 Python | 📅 2025-01-18 Open source implementation for LLaMA-based ChatGPT runnable in a single GPU.
* [pointnetwork/point-alpaca](https://github.com/pointnetwork/point-alpaca) ⭐ 398 | 🐛 12 | 🌐 Python | 📅 2023-03-22 Released weights recreated from Stanford Alpaca, an experiment in fine-tuning LLaMA on a synthetic instruction dataset.

## [BlinkDL/ChatRWKV](https://github.com/BlinkDL/ChatRWKV) ⭐ 9,501 | 🐛 60 | 🌐 Python | 📅 2026-07-19

ChatRWKV is like ChatGPT but powered by RWKV (100% RNN) language model, and open source.

Tags: Full

## [THUDM/ChatGLM-6B](https://github.com/THUDM/ChatGLM-6B) ⭐ 40,988 | 🐛 605 | 🌐 Python | 📅 2024-06-27

ChatGLM-6B is an open bilingual language model based on General Language Model (GLM) framework, with 6.2 billion parameters. With the quantization technique, users can deploy locally on consumer-grade graphics cards (only 6GB of GPU memory is required at the INT4 quantization level).

Related links:

* Alternative Web UI: [Akegarasu/ChatGLM-webui](https://github.com/Akegarasu/ChatGLM-webui) ⭐ 1,888 | 🐛 25 | 🌐 Python | 📅 2023-07-25
* Docker image with built-on playground UI and streaming API compatible with OpenAI, using [Basaran](https://github.com/hyperonym/basaran) ⚠️ Archived: [peakji92/chatglm:6b](https://hub.docker.com/r/peakji92/chatglm/tags)
* Fintune ChatGLM-6b using low-rank adaptation (LoRA): [lich99/ChatGLM-finetune-LoRA](https://github.com/lich99/ChatGLM-finetune-LoRA) ⭐ 715 | 🐛 27 | 🌐 Jupyter Notebook | 📅 2023-07-18
* Deploying ChatGLM on Modelz: [tensorchord/modelz-ChatGLM](https://github.com/tensorchord/modelz-ChatGLM) ⭐ 16 | 🐛 0 | 🌐 Dockerfile | 📅 2023-03-20
* Slim version (remove 20K image tokens to reduce memory usage): [silver/chatglm-6b-slim](https://huggingface.co/silver/chatglm-6b-slim)

Tags: Full

## [bigscience-workshop/xmtf](https://github.com/bigscience-workshop/xmtf) ⭐ 534 | 🐛 12 | 🌐 Jupyter Notebook | 📅 2024-09-22

This repository provides an overview of all components used for the creation of BLOOMZ & mT0 and xP3 introduced in the paper [Crosslingual Generalization through Multitask Finetuning](https://arxiv.org/abs/2211.01786).

Related links:

* [bigscience/bloomz](https://huggingface.co/bigscience/bloomz)
* [bigscience/mt0-base](https://huggingface.co/bigscience/mt0-base)

Tags: Standard

## [carperai/trlx](https://github.com/carperai/trlx) ⭐ 4,753 | 🐛 102 | 🌐 Python | 📅 2024-01-08

A repo for distributed training of language models with Reinforcement Learning via Human Feedback (RLHF), supporting online RL up to 20b params and offline RL to larger models. Basically what you would use to finetune GPT into ChatGPT.

Tags: Bare

## [databrickslabs/dolly](https://github.com/databrickslabs/dolly) ⭐ 10,804 | 🐛 5 | 🌐 Python | 📅 2023-06-30

Databricks’ dolly-v2-12b, an instruction-following large language model trained on the Databricks machine learning platform that is licensed for commercial use. Based on pythia-12b trained on \~15k instruction/response fine tuning records [databricks-dolly-15k](https://github.com/databrickslabs/dolly/tree/master/data) ⭐ 10,804 | 🐛 5 | 🌐 Python | 📅 2023-06-30 generated by Databricks employees in capability domains from the InstructGPT paper.

Related links:

* [dolly v2 12B commercial commercially available model](https://huggingface.co/databricks/dolly-v2-12b)
* [dolly v1 6b model card](https://huggingface.co/databricks/dolly-v1-6b)

Tags: Standard

## [LianjiaTech/BELLE](https://github.com/LianjiaTech/BELLE) ⭐ 8,278 | 🐛 106 | 🌐 HTML | 📅 2024-10-16

The goal of this project is to promote the development of the open-source community for Chinese language large-scale conversational models. This project optimizes Chinese performance in addition to original Stanford Alpaca. The model finetuning uses only data generated via ChatGPT (without other data). This repo contains: 175 chinese seed tasks used for generating the data, code for generating the data, 0.5M generated data used for fine-tuning the model, model finetuned from BLOOMZ-7B1-mt on data generated by this project.

Related links:

* [English readme](https://github.com/LianjiaTech/BELLE#-belle-be-large-language-model-engine-1) ⭐ 8,278 | 🐛 106 | 🌐 HTML | 📅 2024-10-16

Tags: Standard

## [ethanyanjiali/minChatGPT](https://github.com/ethanyanjiali/minChatGPT) ⭐ 226 | 🐛 4 | 🌐 Python | 📅 2023-09-26

A minimum example of aligning language models with RLHF similar to ChatGPT

Related links:

* [huggingface.co/ethanyanjiali/minChatGPT](https://huggingface.co/ethanyanjiali/minChatGPT)

Tags: Standard

## [cerebras/Cerebras-GPT](https://huggingface.co/cerebras/Cerebras-GPT-6.7B)

7 open source GPT-3 style models with parameter ranges from 111 million to 13 billion, trained using the [Chinchilla](https://arxiv.org/abs/2203.15556) formula. Model weights have been released under a permissive license (Apache 2.0 license in particular).

Related links:

* [Announcement](https://www.cerebras.net/blog/cerebras-gpt-a-family-of-open-compute-efficient-large-language-models/)
* [Models with other amount of parameters](https://huggingface.co/cerebras)

Tags: Standard

## [TavernAI/TavernAI](https://github.com/TavernAI/TavernAI) ⭐ 54 | 🐛 2 | 📅 2026-08-14

Atmospheric adventure chat for AI language model **Pygmalion** by default and other models such as **KoboldAI**, ChatGPT, GPT-4

Tags: Full

## [Cohee1207/SillyTavern](https://github.com/Cohee1207/SillyTavern) ⭐ 32,408 | 🐛 571 | 🌐 JavaScript | 📅 2026-08-19

SillyTavern is a fork of TavernAI 1.2.8 which is under more active development, and has added many major features. At this point they can be thought of as completely independent programs. On its own Tavern is useless, as it's just a user interface. You have to have access to an AI system backend that can act as the roleplay character. There are various supported backends: OpenAPI API (GPT), KoboldAI (either running locally or on Google Colab), and more.

Tags: Full

## [h2oai/h2ogpt](https://github.com/h2oai/h2ogpt) ⚠️ Archived

h2oGPT - The world's best open source GPT

* Open-source repository with fully permissive, commercially usable code, data and models
* Code for preparing large open-source datasets as instruction datasets for fine-tuning of large language models (LLMs), including prompt engineering
* Code for fine-tuning large language models (currently up to 20B parameters) on commodity hardware and enterprise GPU servers (single or multi node)
* Code to run a chatbot on a GPU server, with shareable end-point with Python client API
* Code to evaluate and compare the performance of fine-tuned LLMs

Related links:

* [h2oGPT 20B](https://gpt.h2o.ai/)
* [🤗 h2oGPT 12B #1](https://huggingface.co/spaces/h2oai/h2ogpt-chatbot)
* [🤗 h2oGPT 12B #2](https://huggingface.co/spaces/h2oai/h2ogpt-chatbot2)

Tags: Full

## [mlc-ai/web-llm](https://github.com/mlc-ai/web-llm) ⭐ 18,578 | 🐛 155 | 🌐 TypeScript | 📅 2026-08-04

Bringing large-language models and chat to web browsers. Everything runs inside the browser with no server support.

Related links:

* <https://mlc.ai/web-llm>

Tags: Full

## [Stability-AI/StableLM](https://github.com/Stability-AI/StableLM) ⭐ 15,684 | 🐛 27 | 🌐 Jupyter Notebook | 📅 2024-04-08

This repository contains Stability AI's ongoing development of the StableLM series of language models and will be continuously updated with new checkpoints.

Related links:

* [huggingface.co/spaces/stabilityai/stablelm-tuned-alpha-chat](https://huggingface.co/spaces/stabilityai/stablelm-tuned-alpha-chat)
* [StableVicuna](https://github.com/Stability-AI/StableLM#stablevicuna) ⭐ 15,684 | 🐛 27 | 🌐 Jupyter Notebook | 📅 2024-04-08 an RLHF fine-tune of Vicuna-13B v0, which itself is a fine-tune of LLaMA-13B.

Tags: Full

## [clue-ai/ChatYuan](https://github.com/clue-ai/ChatYuan) ⭐ 1,863 | 🐛 30 | 🌐 Python | 📅 2023-06-16

ChatYuan: Large Language Model for Dialogue in Chinese and English (The repos are mostly in Chinese)

Related links:

* [A bit translated readme to English](https://github.com/nichtdax/awesome-totally-open-chatgpt/issues/18#issuecomment-1492826662) ⭐ 4,786 | 🐛 9 | 📅 2023-05-03

Tags: Full

## [OpenLMLab/MOSS](https://github.com/OpenLMLab/MOSS) ⭐ 12,221 | 🐛 242 | 🌐 Python | 📅 2026-05-27

MOSS: An open-source tool-augmented conversational language model from Fudan University. (Most examples are in Chinese)

Related links:

* [English readme](https://github.com/OpenLMLab/MOSS/blob/main/README_en.md) ⭐ 12,221 | 🐛 242 | 🌐 Python | 📅 2026-05-27

Tags: Full

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-20._
