# 🤖 FAQ Chatbot with NLP (TF-IDF + Cosine Similarity)

This project implements a simple yet effective **rule-based chatbot** using **TF-IDF vectorization** and **cosine similarity** to respond to user queries. The bot is powered by **NLTK** for preprocessing and **scikit-learn** for similarity matching and vectorization. It uses a predefined **FAQ knowledge base** and responds to user questions based on similarity scoring.

---

## 📌 Features

- 🧠 Uses **TF-IDF + Cosine Similarity** to match queries  
- 📚 Predefined FAQ dataset (customer support-style)  
- 🛠 Powered by **NLTK** and **Scikit-learn**  
- 🖥️ Simple CLI-style interface



---

## 🧰 Technologies Used

- Python  
- NLTK  
- scikit-learn  
- NumPy  

---

## 📝 Dataset

A manually created **FAQ dictionary** containing 40+ common customer queries, such as:

- Order tracking  
- Returns & refunds  
- Payments & delivery  
- Account & profile updates  
- Support and small talk

---

## 🧪 Evaluation Logic

- Uses **cosine similarity score** to rank FAQs  
- Returns the best-matching answer if score > 0.3  
- Fallback response: *"I'm sorry, I didn't understand that. Can you rephrase?"*

---

## 🚀 How to Run

> ⚠️ This chatbot uses only `input()` for interaction. No widgets are used to avoid metadata rendering issues on GitHub.

### ✅ Steps to Run on Google Colab

1. Open [Google Colab](https://colab.research.google.com/)
2. Upload the `.ipynb` notebook or paste the code
3. Run all cells from top to bottom
4. Interact via the input/output prompt at the bottom

---

## 💬 Sample Questions to Try

- `How can I track my order?`  
- `What is your return policy?`  
- `Do you ship internationally?`  
- `How do I change my address?`  
- `Can I cancel my order?`  
- `Hello`, `Bye`, `Thanks`

---

## 👨‍💻 Developed By

**Yagesh Kumar Jha**

> Completed and tested in Google Colab as part of ML mini-projects.  
> Designed for educational use and chatbot demonstrations.

---

## 📎 License

This project is free to use and modify for educational and non-commercial purposes.
