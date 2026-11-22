# chetan-raghuvanshi.github.io

Plain HTML + one stylesheet. No build step. Pushing to `main` deploys via GitHub Pages.

## Writing a new post

1. `cp -r blog/_template blog/my-post-slug`
2. Edit `blog/my-post-slug/index.html` (title, date, description, body).
3. Add a line at the top of the **Writing** list in `index.html`, linking to `/blog/my-post-slug/`.
4. Add a **News** line if you want.
5. Commit and push.

Posts published elsewhere (like the failproof ai blog) just get an external link in the Writing list.
