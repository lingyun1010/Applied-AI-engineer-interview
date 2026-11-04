# Nuix interview preparation

This repository keeps the self-contained interview-preparation pages for the **Nuix Principal AI Enablement Builder** role.

## Open the pages locally

- **Main interview guide:** double-click `index.html`.
- **Career transition and relocation narrative:** open `career-transition.html`.

Neither page needs a server, build step, package installation or internet connection.

From Terminal on macOS:

```sh
open index.html
open career-transition.html
```

## Update it

The main guide is in `index.html`. The career-transition answer is in `career-transition.html`. Keep new discussion details in the most relevant existing section, and add interview-ready English wording plus concise Chinese coaching notes where useful.

After each focused update:

```sh
git diff --check
git diff
git add index.html career-transition.html README.md
git commit -m "Update Nuix interview preparation"
```

## Optional GitHub Pages publishing

This repository is compatible with GitHub Pages because `index.html` is at the repository root. Publishing can be enabled later from the GitHub repository's **Settings → Pages** without changing the page.

Do not publish private recruiter details, contact information, confidential company information or invented claims.
