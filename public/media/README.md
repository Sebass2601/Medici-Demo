# Pitch videos and thumbnails

Files in this folder are served as-is: `public/media/verdant.mp4` becomes `/media/verdant.mp4`.

To give a startup a real pitch video:

1. Record a vertical video (9:16), 30–60 seconds. Export as **MP4 (H.264)**,
   720p or 1080p, ideally under 20 MB so it loads fast on phones.
2. Optional: a thumbnail image (JPG) to show before it plays, e.g. a frame of the founder.
3. Put the files here, then add them to the startup in `data/startups.json`:

```json
"pitch": {
  "durationSec": 45,
  "videoUrl": "/media/verdant.mp4",
  "posterUrl": "/media/verdant.jpg",
  "script": ["…"]
}
```

With only `posterUrl` (no video), the image is shown behind the animated captions.
