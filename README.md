# genai-fraud-detection
# GenAI-Powered Fraud Detection Microservice 🚀

This project showcases a GenAI-driven microservice built to detect fraud in financial transactions using a hybrid approach:
- GPT-4 for deep reasoning
- FinBERT (Hugging Face) for sentiment analysis
- LangChain + ChromaDB for retrieval-augmented generation (RAG)

Additionally, it includes a custom fine-tuning of BERT (using Unsloth) to recognize fraud-specific patterns and streamline claims management workflows.

---

## 🛠 Tech Stack

- FastAPI (microservice orchestration)
- OpenAI API (GPT-4)
- Hugging Face Transformers (FinBERT, BERT)
- ChromaDB (vector search)
- LangChain (RAG pipeline)
- Docker (containerization)
- PyTorch + Unsloth (fine-tuning)

---

## 📚 Notebooks Included

| Notebook | Purpose |
|:---------|:--------|
| `01_fine_tuning_bert_unsloth.ipynb` | Fine-tune BERT for fraud classification |
| `02_model_evaluation.ipynb` | Evaluate performance metrics & confusion matrices |

---

## 🚀 Running the Microservice Locally

```bash
docker-compose up --build
