# DeepSentiment: IMDb Movie Review Sentiment Analysis

## Overview

DeepSentiment is a deep learning-based sentiment analysis project designed to classify movie reviews from the IMDb dataset as positive or negative. The model leverages a Bidirectional Long Short-Term Memory (LSTM) network with a self-attention mechanism to capture both the sequential dependencies and contextual relationships within the text.

## Key Features

*   **State-of-the-Art Architecture:** Utilizes a powerful combination of Bidirectional LSTM and self-attention, known for its effectiveness in natural language processing tasks.
*   **High Accuracy:** Achieves an impressive 89.26% accuracy on the IMDb test set, demonstrating strong performance in sentiment classification.
*   **Open to Contributions:**  Contributions from the community are welcome to further enhance and improve the model.

## Getting Started

1.  **Clone the Repository:**

    ```bash
    git clone [https://github.com/](https://github.com/)tafartech/DeepSentiment.git
    cd DeepSentiment
    ```

2.  **Install Dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

3.  **Download the IMDb Dataset:** (If not already included)

    ```bash
    python download_imdb.py  
    ```

4.  **Train the Model:**

    ```bash
    python train.py
    ```

5.  **Evaluate the Model:**

    ```bash
    python evaluate.py
    ```

## Results

The trained model achieves an accuracy of 89.26% on the IMDb test set. You can find the confusion matrix and classification report in the `results` Output.

## Call for Contributions

Some areas where you can help:

*   **Hyperparameter Tuning:** Explore different configurations to find optimal values for learning rate, batch size, and model architecture parameters.
*   **Regularization Techniques:** Experiment with L2 regularization, additional dropout layers, or other methods to address the slight overfitting observed in the validation loss.
*   **Alternative Architectures:** Try implementing different neural network architectures like Convolutional Neural Networks (CNNs) or incorporating pre-trained word embeddings like GloVe or Word2Vec.
*   **Ensemble Methods:** Investigate the use of ensemble learning techniques to combine multiple models and potentially achieve higher accuracy.

## Contributing

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/your-feature-name`).
3.  Make your changes and commit them (`git commit -m 'Add your feature'`).
4.  Push to the branch (`git push origin feature/your-feature-name`).
5.  Open a pull request.

Let's collaborate to make DeepSentiment even better.
