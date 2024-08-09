# A tool for removing silences from a video

GUI to remove silence in videos.

## Dependencies

- [python](https://www.python.org/downloads/)
- [ffmpeg](https://ffmpeg.org/download.html)
- [ffprobe](https://ffmpeg.org/download.html)

Download and install them first.

**Windows users**:
Make sure ffmpeg and ffprobe are in your environment path variables. The links above should have information on how to do that. You can also ask any AI agent to help you with that.

## How to use

- Graphical user interface: `python silence_cutter_gui.py`

## For command-line interface:

`python3` is typed in Linux; Windows users should use `python` instead.

- Easiest command: `python3 silence_cutter.py [your video]`

- Show **help** and suggestions: `python3 silence_cutter.py --help`

- More Options: `python3 silence_cutter.py [your video] [outfile] [silence dB border]`


## Most other tools are:
- Unreliable
- Too complex
- Huge in size
- They store each frame of the video as bitmap file<br> (how can you even think about something like that)






