---
layout: page
permalink: /homework/
title: Homework Assignments
---

<h1>Homework 2</h1>

The homework has two parts.

Please download the files from the following link: [Download](https://yaleedu-my.sharepoint.com/:f:/g/personal/arman_cohan_yale_edu/ElymUHe0slZAjMIzNa0ULlEBH6FbxXbdmjIMP8wrTn_NmQ?e=8i0a4U)

<h3> Prompting and in-context learning </h3>

This part focuses on in-context learning using an open-source Large Language Model.  
You will be working with Mistral-7B-0.1, a recently-released large language model, with the goal of finding a prompting technique that causes the model to obtain the best performance on [GSM8K, a dataset of middle-school-level mathematics word problems](https://github.com/openai/grade-school-math).

<h3> Parameter-efficient finetuning using IA3 </h3>

In this focuses on the [IA3](https://arxiv.org/pdf/2205.05638.pdf) algorithm for parameter-efficient fine-tuning (PEFT).  
You will be using the HuggingFace Transformers library to fine-tune a pre-trained model on the XSum dataset for abstractive summarization.
The goal is to compare the performance of the IA3 PEFT method with the baseline full fine-tuning approach.

<h1>Homework 1</h1>

This homework has two parts. One hand out and one coding section.  
Download the homework from the following link: [[Download]](https://yaleedu-my.sharepoint.com/:f:/g/personal/arman_cohan_yale_edu/EqPjfvJErIRAoxY17U94Nr0BOCFBE18f4JXkGXWMwE9Khg?e=q09aE5)

For each part instructions are in the file.


Files:  
```
- CPSC_488_Fall_2023_HW_1.pdf   # the handout
- tensor.py                     # implementing auto differentiation and back propagation
- tokenizer.py                  # implementing a tokenizer
- transformer.ipynb                # implementing GQA
- tokenizer_test.py             # test file for tokenizer
- tensor_test.py                # test file for the tensor implementation
```

For the handout, complete the solutions in latex and return the pdf file.

For the tensor.py and tokenizer.py file, the instructions are in the file.

The transformer.ipynb also includes detailed instructions. 

You can submit the assignment in a zip file with the following format:
`lastname-firstname-hw1.zip`.

Rubric:
- Handout: 30 points (each Q gets 6 points)  
- Backpropagation: 20 points  
- Tokenizer: 40 points  
- Transformer GQA: 10 points  

<!-- - [Homework 1](https://piazza.com/cmu/fall2019/10703/resources): Due by Friday, 20<sup>th</sup> September 2019. -->
