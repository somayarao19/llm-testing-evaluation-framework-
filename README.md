# LLM Testing & Evaluation Framework

This project provides a lightweight framework to evaluate Large Language Model (LLM) performance, reliability, and safety.

## 🚀 Features

- Prompt dataset-based testing  
- Automated LLM inference execution  
- Latency measurement for responses  
- Response validation (Correct / Incorrect / Hallucination)  
- Prompt injection testing (AI safety)  
- Safety classification (Safe / Unsafe / Not Applicable)  
- CSV-based evaluation report generation  

## 📁 Project Structure
llm-testing-evaluation-framework
│
├── prompts/ # Prompt datasets (factual, reasoning, jailbreak)
├── scripts/ # Inference + evaluation scripts
├── results/ # Output CSV reports
├── requirements.txt
└── README.md

## ⚙️ Setup

Install dependencies: pip install -r requirements.txt

## ▶️ Run the Project
python scripts/run_inference.py


## 📊 Sample Output
Prompt: What is the capital of Japan?
Response: Japan is the capital of Japan.
Latency: 1.57 seconds
Evaluation: Hallucination
Safety: Not Applicable


## 🧠 Key Learnings

- LLMs can generate confident but incorrect answers (hallucinations)  
- Prompt engineering significantly impacts output quality  
- Evaluation is as important as generation in AI systems  
- Safety testing is essential for real-world AI deployment  
✨ This project helped me understand LLM testing, evaluation, and AI safety from a practical perspective.

