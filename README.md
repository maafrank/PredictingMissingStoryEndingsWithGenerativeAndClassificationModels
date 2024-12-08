# PredictingMissingStoryEndingsWithGenerativeAndClassificationModels
MIDS w266 NLP Final Project

This repository contains the code and resources for the paper titled *Predicting Missing Story Endings with Generative and Classification Models*. The project explores the challenge of completing the final sentence of a five-sentence story using generative models combined with classification-based evaluation.

## Key Features:
- **Generative Models:** Mistral-7B-Instruct and Llama-3.1-8B-Instruct for sentence generation.
- **Classification Model:** Fine-tuned BERT-based model to evaluate generative outputs.
- **Dataset:** ROCStories, a benchmark for commonsense reasoning and narrative comprehension.
- Visualizations for model flow and dataset distributions.

## Results:
- Generative models: Mistral scored higher than Llama (cosine similarity: 0.4378 vs. 0.4284).
- Classification accuracy: The BERT model achieved 63%.
- Experimented with additional dense layers on BERT, but saw no significant improvement.

## Getting Started:
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/PredictingMissingStoryEndingsWithGenerativeAndClassificationModels.git
```
