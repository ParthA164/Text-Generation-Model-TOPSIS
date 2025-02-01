# TOPSIS Method for Selecting the Best Pretrained Model for Text Generation

### 1. Define Performance Metrics and Models

We are evaluating the following pretrained models: GPT-3, GPT-2, BERT, T5, and BART. The criteria for evaluation include:

- **Perplexity**: A lower value is better.
- **BLEU Score**: A higher value is better.
- **Inference Time**: A lower value is better.
- **Model Size**: A lower value is better for deployment.

Below is the data for each model:

| Model   | Perplexity | BLEU Score | Inference Time (s) | Model Size (MB) |
|---------|------------|------------|--------------------|-----------------|
| GPT-3   | 20         | 40         | 2                  | 3500            |
| GPT-2   | 30         | 35         | 1.5                | 1500            |
| BERT    | 25         | 30         | 0.8                | 1200            |
| T5      | 22         | 33         | 1.2                | 1100            |
| BART    | 28         | 37         | 1.0                | 1600            |


### 2. Python Code Implementation

We will use the TOPSIS method to evaluate the models based on the given criteria.
The process includes:
- Normalizing the decision matrix
- Calculating the weighted normalized decision matrix
- Determining ideal and negative ideal solutions
- Calculating performance scores
- Ranking the models


### 3. Output
![image](https://github.com/user-attachments/assets/7d970be5-ed8c-4088-ad42-71698b60dd97)

### 4. Rankings
   ![image](https://github.com/user-attachments/assets/ac4bed92-b9d3-4e6e-af95-adb984274574)

