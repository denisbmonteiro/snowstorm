# Snowstorm

A simple page with a snow effect, audio playback, and synchronized lyrics, all running directly in the front end.

**Status:** In production

**Summary**
- **Description:** A static page that plays an audio track, displays synchronized lyrics, and adds a falling snow visual effect.
- **Demo:** Open [index.html](index.html) in your browser.
- **Technologies:** HTML, CSS, JavaScript — local scripts `content/snowstorm.js` and `content/rabbit-lyrics.js`.

**Features**
- Snow effect powered by `content/snowstorm.js`.
- Audio player with controls and autoplay (`content/snowstorm.opus`).
- Lyrics synchronization with Rabbit Lyrics (implemented in `content/rabbit-lyrics.js`).
- Lyrics styles in `content/rabbit-lyrics.css`.
- General page styles in `content/style.css`.

**How to run**
1. Clone or download this repository.
2. Open [index.html](index.html) in your browser (Chrome, Firefox, or any other modern browser).

**Usage**
1. When you open [index.html](index.html), the track in `content/snowstorm.opus` is loaded and starts playing automatically (autoplay).
2. Use the player (the `audio` controls) to pause, adjust the volume, or skip ahead.
3. The lyrics are displayed and synchronized automatically with the audio's current position.
4. The snow effect runs in the background; to disable it, remove or comment out the `content/snowstorm.js` include in [index.html](index.html).

Default behavior:
- The initial volume is set by an inline script in [index.html](index.html) (current default: 0.2). To change it, edit the script block below the `audio` element.
- The lyrics are embedded in the HTML, inside the div with the `rabbit-lyrics` class in [index.html](index.html).

**Project structure**
- [index.html](index.html) — main page; includes the audio, lyrics, and scripts.
- [content/rabbit-lyrics.css](content/rabbit-lyrics.css) — styles for displaying the lyrics.
- [content/rabbit-lyrics.js](content/rabbit-lyrics.js) — lyrics synchronization logic (Rabbit Lyrics).
- [content/snowstorm.js](content/snowstorm.js) — snow effect script.
- [content/snowstorm.opus](content/snowstorm.opus) — audio file used by the page.
- [content/style.css](content/style.css) — general page styles.

**License / Notes**
- `content/snowstorm.js` includes a header indicating a BSD license.
- `rabbit-lyrics` mentions a GPLv3 license (see the comments in `content/rabbit-lyrics.js`).
- Check the file headers for license details before redistributing.

**Contributing**
- Suggestions, fixes, and improvements are welcome. Please open an issue describing your proposal before submitting a pull request.

**Author**
- Denis Bittencourt — https://denisbm.com