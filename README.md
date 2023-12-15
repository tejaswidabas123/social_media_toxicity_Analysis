# Social Media Comment Toxicity Analysis

## Project Summary

**Title:** Social Media Comment Toxicity Analysis  
**Author:** Tejaswi LNU  


### Problem Statement

The rise of social media has led to increased instances of toxic behavior such as cyberbullying, harassment, hate speech, and misinformation. This project addresses the need to monitor and mitigate online toxicity, focusing on sentiment analysis to identify and classify toxic comments.

### Objective

Develop a highly accurate machine learning model using neural networks and NLP techniques to detect toxicity in social media comments. The model classifies comments like insult, obscene, or identity hate. The goal is to create a real-time tool to mitigate the negative impact of online toxicity.

### Dataset

Utilized a Kaggle dataset from the Jigsaw Toxic Comment Classification Challenge, containing comments labeled with toxicity indicators.

### Technology and Features

Implemented a deep learning model with a bidirectional LSTM-based neural network. Used tokenization and embedding for data preprocessing. The model architecture includes an embedding layer, bidirectional LSTM layer, dropout layer, and fully connected layers for feature extraction. Evaluated performance using metrics such as precision, recall, accuracy, AUC, binary accuracy, false positives, and false negatives.

### Applications

1. **Customer Service:** Automatically classify customer feedback for better response.
2. **Reputation Management:** Monitor brand reputation and respond to negative feedback.
3. **Product Development:** Analyze customer feedback for product improvement.
4. **Market Research:** Analyze opinions about competitors for a competitive advantage.

### Challenges

Online toxicity impacts mental health; thus, it's crucial to develop effective tools for monitoring and intervention. Challenges include adapting to evolving online behavior and balancing free speech with toxic content prevention.

### Results

The model achieved a precision of 0.932, recall of 0.733, accuracy of 0.4774, AUC of 0.9044, and binary accuracy of 0.987. Hyperparameter tuning showed improved accuracy with the Adgrad optimizer.

### Working Example

Designed a Gradio app for user input, allowing real-time predictions of comment toxicity categories. The model's predictions are based on probability thresholds.


### Conclusion

The bidirectional LSTM-based model demonstrates proficiency in detecting and classifying social media comment toxicity. Further refinement and optimization possibilities exist through exploring various hyperparameter combinations.

## YouTube URLs

- **Long Video:** [Link](https://youtu.be/E__XMcmGlek)
- **Short Video:** [Link](https://youtu.be/C8qLJJaKDUk)

---

**Feel free to add or modify any section based on your project's specific details.**
