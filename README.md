# AI-Generated Text Detection: A Data-Driven Approach

## Project Overview

This project addresses the challenge of distinguishing between AI-generated and human-written text using various machine learning techniques. As AI language models become increasingly sophisticated, the ability to detect AI-authored content is crucial for maintaining academic integrity, combating misinformation, and ensuring authenticity in digital communications.

## Key Features

- Utilizes both TF-IDF and Count Vectorization for text preprocessing
- Implements and compares multiple classification algorithms:
  - Support Vector Machines (SVM)
  - Multinomial Naive Bayes
  - Logistic Regression
  - Random Forest
  - XGBoost
  - Neural Networks (2-layer architecture)
- Comprehensive evaluation using accuracy, precision, F1-score, and recall metrics
- Hyperparameter tuning for optimal model performance

## Dataset

The project uses the "Augmented data for LLM - Detect AI Generated Text" dataset from Kaggle, comprising 433,564 instances (277,999 human-written essays and 155,565 AI-generated texts).

## Methodology

1. Data preprocessing using TF-IDF and Count Vectorization
2. Implementation of various classification algorithms
3. Hyperparameter tuning for each model
4. Performance evaluation using multiple metrics
5. Comparison of model performances and preprocessing techniques

## Results

- Neural Network model outperformed other classifiers with 99.1% accuracy (CountVectorizer) and 98.9% accuracy (TF-IDF)
- Logistic Regression and Random Forest models showed consistently high performance
- XGBoost demonstrated excellent results, especially with CountVectorizer
- SVM and Multinomial Naive Bayes classifiers exhibited lower performance

## Future Work

1. Explore advanced neural network architectures (CNNs, LSTMs)
2. Extend classification capabilities to multilingual text
3. Perform more extensive hyperparameter tuning using grid search and Bayesian optimization
4. Implement a pipeline for real-time data processing and prediction
5. Test models against AI-synthesized texts from tools like Gemini, ChatGPT, and Claude

## Ethical Considerations

- Privacy concerns regarding dataset origins
- Potential for false positives and bias in model predictions
- Importance of model transparency and explainability

## Contributors

- Sagar Swami Rao Kulkarni
- Anirudh Prashant Kalghatkar
- Pavan Sai Appari
- Sachin Kashinath Rathod
- Nihal Srinivasu

## References

1. Mitchell, Eric, et al. "Detectgpt: Zero-shot machine-generated text detection using probability curvature"
2. Soto, Rafael Rivera, et al. "Few-Shot Detection of Machine-Generated Text using Style Representations."
3. Mohammed, Ammar, and Rania Kora. "An effective ensemble deep learning framework for text classification."
4. Zulqarnain, M., et al. "A comparative review on deep learning models for text classification."
5. Brundage, Miles, et al. "The malicious use of artificial intelligence: Forecasting, prevention, and mitigation."

For more detailed information about the project, including methodology, results, and future work, please refer to the full project report.
