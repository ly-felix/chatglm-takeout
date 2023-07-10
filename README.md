# chatglm-takeout
ChatGLM2-6b is a small-sized LLM (Language Model) open-sourced by Tsinghua University. It can be used for inference and fine-tuning with just a regular GPU, 32GB VRAM recommended for stability. It works on google colab (16GB VRAM). It is currently a highly active open-source LLM in the community.

In this example, we use a simple dataset of food delivery reviews to implement fine-tuning. We employ ChatGLM2-6b to classify whether a snippet of a food delivery review is positive or negative.

It can be observed that the fine-tuned model achieves significantly better results compared to directly using a 3-shot prompt.

It is worth noting that while we use text classification as an example here, in practice, any NLP task such as named entity recognition, translation, chat dialogue, and so on, can be transformed into a dialogue question by adding suitable context. By designing appropriate datasets for our specific use case, we can perform fine-tuning on open-source LLMs.
