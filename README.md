# ffmpeg


# How to record channel 2 using ffmpeg
```
ffmpeg -i "http://192.177.7.175:5004/auto/v2.1?transcode=internet540" -acodec copy -vcodec copy ch2.mp4
```

# Playback HDHomeRun using ffplay

```
ffplay -i "http://192.177.7.175:5004/auto/v2.1?transcode=internet480"  -ac 2 -vf "yadif" -fs
ffplay -i "http://192.177.7.175:5004/auto/v2.1?transcode=internet540"  -ac 2 -vf "yadif" -fs
```
