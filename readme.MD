# Smart Lightweight Medical Query System (SLiMQ) 
# Documentation
## Introduction
Smart Lightweight Medical Query System (SLiMQ) is a sophisticated medical response system designed to assist doctors and medical professionals. Unlike conventional chatbots, SLiMQ is tailored for specific medical queries, ensuring accurate and informed responses. This system operates efficiently on off-the-shelf machines and edge devices, making it highly accessible.
## Key Features
- `Specialized Medical Responses:` SLiMQ is designed to answer medical queries accurately, providing reliable information to users.
- `Lightweight and Efficient:` SLiMQ is optimized for performance, enabling it to run seamlessly on various devices without compromising efficiency.
- `Integration of External Data:` To enhance response accuracy, SLiMQ utilizes external data sources, allowing for contextually relevant answers.
- `Flexible Deployment:` SLiMQ can be deployed as a Jupyter Notebook or a standalone application, offering flexibility to users.
- `Quantized Models:` SLiMQ supports quantized models, enabling efficient execution on non-GPU and resource-constrained machines.

## System Architecture
### SLiMQ's architecture comprises several components:

- Embedding Model: SLiMQ utilizes standard embeddings models, such as sentencetransformer as Embedded model  and LangChain as pipeline, to process text data effectively.
- Vector Database: The system employs CromaDb, a versatile vector database, for storing and retrieving contextual information.
- Pretrained Language Models: SLiMQ integrates pretrained language models like Llama-2 to complete answers accurately.
- Document Pipeline: The system incorporates LangChain, an external document pipeline, to manage and process medical documents.
- To make the model lightweight, the system uses a Quantized version of llama-2 7B (precisely the Q4).


