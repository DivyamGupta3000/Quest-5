# GPT-4 Chatbot

A simple command line chatbot with GPT-4.


<img width="822" alt="screenshot" src="https://github.com/DivyamGupta3000/Quest-5/assets/108221297/a7adf4a5-da75-457c-8a69-6dbe1d3dff1a">







You need to create a virtual env and install the packages listed in `requirements.txt`. You can then run Jupyter Notebooks in VS Code.

Follow these steps: [How to Work with Python Virtual Environments, Jupyter Notebooks and VS Code](https://python.plainenglish.io/how-to-work-with-python-virtual-environments-jupyter-notebooks-and-vs-code-536fac3d93a1).

You need to create a `.env` file with your `OPENAI_API_KEY`.

## Usage

To run the CLI:

```
cd 02-gpt-4-chatbot
python3 chatbot.py
```

You can define the personality of your chatbot, it is friendly and helpful by default:

```
python3 chatbot.py --personality "funny"
```

You can quit by typing `ctrl + C` (Mac) or `cmd + C` (Windows).

## Features

- writing the basic chatbot structure.
- persisting messages accross requests.
- adding optional personalities.
- colorizing the chatbot output.


