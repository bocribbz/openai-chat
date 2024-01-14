# openai-chat

Building a simple chat using OpenAI API
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

## Run the chat

Start docker

```
$ docker compose up
```

Navigate to http://127.0.0.1:8888/
use the secret you defined as the access token.

Open the `chat.ipynb`
and execute each instruction,
the last one would start the chat
until you type one of the stop words.
