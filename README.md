# Valentine's page for Kiama 💕

Open `index.html` in a browser (or serve the folder and open the link).

---

## Get a permanent link (free)

Your files are only on your computer until you put them on a host. These options give you a **permanent URL** you can send her (e.g. `https://something.netlify.app` or `https://username.github.io/valentine`).

### Option 1: Netlify Drop (fastest, no account required)

1. Zip this folder: `silly_ui` (include `index.html` and `celebration.jpg`/png).
2. Go to **https://app.netlify.com/drop**
3. Drag the zip file onto the page.
4. Netlify will give you a link like `https://random-name-12345.netlify.app`. That link stays live and you can send it to her.

Optional: Sign up for a free Netlify account to pick a nicer subdomain (e.g. `kiama-valentine.netlify.app`).

### Option 2: GitHub Pages (permanent, good if you use GitHub)

1. Create a new repository on GitHub (e.g. `valentine` or `kiama-valentine`).
2. Upload the contents of `silly_ui` into the repo (drag-and-drop or git): at least `index.html` and your celebration image.
3. In the repo: **Settings → Pages**.
4. Under "Source" choose **Deploy from a branch**.
5. Branch: **main** (or **master**), folder: **/ (root)**. Save.
6. After a minute, your page will be at:  
   `https://<your-username>.github.io/<repo-name>/`  
   e.g. `https://johndoe.github.io/valentine/`

Both options are free and the link stays valid as long as you don’t delete the site/repo.

---

## Add your celebration meme

1. Save your celebration image as **`celebration.jpg`** (or `celebration.png`) in this folder:  
   `/usr/scratch/sli3079/silly_ui/`
2. If you use a different filename, edit `index.html` and change the `src` of the image with `id="celebrationMeme"` to your filename.

## Other ways to share (temporary)

- Run a local server: `python3 -m http.server 8000`, then use your IP + port (same network) or a tunnel (e.g. ngrok) for a temporary public link.

## What the page does

- Asks: **"Kiama, will you be my Valentine?"**
- **Yes** is big and easy to click.
- **No** moves away when the cursor gets close, so it’s (almost) impossible to click.
- When she clicks **Yes**, a full-screen celebration appears with your meme.
