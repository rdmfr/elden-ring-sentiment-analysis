# 🎮 Elden Ring Sentiment Analysis with BERT

This project performs sentiment analysis on player reviews of the game **Elden Ring** from Steam using a fine-tuned BERT (Bidirectional Encoder Representations from Transformers) model. The goal is to classify reviews into sentiment categories (Positive, Negative, Neutral) and analyze game aspects such as graphics, gameplay, difficulty, etc.

---

## 🧠 Features

- Fine-tuned BERT model on real Steam reviews
- Multi-aspect analysis (Graphics, Gameplay, Difficulty, etc.)
- Visualized results using charts
- Clean and modular Python code
- Google Drive integration for large model files

---

## 📁 Project Structure

elden-ring-bert/ ├── main.py # Main script to run sentiment analysis ├── model_bertu.pt # Fine-tuned BERT model (see below for download) ├── elden_ring_reviews.csv # Dataset of player reviews ├── requirements.txt # Required Python libraries └── README.md # Project documentation

yaml
Copy
Edit

---

## ⚙️ Installation

Make sure you have Python 3.8+ and install the required packages:
pip install -r requirements.txt

Or manually:

pip install torch transformers pandas matplotlib seaborn scikit-learn gdown

🚀 Usage
If model is present in your directory:

python main.py

If you don't have the model yet, download it from Google Drive (see below) and place it in the same folder.

💾 Download Model
Because GitHub limits files over 100MB, the trained model is stored on Google Drive :

📊 Example Output
Sentiment Distribution Pie Chart

Aspect Frequency Bar Chart

Confusion Matrix for Model Performance

🎓 Author
M. Fadhilatur Ramadhan
📍 Bandung, Indonesia
📧 082219077215
🔗 LinkedIn | GitHub

🏁 License
This project is open-source and available under the MIT License.

---
