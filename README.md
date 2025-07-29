## pre-requirements
- Prepare your OpenAI API key
- Set up the Langfuse environment & get your public key, secret key, and hostname information.
- Modify the contents of .env.example to create a .env file. The following values are required:
  - OPENAPI_API_KEY
  - LANGFUSE_PUBLIC_KEY
  - LANGFUSE_SECRET_KEY
  - LANGFUSE_HOST
- install uv


## prepare runtime environment
```
$ uv install python 3.11.1
$ uv venv
$ source .venv/bin/activate
$ uv pip install -r requirements.txt
```


## execute
```
$ source .venv/bin/activate
$ python mcp_use_first_agent.py
```