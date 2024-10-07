### README

# Disaster Tweet Classification using RNN

This project builds a Recurrent Neural Network (RNN) model to classify tweets as disaster-related or not. The model is trained on a labeled dataset of tweets and uses various Keras components to preprocess the data, train the model, and evaluate its performance.

## Project Structure
- **Data Preparation**: Loading and cleaning of the text data, including removing URLs, mentions, and stopwords.
- **Exploratory Data Analysis**: Visualization of target distribution and tweet lengths.
- **Model Architecture**: An RNN model with embedding, LSTM layers, and dropout for regularization.
- **Training**: Model training with callbacks for checkpointing, early stopping, and learning rate reduction.
- **Evaluation**: Confusion matrix and F1 score for model performance.

## Dependencies
- Python (3.x)
- TensorFlow & Keras
- Pandas, NumPy
- NLTK
- Matplotlib

## Usage
1. **Preprocess Data**: Run data cleaning and exploratory steps.
2. **Train Model**: The model is trained on cleaned text data and evaluates on a validation set.
3. **Predict**: Use the trained model to classify unseen tweets and generate predictions.

## Files
- **`train.csv`**: Training data.
- **`test.csv`**: Test data for predictions.
- **`disaster_tweet_model.keras`**: Trained model file.
- **`submissions.csv`**: Prediction output.

This README gives a concise overview. Let me know if you want any specific details added.