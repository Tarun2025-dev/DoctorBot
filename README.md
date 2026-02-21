# Medical chatbot with RAG pipeline and LLM

# How to run?
### STEPS:

Clone the repository

```
### STEP 01- clone the existing repository
git clone https://github.com/Tarun2025-dev/DoctorBot.git```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


### Create a `.env` file in the root directory and add your Pinecone & Gemini credentials as follows:

```
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
GEMINI_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```


```
# run the following command to store embeddings to pinecone
python store_index.py
```

```
# Finally run the following command
python app.py
```
### Techstack Used:

- Python
- LangChain
- Flask
- Gemini
- Pinecone


