Emotional Analyzer 🎭
A machine learning project to analyze and classify emotions from audio files into four categories: Euphoric, Joyful, Sad, and Surprised. The project leverages advanced audio processing techniques and deep learning models for accurate emotion recognition.

Features 🚀
Audio Feature Extraction: Key audio features are extracted using Librosa, including MFCCs, chroma features, and mel spectrograms, to capture the unique characteristics of each emotion.
Deep Learning Models: Implements models like:
Artificial Neural Networks (ANN)
Long Short-Term Memory Networks (LSTM)
Gated Recurrent Units (GRU)
Emotion Categories: Focused on analyzing and classifying four specific emotions:
Euphoric
Joyful
Sad
Surprised
Streamlined Workflow: From audio preprocessing to emotion prediction, the pipeline is designed for efficiency and modularity.
Workflow 📑
1. Data Preparation
Collects labeled audio data from publicly available datasets such as RAVDESS or TESS.
Organizes the dataset into training, validation, and test sets.
2. Feature Extraction
Extracts essential features using Librosa, including:
MFCC: Captures timbral information.
Chroma: Analyzes harmonic content.
Mel Spectrogram: Represents audio in a frequency-based format.
Additional features like Zero-Crossing Rate and Spectral Contrast.
3. Preprocessing
Normalizes extracted features for uniform scaling.
4. Model Training
ANN: Used as a baseline model to classify emotions.
LSTM: Explores temporal dependencies within the audio data.
GRU: Offers a computationally efficient alternative to LSTM while maintaining performance.
Models are trained using features extracted from the preprocessing step, with careful tuning of hyperparameters.
5. Evaluation
Analyzes model performance based on qualitative insights rather than numerical scores, focusing on how well the model differentiates between similar emotions like Euphoric and Joyful.
6. Prediction
Processes new audio files to predict the emotion category using the trained models.
