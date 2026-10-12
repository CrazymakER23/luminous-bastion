# Put Luminous Bastion on your phone

This folder is a full-screen phone app (a "web app"). You put it on the internet once, for free, and then each phone adds it to its home screen.

## 1. Put it online (once, about 5 minutes) — GitHub Pages

1. Go to github.com, sign in, click **+** (top right) → **New repository**.
2. Name it `luminous-bastion`. Set it to **Public**. Click **Create repository**.
3. On the next page click **uploading an existing file**.
4. Drag in everything from this folder: `index.html`, `manifest.webmanifest`, `sw.js`, and the whole `icons` folder. Click **Commit changes**.
5. Go to the repo's **Settings** → **Pages**. Under "Branch" pick **main** and **/ (root)**, then **Save**.
6. Wait about a minute and refresh. Your game's address appears at the top, like:
   `https://YOUR-USERNAME.github.io/luminous-bastion/`

## 2. Add it to your phone

**iPhone:** open that address in **Safari** (it has to be Safari) → tap the **Share** button → **Add to Home Screen** → **Add**.

**Android:** open it in **Chrome** → tap **⋮** → **Install app** (or **Add to Home screen**).

Open it from the new Bastion icon. It runs full screen, sideways, with no browser bars, and it works without internet after the first load.

## 3. Your wife's phone

Text her the address. She does step 2 on her phone. Her progress is her own.

## Moving progress

The home-screen app keeps its own save. To bring progress from somewhere else: Settings → **Copy my save code** on the old one, then **Load this code** on the new one.

## Updating later

When there's a new version: upload the new `index.html` over the old one, and in `sw.js` change `bastion-v1.4` to the next number. Phones pick up the update the next time the app is opened with internet.
