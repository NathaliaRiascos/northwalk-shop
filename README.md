<h1 align="center" style="position: relative;">
  <br>
    <img src="./assets/shoppy-x-ray.svg" alt="Northwalk logo" width="200">
  <br>
  Northwalk
</h1>

Northwalk is a Shopify store specialized in men's footwear. It offers a selection of shoes from different brands, including Nike, Puma, and Adidas, with a clear, modern, and easy-to-navigate shopping experience.

This project uses [`Shopify/skeleton-theme`](https://github.com/Shopify/skeleton-theme) as its foundation. It preserves Shopify's modular architecture and best practices while adapting them to the needs of a multi-brand men's footwear store.

<p align="center">
  <a href="./LICENSE.md"><img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License"></a>
</p>

## Getting started

### Prerequisites

Before getting started, install Shopify CLI:

- [Shopify CLI](https://shopify.dev/docs/api/shopify-cli)

For working with Liquid in VS Code, install:

- [Shopify Liquid VS Code Extension](https://shopify.dev/docs/storefronts/themes/tools/shopify-liquid-vscode)

### Clone

Clone this repository:

```bash
git clone <https://github.com/NathaliaRiascos/northwalk-shop.git>
```

### Preview

Start a local preview with Shopify CLI:

```bash
shopify theme dev
```

## Theme structure

```bash
.
├── assets          # CSS, JavaScript, images, and fonts
├── blocks          # Reusable components
├── config          # Global theme settings
├── layout          # Main page structure
├── locales         # Translations
├── sections        # Customizable sections
├── snippets        # Reusable Liquid fragments
└── templates       # Page templates
```

See Shopify's [theme architecture documentation](https://shopify.dev/docs/storefronts/themes/architecture) for more information.

## License

This project is available under the [MIT](./LICENSE.md) license.
