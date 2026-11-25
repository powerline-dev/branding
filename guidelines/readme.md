# Product README guidelines

Keep product READMEs consistent across CLI, VS Code, and Visual Studio repositories.
Release-folder READMEs are historical release notes and do not use this template.
The branding repository itself is an asset catalog, not a product install guide.

## Section order

1. Centered project header as the first visible content. Keep the supplied header artwork.
2. A short product tagline and description. Only the CLI calls itself ccstatusline rewritten for Codex.
3. A centered **Also supported in** row with linked icons and names for the other two hosts. State that all hosts share CLI layouts, themes, and widgets.
4. A friendly request to star the project.
5. Badges for this repository: social badges, package or host requirements, license, and project activity. Do not imply an unpublished Marketplace listing exists.
6. The current `assets/preview.png`, with useful alt text.
7. Installation, with a heading for each supported operating system and architecture. Even Windows-only products need an explicit Windows heading.
8. Features.
9. Configuration, then troubleshooting when needed.
10. A short invitation to contribute, linked to `docs/development.md`.
11. Author and acknowledgments.
12. License.

## Installation sections

Each supported platform has **📦 Install and launch**, **🔄 Update**, and
**🧹 Uninstall** blocks. Include prerequisites, copy-paste commands or exact IDE
steps, and the first launch. Distinguish an IDE extension from the shared CLI.
State what uninstall keeps. Do not list source-build targets as prebuilt downloads.
Keep publication caveats until the corresponding packages are available.

## Tone and assets

- Write user documentation in English. Keep it friendly, short, and practical.
- Use a few emoji in headings and action labels. Use the same labels across projects.
- Keep product artwork in `assets/`, fonts in `assets/fonts/`, and host icons in `assets/platforms/`.
- Keep host icon sources, rendered PNG files, source links, and licenses together.
- Use PNG host icons for extension-gallery compatibility. Give every linked icon a visible text label.
- Preserve the header aspect ratio. Use the existing PNG header for IDE extensions and SVG for the CLI.
- Include referenced README assets in package allowlists so packed READMEs do not lose images.
- Keep build, test, architecture, and release instructions in `docs/development.md`, not in the product README.
- Keep release history in changelogs or versioned release folders.
- Keep legal attribution in `LICENSE` and `NOTICE`. The IDE README does not repeat the CLI's ccstatusline history.

## Review

Check section order, relative links, images, download filenames, platform support,
package asset lists, and install/update/uninstall coverage after edits.
