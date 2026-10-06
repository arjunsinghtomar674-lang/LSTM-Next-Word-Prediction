# LSTM Next Word Prediction

A simple **Next Word Prediction** project built using **Long Short-Term Memory (LSTM)** networks.

The model learns patterns from a text dataset and predicts the most likely next word based on the sequence of words given as input.

## 🚀 Project Overview

Next Word Prediction is a basic Natural Language Processing (NLP) task where a deep learning model predicts what word is most likely to come next in a sentence.

For example:

```text
Input:
"I love"

Prediction:
"machine"
```

The model is trained using an **LSTM neural network**, which is well suited for learning sequential patterns in text.

## 🧠 Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Natural Language Processing (NLP)
- LSTM
- Jupyter Notebook

## 🔄 Project Workflow

```text
Text Dataset
     ↓
Text Preprocessing
     ↓
Tokenization
     ↓
Create Input Sequences
     ↓
Padding
     ↓
LSTM Model
     ↓
Model Training
     ↓
Next Word Prediction
```

## 🏗️ Model Architecture

The project uses an LSTM-based neural network consisting of:

```text
Input Sequence
      ↓
Embedding Layer
      ↓
LSTM Layer
      ↓
Dense Layer
      ↓
Softmax
      ↓
Predicted Next Word
```

## 📚 How It Works

### 1. Text Preprocessing

The text data is cleaned and prepared before training.

### 2. Tokenization

Words are converted into numerical representations using a tokenizer.

Example:

```text
"I love machine learning"
```

can be converted into:

```text
[1, 2, 3, 4]
```

### 3. Sequence Creation

The model is trained using sequences of words.

Example:

```text
Input                  Target

I                      love
I love                 machine
I love machine         learning
```

### 4. LSTM Training

The sequences are passed through the LSTM network so that the model can learn relationships between words.

### 5. Prediction

After training, we provide a starting sequence and the model predicts the next word.

Example:

```text
Input:
"machine learning is"

Predicted:
"powerful"
```

## 💻 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/LSTM-Next-Word-Prediction.git
```

Move into the project directory:

```bash
cd LSTM-Next-Word-Prediction
```

Install the required libraries:

```bash
pip install tensorflow numpy pandas matplotlib
```

## ▶️ How to Run

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Then open the project notebook and run the cells sequentially.

## 📊 Results

The trained LSTM model can generate the most probable next word based on the input text sequence.

The project demonstrates the basic working of:

- NLP preprocessing
- Tokenization
- Sequence generation
- Word embeddings
- LSTM networks
- Text prediction

## 🎯 Learning Outcomes

Through this project, I learned:

- How text data is prepared for deep learning
- How tokenization works
- How input sequences are created
- How LSTM handles sequential data
- How word embeddings are used
- How a neural network can be used for text prediction

## 🔮 Future Improvements

- Train on a larger dataset
- Improve prediction accuracy
- Use Bidirectional LSTM
- Add multiple LSTM layers
- Build a web interface
- Deploy the model
- Experiment with GRU and Transformer-based models

## 👨‍💻 Author

**Arjun Singh Tomar**

---

⭐ If you find this project useful, consider giving the repository a star!
