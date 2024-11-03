# Improving Dialogue Summarization and Ethical AI Responsiveness

This project enhances dialogue summarization and ethical responsiveness in AI using Large Language Models (LLMs), specifically fine-tuning Google's FLAN-T5 model. Our approach leverages Proximal Policy Optimization (PPO) and Reinforcement Learning with Human Feedback (RLHF) to align AI responses with ethical standards and human preferences.

# Key Features

* Fine-Tuning with DialogSum: Trained on the DialogSum dataset for improved summarization, capturing conversational intent and sentiment.
* Detoxification with Reward Models: Uses Facebook’s Detox model to ensure responses are safe and non-toxic.
* RLHF for Ethical Alignment: RLHF fine-tuning ensures that generated summaries are empathetic, safe, and aligned with human values.


# Technical Details
* Model: FLAN-T5 (Google’s instruction-based LLM extension of T5).
* Training Methods: Self-supervised learning for pre-training, RLHF and PPO for ethical fine-tuning.
* Key Dataset: DialogSum, which includes human-annotated summaries covering diverse dialogue types.
Usage
* Setup: Clone the repository and install dependencies.

# Model Training: Follow the scripts to fine-tune FLAN-T5 using RLHF with PPO.
* Evaluation: Compare generated summaries to ensure ethical alignment and summarization quality.
  
# Future Scope
Direct Preference Optimization (DPO): Exploring user-driven optimization to further improve human-aligned responses.
