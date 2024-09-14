# fintech-chatbot-t5

## Model Description
This model was fine-tuned using a [retail banking chatbot dataset](https://huggingface.co/datasets/bitext/Bitext-retail-banking-llm-chatbot-training-dataset/tree/main). It is based on the T5-small architecture and is capable of answering common banking-related queries like account balances, transaction details, card activations, and more.

The model has been trained to generate responses to banking-related customer queries and is suited for use in automated customer service systems or virtual assistants.

## Model Details
- **Model Type:** T5-small
- **Training Dataset:** [retail banking chatbot dataset](https://huggingface.co/datasets/bitext/Bitext-retail-banking-llm-chatbot-training-dataset/tree/main)
- **Tasks:** Natural Language Generation (NLG)
- **Languages Supported:** English

## Training Details
- **Number of Epochs:** 3
- **Training Loss:** 0.79
- **Evaluation Loss:** 0.46
- **Evaluation Metric:** Mean Squared Error
- **Batch Size:** 8
