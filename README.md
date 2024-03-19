GLiNER : Generalist and Lightweight model for Named Entity Recognition

GLiNER is a Named Entity Recognition (NER) model capable of identifying any entity type using a bidirectional transformer encoder (BERT-like). It provides a practical alternative to traditional NER models, which are limited to predefined entities, and Large Language Models (LLMs) that, despite their flexibility, are costly and large for resource-constrained scenarios.

Paper: https://arxiv.org/abs/2311.08526 (by Urchade Zaratiana, Nadi Tomeh, Pierre Holat, Thierry Charnois)

Git repo: https://github.com/urchade/GLiNER

GLiNER Hugging Face models: https://huggingface.co/urchade/gliner_base

GLiNER SpaCy Wrapper: https://pypi.org/project/gliner-spacy/0.0.2/

PROJECT DETAILS

The project takes in a long text as the base corpus on which the NER task is performed. The task is to identify skills, technologies and programing language from a job dcription posted online.

