# mp4towebm

Convert `mp4` videos in the current directory to optimized `webm` with [ffmpeg](https://www.ffmpeg.org/) and [mkclean](https://www.matroska.org/downloads/mkclean.html).

### How to use

Run this script from a directory containing mp4 files, optionally specifying a bitrate if you don't want to use the one from the source video.

```bash
# Convert all files in current directory
mp4towebm

# Convert all files in current directory with additional ffmpeg arguments
mp4towebm -vf scale=-1:1080
```
