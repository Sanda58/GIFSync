# TempoGIF

TempoGIF is a web application that adjusts the speed of a GIF animation based on the tempo of an uploaded music file. This application uses Python Flask for the backend server, JavaScript for the frontend interaction, and libraries like pydub and librosa for audio analysis.

## Installation

### Prerequisites

Before running this application, make sure you have the following installed:

- Python 3.x
- pip (Python package installer)

### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/TempoGIF.git
Navigate into the project directory:

bash
Copy code
cd TempoGIF
Create and activate a virtual environment (optional but recommended):

bash
Copy code
# On Windows
python -m venv venv
venv\Scripts\activate

# On macOS/Linux
python3 -m venv venv
source venv/bin/activate
Install dependencies:

bash
Copy code
pip install -r requirements.txt
This will install Flask, pydub, and librosa.

Install FFmpeg:

Windows: Download FFmpeg from ffmpeg.org and add its bin directory to your system's PATH.

macOS: Install FFmpeg using Homebrew:

bash
Copy code
brew install ffmpeg
Linux: Install FFmpeg using your distribution's package manager:

bash
Copy code
sudo apt-get update
sudo apt-get install ffmpeg
Verify FFmpeg installation:

bash
Copy code
ffmpeg -version
Usage
Ensure you are in the project directory and your virtual environment is activated (if used).

Run the Flask application:

bash
Copy code
python app.py
You should see output similar to:

bash
Copy code
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
Open your web browser and navigate to http://127.0.0.1:5000/.

Upload a music file (MP3, WAV, etc.) using the provided input field and click "Upload and Analyze". The application will analyze the tempo of the music and adjust the speed of the GIF animation accordingly.

The adjusted GIF animation will be displayed on the page with the modified speed.

License
This project is licensed under the MIT License
