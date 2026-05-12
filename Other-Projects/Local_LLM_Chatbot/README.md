# 🤖 Local / On-Premise LLM Chatbot

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mounibwassim/University-Projects/blob/main/Other-Projects/Local_LLM_Chatbot/TNL6323_Lab07a_(LLM_Chatbot).ipynb)

## 📖 Overview

A fully **local / on-premise AI chatbot** powered by Microsoft's **DialoGPT-medium** — a large language model built on the GPT-2 (medium, ~345M parameter) decoder-only transformer architecture, fine-tuned specifically for open-domain conversation.

Unlike cloud-based solutions, this chatbot runs **entirely within local infrastructure** (personal computer, lab server, or institutional data center), guaranteeing:
- 🔒 **Data Privacy** — no data leaves your machine.
- 🔐 **Security** — no external API calls or cloud dependencies.
- 📴 **Offline Operation** — works without an internet connection after setup.

A custom **Gradio** web interface is provided for easy, browser-based interaction.

---

## 🛠️ Technologies Used

| Tool / Library | Purpose |
|---|---|
| **Python** | Core programming language |
| **PyTorch** | Deep learning backend (GPU/CPU detection) |
| **Hugging Face Transformers** | Loading DialoGPT-medium model & tokenizer |
| **DialoGPT-medium** | Pre-trained conversational LLM (~345M params) |
| **Gradio** | Interactive browser-based chat UI |
| **Datasets** | (Available for fine-tuning extensions) |

---

## 🔑 Key Features

- **Baseline Chatbot** — Loads `microsoft/DialoGPT-medium` and maintains multi-turn conversational history using token concatenation.
- **GPU Acceleration** — Automatically detects and uses CUDA if available; falls back to CPU.
- **Custom Gradio UI** — A styled, browser-launched chat interface with a custom CSS theme.
- **On-Premise Deployment** — No external cloud APIs required after the initial model download from Hugging Face.

---

## 🗂️ Project Structure

```
Local_LLM_Chatbot/
│
└── TNL6323_Lab07a_(LLM_Chatbot).ipynb   # Main lab notebook
```

---

## 🚀 How to Run

### Prerequisites
```bash
pip install transformers torch gradio datasets
```

> **Note:** A [Hugging Face Access Token (HF_TOKEN)](https://huggingface.co/settings/tokens) is required to download the DialoGPT-medium model weights.

### Steps
1. Open the notebook in **Google Colab** (click the badge above) or locally in **Jupyter**.
2. Install the required dependencies (Cell 4).
3. Run the cells sequentially — the model will be downloaded from Hugging Face on first run.
4. The Gradio interface will launch automatically and provide a local URL to open in your browser.

---

## 📚 References

- [Microsoft DialoGPT on Hugging Face](https://huggingface.co/microsoft/DialoGPT-medium)
- [Hugging Face Transformers Documentation](https://huggingface.co/docs/transformers)
- [Gradio Documentation](https://www.gradio.app/docs/)
- Course resources adapted from [Zhongyu Pan — LinkedIn Learning](https://www.linkedin.com/learning/instructors/zhongyu-pan?u=114913666)
