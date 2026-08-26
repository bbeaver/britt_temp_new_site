# Speaker site — GitHub Pages kit

A static, WordPress-style website for a teacher moving into public speaking.
No build step. Upload these files to a GitHub repository and turn on Pages.

## Pages

| File | Purpose |
| --- | --- |
| `index.html` | Home |
| `about.html` | About Me |
| `references.html` | References / testimonials |
| `media.html` | Link to a Google Drive folder (Audio + Media subfolders) |
| `css/style.css` | Theme (colors, type, layout) |
| `js/site.js` | Mobile menu |
| `favicon.svg` | Tab icon |

## Put it on GitHub Pages

1. Create a new repository on GitHub (for example `yourname.github.io` for a site at `https://yourname.github.io`, or any repo name for a project site).
2. Upload every file in this folder, keeping the same structure (`css/`, `js/`, the HTML files).
3. In the repo: **Settings → Pages → Build and deployment**.
4. Source: **Deploy from a branch**. Branch: `main` (or `master`). Folder: `/ (root)`.
5. After a minute, GitHub will show the live URL.

If the repo is *not* named `username.github.io`, the site will live at
`https://username.github.io/repository-name/`. Relative links in this kit already work for that.

## Replace the sample content

Search the HTML files for:

- `Claire Whitmore` / `Claire` / `Whitmore`
- `hello@clairewhitmore.com`
- `Portland, Oregon`
- `YOUR_FOLDER_ID` (on `media.html`, three times)

Colors live in `css/style.css` under `:root`.

## Google Drive (Media page)

1. Create a Drive folder (for example “Speaking Media”).
2. Inside it, create two subfolders: **Audio** and **Media**.
3. Right-click the parent folder → Share → General access → **Anyone with the link** → Viewer.
4. Copy the folder URL and paste it over `https://drive.google.com/drive/folders/YOUR_FOLDER_ID` in `media.html`.

## Optional: custom domain

In the repo, add a file named `CNAME` containing your domain (for example `www.yourname.com`), then point the domain’s DNS at GitHub Pages as described in GitHub’s docs.
