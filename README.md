# Text Summarization with Transformers

## Introduction

In the Text-Summarisation-Lab01 notebook, we will embark on the task of dialogue summarization using generative AI models. Our focus will be on understanding the impact of different types of input text on the model's output and on the art of prompt engineering to steer the model towards our desired task.

Throughout this exploration, we will engage in a comparative analysis of zero-shot, one-shot, and few-shot learning approaches. This will enable us to grasp the subtleties of how various prompting techniques influence the generative capabilities of Large Language Models (LLMs).

## Experimentation
The model was tested with various prompts to evaluate the effectiveness of different learning approaches:

Zero-Shot Learning: The model generates a summary without any prior examples.
Single-Shot Learning: The model is given a single example to guide the summarization.
Few-Shot Learning: The model uses multiple examples to understand the summarization context better.

# Results
The summaries generated by the model were compared to baseline human summaries. This comparison was crucial in assessing the impact of different prompting strategies on the model's performance.

# Conclusion
The experiments with the T5 model showcased its versatility in handling various summarization tasks. Future work could involve exploring other models or fine-tuning the T5 on specific datasets for improved performance.
