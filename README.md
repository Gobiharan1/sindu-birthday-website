# Sindu Maa’s Birthday Website

A birthday letter from Gopi, with a sage-green vinyl player, Magale starting at 0:58, and large rotating lines from the letter.

Live site: https://sindu-ma-little-universe.gobiharan.chatgpt.site (private)

## Run locally

No build or package installation is required.

```sh
python3 -m http.server 4173 --directory dist
```

Open http://localhost:4173 and press Play to start the music. Playback uses the YouTube IFrame API and requires internet access. Google Fonts also loads online.

## Files

- `dist/index.html`: birthday letter and page layout
- `dist/style.css`: responsive styles and vinyl animation
- `dist/app.js`: music controls, timed text, locally saved lyrics, and birthday wishes
- `.openai/hosting.json`: existing Sites deployment configuration

Custom lyrics can be added from the page using plain lines or LRC timestamps. They remain in the visitor’s browser storage.

The vinyl design is inspired by TheAbieza’s Uiverse.io player supplied in the original brief. Music is played through the original YouTube video; no audio files are included.
