# Daily Learning
## Morning Planning
## Review
Convert an image or video from dark to light mode using [[ffmpeg].org

```bash
ffmpeg -i input.mp4 -vf "negate, hue=h=180, eq=contrast=1.2:saturation=1.1" output.mp4
```
