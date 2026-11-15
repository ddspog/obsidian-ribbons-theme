# Ribbons Theme for Obsidian

This theme was developed for Obsidian, offering a rich, modular, and customizable visual experience.

## Structure of the `src/` folder

The `src/` folder contains all SCSS source files organized by function. Below is a summary of the main folders and their purposes:

- **_assets.scss**  
  Global variables, mixins, and functions shared throughout the theme.

- **callouts/**  
  Styles for callout boxes, organized into subfolders:
  - `decorative/`: Decorative callouts such as ribbons and letters.
  - `layout/`: Layout structures for callouts (blocks, entries).
  - `options/`: Style options for callouts (hiding the title).

- **editor/**  
  Styles specific to the Obsidian editor, including the file explorer and properties view.

- **embed/**  
  Styles for embedded elements (embeds), such as images, fields, headings, and overflow control.

- **markdown/**  
  Styles for markdown rendering, with subfolders for different content types:
  - `default/`: Headings, cells, links, quotes, etc.
  - `feature/`, `item/`, `spell/`, `statblock/`: Styles for specific note or resource types.

- **settings/**  
  Styles for the theme's settings screens and options.

- **tags/**  
  Styles for tags and related elements, organized into subfolders for different tag types.

- **tasks/**  
  Styles for task lists and checklists.

---

Character sheets, stat blocks, spell cards and the like are drawn by the [RPG UI plugin](https://github.com/ddspog/obsidian-rpg-ui), which carries its own styles; the theme no longer holds components for them, nor rules for Dataview, Meta Bind, Leaflet or Iconize.

Each subfolder and SCSS file was created to modularize and facilitate the maintenance of the theme, allowing for customization and expansion as needed.

## How to use

1. Install the theme in Obsidian.
2. Activate the theme in the appearance settings.
3. (Optional) Edit the SCSS files to further customize the look.

If you need more details about any specific directory or file, open an issue or get in touch!