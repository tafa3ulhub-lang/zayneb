# The 13th Frame

A private, seven-act interactive gothic mystery for Zayneb Hameed. It's a static site: plain HTML, CSS and JavaScript with local images, so there's no build step and no server.

## What's in this folder

```
index.html     the whole site (styles and script are inside)
assets/        every image the site uses
  poster.jpg                        poster shown on screen
  zayneb-hameed-the-13th-frame.png  1080 × 1920 poster used for Download and Share
  mandala.jpg                       Zayneb's original mandala (Act III)
  room.jpg, room-shadow.jpg         the darkroom print and its "changed" version (Act II)
  frame-01.jpg … frame-13.jpg       the archive filmstrip (frame-07b.jpg is the revisited frame)
  subject.jpg                       her original photo for the identity analysis (Act V)
  favicon.png, social-preview.jpg
```

## Publishing with GitHub Pages

1. In this repository, open **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to *Deploy from a branch*, choose the `main` branch and the `/ (root)` folder, then **Save**.
3. Wait a minute or two, then refresh that page. The site will be at:
   `https://tafa3ulhub-lang.github.io/zayneb/`
4. Make the QR code for the envelope from that link, **without** `?preview=1`.

Any change merged into `main` republishes the site automatically within a few minutes.

## Preview mode

Add `?preview=1` to the address:

`https://tafa3ulhub-lang.github.io/zayneb/?preview=1`

This shows a panel with **Prev**, **Next**, **Final reveal** and **Restart**. Every act plays its animations and taps itself through, so you can watch the whole story without touching anything. `#preview` at the end of the address works too.

Zayneb's link should not include `?preview=1`. Without it, the panel never appears.

## The song (Act IV)

When she taps the record, the official YouTube video of Adonis — حلمت (`hwwbh7tVL_8`) plays in the visible player on the radiogram, through YouTube's official embed. Nothing is downloaded or rehosted.

- Music starts only after she taps.
- **Pause** and **Mute** buttons control the player, and the record stops spinning when the music is paused.
- Leaving the scene pauses the song.
- If YouTube can't load, or the video's owner blocks embedding, the cabinet shows a "Listen on YouTube" link and the story carries on.

## Sound

Sound effects are off by default and are generated in the browser (nothing is copied from elsewhere). She can turn them on at the opening screen or with the button at the top. The story works fully with sound off.

## Editing the letter

Search `index.html` for `Dear Zayneb` and edit the paragraphs below it.
