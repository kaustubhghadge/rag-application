# Building a RAG application from scratch

## Setup

1. Create a virtual environment and install the required packages:

```bash
$ python3 -m venv .venv
$ source .venv/bin/activate
$ pip install -r requirements.txt
```

2. Create a `.env` file with the following variables:

```bash
OPENAI_API_KEY = [ENTER OPENAI API KEY HERE]
PINECONE_API_KEY = [ENTER PINECONE API KEY HERE]
PINECONE_API_ENV = [ENTER PINECONE API ENVIRONMENT HERE]
```