# 📰 BBC News Classification NLP Application 🚀

Welcome to the **BBC News Classification** project! This Natural Language Processing (NLP) application classifies BBC news articles into various genres such as **Sports**, **Politics**, **Entertainment**, **Business**, and **Technology**. Utilizing powerful models like **LSTM (Long Short-Term Memory)** and **GRU (Gated Recurrent Unit)**, our application achieves an impressive accuracy of **~94%**. 🎯

---

## 📑 Table of Contents

- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Demo](#demo)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## 🧐 Introduction

In the **BBC News Classification** project, our goal is to accurately categorize BBC news articles into distinct genres using advanced NLP techniques. By training **LSTM** and **GRU** models on a labeled dataset, the application learns to identify patterns and features unique to each genre. Once trained, these models can predict the genre of new, unseen articles with high reliability. 📈

---

## 🛠️ Technologies Used

- **Python** 🐍
- **Regular Expressions (re)** 🔍
- **NumPy** ➗
- **Pandas** 📊
- **Scikit-Learn** 🧠
- **TensorFlow** 🤖
- **Keras** 🏗️
- **HuggingFace Transformers** 🔄
- **Streamlit** 🌐

---

## 💾 Installation

Follow these steps to set up the project locally:

1. **Install `virtualenv`** (if not already installed):

   ```bash
   pip install virtualenv
   ```

2. **Create a Virtual Environment**:

   Create a new virtual environment. You can name it as you prefer; here, we'll use `bbc-news-classification-venv`:

   ```bash
   virtualenv bbc-news-classification-venv
   ```

3. **Activate the Virtual Environment**:

   - **Windows**:

     ```bash
     bbc-news-classification-venv\Scripts\activate
     ```

   - **macOS/Linux**:

     ```bash
     source bbc-news-classification-venv/bin/activate
     ```

4. **Clone the Repository**:

   Clone the repository into the directory where you created the virtual environment:

   ```bash
   git clone https://github.com/alphatechlogics/Text-Classification.git
   ```

5. **Navigate to the Project Directory**:

   ```bash
   cd BBCNewsClassifier
   ```

6. **Install Project Requirements**:

   Install all necessary dependencies using `pip`:

   ```bash
   pip install -r requirements.txt
   ```

7. **Run the Application**:

   Launch the Streamlit application:

   ```bash
   streamlit run src/app.py
   ```

8. **Deactivate the Virtual Environment**:

   After you're done, deactivate the environment:

   ```bash
   deactivate
   ```

---

## 🎮 Usage

Once the application is up and running, access it through your web browser using the URL provided in the terminal (usually [http://localhost:8501](http://localhost:8501)).

1. **Enter Text**: Input the content of a BBC news article into the text area provided.

2. **Select Model**: Choose between the **LSTM** or **GRU** model for classification. You can also select both to get an averaged prediction.

3. **Submit**: Click the **Submit** button to classify the article.

4. **View Results**:
   - **Predicted Category**: Displays the genre the article belongs to.
   - **Prediction Score**: Shows the confidence level of the prediction.
   - **Prediction Plot**: Visualizes the prediction scores across different genres.

---

## 📽️ Demo

![BBC News Classification Demo](Screenshots/DemoV.webm)

_Demo of the BBC News Classification application in action._

---
