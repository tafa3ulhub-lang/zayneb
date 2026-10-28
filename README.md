# THE 13TH FRAME · الإطار الثالث عشر

A small static website: plain HTML, CSS and JavaScript with local images and fonts. There's no build step, no server and no external services, apart from YouTube's official player for one song.

Live: https://tafa3ulhub-lang.github.io/zayneb/

## Files

```
index.html        the whole site (styles and script are inside)
assets/           images used by the site
assets/fonts/     self-hosted webfonts (SIL Open Font License, see OFL.txt)
```

Every path is relative (`./assets/...`), so the site works under the `/zayneb/` GitHub Pages path.

## Preview mode

Add `?preview=1` (or `#preview`) to the address. A small panel at the bottom lets you:

- jump to any scene
- solve the current scene
- show its hints
- open the poster and test the download
- see the ending
- restart
- try the second-visit variation

The normal address never shows this panel.

## Publishing

GitHub Pages publishes from the `main` branch, root folder (**Settings → Pages**). Changes merged into `main` appear on the live address within a few minutes.

## Notes

- Sound effects are generated in the browser and are off until the visitor turns them on.
- The song plays only through YouTube's official embedded player, and only after a tap. If the player can't load, a link to YouTube appears and the site carries on.
- The site stores one small flag in the visitor's browser (`localStorage`) after the ending, used for a small change on a second visit. Nothing else is stored or sent anywhere.
