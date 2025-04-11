# Multimodal Misinformation Detection using Large Vision-Language Models (2024)

## 📄 Paper
**Title**: Multimodal Misinformation Detection using Large Vision-Language Models  
**Authors**: Sahar Tahmasebi, Eric Muller-Budack, Ralph Ewerth  
**Link**: https://arxiv.org/abs/2407.14321

## 🧠 Summary
This paper investigates the effectiveness of large vision-language models (VLMs), particularly BLIP-2 and OpenFlamingo, for detecting misinformation across multiple modalities. The study explores both zero-shot and few-shot scenarios, analyzing how well these models can identify misleading content from social media posts that include both text and images.

## 📌 Key Contributions
- Provides a benchmark analysis of VLMs on multimodal misinformation detection tasks.
- Introduces a comprehensive evaluation across multiple VLM architectures and prompt strategies.
- Proposes a novel reasoning-based prompt to enhance model performance in zero-shot settings.

## 🔬 Methodology
- Models: BLIP-2, OpenFlamingo
- Input: Combined text and image from social media posts
- Evaluation: Zero-shot, few-shot, and chain-of-thought prompting strategies
- Tasks: Binary classification of posts as "Misinformation" or "Not Misinformation"

## 🔎 Relevance to My Work
- Offers strong baselines and evaluation design for detecting misinformation in political or deceptive ads.
- Supports the use of VLMs as a zero-shot/few-shot alternative for large-scale ad transparency analysis.
- Can help design better prompting strategies for real-world deployment of ad audits.

## 📊 Dataset & Performance
- Benchmarked on popular misinformation datasets (e.g., Twitter-based multimodal datasets).
- Results show that BLIP-2 outperforms OpenFlamingo on most tasks.
- Reasoning-based prompts significantly boost zero-shot accuracy.
