# EXP-1-PROMPT-ENGINEERING-
## NAME: Sreenithi
## REG NO: 212223220109
## Aim: 
Comprehensive Report on the Fundamentals of Generative AI and Large Language Models (LLMs)
## Experiment: 
Develop a comprehensive report for the following exercises:

Explain the foundational concepts of Generative AI.
Focusing on Generative AI architectures. (like transformers).
Generative AI applications.
Generative AI impact of scaling in LLMs.

## Algorithm:
Data Preparation : The first step is to collect and clean a large dataset, removing duplicates, errors, and sensitive data. The cleaned text is then tokenized into subword units so the model can process language efficiently.

Model Setup : A Transformer-based architecture is defined with layers, attention heads, and embedding sizes. The weights are initialized, and hyperparameters such as learning rate, batch size, and optimizer are chosen.

Training : During training, tokenized sequences are converted into embeddings and passed through self-attention and feed-forward layers. The model predicts the next token, calculates cross-entropy loss, and updates weights using gradient descent until it learns language patterns.

Fine-Tuning & Alignment : After pretraining, the model is fine-tuned with curated instruction–response datasets. Alignment methods like Reinforcement Learning with Human Feedback (RLHF) or Direct Preference Optimization (DPO) ensure the outputs are helpful, safe, and aligned with user expectations.

Inference : When deployed, the model takes a user prompt, encodes it, and generates text using decoding methods such as greedy search, top-k sampling, or nucleus sampling to balance fluency and creativity.

Evaluation & Deployment : The model is tested with metrics like perplexity, BLEU, or human evaluation to measure accuracy, usefulness, and safety. Once validated, it is deployed with guardrails, monitoring systems, and filters to ensure reliable and responsible usage.

## Output
[PROMPT EX1 PDF(1).pdf](https://github.com/user-attachments/files/22099894/PROMPT.EX1.PDF.1.pdf)

## Result
The experiment showed that prompt design greatly improves the quality of outputs from LLMs. It successfully demonstrated Generative AI concepts, architectures, applications, and scaling impacts.

