# *Audio Classification: Crying vs. Laughing*

## 📌 **Project Overview**

This project focuses on classifying audio files as either crying or laughing using machine learning techniques. The dataset consists of audio clips extracted from various sources, and the model is trained using MFCC features and a Random Forest Classifier.

## 🚀 **Features**

Preprocessing: Converts audio files into structured datasets.

Feature Extraction: Uses MFCC (Mel-Frequency Cepstral Coefficients).

Machine Learning Model: Trained using Random Forest Classifier.

High Accuracy: Achieves 98.22% accuracy on test data.

Tamazight Support: Displays output labels in Tamazight (Berber language).

## 📂 **Dataset**

The dataset consists of two categories:

Crying Sounds

Laughing Sounds

## ⚙️ **Installation & Setup**

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

## 📊 **Model Performance**

| Metric               | Score  |
|----------------------|--------|
| Validation Accuracy | 98.57% |
| Test Accuracy      | 98.22% |


## 📜 **How It Works**

Extracts MFCC features from audio files.
Breakdown of the 13 MFCC Features:
MFCC 1 (Overall spectral energy) – Represents the total energy of the signal.
MFCC 2 (Spectral tilt) – Captures the general slope of the spectrum, related to vocal effort.
MFCC 3 (Formant structure) – Helps capture the resonance frequencies (formants) of speech.
MFCC 4 (Balance between low and high frequencies) – Distinguishes between sharp and flat sounds.
MFCC 5 (Spectral variations) – Captures detailed changes in the spectral envelope.
MFCC 6 (Nasality information) – Helps differentiate nasal sounds from non-nasal sounds.
MFCC 7 (Vowel/consonant distinction) – Aids in distinguishing between vowel and consonant sounds.
MFCC 8 (Speech articulation details) – Captures subtle changes in pronunciation.
MFCC 9 (High-frequency formants) – Helps detect formants at higher frequencies.
MFCC 10 (Pitch and tone variations) – Related to voice intonation and emotion.
MFCC 11 (Harmonic-to-noise ratio) – Helps distinguish voiced and unvoiced sounds.
MFCC 12 (Speaker identity features) – Often used for speaker recognition.
MFCC 13 (Residual spectral energy) – Captures the fine details of the sound signal.

Trains a Random Forest Classifier.

Saves the trained model using joblib.

Classifies new audio files as crying or laughing.

## 🎯 **Example Usage**

python predict.py --file test_audio.wav

💡 Output: "The sound is classified as Laughing (in Tamazight)"

## 📜 **License**

This project is licensed under the MIT License.
