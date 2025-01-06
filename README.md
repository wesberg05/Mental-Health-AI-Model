# Mental Health AI Model

This repository contains a **Mental Health AI Model** built using the `FLAN-T5` transformer model. The chatbot is fine-tuned on a dataset of counseling conversations to provide empathetic and contextually relevant responses to client concerns. The project is designed to aid in mental health support by generating meaningful conversations.

---
## Disclaimer
 - This chatbot is a research project and not a substitute for professional mental health support. For urgent or serious concerns, please seek help from qualified professionals.

## Features

- **Fine-Tuned Transformer Model**:
  - Built on [Google's FLAN-T5](https://huggingface.co/google/flan-t5-small).
  - Specifically adapted to mental health counseling dialogues.

- **Dataset**:
  - Based on the `Amod/mental_health_counseling_conversations` dataset.
  - Contains structured input (`Context`) and target (`Response`) pairs.

- **Deployment**:
  - Model is hosted on [Hugging Face Hub](https://huggingface.co/wesberg05/MentalHealthChatbot) for easy accessibility.
  - Uses the Hugging Face `pipeline` for real-time inference.
