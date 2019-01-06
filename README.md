# Gensub
### Note

This repository is being rewritten.

### Auto-generated subtitles for any video

Gensub, is forked from [autosub](https://github.com/agermanidis/autosub), is a utility for automatic speech recognition and subtitle generation. It takes a video or an audio file as input, performs voice activity detection to find speech regions, makes parallel requests to Google Web Speech API to generate transcriptions for those regions, (optionally) translates them to a different language, and finally saves the resulting subtitles to disk. It supports a variety of input and output languages (to see which, run the utility with the argument `--list-languages`) and can currently produce subtitles in either the SRT format or simple JSON.

### License

MIT
