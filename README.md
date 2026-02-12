# LLM-Finetuning
This repository offers a comprehensive suite of resources for fine-tuning large language models (LLMs). It includes carefully curated datasets designed for supervised fine-tuning (SFT), as well as fully fine-tuned model checkpoints ready for evaluation and deployment. The repository provides clean, modular, and well-documented implementations of several parameter-efficient fine-tuning techniques, including LoRA (Low-Rank Adaptation), QLoRA (Quantized LoRA), and DoRA. These methods enable efficient adaptation of large-scale models while significantly reducing computational overhead and memory requirements.

Designed to support both research and production use cases, the codebase emphasizes reproducibility, scalability, and ease of experimentation. It facilitates streamlined training pipelines, configurable workflows, and systematic evaluation procedures. Whether for academic research, prototyping, or real-world deployment, this repository serves as a practical and extensible foundation for optimizing and customizing large language models efficiently.

## Repository Contents

#### Dataset
The dataset comprises 1,277 English question–answer pairs for training and 142 English question–answer pairs for testing, carefully curated from a wide range of scholarly journal publications and authoritative online sources. It also incorporates key insights from the European Commission’s reports on Industry 4.0 and Industry 5.0, ensuring both academic rigor and policy relevance.

The question–answer format is designed to provide structured, in-depth understanding of core concepts such as Industry 5.0, Industry 4.0, Human–Machine Collaboration, Collaborative Robots (COBOTs), Cyber-Physical Systems (CPS), Digital Twins, and related emerging technologies.

This high-quality dataset was utilized to fine-tune a 4-bit quantized Krishm/industry5-llama3-qlora model using the LoRA (Low-Rank Adaptation) technique, enabling efficient domain adaptation while maintaining computational efficiency.

Krishm/industry5-qa-dataset
https://huggingface.co/datasets/Krishm/industry5-qa-dataset

### Finetuned 4-Bit Llama - 3.2 3B with the above dataset and LoRA

Krishm/industry5-llama3-qlora
https://huggingface.co/Krishm/industry5-llama3-qlora
