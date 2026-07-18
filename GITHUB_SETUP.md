# GitHub Repository Setup Guide

A few professional touches are configured through GitHub's web UI rather
than files in the repository. Once this repo is pushed, do the
following:

## 1. Repository Topics
Go to the repository homepage → gear icon next to "About" → add these
topics:

```
netflix, crime-drama, screenwriting, screenplay, tv-series, mafia, italy,
naples, creative-writing, film, cinematic, storytelling, pitch-deck
```

## 2. Social Preview Image
Settings → General → Social preview → upload
`media/social/social-preview.jpg`. This is the image shown when the
repository link is shared on social media / messaging apps.

## 3. Repository Description & Website
In the same "About" panel, set:
- **Description:** "VESUVIO: Blood of Naples — an original mafia TV
  series pitch package by Ciprian Stefan Plesca."
- **Website:** link to `website/mockups/landing-page-mockup.html` (via
  GitHub Pages, if enabled) or your own project site once live.

## 4. GitHub Pages (optional)
To publish `website/mockups/landing-page-mockup.html` as a live page:
Settings → Pages → Deploy from a branch → select `main` → `/ (root)` or
`/website` depending on preference, then link the page's exact path.

## 5. Releases
Create your first tagged release once the repo is pushed:

- Tag: `v1.0`
- Title: `v1.0 — Pitch Package`
- Description: summarize what's included (story bible, character bible,
  episode guide, pilot script, theme song, key art) — see
  [`CHANGELOG.md`](CHANGELOG.md) for exact contents.

## 6. Branch Protection & Actions
The included workflows (`.github/workflows/`) run automatically on push/
PR once the repo is on GitHub — no extra setup required beyond enabling
Actions if it's disabled by default on your account.
