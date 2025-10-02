The 🎶 Music Mood Classification project focuses on classifying songs into different moods using 🧠 machine learning and 🎧 audio feature analysis. Its goal is to automatically recognize the emotional category of a track based on its sound properties, which can be applied in playlist generation, recommendation systems, and even music therapy.

The project is built on the 📂 HWNAS Music Mood Classification Dataset from Kaggle, which contains WAV audio files organized into 14 moods: 😡 angry, 🌑 dark, ⚡ energetic, 🏔 epic, ✨ euphoric, 💎 glamorous, 😀 happy, 🕵 mysterious, 🌿 relaxing, ❤️ romantic, 😢 sad, 👻 scary, 💌 sentimental, and 🚀 uplifting. This diverse dataset enables the model to learn mood-related audio patterns across a wide range of emotions.

Using Librosa 🎵, the audio files are preprocessed and converted into numerical features such as MFCCs, spectral contrast, tempo, and energy. These extracted features are then used to train machine learning models that can predict the mood of unseen tracks.

The notebook walks through data preprocessing, feature extraction, model training, and evaluation 🔍. Metrics like accuracy, confusion matrices, and F1-scores help measure how well the models perform. Initial results are promising, showing that audio features are strong indicators of musical mood.

This work opens the door to future improvements, including 🎨 deep learning with spectrogram-based CNNs, ⏳ sequence models like RNNs, and 🚀 deployment as a real-time web app for mood-based music classification and recommendations.
