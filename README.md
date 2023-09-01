# Convert Format

## mov to mp4

```
docker compose exec ffmpeg ffmpeg -i input.mov output.mp4
```

# Compress

## mp4

```
docker compose exec ffmpeg ffmpeg -i input.mp4 -vcodec libx265 -acodec aac -crf 28 output.mp4
```

