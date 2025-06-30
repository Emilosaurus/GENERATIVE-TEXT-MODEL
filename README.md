
# 🧠 Generative Text Model

Generate coherent, creative text on any topic using powerful GPT-based models (like GPT-Neo or GPT-2) from Hugging Face Transformers.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Emilosaurus/GENERATIVE-TEXT-MODEL/blob/main/Generative%20text%20model.ipynb)

---

## 👨‍💻 Intern Details

- **Company**: CODTECH IT SOLUTIONS  
- **Name**: Emil Saj Abraham  
- **Intern ID**: CT08DL252  
- **Domain**: AI  
- **Duration**: 8 weeks  
- **Mentor**: Neela Santhosh  

---

## 🚀 Features

- Interactive prompt input (no widgets required)
- Runs on GPU automatically if available
- Supports large language models:
  - `distilgpt2`, `gpt2`, `gpt2-large`
  - `EleutherAI/gpt-neo-1.3B`, `2.7B`
  - `EleutherAI/gpt-j-6B`
- Uses top-k/top-p sampling for diverse text

---

## 📋 How to Use

1. Click the **"Open in Colab"** button above.
2. Run all cells (Shift + Enter).
3. Enter your desired topic or sentence when prompted.
4. Let the model generate creative text for you!

---

## 🛠 Dependencies

Preinstalled in Colab, but for local use:

```bash
pip install transformers torch
```

---

## 💡 Example Output

```
📝 Enter your topic or prompt: The future of AI is
🚀 Loading model `EleutherAI/gpt-neo-2.7B` on CUDA...

===========================

### 🧠 Generated Text:

The future of AI is filled with possibilities. As machines become smarter and more adaptive, humans will increasingly collaborate with intelligent systems...
```

---

## 📁 File Structure

```
GENERATIVE-TEXT-MODEL/
├── Generative text model.ipynb   # Main Colab-compatible notebook
└── README.md                     # You're here
```

---

## 🤖 Built With

- [Transformers by Hugging Face](https://huggingface.co/docs/transformers)
- [Google Colab](https://colab.research.google.com/)
- [PyTorch](https://pytorch.org/)

---

## 🙌 Author

Made by [Emilosaurus](https://github.com/Emilosaurus)  
Feel free to star ⭐ the repo or contribute!
