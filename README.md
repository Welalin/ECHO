# ECHO: Empathetic Conversation for Holistic Optimization

<div align="center">

[[Website]](https://github.com/Welalin/ECHO)
[[Paper]](NOTREADYYET)
[[Demo]](https://huggingface.co/spaces/babaei/ECHO)

![](assets/motiveExample.pdf)

</div>

## Abstract

Large Language Models (LLMs) in conversation systems struggle with sensitive topics due to limitations in factual accuracy, diverse perspective modeling, and mutual empathy assessment. To address this, we propose ECHO (Empathetic Conversation for Holistic Optimization). ECHO leverages a Retrieval-Augmented Graph of Thought (GoT) for improved context and reasoning, alongside a Mutual Empathy Assessment (MEA) component to evaluate both expressed empathy from the LLM and perceived empathy from the user. This framework, inspired by research on collaborative empathy, aims to enhance LLM interactions in sensitive conversations.

## Prerequisites

- Python packages can be installed with `pip install -r requirements.txt`

- `OpenAI_API_key` is required for the language model. You can get it from [OpenAI](https://beta.openai.com/signup/).

```
export OPENAI_API_KEY="sk-******"
```

- You can also use the Huggingface API key for the language model. You can get it from [Huggingface](https://huggingface.co/join).

- You also need to prepare the `GOOGLE_API_KEY` for Google Search API. You can get it from [Google Cloud Platform](https://cloud.google.com/docs/authentication/getting-started).

```
export GOOGLE_API_KEY="********"
```

## Getting Started

You can run the ipython notebook named `creative.ipynb` to generate open-ended creative text with ECHO.

You can also use the following code to start a Gradio interface to interact with ECHO:

```shell
python app/gradio_app.py
```

## Experimental Results

Comming Soon!

## Check out our paper!

Comming Soon!
