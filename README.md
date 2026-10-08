# Author page

A single-screen "about the author" page. Your photos fill the background and crossfade; visitors can swipe, tap the thumbnails, or use the arrow keys.

## Add your photos (no code needed)

1. Open `index.html` in your browser with `?edit` on the end of the address. Once it is on GitHub that is `https://YOUR-USERNAME.github.io/REPO-NAME/?edit`.
2. Click **Add photos** and pick as many as you like, from your phone or computer. They are resized automatically so the page loads fast. The small × on a thumbnail removes a photo.
3. Click **Download photo pack**. You get `photo-pack.zip`.
4. Unzip it. Upload the files inside its `images` folder (the photos and `photos.json`) into the `images` folder of your GitHub repository, using **Add file → Upload files**.
5. Reload the normal link (without `?edit`). Your photos are now the background for everyone.

To change the photos later, repeat the steps. Visitors never see the edit controls unless they add `?edit` themselves, and nothing they do there changes your site.

## Change the text

Open `index.html` in GitHub's editor (the pencil icon) and replace `Author`, `Your Book Title`, the bio paragraph, `you@example.com` and the `https://example.com` links. Remove the dashed "Sample text" tag when you are done.

## Put it online with GitHub Pages

1. Create a new public repository on github.com (for example `about-the-author`).
2. Upload everything in this folder, including the `images` folder and the `.nojekyll` file.
3. Go to **Settings → Pages**, set **Source** to "Deploy from a branch", choose `main` and `/ (root)`, and save.
4. After a minute your page is live at `https://YOUR-USERNAME.github.io/about-the-author/`.

## QR code

Once the link works, make a QR code from it (without `?edit`), download it as a PNG or SVG, and print it at least 2 cm wide with a plain white margin. Test it with a couple of phones before printing.
