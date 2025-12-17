# 🩺 AI-Medical-Chatbot

An AI-powered medical assistant that helps users get preliminary health-related information through natural language conversations. This chatbot is designed to provide instant responses to medical queries using LLMs and retrieval-based techniques.

⚠️ Disclaimer: This chatbot is for informational purposes only and does not replace professional medical advice, diagnosis, or treatment.

# How to run?

### STEPS:

Clone the repository

```bash
git clone https://github.com/anjali067verma/AI-Medical-Chatbot.git
```

### STEP 01: Create a conda environment after opening the repository

```bash
conda create -n medibot python=3.10 -y
```

```bash
conda activate medibot
```

### STEP 02: Install the requirements

```bash
pip install -r requirements.txt
```

### Create a `.env` file in the root directory and add your Pinecone & GROQ credentials as follows:

```ini
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
GROQ_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

```bash
# run the following command to store embeddings to pinecone
python store_index.py
```

```bash
# Finally run the following command
python app.py
```

Now,

```bash
open up localhost:
```

### Techstack Used:

- Python
- LangChain
- Flask
- GROQ LLM
- Pinecone