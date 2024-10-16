# 🌟 Generative AI Use Case: Summarize Dialogue 🌟

Welcome to the Generative AI Dialogue Summarization lab! 🎉 In this project, you'll dive deep into using generative AI to create meaningful dialogue summaries. The focus here is prompt engineering — shaping how input text influences the model's output.

## 💡 By comparing zero shot, one shot, and few shot inferences, you'll gain insight into how crafting prompts can improve the performance of Large Language Models (LLMs).
📋 Table of Contents

    ⚙️ Set up Kernel and Required Dependencies
    ✍️ Summarize Dialogue without Prompt Engineering
    🔧 Summarize Dialogue with an Instruction Prompt
    3.1. 🎯 Zero Shot Inference with an Instruction Prompt
    3.2. 📜 Zero Shot Inference with the Prompt Template from FLAN-T5
    🎓 Summarize Dialogue with One Shot and Few Shot Inference
    4.1. 📍 One Shot Inference
    4.2. 🔄 Few Shot Inference
    ⚡️ Generative Configuration Parameters for Inference

## 🔍 Overview

In this project, you’ll summarize dialogues using LLMs and experiment with prompt engineering to make the output even better. Here are some things you'll discover:

    🔧 The difference between Zero Shot, One Shot, and Few Shot inferences.
    📝 How prompt design can influence generative AI models.
    🔄 Comparing results across different inference strategies and configurations.

## 🌐 Key Sections
### 1. ⚙️ Set up Kernel and Required Dependencies

Before you start, make sure your environment is ready to go! This section walks you through setting up the necessary libraries and selecting the appropriate kernel.
### 2. ✍️ Summarize Dialogue without Prompt Engineering

Start by generating dialogue summaries without giving the model any specific instructions. This serves as a baseline to compare how adding prompts can improve the output.
### 3. 🔧 Summarize Dialogue with an Instruction Prompt

Here’s where the magic happens! ✨ By giving the model clear instructions, you'll steer it towards better summaries:

    Zero Shot Inference with an Instruction Prompt: Generate summaries without providing examples.
    Zero Shot Inference with FLAN-T5 Prompt Template: Use a predefined prompt template to guide the model.

### 4. 🎓 Summarize Dialogue with One Shot and Few Shot Inference

Take it up a notch:

    One Shot Inference: Provide the model with a single example to improve its output.
    Few Shot Inference: Supply multiple examples to fine-tune the model’s performance even further.

### 5. ⚡️ Generative Configuration Parameters for Inference

Explore different parameters such as temperature, top-p, and max token length to fine-tune your AI model and get the best possible summaries.
🚀 How to Run

    Clone the repository to your local machine:

    

git clone <repository-link>

Install the required dependencies:



    pip install -r requirements.txt

    Run the Jupyter notebook or the provided script to follow along with the lab instructions.

## 🛠️ Example Command

To download the lab contents, including notebooks and data files, run:


    aws s3 cp --recursive s3://dlai-generative-ai/labs/w1-549876/ ./

This command fetches all the required materials for the lab and places them in your local directory.

Happy coding and enjoy your journey with Generative AI! 🚀
