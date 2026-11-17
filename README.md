# Jamal Shopify Sections

Two lightweight, standalone sections for Shopify Online Store 2.0 themes.
Designed for merchants and students who want editable content without an app,
external scripts, or a build process.

## Included

| Section | Features |
| --- | --- |
| JAS FAQ | Native keyboard-operable disclosure controls, rich-text answers, optional first answer open, up to 20 questions |
| JAS Benefits | Responsive cards, 1–4 desktop columns, up to 8 benefits, rich-text descriptions |

Both sections have editable headings and colors, instance-scoped styles, and
Shopify block selection attributes. No external dependencies or tracking.
This is a new, AI-assisted project; no adoption or compatibility claims are made.

## Install

1. Duplicate your Shopify theme as a backup and work on the duplicate.
2. Open its code editor.
3. Add the two files from this project's `sections/` folder to the theme's
   `sections/` folder, preserving the filenames. Do not paste the schema into
   a Custom Liquid block.
4. Open the theme editor and select a page using a JSON template.
5. Choose **Add section**, then **JAS FAQ** or **JAS Benefits**.
6. Add/reorder blocks and replace the example content with actual store details.
7. Preview on desktop and mobile before publishing the theme.

This ZIP is a section collection, not an uploadable complete Shopify theme.
To remove a section, remove its instances in the theme editor, then delete its file.

## Configuration

Use the section's color controls for readable text/background contrast.
The sections inherit the theme font. All content is editable in the theme editor.
Links in rich text retain an underline. FAQ answers operate without JavaScript.
Each FAQ opens independently; selecting a closed FAQ block in the editor may
require opening its summary manually.

## Validation and limits

Embedded JSON schemas and setting references were checked locally.
No live Shopify store rendering or Shopify Theme Check run has been completed.
Third-party themes may introduce styling conflicts. Follow
[the manual checklist](docs/TESTING.md) before production use.
There is no automatic FAQ structured data, cart behavior, or translation service.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). Useful improvements include documented
theme compatibility, accessibility fixes, and genuinely useful small sections.

## License

MIT — see [LICENSE](LICENSE). Independent project, not affiliated with Shopify.

## Reference

- https://shopify.dev/docs/storefronts/themes/architecture/sections/section-schema
- https://shopify.dev/docs/storefronts/themes/best-practices/editor/integrate-sections-and-blocks
