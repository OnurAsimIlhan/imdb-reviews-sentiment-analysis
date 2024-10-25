# IMDB Movie Review Sentiment Analysis
## Description
This project uses a pre-trained Recurrent Neural Network (RNN) model to classify IMDB movie reviews as positive or negative. The model is integrated into a Streamlit web application for easy user interaction.

## Streamlit Deployment

The application is deployed using Streamlit. You can access it without running the code locally by visiting the following link:

[Streamlit App](https://imdb-reviews-sentiment-analysis-amvnee5h4m7jkcqesvgdvn.streamlit.app/)

## Setup (if you want to run locally)

1. **Clone the repository**:
    ```sh
    git clone https://github.com/OnurAsimIlhan/imdb-reviews-sentiment-analysis.git
    cd imdb-reviews-sentiment-analysis
    ```

2. **Create a virtual environment**:
    ```sh
    python3 -m venv venv
    source venv/bin/activate
    ```

3. **Install the required packages**:
    ```sh
    pip install -r requirements.txt
    ```

4. **Download the pre-trained model**:
    Place the `simple_rnn_imdb.h5` file in the project directory.

## Usage

1. **Run the Streamlit app**:
    ```sh
    streamlit run main.py
    ```

2. **Interact with the app**:
    - Open your web browser and go to `http://localhost:8501`.
    - Enter a movie review in the text area.
    - Click the 'Classify' button to see the sentiment analysis result.
