# PRG32 website

The official Jekyll website for [PRG32](https://github.com/riscv-prg32), an open-source platform for learning RISC-V assembly and C through game development.

## Run locally

```bash
brew install ruby@3.3
bin/setup
$(brew --prefix ruby@3.3)/bin/bundle exec jekyll serve
```

Open `http://127.0.0.1:4000/website/`.

## Build locally

```bash
bin/build
```

The project scripts deliberately use Homebrew Ruby 3.3 instead of macOS system Ruby,
which is obsolete and cannot safely install project gems. Dependencies are kept in
the ignored `vendor/bundle` directory.

## Deploy

Pushes to `main` are built and deployed by the GitHub Pages workflow in `.github/workflows/pages.yml`. In the repository settings, select **GitHub Actions** as the Pages source.
