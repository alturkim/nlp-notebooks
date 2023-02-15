# nlp-notebooks
A collection of Jupyter notebook on various NLP topics.

## Content
### Sentiment Analysis with Hugging Face Trainer API.
The HF Trainer API is a simple way to train a model for a specifi task. There are many supported NLP tasks in the HF library. See the [doc](https://huggingface.co/docs) for details.
### Sentiment Analysis with Pytorch.
This is a more detailed implementation of the code in the previous notebook (Sentiment Analysis with Hugging Face Trainer API.) Here we use pytorch training loop which gives you more control into your training and evaluation.
### Few-shot Arabic sentiment Analysis with SetFit.
SefFit is an algorithm for few-shot learning based on the [sentence-transformer library](https://www.sbert.net/). On a high level, the algorithm fine-tune a sentence-transformer model using Contrastive Learning such that embeddings of examples of different classes are pushed apart, and embeddings for same-class examples are pulled closer. A more detailed description can be found on my Linkedin post [here](https://www.linkedin.com/posts/mustafa-alturki-78b86812b_few-shot-learning-using-setfit-activity-7027588511616634880-PAx0?utm_source=share&utm_medium=member_desktop)
### Sentiment_Analysis_with_Parameter_Efficient_Finetuning.
Parameter Efficient Finetuning aims to reduce the amount of necessary computation power (GPU time and disk space) needed to finetune and deploy a system based on Large Language Model (or any pretrained large model), there are several methods proposed in the literature, here we are using the method from [LoRA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/abs/2106.09685) as implemented in the [PEFT library by Hugging Face.](https://huggingface.co/blog/peft) For more about the PEFT library see my [Linkedin post here](https://www.linkedin.com/posts/mustafa-alturki-78b86812b_peft-parameter-efficient-finetuning-activity-7030157730652827648-rz1G?utm_source=share&utm_medium=member_desktop)
