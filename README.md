## Creating AI project
- **Model**: `distilbert-base-uncased` (Transformer from Hugging Face)
- **Input**: User prompt (text)
- **Output**: Class label → `0 = safe`, `1 = unsafe`
- **Dataset**: [Civil Comments](https://huggingface.co/datasets/civil_comments) → converted into binary labels using a threshold on toxicity scores (`>= 0.5 = unsafe`)
- **Training**: Fine-tuned using Hugging Face `Trainer` API
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1 Score
- **Optional**: OpenAI Moderation API used as a second layer of classification

# How to run

- Clone the project using these urls

- HTTPS: https://github.com/prateekshaec/AI-Project.git
- SSH: git@github.com:prateekshaec/AI-Project.git

- Select the python environment or create the enivironment if its not exist