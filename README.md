# 🌟 AI NLP Assistant – Powered by Transformers

Welcome to the **AI NLP Assistant**, a multi-model, interactive language tool powered by Hugging Face Transformers!  
This project integrates several state-of-the-art NLP capabilities into a clean, user-friendly Gradio interface.

---

## 🚀 Features

This assistant does **much more than just chat!**

| Feature                  | Model Used                                     | Description |
|--------------------------|------------------------------------------------|-------------|
| 💬 **ChatBot**            | Qwen2-1.5B-Instruct                            | A conversational assistant trained for instruction-following chat |
| 🧠 **Sentiment Analysis** | distilBERT fine-tuned on SST-2                 | Understand the emotional tone of any text |
| ✍️ **Text Generation**    | GPT-2                                          | Generate creative, coherent text from a prompt |
| 🔍 **Named Entity Recognition (NER)** | BERT fine-tuned on CoNLL-03 dataset     | Recognize people, places, organizations in your text |
| ❓ **Question Answering** | distilBERT fine-tuned on SQuAD                 | Answer questions based on provided context |

---

## 🛠️ Tech Stack

- 💬 [Transformers](https://huggingface.co/transformers/)
- 🖼️ [Gradio](https://www.gradio.app/)
- 🐍 Python 3.11+
- ⚡ Google Colab (or run locally)

---

## 📦 Installation (Local)

```bash
git clone https://github.com/your-username/ai-nlp-assistant.git
cd ai-nlp-assistant
pip install -r requirements.txt
python app.py
