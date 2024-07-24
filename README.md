---
title: CustomizedLLMApp
emoji: 💬
colorFrom: yellow
colorTo: purple
sdk: gradio
sdk_version: 4.36.1
app_file: app.py
pinned: false
---

An example chatbot using [Gradio](https://gradio.app), [`huggingface_hub`](https://huggingface.co/docs/huggingface_hub/v0.22.2/en/index), and the [Hugging Face Inference API](https://huggingface.co/docs/api-inference/index).
The code creates an interactive chat application using Gradio and HuggingFace's Inference API to discuss AI in healthcare. It processes a PDF on AI in healthcare, builds a searchable vector database of its contents, and retrieves relevant document excerpts to enhance responses to user queries about AI's impact on health and healthcare.
