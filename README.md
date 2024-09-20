# youtube_downloader
This Python project allows you to download YouTube videos in MP4 format or extract audio in MP3 format. It uses the yt-dlp library, a powerful tool for downloading content from YouTube and other video sites.

![gif](https://imgur.com/0XmGY0F.gif)

## Requirements

Make sure you have the following installed on your system:

- Python 3.x
- `yt-dlp`
- `ffmpeg` (to convert audio to MP3)

## Installation

1. Clone the repository:
   
       git clone https://github.com/R1-cochet/youtube_downloader.git
       cd youtube_downloader

2. Install yt-dlp:
    
      pip install yt-dlp

3. Install FFmpeg:
   
   * Windows: Download it from [FFmpeg](https://www.ffmpeg.org/download.html) and follow the installation instructions.
   
   * Linux: You can install it using your package manager. For example, on Debian/Ubuntu:
  
        `sudo apt-get install ffmpeg`
     
   * macOS: You can install it using Homebrew:
   
        `brew install ffmpeg`
  
  ## Usage
  
  Run the script: In your terminal, navigate to the project folder and run the following command:
  
      python youtube_downloader.py

  Enter the video URL: When prompted, enter the URL of the YouTube video you want to download.

  Choose an option:

    Enter 1 to download the video in MP4 format.
    Enter 2 to download only the audio in MP3 format.

  Wait for the download to complete: You will see a message confirming that the download has been completed.

  ## Contributions

  Contributions are welcome! If you have ideas for improving this project, feel free to open an issue or submit a pull request.


