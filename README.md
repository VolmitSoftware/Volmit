# Volmit assets

Images, animations, and design files for Volmit projects. Each project has its own folder at the repository root. Company artwork lives in [brand/](brand/).

## Organization

Keep an asset with the project that owns it, then group it by purpose. Create a category folder when it has files to hold.

| Folder | Contents | Example |
| --- | --- | --- |
| `icons/` | Project icons, symbols, and their style or size variants | [Inscribe icons](inscribe/icons/) |
| `logos/` | Wordmarks and composed logo artwork, including vector exports | [Iris logo](iris/logos/) |
| `screenshots/` | Captures and still images showing the project | [Gloss screenshots](gloss/screenshots/) |
| `demos/` | Finished animated feature demonstrations | [Gloss demos](gloss/demos/) |
| `thread-designs/` | Ordered panels for marketplace descriptions and forum threads | [Adapt thread design](adapt/thread-designs/) |
| `backgrounds/` | Artwork used behind text or other design elements | [React backgrounds](react/backgrounds/) |
| `banners/` | Signatures and promotional banners | [React banners](react/banners/) |
| `source/` | Editable originals, raw captures, and original design bundles | [React source files](react/source/) |

Use subject subfolders when a collection needs them, such as [iris/screenshots/biomes/](iris/screenshots/biomes/). Reserve `shared/` for templates or design elements used by multiple projects; create it when shared assets are added.

## Adding assets

- Use lowercase folder and file names with hyphens between words. Match the project's name, such as `foundation/`.
- Use `icon.png` for a project's default PNG icon and descriptive variant names such as `icon-flat.png` or `icon-charcoal.svg`. Keep distinct formats and designs when they serve different uses.
- Keep numbered thread panels in reading order, using two-digit prefixes followed by their topic, such as `01-hero.png` and `05-commands-and-permissions.png`.
- Name screenshots by the visible subject or state, such as `sunlit-conifer-valley.png`, `entity-overlay-slime.png`, or `furnace-preview-smelting.png`. Avoid guessing a biome's formal name from its appearance.
- Name visual variants by their distinguishing shape, color, or treatment, such as `icon-circle-mint.png` or `symbol-shadow-blue.png`.
- Add dimensions when keeping multiple sizes of the same design, such as `symbol-black-256.png` and `symbol-black-512.png`. Use width and height for rectangular variants, such as `wordmark-signature-455x170.png`.
- Give raw and finished animations matching stems, such as `chat-bubbles-conversation-raw.gif` in `source/` and `chat-bubbles-conversation.gif` in `demos/`.
- Keep one copy of each identical asset. Reference its existing path wherever it is needed.
- Preserve original image quality and editable files. Store raw captures in `source/` and finished animations in `demos/`.

## Linking assets

Use the asset's canonical repository path in websites, documentation, announcement profiles, and marketplace content. For example, the Iris icon is `iris/icons/icon.png`.

Moving or renaming an asset changes its hosted URL. Update consumers whenever a path changes, and publish the assets before using their new URLs in live content. Historical imports and delivery receipts retain the URLs captured at the time.
