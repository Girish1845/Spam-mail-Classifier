# Spam-mail-Classifier

# 📧 Intelligent Email Assistant - Spam Classifier & Summarizer

A smart email analysis tool that classifies emails as **Spam or Not Spam** using an **LSTM + RNN** deep learning model and generates concise summaries using the **BART Transformer**. The project features a clean and interactive **Gradio** web interface for real-time use.

---

## 📸 Demo

![App Demo](demo_image.png)

![image](https://github.com/user-attachments/assets/d8877d14-8445-4819-a567-52456db1b015)


## 🚀 Features

- 📬 Input any email content
- 🧠 Classifies email as **Spam** or **Not Spam**
- 📈 Displays **confidence score**
- 📝 Generates a short **summary** of the email
- 🌐 Accessible through a **Gradio web app**

---

## 🧠 Tech Stack

| Component        | Tool / Library                |
|------------------|-------------------------------|
| Language         | Python                        |
| ML Framework     | TensorFlow / Keras            |
| NLP Model        | HuggingFace BART              |
| Interface        | Gradio                        |
| Data Handling    | Pandas, NumPy                 |
| Preprocessing    | NLTK, re, sklearn              |
| Platform         | Google Colab (for training)   |

---

## 🗂️ Dataset

We used the **Spam-Ham dataset** (`spam_ham_dataset.csv`) which contains real-world emails labeled as either "spam" or "ham" (not spam).

**Columns:**
- `text`: Email content
- `label`: spam or ham
- `label_num`: 1 for spam, 0 for ham

---

## 🛠️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/email-spam-classifier-summarizer.git
cd email-spam-classifier-summarizer
