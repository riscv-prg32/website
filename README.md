# PRG32 website

The official Jekyll website for [PRG32](https://github.com/riscv-prg32), an open-source platform for learning RISC-V assembly and C through game development.

## Run locally

```bash
bundle install
bundle exec jekyll serve
```

Open `http://127.0.0.1:4000/website/`.

## Deploy

Pushes to `main` are built and deployed by the GitHub Pages workflow in `.github/workflows/pages.yml`. In the repository settings, select **GitHub Actions** as the Pages source.
