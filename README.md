# Hate Speech Detection using LSTM

## Overview
This project focuses on detecting hate speech and offensive language in text data using a deep learning model based on LSTMs (Long Short-Term Memory networks). The model is trained on a labeled dataset and can classify text into three categories:

- **Hate Speech**
- **Offensive Language**
- **Neither**

A user-friendly **Gradio** interface is provided for real-time text classification.

## Dataset
The model is trained on the **Hate Speech and Offensive Language Dataset** from Kaggle:
[Dataset Link](https://www.kaggle.com/datasets/mrmorj/hate-speech-and-offensive-language-dataset/data)

## Features
- ✅ LSTM-based deep learning model
- ✅ Preprocessing with text cleaning, tokenization, and padding
- ✅ SMOTE for handling imbalanced data
- ✅ Gradio-powered web interface for easy use
- ✅ Real-time hate speech detection

## Installation & Setup
### 1. Clone the repository:
```sh
git clone https://github.com/your-repo/hate-speech-detection.git
cd hate-speech-detection
```

### 2. Install dependencies:
```sh
pip install -r requirements.txt
```

### 3. Run the model training (optional if using a pre-trained model):
```sh
python train.py
```

### 4. Run the Gradio web interface:
```sh
python app.py
```

## Model Architecture
- **Embedding Layer** (Word embeddings with a vocabulary size of 10,000)
- **Stacked LSTMs** (100 → 50 → 32 units)
- **Dense Layer** (Softmax activation for classification)

## Usage
1. Enter a sentence in the Gradio UI.
2. Click **"Submit"**.
3. The model will classify the text as **Hate Speech, Offensive Language, or Neither**.

## Example Predictions
| Input Text | Prediction |
|------------|------------|
| "I hate all [group]!" | Hate Speech |
| "This is so dumb!" | Offensive Language |
| "Hope you have a great day!" | Neither |

## Future Improvements
- 🔹 Fine-tune the model with more diverse datasets.
- 🔹 Improve accuracy by experimenting with transformer-based models (BERT, RoBERTa).
- 🔹 Deploy the model as a web app using Flask or FastAPI.
  
---

## License
This project is open-source under the **MIT License**.

---

## 🤝 Contributing  
Contributions are welcome! If you find a bug or want to improve the model, feel free to open an issue or submit a pull request.  

---

## 📜 License  
This project is licensed under the **MIT License**.  

---

## 🔗 Connect  
📧 **Email:** [sommyajain2005@gmail.com](mailto:sommyajain2005@gmail.com)  
🌍 **GitHub:** [@iamsommyajain](https://github.com/iamsommyajain)  

---
🚀 **Let's make the internet a safer place!**

