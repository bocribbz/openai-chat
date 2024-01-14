# openai-chatbot

Building a simple chatbot using OpenAI API
inside a Jupyter Notebook.

## Generate a token to use with Jupyter Notebook

```
import IPython as IPython
hash = IPython.lib.passwd("S-E-C-R-E-T")
print(hash)
```

And dump it in `.env` file.

## OpenAI API Key

Generate an OpenAI API Key
and dump it in `.env` file.

## Run the chatbot

Start docker

```
$ docker compose up
```

Navigate to http://127.0.0.1:8888/
use the secret you defined as the access token.

Open the `chatbot.ipynb`
and execute each instruction,
the last one would start the chatbot
until you type one of the stop words.
