# Predicting Missing Story Endings With Generative And Classification Models
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


## Directory Structure

### Explanation of Folders:
- **data/**: Contains the datasets used in the project, including the original ROCStories datasets, narrative combinations, and labeled data.
- **notebooks/**: Jupyter notebooks for experimentation and analysis. Each notebook corresponds to a specific aspect of the project (e.g., baseline evaluation, exploratory data analysis).
- **results/**: Outputs, visualizations, and project artifacts such as generated results and model flow diagrams.
- **LICENSE**: The licensing information for this repository.
- **PredictingMissingStoryEndingsWithGenerativeAndClassificationModels.pdf**: The final paper for the project.
- **README.md**: This documentation file.

### How to Use:
1. Explore **data/** to view the datasets used in training and evaluation.
2. Use **notebooks/** for step-by-step workflows and analyses.
3. Refer to **results/** for final outputs, visualizations, and presentations.

---

This structure keeps it neat and organized, while providing clear guidance to users exploring the repository.
