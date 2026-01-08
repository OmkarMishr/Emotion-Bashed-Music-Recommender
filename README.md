#  Emotion-Based Music Recommender

An intelligent music recommendation system that detects your emotions in real-time using facial expression analysis and suggests music that matches your mood [web:1][web:14].

##  Overview

This project leverages computer vision and deep learning to analyze facial expressions through your webcam, classify your current emotional state, and recommend music tracks that resonate with your feelings [web:13]. The system provides a personalized and immersive listening experience by bridging the gap between your emotions and music preferences [web:17].

##  Features

- **Real-time Emotion Detection**: Captures facial expressions using webcam and processes them in real-time
- **Multi-Emotion Classification**: Detects various emotions including Happy, Sad, Angry, Surprise, Fear, Disgust, and Neutral
- **Intelligent Music Recommendations**: Suggests music tracks based on detected emotional state
- **Deep Learning Model**: Uses CNN architecture with Keras for accurate emotion classification [web:14]
- **Facial Landmark Detection**: Employs MediaPipe for precise facial feature extraction [web:17]

##  Technologies Used

- **Python**: Core programming language
- **OpenCV (cv2)**: Video capture and image processing
- **MediaPipe**: Facial landmark detection and tracking
- **Keras**: Deep learning model for emotion classification
- **NumPy**: Numerical computations and array operations
- **AV**: Audio/video processing

##  Installation

### Prerequisites
- Python 3.7 or higher
- Webcam access

### Setup

1. Clone the repository:
``bash
git clone https://github.com/OmkarMishr/Emotion-Bashed-Music-Recommender.git
cd Emotion-Bashed-Music-Recommender

2. Install required dependencies:
pip install -r requirements.txt

3. Run the application:
streamlit music.py

## How It Works
Video Capture: The system captures live video feed from your webcam using OpenCV

Face Detection: MediaPipe detects facial landmarks from the video frames.

Emotion Classification: The preprocessed facial data is fed into a trained CNN model that classifies the emotion.

Music Recommendation: Based on the detected emotion, the system recommends appropriate music tracks from the database.

## Project Structure
Emotion-Bashed-Music-Recommender/
├── main.py                 # Main application file
├── model/                  # Trained Keras models
├── data/                   # Dataset and music database
├── utils/                  # Helper functions
├── requirements.txt        # Project dependencies
└── README.md              # Project documentation

## Emotion-Music Mapping
The system maps detected emotions to music genres/moods:

Happy: Upbeat, energetic tracks

Sad: Melancholic, soothing music

Angry: Intense, powerful songs

Calm/Neutral: Ambient, relaxing tracks

Surprise: Dynamic, unexpected music choices

## Future Enhancements
Integration with Spotify/YouTube API for direct music playback

Support for multiple users and profile-based recommendations

Emotion history tracking and mood pattern analysis

Mobile application support

Voice-based emotion detection

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Author
Omkar Mishra
GitHub: @OmkarMishr
