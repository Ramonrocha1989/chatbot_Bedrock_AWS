# 🤖 Chatbot Ramon - Powered by Amazon Bedrock & Streamlit

An intelligent chatbot named **Ramon**, built using [LangChain](https://www.langchain.com/), [Streamlit](https://streamlit.io/), and [Amazon Bedrock](https://aws.amazon.com/bedrock/), enabling natural language interactions with conversational memory.


---

## 🛠 Technologies Used

- **Python 3.10+**
- **Streamlit** — Interface interativa
- **LangChain** — Gerenciamento de cadeia de conversação e memória
- **Amazon Bedrock** — Modelo LLM Titan (nova-pro-v1)
- **AWS SDK com perfil configurado**

---

## ⚙️ How to Run locally

1. **Clone this repository:**
   ```bash
   git clone https://github.com/seu-usuario/seu-repo.git
   cd seu-repo

2. **Create and activate a virtual environment:**
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows

3. **Install dependencies:**:
pip install -r requirements.txt

4. **Configure your AWS profile:**:
aws configure --profile default

5. **Run the chatbot:**:
streamlit run chatbot_frontend.py

6. **Project structure:**:
.
├── app.py                   # Main Streamlit application
├── chatbot_backend.py       # Backend logic with LangChain
├── images/                  # (Optional) Project-related images
├── requirements.txt
└── README.md

## 📷 UI Example
(images/image1.png)
(images/image2.png)






