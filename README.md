# Priya’s voice print, growing live

A motion graphic of a Sunburst voice print forming as a client answers each interview question. It's designed for the sidebar of the intake screen, above the transcript.

![Priya’s voice print growing](assets/priya-print-light.gif)

**Live version:** turn on GitHub Pages (see below), then open `https://<your-username>.github.io/priya-voice-print/`

## How to read it

- **Dots around the ring** fill in while she waits to answer. Each dot is a quarter second.
- **Rays pointing out** are things she wants. **Rays pointing in** are worries.
- **Ray length** is the energy in her voice. The lighter steps mark 40% and 70%.
- **Color** is the feeling: lavender for hopeful, brown for worried, gray for neutral.
- **Gaps** are pauses of at least half a second.

## Files

| File | What it is |
|---|---|
| `index.html` | Live animation with play, replay and a light/dark switch |
| `print-data.js` | Ray shapes, wait dots and timing for the animation |
| `assets/priya-print-light.mp4`, `-dark.mp4` | 1080 × 1080 video, 30 fps, about 29 seconds |
| `assets/priya-print-light.gif`, `-dark.gif` | 480 × 480 animated GIF, 15 fps |
| `assets/priya-print-final-light.svg`, `-dark.svg` | The finished print as editable vectors, one layer per ray |

## Run it locally

Open `index.html` in a browser. No build step or server needed.

## Notes

- Priya Shah and her interview are sample data made to demonstrate the design.
- Don't commit real client recordings, transcripts or voice embeddings to a public repository. They are personal and biometric data.
