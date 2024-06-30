# Automating the Cybersecurity Triage Process: A Comparative Study on the Performance of Large Language Models

### Abstract
Security analysts have the task of inspecting cybersecurity alarms to filter false positives and identify their severity: triage.
The problem with this process is that it is complicated and time-consuming, limiting the depth and speed of investigations.
Whereas other proposed optimizations and automations appear to be very promising, rapid advancements in the development of Large Language Models (LLMs) opened up new possibilities to speed up parts of the triage process that previously required human judgment.
This research aims to identify ways in which LLMs can optimize triage, evaluate the performance of these techniques and offer a comparison between different LLMs including GPT-4, Aya, Code Llama, Gemma, Llama 3, Mistral and Phi-3.
The study shows that GPT-4 is the most capable model, while Llama 3 and Mistral achieve competitively similar results.
The findings in this study are expected to help security teams make informed implementation decisions when optimizing the triage process.

### Scripts, Prompts and Data
The Jupyter Notebook is available in [dataNscripts/llm-triage-automation.ipynb](./dataNscripts/llm-triage-automation.ipynb).
The used data and prompts are available in [dataNscripts/data](./dataNscripts/data).
The Enron email dataset is excluded due to its size, it is available [here](https://www.loc.gov/item/2018487913/).
