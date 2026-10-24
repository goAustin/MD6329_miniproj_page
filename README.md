# Mini-project page (MD6329 Deep Learning for Healthcare AI)

A single self-contained file: `index.html`. No build step, no dependencies. The Inter font loads from Google Fonts and falls back to system fonts if it is blocked.

## Publish it with GitHub Pages (about two minutes)

1. On GitHub, create a new **public** repository, for example `MD6329_miniproj_page`.
2. Click **Add file > Upload files**, drop in `index.html` (at the repository root) and commit.
3. Open **Settings > Pages**. Under *Build and deployment*, choose **Deploy from a branch**, select branch `main` and folder `/ (root)`, then **Save**.
4. After a minute or two the page is live at `https://<your-github-name>.github.io/<repository-name>/`. For the repository above and the account that hosts LecTrace, that is `https://goaustin.github.io/MD6329_miniproj_page/`. Anyone can open it without signing in.

Do not put this file into the LecTrace repository: it would replace that site's own `index.html`.

## Edit before you publish

- **Byline.** Search `index.html` for `Byline` (an HTML comment under the title) and add your name and student ID.
- **Links.** The LecTrace and Google Drive links appear as plain `href` values. To change one, search for `goaustin.github.io` or `drive.google.com` and replace every occurrence.
- **Check the Google Drive link.** Open it in a private browser window. It must show the PDF without asking you to sign in (Share > General access > Anyone with the link).

## What the page contains

A blog-style article. Title and two link buttons (LecTrace presentation, report), a cover figure, a Question callout and a TL;DR, then the sections Question, Approach, Results (two interactive charts with table views), Takeaways, LecTrace and Report. The sticky top bar jumps between the sections and highlights the one in view.
