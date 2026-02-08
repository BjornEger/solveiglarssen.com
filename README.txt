SolveigLarssen.com static site (no build needed)

1) Replace placeholders:
   - Amazon link: search for https://www.amazon.com/ and replace with the exact book page.
   - Google Form link: search for https://forms.gle/REPLACE_WITH_YOUR_FORM and replace.

2) Upload everything in this folder to a GitHub repository.
   - Repo name for GitHub Pages can be anything, e.g. solveiglarssen.com
   - In GitHub: Settings → Pages → Build and deployment → Source: Deploy from a branch
     Branch: main / root

3) Custom domain:
   - Add a file named CNAME with: solveiglarssen.com
   - In Settings → Pages, set Custom domain to solveiglarssen.com
   - Point DNS A-records to GitHub Pages (see GitHub docs), and set www CNAME to <username>.github.io
