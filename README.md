# Volmit assets

Assets for Volmit projects. Each project has a folder at the root. Company artwork goes in [brand/](brand/).

## Organization

Group files by type within each project. Only create folders you need.

| Folder | Contents | Example |
| --- | --- | --- |
| `icons/` | Icons and variants | [Wormholes](wormholes/icons/) |
| `logos/` | Logos and wordmarks | [Iris](iris/logos/) |
| `screenshots/` | In-game screenshots | [Gloss](gloss/screenshots/) |
| `demos/` | Animated demos | [Gloss](gloss/demos/) |
| `thread-designs/` | Marketplace and forum panels | [Adapt](adapt/thread-designs/) |
| `backgrounds/` | Background artwork | [React](react/backgrounds/) |
| `banners/` | Banners and signatures | [React](react/banners/) |
| `source/` | Editable originals and raw files | [React](react/source/) |

Add subfolders for larger collections, like [Iris biomes](iris/screenshots/biomes/). Use `shared/` for assets used by multiple projects.

## Adding assets

- Use short, descriptive names in lowercase with hyphens.
- Keep thread panels numbered in order, starting with `01-hero.png`.
- Add a size, color, or style when needed to tell variants apart.
- Keep editable originals in `source/`.
- Avoid duplicate copies.

## Linking assets

Renaming or moving a file changes its URL. Update links that use it, and publish the asset before using the new URL in live content.
