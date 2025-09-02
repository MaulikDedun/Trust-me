# Trust Me

A simple button that plays music when you click it. Made this for fun during my web development learning.

## Demo

Just open the `index.html` file in your browser and click the button!

## Adding Music

### Method 1: Direct Audio Files

1. Find the line `USE_YOUTUBE = false` in the code
2. Replace `YOUR_DIRECT_AUDIO_LINK.mp3` with your music file link

```javascript
const USE_YOUTUBE = false;
```

You can get music from:
- Your own audio files
- Free music websites like freesound.org
- Any direct MP3 link

### Method 2: YouTube (might not work sometimes)

1. Change `USE_YOUTUBE = false` to `USE_YOUTUBE = true`
2. Get the video ID from YouTube URL (the part after `v=`)
3. Replace `YOUR_YOUTUBE_VIDEO_ID_HERE` with that ID

```javascript
const USE_YOUTUBE = true;
const YOUTUBE_VIDEO_ID = "dQw4w9WgXcQ";
```

**Note:** YouTube doesn't always work because of browser restrictions.

## Browser Support

- Chrome - Works
- Firefox - Works  
- Safari - Works
- Edge - Works

That's it! Pretty simple project.
