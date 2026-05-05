# GitHub Contribution Snake Setup

This profile repo now includes `.github/workflows/generate-snake.yml`.

## What it does

- Generates `github-contribution-grid-snake.svg` for the GareBear99 profile.
- Generates `github-contribution-grid-snake-dark.svg` for dark mode.
- Publishes both SVGs to the `output` branch.
- Runs on push to `main`, manually through workflow dispatch, and daily at midnight UTC.

## Required GitHub setting

Go to:

```text
Settings → Actions → General → Workflow permissions → Read and write permissions → Save
```

Then run:

```text
Actions → Generate GitHub Contribution Snake → Run workflow
```

After the first successful run, the README will show the snake animation from:

```text
https://raw.githubusercontent.com/GareBear99/GareBear99/output/github-contribution-grid-snake.svg
https://raw.githubusercontent.com/GareBear99/GareBear99/output/github-contribution-grid-snake-dark.svg
```

## Files added

```text
.github/workflows/generate-snake.yml
SNAKE_SETUP.md
README.md updated with Contribution Signal Trail section
```
