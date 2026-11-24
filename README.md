<p align="center">
  <img src="./organization/logos/header.svg" alt="Powerline Dev" width="480" />
</p>

# Branding

Official brand assets and visual identity of Powerline Dev.

This repository serves as the central source for logos, icons, banners, social previews, screenshots, project descriptions, and brand guidelines across all Powerline Dev projects.

## Repository Structure

```text
branding/
├── organization/
│   ├── logos/
│   ├── banners/
│   ├── social-preview.png
│   └── description.txt
├── projects/
│   ├── codex-powerline-cli/
│   │   ├── logos/
│   │   ├── banners/
│   │   ├── screenshots/
│   │   ├── social-preview.png
│   │   └── description.txt
│   ├── codex-powerline-vscode/
│   │   ├── logos/
│   │   ├── banners/
│   │   ├── screenshots/
│   │   ├── social-preview.png
│   │   └── description.txt
│   └── codex-powerline-core/
│       ├── logos/
│       └── description.txt
├── guidelines/
│   ├── colors.md
│   └── typography.md
└── README.md
```

## Projects

| Project | Description |
|---|---|
| `codex-powerline-cli` | Customizable Powerline statusline for OpenAI Codex CLI. |
| `codex-powerline-vscode` | Powerline integration for the Codex VS Code extension. |
| `codex-powerline-core` | Shared components, themes, configuration, and utilities. |

## Brand Identity

The Powerline Dev visual identity is built around simplicity, bold monospace typography, and a signature color gradient transitioning from indigo through purple and coral to golden yellow.

All projects follow a consistent visual language while maintaining their own product-specific assets.

## Usage

Assets can be referenced directly from other repositories using raw GitHub URLs.

### Organization Logo

```html
<p align="center">
  <img
    src="https://raw.githubusercontent.com/powerline-dev/branding/main/organization/logos/header.svg"
    alt="Powerline Dev"
    width="480"
  />
</p>
```

### Project Assets

Project-specific assets are located under:

```text
projects/<project-name>/
```

This repository is intended to be the single source of truth for all Powerline Dev branding assets.

## Organization

[Powerline Dev](https://github.com/powerline-dev)