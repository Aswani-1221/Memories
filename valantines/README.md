# Valentine Proposal Site

A warm, romantic, and playful Valentine’s Day proposal website with soft gradients, floating hearts, magical transitions, and a celebration mode.

## How to Run
- Open `index.html` directly in your browser, or use a local server.
- Optional (PowerShell):
  ```powershell
  # in the project folder
  python -m http.server 8000
  # then open http://localhost:8000/index.html
  ```

## Customize Your Story
- Background music: place a soft instrumental file at `assets/music.mp3`.
- Gallery images: add `assets/moment1.jpg`, `assets/moment2.jpg`, `assets/moment3.jpg`.
- Video: replace the YouTube `iframe` `src` in the Video section.
- Messages: edit the `heroMessage` string and captions in `index.html`.

## Accessibility & Motion
- Supports reduced motion via `prefers-reduced-motion`.
- Large, touch-friendly buttons and readable typography.

## Notes
- The NO button playfully avoids clicks (hover/touch/click causes it to float away).
- The YES button triggers hearts & confetti, glow overlay, and transitions to celebration without stopping the music.
- Back button smoothly returns to the question.

## License
- Use your own media (music/images/video). Avoid uploading copyrighted files you don’t have rights to.
