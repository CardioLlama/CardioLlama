# 🫀 CardioLlama — A Clinical Language Model for Cardiology

**CardioLlama** is a domain-adapted large language model fine-tuned specifically for cardiology and clinical medicine.  
It is built on the **LLaMA-2-7B** architecture and fine-tuned using **LoRA** (Low-Rank Adaptation), enabling parameter-efficient training on domain-specific texts such as clinical notes, ECG interpretations, discharge summaries, and guidelines.

---

## 🚀 Quick Start

👉 **[Run CardioLlama on Hugging Face Spaces](https://huggingface.co/spaces/CardioLlama/CardioLlama)** 

👉 **[Run CardioLlama on Hugging Face Spaces (Duplicate Space)](https://huggingface.co/spaces/CardioLlama/CardioLlama-Chatbot)** 
Interact with the model directly from your browser. No setup required.

---

## 📦 Model Details

| Detail | Value |
|--------|-------|
| **Base Model** | [LLaMA-2-7B](https://huggingface.co/meta-llama/Llama-2-7b) |
| **Fine-Tuning Method** | LoRA |
| **Domain** | Cardiology, Clinical Medicine |
| **Tokenizer** | LLaMA tokenizer |
| **Model Files** | `adapter_model.safetensors`, `model.safetensors`, tokenizer files |

This model was trained to understand and generate text specific to cardiovascular disease, diagnostic terminology, patient narratives, and clinical workflows.

---

## 📁 Repository Contents

This repo hosts documentation and pointers to:

- 🔗 Model weights on Hugging Face: [`CardioLlama/CardioLlama`](https://huggingface.co/CardioLlama/CardioLlama)
- 🌐 Inference space: [`CardioLlama/CardioLlama`](https://huggingface.co/spaces/CardioLlama/CardioLlama)
- 🌐 Inference space (Duplicate): [`CardioLlama/CardioLlama-Chatbot`](https://huggingface.co/spaces/CardioLlama/CardioLlama-Chatbot)
- 🧾 Example prompts and expected responses
- 📜 Licensing and limitations

---

