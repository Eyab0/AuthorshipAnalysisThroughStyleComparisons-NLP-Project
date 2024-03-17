# Authorship Attribution Pipeline

This repository contains a comprehensive pipeline for authorship attribution implemented in a Jupyter Notebook format. The pipeline involves the following steps:

## 1. Data Collection

Authors' texts are collected from two datasets: "taamolat" and "alaraby."

## 2. Preprocessing

The collected texts undergo several preprocessing steps, including normalization, tokenization, stop word removal, and stemming.

## 3. Feature Extraction

Two types of features are extracted from the preprocessed texts:

- **TF-IDF features**: Representing the importance of words in each document using the Term Frequency-Inverse Document Frequency (TF-IDF) method.
- **Word Embedding features**: Using FastText to generate word embeddings, representing words as dense vectors.

## 4. Modeling

Several classification models are trained and evaluated using the extracted features:

- **Support Vector Machine (SVM)**
- **Logistic Regression**
- **Random Forest**
- **K-Nearest Neighbors (KNN)**
- **Multilayer Perceptron (MLP)**

## 5. Evaluation

The trained models are evaluated based on precision, recall, F1 score, and accuracy.

## 6. GUI Implementation

A graphical user interface (GUI) is created to input two texts and predict whether they are written by the same author or not using the trained models.

## 7. Interactive Testing

Users can input text samples into the GUI and select a model to predict the authorship of the texts.

## Usage

To use the authorship attribution pipeline in Google Colab:

1. Open the provided Jupyter Notebook (`authorship_attribution.ipynb`) in Google Colab.
2. Execute each cell in the notebook sequentially.
3. Follow the instructions in the notebook to interact with the pipeline.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Make your changes in the notebook.
3. Test your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to your forked repository.
6. Create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
