# Youtube watchtime analyzer

This script analyzes the sum of all videos you watched at youtube.

Creates an intermediate CSV file with all the info from the API.

# Requirements:
* [Google Takeout](https://takeout.google.com/settings/takeout) youtube export
* Google youtube API Key [Get your API key](https://console.developers.google.com/apis/credentials)

Info on [getting started witt the API](https://developers.google.com/youtube/v3/getting-started)

[More technical info about API key](https://stackoverflow.com/questions/15596753/how-do-i-get-video-durations-with-youtube-api-version-3)

One api key is limited to 10k requests per day. 50 Videos per request.

Example output:
```
2388 h 23 min
9058 / 19823 videos analyzed
Skipped videos 147
Continue analyzing at id 9205
```