
# Fine-Tuning LLaMA with QLoRA

This repository provides a Jupyter notebook to fine-tune a LLaMA model using modern, memory-efficient techniques — ideal for training large models in environments like Google Colab.

## 🚀 What’s Inside

This notebook demonstrates how to fine-tune **LLaMA-3.2-1B-Instruct** using:

- 🤖 **QLoRA** (Quantized Low-Rank Adaptation)
- 🧠 **PEFT** (Parameter Efficient Fine-Tuning)
- ⚙️ **Hugging Face Transformers**
- 💾 **Google Colab** (free or Pro)

---

## 📂 Contents

- `llm_finetuning.ipynb` — Main notebook that walks through:
  - Model loading (from Hugging Face)
  - 4-bit quantization using `bitsandbytes`
  - LoRA configuration with `peft`
  - Custom dataset loading and prompt formatting
  - Fine-tuning and saving the adapted model

---

## 🧠 Model Info

- **Model:** `LLaMA-3.2-1B-Instruct` (custom model)
- **Architecture:** Based on Meta's LLaMA-3 series
- **Quantization:** 4-bit QLoRA using `bitsandbytes`
- **PEFT Adapter:** Applied LoRA layers to reduce trainable parameters
- **Dataset:** Human preference data with structured prompts

---

## 🔧 Setup Instructions

### 1. Clone the repository:

```bash
git clone https://github.com/yourusername/llm-finetuning-notebook.git
cd llm-finetuning-notebook
