 <p align="center">
  <img src="./organization/logos/header.svg" alt="Powerline Dev" width="480" />
</p>

# Branding

Official brand assets and visual identity of Powerline Dev.

This repository defines the shared visual identity, brand assets, and design guidelines used across Powerline Dev projects.

## Repository Structure

```text
branding/
├── organization/
│   ├── logos/
│   │   ├── icon.svg
│   │   ├── icon.png
│   │   └── header.svg
│   └── description.txt
├── guidelines/
│   ├── colors.md
│   ├── typography.md
│   └── logos.md
└── README.md
```

## Brand Identity

The Powerline Dev visual identity is built around:

- Minimalist, terminal-inspired design.
- Bold monospace typography.
- A signature color gradient transitioning from indigo through purple and coral to golden yellow.
- Consistent visual language across all projects.

## Brand Guidelines

- [Color Palette](./guidelines/colors.md)
- [Typography](./guidelines/typography.md)
- [Logo Guidelines](./guidelines/logos.md)
- [Product README Guidelines](./guidelines/readme.md)

## Brand Assets

| Asset | Description |
|---|---|
| [Icon (SVG)](./organization/logos/icon.svg) | Square organization logo |
| [Icon (PNG)](./organization/logos/icon.png) | Raster organization logo |
| [Header (SVG)](./organization/logos/header.svg) | Horizontal logo with transparent background |

## Usage

Organization assets can be referenced directly from other repositories using raw GitHub URLs.

```html
<p align="center">
  <img
    src="https://raw.githubusercontent.com/powerline-dev/branding/main/organization/logos/header.svg"
    alt="Powerline Dev"
    width="480"
  />
</p>
```

## Project Branding

Each Powerline Dev project maintains its own product-specific assets within its repository, including logos, screenshots, banners, and social previews.

All project assets should follow the shared visual guidelines defined in this repository.

## Active Projects

- [Codex Powerline CLI](https://github.com/powerline-dev/codex-powerline-cli):
  terminal launcher, settings, themes, widgets, and presets.
- [Codex Powerline for VS Code](https://github.com/powerline-dev/codex-powerline-vscode):
  a sidebar terminal that runs the installed CLI.

The former Core library is maintained inside the CLI repository. New product
assets and documentation should point to the CLI or VS Code project.

## Organization

[Powerline Dev](https://github.com/powerline-dev)
