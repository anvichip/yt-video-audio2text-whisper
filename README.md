# Whisper AI YouTube Transcription 

This project demonstrates how to use the Whisper AI tool to transcribe audio from a YouTube video into formatted text with timestamps. The Pytube library is used to download the video from the YouTube link.

## Description

This project utilizes the Whisper AI tool to transcribe spoken audio segments from a YouTube video into textual format. The provided YouTube link is used to download the video using the Pytube library. The script then processes the downloaded video to extract transcriptions with precise timestamps in the format [hh:mm:ss.sss --> hh:mm:ss.sss]. The formatted transcriptions are saved to a text file named `transcribed_text.txt`.

## How to Run

1. Open the Google Colab notebook in your Google Drive.

2. Execute the provided code cells in the notebook. The notebook will use the Whisper AI results to format the transcriptions.
   
3. Run the main() function code block in Google Colab.
   
4. You will encounter a prompt to enter the link of the Youtube video. Enter the link then press enter.

5. Once the notebook has finished executing, a text file named `transcribed_text.txt` will be created in the same directory.

## Libraries Used

The following Python libraries are used in this project:

- Whisper AI: The Whisper AI tool is used for audio transcription.
- Pytube: The Pytube library is used to download YouTube videos.
- Torch: The Torch library is used for neural network computations.

## Installation

No separate installation is required for Whisper AI within Google Colab. The Pytube library will be installed using the command `!pip -qqq install pytube` within the notebook.


You can find an article with the explanation of the code at https://medium.com/@anvikohli13/convert-youtube-videos-into-subtitled-text-with-whisper-ai-and-pytube-6043b3fe9fa3


