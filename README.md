# Aishi's Birthday Site

A single-page, dark "midnight garden" birthday website. Pure HTML/CSS/JS, no build step, no installs.

## 1. Folder structure

You already have it:

```
aishi-birthday/
├── index.html
├── style.css
├── script.js
├── images/       ← put your photos here
└── music/        ← put your song here
```

## 2. Customize the text

Open **script.js** in any text editor (Notepad, VS Code, TextEdit) and edit the
`CONFIG` object at the very top of the file — it's clearly marked. That one
object controls every piece of text on the site: the opening lines, the
letter, the 6 "things I like about you", the timeline, the final message,
and so on. You never need to touch anything below the line that says
`EVERYTHING BELOW THIS LINE RUNS THE SITE`.

## 3. Add your photos

Drop your images into the `images/` folder. Name them to match `CONFIG.photos`
in script.js (e.g. `photo1.jpg`, `photo2.jpg`...), or edit the file names in
`CONFIG.photos` to match whatever you actually have. Add or delete entries
freely — the gallery adjusts automatically. If a photo file is missing, the
site shows a soft placeholder instead of breaking, so it's safe to preview
before every photo is ready.

Tip: keep each photo under ~500KB so the site loads fast on her phone. Any
free tool like squoosh.app can compress images without installing anything.

## 4. Add your song

Put one MP3 file in the `music/` folder named `song.mp3` (or change
`CONFIG.music.file` in script.js to match your file name). The player never
autoplays — she taps play herself.

## 5. Preview it locally

Just double-click `index.html` and it opens in your browser. That's it — no
server needed. Refresh the page after every edit to see your changes.

## 6. Put it on GitHub

1. Create a free GitHub account if you don't have one, at github.com.
2. Click **New repository**. Name it something like `aishi-birthday`. Keep it
   Public. Don't add a README (you already have one).
3. On the new repo's page, click **uploading an existing file**.
4. Drag in `index.html`, `style.css`, `script.js`, the `images` folder, and
   the `music` folder. Commit the changes.

## 7. Turn on GitHub Pages

1. In your repository, go to **Settings → Pages**.
2. Under "Build and deployment", set **Source** to `Deploy from a branch`.
3. Set the branch to `main` (or `master`) and the folder to `/ (root)`. Save.
4. Wait 1–2 minutes.

## 8. Get the link

Refresh the **Settings → Pages** screen — it will show a green box with your
live link, something like:

```
https://yourusername.github.io/aishi-birthday/
```

That's the link you send to Aishi. Open it yourself first on your own phone
to double check everything looks right.
