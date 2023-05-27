# financial-sentiment-classifier


Model_USE is a pre-trained NLP model to analyze the sentiment of financial or economic commentary, tweet, or news. It is built upon Universal Sentence Encoder (USE) and fine-tuned for financial sentiment classification purposes. Financial Phrasebank's 'agreeall' dataset was used for fine-tuning.
* To download : https://huggingface.co/dfavenfre/model_use
* Dataset: https://huggingface.co/datasets/financial_phrasebank/viewer/sentences_allagree/train


Example Prompt: 
"However, the Euro 7 proposal is simply not the right way to do this, as it would have an extremely low environmental impact at an extremely high cost."

Predictin Output:
[Negative: 0.99942374, Neutral: 0.00015279527, Positive: 0.00042358576]


# Model Architecture
![image](https://github.com/dfavenfre/financial-sentiment-classifier/assets/118773869/4cf2d695-22b8-4716-b8fa-ebeff29c0e31)
