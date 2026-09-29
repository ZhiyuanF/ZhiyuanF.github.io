# Zhiyuan Fan academic website

A plain HTML/CSS academic website designed for GitHub Pages. No build step or framework is required.

## Important: GitHub Pages repository name

Your current GitHub username is `ZhiyuanF`. For a root personal site at `https://ZhiyuanF.github.io`, create a repository named exactly:

`ZhiyuanF.github.io`

GitHub requires a user site repository to match the account username. If you later change your GitHub username to `ZhiyuanFan`, rename/create the repository as `ZhiyuanFan.github.io` and the root site will become `https://ZhiyuanFan.github.io`.

A repository named `ZhiyuanFan.github.io` under the existing `ZhiyuanF` account is not the standard root user-site configuration.

## Publish the site

1. Create a new **public** repository named `ZhiyuanF.github.io`.
2. Upload **the contents of this folder** to the repository root. `index.html` must be at the top level.
3. Commit the files.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and `/(root)`, then save.
7. After GitHub finishes publishing, visit `https://ZhiyuanF.github.io`.

## Add the final CV

1. Export the final CV PDF from Overleaf.
2. Rename it to `Zhiyuan_Fan_CV.pdf`.
3. Place it in:

`assets/files/Zhiyuan_Fan_CV.pdf`

4. Replace the content inside `<main>...</main>` in `cv.html` with:

```html
<main>
  <div class="eyebrow">Curriculum vitae</div>
  <h1>CV</h1>
  <p><a href="assets/files/Zhiyuan_Fan_CV.pdf" target="_blank" rel="noopener">Download CV (PDF)</a></p>
  <object data="assets/files/Zhiyuan_Fan_CV.pdf" type="application/pdf" width="100%" height="900">
    <p>Your browser cannot display the PDF. <a href="assets/files/Zhiyuan_Fan_CV.pdf">Download it here.</a></p>
  </object>
</main>
```

## Update content

- Homepage: `index.html`
- Research: `research.html`
- Publications: `publications.html`
- Teaching/mentoring/service: `teaching.html`
- Styling: `assets/css/style.css`
- Headshot: `assets/images/headshot.jpg`

Because all links are relative, the same files can be used if the GitHub username or repository name changes later.

## Current public links

- Email: `zhiyuan_fan@seas.harvard.edu`
- Google Scholar: https://scholar.google.com/citations?user=3Sm2KyUAAAAJ&hl=en
- GitHub: https://github.com/ZhiyuanF
