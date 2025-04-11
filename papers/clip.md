# CLIP (Radford et al., 2021)

## 📄 Paper
**Title**: Learning Transferable Visual Models From Natural Language Supervision  
**Link**: https://arxiv.org/abs/2103.00020  
**Code**: https://github.com/openai/CLIP

## 🧠 Summary
CLIP is trained to match images and their textual descriptions using contrastive learning over 400M web-curated (image, text) pairs. It encodes both modalities into a joint space where semantically similar pairs are close.

## 📌 Key Contributions
- Unified image-text representation space
- Enables zero-shot classification and retrieval
- Requires no task-specific fine-tuning

## 🔬 Architecture
- Vision Encoder: ResNet or ViT
- Text Encoder: Transformer
- Loss: Contrastive InfoNCE

## 🔎 Relevance to My Work
- CLIP can detect semantic inconsistencies in political ads between text and visuals
- Useful for building a zero-shot detector of deceptive ads

## 📊 Results
- Outperforms many supervised models on benchmarks without fine-tuning
