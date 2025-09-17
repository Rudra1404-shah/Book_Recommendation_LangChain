# 📚 Book Recommendation System with LangChain

An AI-powered **Book Recommendation System** built using **LangChain**, **LLMs**, and **Vector Databases**.  
This project analyzes books, embeddings, and sentiment to recommend titles tailored to user queries.

---

## 🔥 Features
- 📖 **Book Embeddings** – Store and query book descriptions using `chroma_db`.
- 🤖 **LLM Integration** – Uses OpenAI + Hugging Face models for text analysis.
- ❤️ **Sentiment Analysis** – Analyze user/book sentiment (`sentiment-analysis.ipynb`).
- 🔍 **Vector Search** – Semantic search for better book recommendations.
- 📊 **Data Visualization** – Insights from book datasets.
- 🛡️ **Secret Management** – Supports `.env` for API keys (no hardcoding!).

---

## 🏗️ Tech Stack
- **Python 3.12**
- [LangChain](https://www.langchain.com/)
- [ChromaDB](https://docs.trychroma.com/)
- [Hugging Face Transformers](https://huggingface.co/transformers/)
- Pandas, NumPy, Matplotlib, Scikit-learn

---

## 📂 Project Structure
Book_Recommendation_LangChain/
- chroma_db/ # Vector database (ignored in git)
- .env 
- .gitignore # Ignore env, db, and large files
- books.csv # Raw dataset
- books_with_categories.csv # Processed dataset with categories
- books_with_emotions.csv # Dataset with sentiment annotations
- dashboard.py # Streamlit/Gradio dashboard
- data-explorations.ipynb # Notebook for data analysis
- less_than_25.csv # Filtered dataset (books < 25 ratings)
- sentiment-analysis.ipynb # Sentiment analysis
- tagged_description.txt # Tagged book descriptions
- text-classification.ipynb # Text classification
