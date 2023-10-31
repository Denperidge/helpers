# Denperidge's Helpers

Boilerplate code that may need to be adapted per project!

## Accessibility 
Ready-to-drop files to...
- Add a `skip-link` *(an element that will only be visible for keyboard navigation to skip to the main content, improving the usability and accessibility of your site)*
- Add a `sr-only` class *(a class you can use for headings that you stylistically want to hide, but may be important for those with limited vision)*

### How-to
Add one of the following...
- [.css](accessibility/accessibility.css)
- [.scss](accessibility/_accessibility.scss)

... and one of the following ...
- [.html](accessibility/accessibility.html)
- [.pug](accessibility/accessibility.pug)

### Source
The skip-link element and sr-only class are respectively based on [W3Schools' Skip link page](https://www.w3schools.com/accessibility/accessibility_skip_links.php) and [W3Schools' Heading levels page](https://www.w3schools.com/accessibility/accessibility_heading_levels.php)


## Eleventy
An extractable template with...
- YAML & SASS/SCSS (including importing from `node_modules`) support
- Directory structure with `src/` and `dist/`
- Base template which has a skip-link & allows for custom title + page specific stylesheet import
- Templates extending base template into page.md & page.pug, which when used get automatically added in nav
- Classes from [the accessibility section above](#accessibility) built-in

### How-to
## Usage
Simply [click here to download eleventy.zip](https://github.com/Denperidge/helpers/releases/latest/download/eleventy.zip) or go to the [releases page](releases/). Then simply extract, and you're set!

## License