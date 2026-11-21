# Jenny — English Teacher Personal Website

A responsive bilingual (Chinese / English) personal-brand website built with plain HTML, CSS, and JavaScript. It is designed to deploy directly to GitHub Pages—no build step required.

## Preview locally

Open `index.html` in your browser. For a more realistic local preview, run a simple static server from this folder:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

1. Create a new GitHub repository. For a personal homepage, name it `YOUR-USERNAME.github.io`.
2. Upload all files in this folder (`index.html`, `styles.css`, `script.js`, `README.md`, and the `assets/` folder) to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then save.
6. Wait for GitHub Pages to publish. Your site will be available at `https://YOUR-USERNAME.github.io/`.

## Personalize before publishing

Search and replace the sample content in `index.html` and `script.js`:

- `hello@example.com` — replace with your public contact email.
- Brand avatar: `assets/jenny-brand-avatar.png` is used in the hero and as the favicon. Replace it with a different image if desired.
- About section — add your real education, teaching experience, qualifications, and areas of expertise.
- Courses section — replace the sample service cards with courses you actually offer.
- Social links — replace the GitHub and placeholder social URLs with your own profiles, or remove links you do not use.
- Update the page title and description in the `<head>` if you want a more specific professional focus.

## Notes

- The site uses Google Fonts; if Google Fonts are unavailable in a visitor's region, system fallback fonts will be used.
- No analytics, trackers, or external JavaScript libraries are included.
- All course and biography details are intentionally generic placeholders. Do not publish them as factual credentials until you personalize them.


## Important before going public

The biography, teaching credentials, course details, email address, and social links are still sample content. Replace them with accurate information before sharing the website publicly.
