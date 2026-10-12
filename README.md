# CITAbleX website

Public site for [citablex.com](https://citablex.com). It introduces the CITAbleX family and starts with CITAble Business.

## Design reference

Lithic: https://styles.refero.design/style/077aecd0-4401-4696-a196-164d74ac8746

Warm cream `#f6f3ee`, ink black `#000000`, ember orange `#ff6600` for actions, architect violet `#5c2999` for frames, lichen green `#00cc88` and sandstone `#aa8855` as supporting accents.

The palette and the page mood are the reference. This site does not copy the source product's name, logo, or copy.

## Develop

```bash
pnpm install
pnpm dev
```

The dev server binds `0.0.0.0`. GitHub Pages deploys from `main` through `.github/workflows/deploy.yml`. Custom DNS for citablex.com is a registrar step after Pages is serving.
