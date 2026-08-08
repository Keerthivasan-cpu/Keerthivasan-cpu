# GitHub Contribution Snake Setup

This workflow generates `snake-light.svg` and `snake-dark.svg` from the contribution graph of `Keerthivasan-cpu` and publishes them to the `output` branch.

## Setup

1. Open your `Keerthivasan-cpu` profile repository.
2. Create `.github/workflows/snake.yml`.
3. Copy the provided workflow into it.
4. Commit and push.
5. Open **Actions → Generate Contribution Snake**.
6. Click **Run workflow**.
7. After it succeeds, the `output` branch will contain the SVG files.

## README code

```html
<div align="center">

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/Keerthivasan-cpu/Keerthivasan-cpu/output/snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/Keerthivasan-cpu/Keerthivasan-cpu/output/snake-light.svg"
  />
  <img
    alt="Keerthivasan's GitHub contribution snake"
    src="https://raw.githubusercontent.com/Keerthivasan-cpu/Keerthivasan-cpu/output/snake-light.svg"
  />
</picture>

</div>
```
