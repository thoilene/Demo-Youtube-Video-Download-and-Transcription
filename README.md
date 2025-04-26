# Demo - Youtube Video Download and Transcription

This demo project demonstrates the steps for pre-processing Youtube-video data using python libraries.  

## Download Youtube Video and Extract Audio from Video

Jupyter Notebook "Youtube_Video_Download.ipynb" contains a function "download_youtube_video" to download youtube video in mp4-format. The same Jupyter Notebook contains the function "extract_audio" to extract video from downloaded Youtube video and save it in wav-format. Python libraries "yt_dlp" and "moviepy" are use to download Youtube video and extract audio from video.

## Transcription of Audio (from Youtube Video) in Text 

Jupyter Notebook "Transcribe.ipynb" contains a function "whisper_convert_audio_to_text" to extract the text from audio using python library "Whisper" from openAI.


## Usage of the Jupyter Notebooks

This demo project has been developped in Google Colab.

In order to use the Jupyter Notebooks, install the python libraries mentioned above:

### !pip install git+https://github.com/yt-dlp/yt-dlp.git -q

### !pip install moviepy

### !pip install git+https://github.com/openai/whisper.git -q

In this demo project a youtube video of president Trump with Norway prime minister is preprocessed. The text of their conversation is displayed at the bottom of the Jupyter Notebook "Transcribe.ipynb".
