# vLLM Scalable AI Modal

Deploying private LLMs can be efficiently scaled using Hugging Face, vLLM, and Modal.com serverless architecture. 
This cost-effective solution leverages Modal’s on-demand GPUs, minimizing operational costs by only using resources during active requests. 
The setup allows for efficient scaling for concurrent users and makes specialized LLMs more accessible. 
Future improvements could include model compression or exploring other cloud providers, but this setup offers a strong base for effective private LLM management.

## Setup
```bash
pip install modal

```

## Run
```bash
modal run get_started.py
```
