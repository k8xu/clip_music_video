# Lyric and Audio-Based Music Video Generation

## Introduction

We are interested in using song data and machine learning to create visually appealing music videos that represent the energy and valence of a song. We combine AI-generated images from song lyrics with visual effects based on the features of the audio track. Our project is inspired by related work in deep learning and video generation using generative adversarial networks, or GANs for short. GANs are a popular framework for making high-quality, synthetic, yet realistic images that can be used as individual video frames. There have been interesting previous works on GANs for video generation, but few have used GANs to create videos from songs or have combined audio features with lyric text.


## Requirements

You will need Python 3.7 and access to a GPU to run the code. The required packages are listed in the `requirements.txt` file.


## How to Generate a Music Video

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1qVgnqV7uChEYqF3VKAcDuL1B2b54p0Lp?usp=sharing)

To run the code locally, follow these instructions:
1. Clone this GitHub repository using `git clone https://github.com/k8xu/music-video-generation.git`.
2. Navigate to the directory containing this repository.
3. Run the cells in the `music_video_generation.ipynb` notebook. The notebook has a code cell to install the required packages.
4. To watch the generated music video (MP4 file), we recommend that you upload the video to Google Drive or YouTube. QuickTime Player does not work for playing the video.

In the notebook, we have provided an example using Levitating by Dua Lipa. If you wish to use a different song, you will need:
- The song name (e.g. "Levitating")
- The ID of a YouTube video for the song containing a transcript of the lyrics (e.g. "G2nJPEDc02k" for [this YouTube video](https://www.youtube.com/watch?v=G2nJPEDc02k) of Levitating)
- The audio features containing the energy and valence of the song from Spotipy, a Python library for the Spotify Web API (e.g. refer to the [Spotipy API Reference](https://spotipy.readthedocs.io/en/2.19.0/#spotipy.client.Spotify.audio_features))
- The audio track of the song as a M4A file (e.g. `audio_files/Levitating.m4a`)
- You can also modify the directory and file paths for the outputs of your song if needed

## Examples

Here are some examples of generated music videos using our implementation. Clicking on the images below will take you to the YouTube videos.

[![AI-Generated Music Video for Levitating with Style](https://img.youtube.com/vi/h156JXG2FM4/0.jpg)](https://www.youtube.com/watch?v=h156JXG2FM4)

[![AI-Generated Music Video for White Horse with Style](https://img.youtube.com/vi/ixe4T3Ly4pM/0.jpg)](https://www.youtube.com/watch?v=ixe4T3Ly4pM)
