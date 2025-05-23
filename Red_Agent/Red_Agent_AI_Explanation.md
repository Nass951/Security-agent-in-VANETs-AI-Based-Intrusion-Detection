# Local LLM Query Tool with GPT4All / Ollama

This project provides a Python-based template for interacting with local Large Language Models (LLMs), such as **Nous Hermes 2 - Mistral DPO**, using either the **GPT4All** or **Ollama** interface. It supports simple natural language prompts and can be adapted for specialized domains such as cybersecurity simulations in vehicular networks (VANETs).

---

## Features

* Local inference with fast responses (no internet required after model download)
* Supports **GPT4All** or **Ollama** inference frameworks
* Easily switch between models

---

## Installation

### 1. Python dependencies

```bash
pip install gpt4all requests
```

| GPT4All                                                   | Ollama                                                    |
| --------------------------------------------------------- | --------------------------------------------------------- |
| Download from: [https://gpt4all.io/](https://www.nomic.ai/gpt4a) | Download from: [https://ollama.com/](https://ollama.com/download) |
| Place model in GPT4All models directory                   | Use `ollama run nous-hermes` to launch                    |
| Example model: `nous-hermes-2-mistral-7b-dpo.Q4_0.gguf`   | Example model name: `nous-hermes`                         |

---

### 4. Usage
* The goal of this agent is to try to hack the VANETs. We use an open source IA and give him a special prompt to try to cyber-attacks the traffic.

## Notes

* For heavier models like Mistral 7B, at least **8 GB of RAM** is recommended.

---
