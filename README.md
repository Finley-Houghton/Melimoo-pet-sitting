# Melimoo Pet Sitting — Website

A single-page website for Melimoo Pet Sitting (pet sitting & dog walking across the Vale of Evesham).

## What's in here

```
index.html        ← the whole website (one file)
favicon.svg       ← the logo icon shown in the browser tab
images/           ← the photos used on the page
README.md         ← this file
```

The site is plain HTML/CSS/JS — no build step, no frameworks. Just open `index.html` in a browser to preview it locally.

## Putting it live for free with GitHub Pages

You don't need to touch the command line for any of this.

### 1. Create the repository
1. Sign in at https://github.com (create an account if you don't have one).
2. Click the **+** (top right) → **New repository**.
3. Name it something like `melimoo-pet-sitting`.
4. Set it to **Public**, then click **Create repository**.

### 2. Upload these files
1. On the new repo page, click **uploading an existing file** (or **Add file → Upload files**).
2. Drag in **`index.html`**, **`favicon.svg`**, the **`images`** folder, and **`README.md`**.
   - Tip: select `index.html`, `favicon.svg`, `README.md`, and the whole `images` folder together and drop them in. GitHub keeps the folder structure.
3. Scroll down and click **Commit changes**.

### 3. Turn on GitHub Pages
1. In the repo, go to **Settings** (top menu) → **Pages** (left sidebar).
2. Under **Build and deployment → Source**, choose **Deploy from a branch**.
3. Set the branch to **main** and the folder to **/(root)**, then **Save**.
4. Wait about a minute, then refresh. GitHub will show a green box with your live link, e.g.
   `https://YOUR-USERNAME.github.io/melimoo-pet-sitting/`

That URL is your live website. Share it anywhere.

## Making changes later
- To edit text, open `index.html` on GitHub, click the pencil ✏️ icon, edit, and **Commit changes**. The live site updates within a minute or so.
- To swap a photo, upload a new image into the `images` folder and update the matching filename in `index.html`.

## Using your own domain (optional)
If you buy a domain (e.g. `melimoopetsitting.co.uk`):
1. In **Settings → Pages → Custom domain**, type your domain and **Save**.
2. At your domain registrar, add the DNS records GitHub shows you.
3. Tick **Enforce HTTPS** once it's verified.

## Things to update before going live
- **Email address:** the page currently uses `Mel@melimoopetsitting.co.uk` as a best guess. Search `index.html` for `melimoopetsitting.co.uk` and replace with the correct address (it appears in the Book Now button and the footer).
- Double-check the phone number (`07751 864465`) and rates.
