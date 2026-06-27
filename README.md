# Lesnack

Private menu content for [walnuts-n-zola](https://github.com/thelazyone/walnuts-n-zola). This folder is gitignored in the theme repo.

## Setup

Requires [Zola 0.19+](https://www.getzola.org/documentation/getting-started/installation/).

One-time theme install:

```powershell
git clone --depth 1 https://github.com/thelazyone/walnuts-n-zola themes/walnuts-n-zola
```

## Local development

```powershell
zola serve
```

Open http://127.0.0.1:1111

To update the theme later:

```powershell
git -C themes/walnuts-n-zola pull
```

## Deploy

Pushes to `main` build and deploy via GitHub Actions (`.github/workflows/deploy.yml`).

1. In the repo **Settings → Pages**, set source to **GitHub Actions**.
2. Push to `main`.

Live site: https://thelazyone.github.io/lesnack/
