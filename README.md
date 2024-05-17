# Sequence-to-sequence networks for multi-text document summarization on medical dataset

## Overview

This project explores the application of advanced sequence-to-sequence networks and transformer models for multi-text document summarization in the medical domain. Given the exponential growth of medical literature, efficiently summarizing this vast amount of information is crucial for healthcare professionals, researchers, and policymakers. Our research focuses on leveraging state-of-the-art natural language processing (NLP) techniques to generate concise, informative, and coherent summaries of medical documents.

## Project Objectives

- **Develop and fine-tune transformer models**: Utilize models such as BART, BERT, PEGASUS, and T5 for the task of summarizing biomedical research articles.
- **Evaluate model performance**: Assess the summarization quality using metrics like ROUGE to ensure the generated summaries are accurate and meaningful.
- **Address domain-specific challenges**: Tackle issues related to specialized medical terminology, document diversity, and the complexity of medical texts.

## Methodology

### Datasets


1. **CORD-19 Dataset**: A large collection of over 1,000,000 scholarly articles on COVID-19 and related coronaviruses, freely accessible to support NLP and AI research.

2. **Biomedical Abstracts Dataset**: A dataset from Hugging Face with 210,000 training abstracts and 45,000 each for validation and test sets, used for text summarization and NLP tasks.

### Models Implemented

- **BART (Bidirectional and Auto-Regressive Transformers)**
- **BERT (Bidirectional Encoder Representations from Transformers)**
- **PEGASUS**
- **T5 (Text-To-Text Transfer Transformer)**

### Evaluation Metrics

- **ROUGE (Recall-Oriented Understudy for Gisting Evaluation)**: Measures the quality of machine-generated summaries by comparing them to reference summaries, evaluating precision, recall, and F1-score.

## Implementation

1. **Data Preprocessing**: Tokenization and preparation of datasets for training.
2. **Model Training**: Fine-tuning pre-trained transformer models using the biomedical dataset.
3. **Evaluation**: Assessing model performance using ROUGE scores to ensure high-quality summarization.
4. **Summarization**: Generating summaries for biomedical research articles and evaluating them qualitatively.

## Results and Discussions

- **Performance**: The fine-tuned models demonstrated significant improvement in summarization quality compared to traditional methods. ROUGE scores indicated high precision, recall, and F1-score.
- **Challenges**: Handling domain-specific jargon and abbreviations, ensuring accurate and contextually relevant summaries.
- **Future Work**: Further fine-tuning, exploring hybrid models, and improving domain-specific summarization.
  ![image](https://github.com/Arjun-08/Sequence-to-sequence-networks-for-multi-text-document-summarization/assets/88790572/baf5d807-81e8-4422-95ae-14bf1e9bdf63)


## Repository Contents

- **BERT and BART-Dataset-1.ipynb**: Implementation notebook for BERT and BART models on Dataset-1.
- **BERT and BART-Dataset-2.ipynb**: Implementation notebook for BERT and BART models on Dataset-2.
- **Pegasusmodel-Dataset-1.ipynb**: Implementation notebook for PEGASUS model on Dataset-1.
- **Pegasusmodel-Dataset-2.ipynb**: Implementation notebook for PEGASUS model on Dataset-2.
- **T5-dataset-1.ipynb**: Implementation notebook for T5 model on Dataset-1.
- **T5_dataset-2.ipynb**: Implementation notebook for T5 model on Dataset-2.
- **Summarization-Project_Report.pdf**: Detailed project report.
- **PPT-summarization.pdf**: Presentation slides summarizing the project.
- **recorded-video-presentation.mp4**: Video presentation of the project.

## Conclusion

This project demonstrates the potential of transformer models in revolutionizing the summarization of biomedical texts. By effectively condensing vast amounts of information into coherent summaries, these models can significantly aid healthcare professionals, researchers, and decision-makers in staying updated with the latest developments in the medical field. The continued advancement and refinement of these models promise even greater contributions to the accessibility and dissemination of medical knowledge.

## PS 

For a more comprehensive explanation and understanding, please refer to the detailed project report and the recorded video presentation included in the repository.
## Contact

If you have any questions or suggestions, please feel free to reach out to me at [nvarjunmani07@gmail.com](mailto:nvarjunmani07@gmail.com).

