# Medical-Chatbot

# STEPS:

```bash
Project repo : git@github.com:Sohan-Sekhar-Sabat/Medical-Chatbot-.git 
```

# STEP 1: Create a conda environment after opening repo

```bash
conda create -n WellNudgeAI python=3.10 -y
```

```bash
conda activate WellNudgeAI 
```

### STEP-02 install the requirements
```bash
pip install -r requirements.txt
```

### Create a .env file in the root directory and add your Pinecone & openai credentials as follows:
```bash
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
YOUR_DESIRED_LLM_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

```bash
# run to store embeddings to pinecone
python store_index.py
```

```bash
# Finally running the following command
python app.py
```

### Techstack Used:
- Python
- LangChain
- Flask
- GPT
- Pinecone