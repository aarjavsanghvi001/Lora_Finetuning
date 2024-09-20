# Lora_Finetuning

The project aims to fine-tune a pre-trained language model, TinyLlama-1.1B, to perform better on conversational tasks. Specifically, it leverages the Guanaco dataset, which contains human-generated responses to prompts, to enhance the model's ability to generate coherent and informative text in response to user queries.

Here's a breakdown of the key steps involved:

Data Loading: The Guanaco dataset is loaded, and the pre-trained model (TinyLlama-1.1B) and its corresponding tokenizer are initialized.
Inference: A sample prompt is passed to the model to demonstrate its initial capabilities.
Fine-Tuning: The model is fine-tuned using the LoRA (Low-Rank Adaptation) technique, which allows for efficient training while preserving the original model's parameters.
Training: The model is trained on the Guanaco dataset using specified training parameters.
Evaluation: The fine-tuned model is evaluated on the same prompt used earlier to assess the improvement in its responses.

Overall, this project demonstrates how to effectively fine-tune a language model for conversational tasks using a publicly available dataset and a parameter-efficient training technique.

Method adapted from: Machine Learning Warrior 
