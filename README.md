# Automated LaTeX CV Pipeline

Automated build and release pipeline for a single-page LaTeX resume using **GitHub Actions** and **GitHub Releases**.

## Latest Rendered CV
Download the latest compiled PDF from the [**Releases**](https://github.com/LucaTrofim/latex-cv-pipeline/releases) page.

## How It Works
1. Resume source lives in `cv.tex` as version-controlled plain text.
2. Pushing changes triggers a **GitHub Actions** workflow (`build-cv.yml`) that compiles `cv.tex` into `cv.pdf`.
3. Tagged versions (`v*`) automatically publish the compiled PDF as a downloadable asset under **GitHub Releases**.
