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
```plaintext
PredictingMissingStoryEndingsWithGenerativeAndClassificationModels.pdf
├── README.md
├── data
│   ├── ROCStories__spring2016 - ROCStories_spring2016.csv
│   ├── ROCStories_winter2017 - ROCStories_winter2017.csv
│   ├── cloze_test_test__spring2016 - cloze_test_ALL_test.csv
│   ├── cloze_test_test__winter2018-cloze_test_ALL_test.csv
│   ├── cloze_test_val__spring2016 - cloze_test_ALL_val.csv
│   ├── cloze_test_val__winter2018-cloze_test_ALL_val.csv
│   ├── combined_narrative_stories.csv
│   ├── generated_narratives_llama.csv
│   ├── generated_narratives_mistral.csv
│   └── sentences_with_labels.csv
├── notebooks
│   ├── ClassificationModel.ipynb
│   ├── CreateClassificationData.ipynb
│   ├── EDA.ipynb
│   ├── EvaluateBaseline.ipynb
│   ├── LlamaBaseline.ipynb
│   ├── MistralBaseline.ipynb
│   └── NovelClassificationModel.ipynb
└── results
    ├── NovelResults.csv
    ├── PredictingMissingStoryEndingsWithGenerativeAndClassificationModels.pptx
    ├── ProjectProposal.docx
    ├── bert_dense_classifier.png
    ├── class_distribution.png
    ├── model_flow_diagram.png
    ├── model_flow_no_dense_diagram.png
    └── results.csv
```

### Explanation of Folders:
- **data/**: Contains the datasets used in the project, including the original ROCStories datasets, narrative combinations, and labeled data.
- **notebooks/**: Jupyter notebooks for experimentation and analysis. Each notebook corresponds to a specific aspect of the project (e.g., baseline evaluation, exploratory data analysis).
- **results/**: Outputs, visualizations, and project artifacts such as generated results and model flow diagrams.
- **LICENSE**: The licensing information for this repository.
- **PredictingMissingStoryEndingsWithGenerativeAndClassificationModels.pdf**: The final paper for the project.
- **README.md**: This documentation file.
