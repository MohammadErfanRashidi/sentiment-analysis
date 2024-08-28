# sentiment-analysis
This project involves creating a sentiment analysis tool that classifies text into categories such as positive, negative, or neutral. You’ll use a dataset with labeled sentiments to train a model and then evaluate its performance.

## requirements

transformers==4.31.0

nltk==3.8.1

scikit-learn==1.3.0

pandas==2.0.3

numpy==1.25.2

matplotlib==3.7.2

seaborn==0.12.2

## Installation

1. **Create a virtual environment:** (Recommended)

2. **Install dependencies:**

## Usage

1. **Prepare your dataset:**
   - Replace `YourDataSet.csv` in the code with the path to your own dataset.
   - Replace `TestFile.txt` with the text file on which you want to do sentiment analysis.
   - Ensure your dataset has columns for sentiment labels and text.

2. **Run the notebook:**
   - Execute the code cells in the provided Jupyter Notebook.
  
3. **Results:**
   - Positive, negative, and neutral sentences will be stored in three different files.

## Components

- **Preprocessing:** Text is tokenized, lowercased, and stop words are removed.
- **TF-IDF Vectorization:** Converts text into numerical features.
- **Naive Bayes Classifier:** A traditional machine learning model for sentiment classification.
- **Transformer Model:** Utilizes a pre-trained sentiment analysis model from the Hugging Face Transformers library.

## Customization

- **Experiment with different classifiers:** Try other models like SVM or Logistic Regression.
- **Fine-tune the transformer model:** For improved performance, fine-tune the pre-trained model on your specific dataset.
- **Explore other NLP tasks:** Adapt the code for tasks like text classification or named entity recognition.
