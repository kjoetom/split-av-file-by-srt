# split-av-file-by-srt

This Script is forked and based on the Skript by adueck https://github.com/adueck/split-video-by-srt

To use the srt-file as produced by audapolis audio editor, I had to modify the extraction of the time codes.

You can use this bash script to automatically split audio or video files up into seperate chunks based on timecodes from an .srt subtitle file.

This could be useful for:

- language learners looking to make an Anki deck out of phrases from a movie or TV show.
- people looking for an easier way to edit and export a large number of smaller clips from a larger file

I used audapolis for making subtitle files. Originally adueck reccomended [Subtitle Edit](http://www.nikse.dk/SubtitleEdit/) for making subtitle files.

`usage: .\srt-split.sh [video file] [subtitle file] (optional)[output format]`

This script takes the timecodes out of the .srt file and outputs a seperate video file for each subtitle duration. You are also given an option to export the clips to the file format of your choice. If no output format is supplied, the clips will be exported in the same format as the original.

**requires ffmpeg**

More features and functionality to come. Contributions welcome.

