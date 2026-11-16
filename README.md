# STEMEd+ Commons: Start here

The **Start here** page for [STEMEd+ Commons](https://stemedplus.org/): one page that shows new
visitors (research faculty, graduate students, K-12 teachers, and STEM instructors) where to go
first, organized as **Find → Build → Share**.

Live at **https://jlib271.github.io/stemed-start-here/**

## What's on the page

1. **Find · Build · Share** banner. Each card jumps to its part of "How it all fits together".
2. **ROLE: I am a…** Four role buttons. Each shows a four-step path (Find, Sign in, Build, Share back).
   Link straight to a role with `#faculty`, `#grad`, `#k12`, or `#instructor`.
3. **GOAL: I want to…** Four goal groups. Picking a role marks the goals suggested for it.
   `#goals` jumps here.
4. **Do I need an account?**
5. **How it all fits together**, with the find → build → share network picture.

Without JavaScript, all four role paths show one after another, so nothing is hidden.

## Editing

Everything is in `site/index.html`. Links, role paths, and goals are plain HTML: edit the text or the
`href` and commit. A goal's `data-who` lists the roles it is suggested for.

The green band, menu, and footer come from [stemedplus-theme](https://github.com/JLib271/stemedplus-theme)
and are refreshed at every publish; don't edit them here. Icons are in `site/icons/`.

## Publishing

`.github/workflows/publish.yml` publishes `site/` to GitHub Pages on every push to `main` and weekly.
Turn on once: **Settings → Pages → Source: GitHub Actions**.
