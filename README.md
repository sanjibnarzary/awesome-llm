# AwesomeLLM
Curated List of Large Language Models
# What is LLMs
Large Language Models (LLMs) are computer programs designed to understand and generate human language. They are based on deep learning techniques, which allow them to learn from vast amounts of data and make predictions based on that knowledge. The development of LLMs is one of the most exciting recent advancements in artificial intelligence and natural language processing.

LLMs are able to generate text that is often indistinguishable from text written by humans. They can be used to write news articles, generate dialogue, create captions for images, and even complete tasks like answering questions and translating languages. LLMs have a wide range of applications, from chatbots to virtual assistants, and they are becoming increasingly important in fields such as journalism, marketing, and customer service.

One of the most important aspects of LLMs is their ability to learn from large amounts of data. They are often trained on massive datasets of text, such as books, articles, and social media posts. By analyzing this data, they are able to learn the patterns and structures of language and use that knowledge to generate new text.

## Large Language Models
- Bloom: BigScience Large Open-science Open-access Multilingual Language Model
  - Model Parameters - 176B
  - [Code](https://huggingface.co/bigscience/bloom)
  - [Paper](https://arxiv.org/abs/2211.05100)
- Galactica: A Large Language Model for Science. 
  GALACTICA is a general-purpose scientific language model. It is trained on a large corpus of scientific text and data. It can perform scientific NLP tasks at a high level, as well as tasks such as citation prediction, mathematical reasoning, molecular property prediction and protein annotation. More information is available at galactica.org.
  - Model Parameters - 125M, 1.3B, 6.7B, 30B. 120B
  - [Code](https://github.com/paperswithcode/galai)
  - [Paper](https://arxiv.org/abs/2211.09085)
- LLaMA: Open and Efficient Foundation Language Models
  - Model Parameters - 7B, 13B, 33B, 65B
  - [Code](https://github.com/facebookresearch/llama)
  - [Paper](https://arxiv.org/abs/2302.13971)
- MPT30B: Mosaic Pretrained Transformer
  - Model Parameters - 30B
  - [Code](https://github.com/mosaicml/llm-foundry/)
  - [Model](https://huggingface.co/mosaicml/mpt-30b)
  - [Blog](https://www.mosaicml.com/blog/mpt-30b)
  - [Demo](https://huggingface.co/spaces/mosaicml/mpt-30b-chat)
  - Minimum System Requirements: NVIDIA A100 40GB (It did not work on NVIDIA A100 32GB)
  - *Release Date*: 22 June, 2023
- OPT (Open Pre-trained Transformers)
  - Model Parameters - 125M, 350M, 1.3B, 2.7B, 13B, 30B, 66B, 175B
  - [Code](https://github.com/facebookresearch/metaseq/tree/main/projects/OPT)
  - [Paper](https://arxiv.org/abs/2205.01068)
- OPT-IML: Scaling Language Model Instruction Meta Learning through the Lens of Generalization
  - Model parameters - 30B, 175B
  - [Code](https://github.com/facebookresearch/metaseq/tree/main/projects/OPT-IML)
  - [Paper](https://arxiv.org/abs/2212.12017)
- Pythia : a suite of 16 Large Language Models (LLMs) with varying model parameters, ranging from 70 million to 12 billion parameters. Developed by EleutherAI.
  - Model parameters - 70M, 160M, 410M, 1.0B, 1.4B, 2.8B, 6.9B, 12B
  - [Code](https://github.com/EleutherAI/pythia/tree/main/models)
  - [Paper](https://arxiv.org/pdf/2304.01373)
  - [Hugging Face](https://huggingface.co/EleutherAI/pythia-410m-deduped)

## Fine Tuned Models
- Alpaca: Stanford Alpaca: An Instruction-following LLaMA Model
  - Fine tuned on *LLaMA*
  - Application for Dialogue System or ChatGPT alternative
  - [Code](https://github.com/tatsu-lab/stanford_alpaca.git)
  - [Paper](https://crfm.stanford.edu/2023/03/13/alpaca.html)
- Alpaca-lora:
  - Training chatGPT alternative on consumer device gpus
  - [Code](https://github.com/sanjibnarzary/awesome-llm)
- 🦙 ChatLLaMA: ChatLLaMA 🦙 is a library that allows you to create hyper-personalized ChatGPT-like assistants using your own data and the least amount of compute possible. Instead of depending on one large assistant that “rules us all”, we envision a future where each of us can create our own personalized version of ChatGPT-like assistants. Imagine a future where many ChatLLaMAs at the "edge" will support a variety of human's needs. But creating a personalized assistant at the "edge" requires huge optimization efforts on many fronts: dataset creation, efficient training with RLHF, and inference optimization.
  - [Code](https://github.com/nebuly-ai/nebullvm/tree/main/apps/accelerate/chatllama)
  - Paper: Not available
  - Demo: on own model

- Koala: A Dialogue Model for Academic Research
  - Fine tuned on *LLaMA* 
  - Application for Dialogue System or ChatGPT alternative
  - [Code](https://github.com/young-geng/EasyLM)
  - [Paper](https://bair.berkeley.edu/blog/2023/04/03/koala/)
  - [Demo](https://chat.lmsys.org/?model=koala-13b)
- MPT-30B-Instruct: MPT-30B-Instruct is a model for short-form instruction following. It is built by finetuning MPT-30B on Dolly HHRLHF derived from the Databricks Dolly-15k and the Anthropic Helpful and Harmless (HH-RLHF) datasets. It is also trained on Competition Math, Duorc, CoT GSM8k, Qasper, Quality, Summ Screen FD and Spider.
  - [Code](https://github.com/mosaicml/llm-foundry/)
  - [Blog](https://www.mosaicml.com/blog/mpt-30b)
  - [Demo](https://huggingface.co/spaces/mosaicml/mpt-30b-chat)
  - Minimum System Requirements: NVIDIA A100 40GB (It did not work on NVIDIA A100 32GB)
  - *Release Date*: 22 June, 2023
- Vicuna: An Open-Source Chatbot Impressing GPT-4 with 90%* ChatGPT Quality 
  - Fine tuned on *LLaMA* 
  - Application for Dialogue System or ChatGPT alternative
  - [Code](https://github.com/lm-sys/FastChat)
  - [Paper](https://vicuna.lmsys.org/)
  - [Demo](https://chat.lmsys.org/)
- Xturing: xturing provides fast, efficient and simple fine-tuning of LLMs, such as LLaMA, GPT-J, GPT-2, OPT, Cerebras-GPT, Galactica, and more. By providing an easy-to-use interface for personalizing LLMs to your own data and application, xTuring makes it simple to build and control LLMs. The entire process can be done inside your computer or in your private cloud, ensuring data privacy and security.
  - [Code](https://github.com/stochasticai/xturing)
  - Paper - Not available
  - Demo
  <img src="https://github.com/stochasticai/xturing/raw/main/.github/cli-playground.gif" width="100%" style="margin: 0 1%;"/>
- Dolly 2.0 : An open source, commercially usable ChatGPT-style AI model developed by Databricks. Trained on a high-quality human-generated instruction following dataset, crowdsourced among Databricks employees
  - Fine tuned on *Pythia* 
  - Application for Dialogue System or ChatGPT alternative
  - [Code](https://github.com/databrickslabs/dolly/tree/master/data)
  - [Paper](https://www.databricks.com/blog/2023/04/12/dolly-first-open-commercially-viable-instruction-tuned-llm)
  - Demo
  - [Weights](https://huggingface.co/databricks/dolly-v2-7b)



## 🌎 Contributing
As an open source project in a rapidly evolving field, we welcome contributions of all kinds, including new features and better documentation.
