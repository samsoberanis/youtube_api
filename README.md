# youtube_api
This repository provides a Python wrapper for the YouTube API, allowing users to interact with YouTube's data, search, and video resources. This wrapper simplifies the process of working with the API, making it easier to retrieve and analyze YouTube data.

Following tutorial https://youtu.be/D56_Cx36oGY.
All credits to @thu-vu92

## Getting Started

To use the YouTube API wrapper, you will need to set up a Google API account and obtain an API key. You can follow the instructions in Google's API documentation to get started.

Once you have an API key, you can install the YouTube API wrapper using pip:

pip install youtube_api

To use the wrapper in your Python code, simply import the YouTubeDataAPI class and create an instance with your API key:

from youtube_api import YouTubeDataAPI
api_key = "your-api-key-here"
yt = YouTubeDataAPI(api_key)

You can then use the yt object to interact with the YouTube API and retrieve data.

Examples

The repository includes several examples of how to use the wrapper to retrieve data from YouTube. These examples cover topics such as searching for videos, retrieving video details, and analyzing video comments.
