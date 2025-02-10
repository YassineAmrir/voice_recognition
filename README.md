Audio Classification: Crying vs. Laughing

📌 Project Overview

This project focuses on classifying audio files as either crying or laughing using machine learning techniques. The dataset consists of audio clips extracted from various sources, and the model is trained using MFCC features and a Random Forest Classifier.

🚀 Features

Preprocessing: Converts audio files into structured datasets.

Feature Extraction: Uses MFCC (Mel-Frequency Cepstral Coefficients).

Machine Learning Model: Trained using Random Forest Classifier.

High Accuracy: Achieves 98.22% accuracy on test data.

Tamazight Support: Displays output labels in Tamazight (Berber language).

📂 Dataset

The dataset consists of two categories:

Crying Sounds

Laughing Sounds

⚙️ Installation & Setup

1️⃣ Clone the Repository

 git clone https://github.com/yourusername/audio-classification.git
 cd audio-classification

2️⃣ Install Dependencies

pip install -r requirements.txt

3️⃣ Run Feature Extraction

python extract_features.py

4️⃣ Train the Model

python train_model.py

5️⃣ Test with a New Audio File

python predict.py --file sample.wav

📊 Model Performance

Metric

Score

Validation Accuracy

98.57%

Test Accuracy

98.22%

📜 How It Works

Extracts MFCC features from audio files.

Trains a Random Forest Classifier.

Saves the trained model using joblib.

Classifies new audio files as crying or laughing.

🎯 Example Usage

python predict.py --file test_audio.wav

💡 Output: "The sound is classified as Laughing (in Tamazight)"

📜 License

This project is licensed under the MIT License.

⭐ Contributing

Contributions are welcome! Feel free to submit a PR or open an issue.
