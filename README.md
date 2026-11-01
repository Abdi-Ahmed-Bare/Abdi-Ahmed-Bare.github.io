# Abdi Bare — Embedded Systems Portfolio

## Start
Open `index.html` in Chrome or Edge. Your profile photo and current resume PDF are already included.

## Edit projects, experience, and skills
1. Open `admin.html` in your browser.
2. Choose Projects, Experience, or Skills.
3. Select an entry or click **+ Add new**.
4. Enter information and click **Save entry**.
5. Click **Download site-data.js**.
6. Replace `data/site-data.js` with your downloaded file. Refresh `index.html`.

Important: The editor does **not** automatically upload files to GitHub or save changes to the site. Export your JSON before closing the editor. If you want to edit again later, import the current `data/site-data.js` first.

## Add images and videos
- Create a folder `assets/projects/` if it does not exist.
- Copy project images into it, e.g. `assets/projects/air-monitor.jpg`.
- In the editor, enter that relative path under Cover image. Add gallery paths on separate lines.
- Paste a public YouTube video URL under YouTube video link.
- Export and replace `data/site-data.js`.

## Update the resume
Replace `assets/Abdi_Bare_Resume.pdf` with the revised PDF using the same filename. The included PDF is the original resume you supplied and may still show the older graduation date; the website text says April 2027.

## Publish on GitHub Pages
1. Create a public repository named `Abdi-Ahmed-Bare.github.io` on your GitHub account (or use another repository).
2. Upload the *contents* of this folder to the root of the repository, including `index.html`, `data/`, `assets/`, and all `.js`/`.css` files.
3. Under Settings → Pages, select Deploy from a branch → main → /(root).
4. Wait for deployment. For the specially named repository, the URL is `https://Abdi-Ahmed-Bare.github.io/`.
5. After updating content, commit the new `data/site-data.js` and any new images to the repository.

The local editor is not password-protected; do not treat it as a private cloud admin dashboard. You may omit `admin.html` and `editor.js` when publishing if you want the editor to remain local only.

## Project cover images
The autonomous vehicle card uses the actual photo you provided. The other three cards use **conceptual SVG illustrations**, not photographs of completed builds. Replace them with actual project images when available by editing each project Cover image in `admin.html` and placing photos in `assets/projects/`. Export `site-data.js` afterward.


## Latest project photos
The four project cover images are stored in `assets/projects/`. Your original portrait (`assets/profile.jpg`) was preserved byte-for-byte without alteration. Update project entries using `admin.html`, then export the JSON as described above. The autonomous car photo shows the prototype on a table.
