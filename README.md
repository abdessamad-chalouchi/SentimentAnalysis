# Aspect Categorization Model using Convolutional Neural Networks (CNNs)

This project implements a text classification model for aspect categorization using Convolutional Neural Networks (CNNs). The model aims to classify product aspects based on user reviews. It utilizes pre-trained GloVe word embeddings and Keras for model construction and training.

## Key Features:

- Data preprocessing including tokenization and padding of word embeddings.
- Hyperparameter tuning to optimize the model architecture.
- Training and evaluation of the model with accuracy and F1-score as performance metrics.
- Visualization of training history to monitor model performance and potential overfitting.

## Dependencies:

- Python 3.x
- pandas
- nltk
- gensim
- keras
- scikit-learn
- tensorflow
- matplotlib

## How to Use:

1. Clone the repository to your local machine.
2. Install the dependencies listed in the `requirements.txt` file using `pip install -r requirements.txt`.
3. Download the GloVe word embeddings and the dataset (`PRODUCTS.data`) and place them in the project directory.
4. Run the provided Python scripts to preprocess the data, train the model, and evaluate its performance.
5. Customize the hyperparameters, model architecture, or data preprocessing steps as needed for your specific use case.

## Contributors:

- Chalouchi Abdessamad

## License:

This project is licensed under the [MIT License](LICENSE).
