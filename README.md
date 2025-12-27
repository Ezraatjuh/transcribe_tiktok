# transcribe_tiktok
This repository downloads and transcribes tiktok video's

First execute transcribe_tiktok\V4tiktok_scroll_inf.ipynb
For this, open Chrome in debugger using the first cell. In this Chrome browser you can search for tiktok.
Here you can search for the wanted video's. First scroll all the way down, until no more video's appear.
Than scroll all the way back up and click on the first video in the list, so it will play. Then run the code.

When all these links are collected, we need to download the video's, before we can transcribe them.
For this, run the transcribe_tiktok\download_tiktok.ipynb code. The video's will be downloaded on local storage.

These video's can be transcribed using transcribe_tiktok\whisper.ipynb. This gives a csv file with all the 
transcribed video's.
