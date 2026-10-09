# Anant Bhardwaj - Terminal Portfolio

`index.html` is the whole site (HTML, CSS, JS, no build step).

## Deploy (free)
- Netlify: drag this folder onto app.netlify.com/drop
- Vercel: `npx vercel` inside this folder
- GitHub Pages: push to a repo, then Settings > Pages > deploy from main branch
Custom domain: add it in your host's domain settings.

## What needs the deployed site
`repos` and `git log` (GitHub API) and `resume` (resume.pdf).

## Edit content
Text lives in the `D` object near the top of the script. Add a repo link to a project by
appending a 4th item to its array in `D.P`, e.g. ["Title","tags",[bullets],"https://github.com/Mobx01/repo"],
then `open <project-key>` will open it.

## Frustration model
A 4-6-1 MLP (tanh) trained with scikit-learn on synthetic interaction sessions, weights embedded in the page
and run in plain JS. Inputs: backspace ratio, fast-key ratio, error streak, total errors.
