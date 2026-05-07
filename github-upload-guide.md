# GitHub Upload Guide

## What to upload

Upload the entire contents of this folder:

- `index.html`
- `assets/images/flower-icon.png`
- `assets/videos/squats.mp4`
- `assets/videos/pushups.mp4`
- `assets/videos/jumping-jacks.mp4`
- `assets/videos/plank.mp4`
- `assets/videos/lunges.mp4`
- `assets/videos/crunches.mp4`
- `media-sources.md`

## Recommended repository structure

Your GitHub repository should look like this:

```text
index.html
media-sources.md
assets/
  images/
    flower-icon.png
  videos/
    squats.mp4
    pushups.mp4
    jumping-jacks.mp4
    plank.mp4
    lunges.mp4
    crunches.mp4
```

## How to add it on GitHub

1. Open your repository on GitHub.
2. If old files are there with different names or in different folders, delete or replace them.
3. Click `Add file`.
4. Choose `Upload files`.
5. Drag in:
   - `index.html`
   - `media-sources.md`
   - the whole `assets` folder contents
6. Wait for all uploads to finish.
7. Write a commit message, for example:
   - `Update app media and folder structure`
8. Click `Commit changes`.

## Important notes

- The app page should use `index.html`, not `index.html.html`.
- The video paths in this prepared package already point to `./assets/videos/...`
- The image paths in this prepared package already point to `./assets/images/...`

## GitHub Pages

If you use GitHub Pages:

1. Open repository `Settings`.
2. Open `Pages`.
3. Set source to:
   - `Deploy from a branch`
   - branch `main`
   - folder `/ (root)`
4. Save.
5. Wait for the deployment to finish.

## After upload

If media still does not show:

- hard refresh the page
- check that file names match exactly
- check that `assets/videos` and `assets/images` are in the repository root next to `index.html`
