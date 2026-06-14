# wdd331R_aCSS

WDD 331R Practice Site for Advanced CSS

## Author

**Student:** Harrison Merrill
**Semester:** Spring 2026
**Live Site:** [View Site](https://hwalkermerrill.github.io/wdd331R_aCSS/)

## About

This repository is my Practice Site for WDD 331R: Advanced CSS.
Each week I add new pages and styles as I work through the course
assignments. The site deploys automatically to GitHub Pages on
every push to main. This site supports dark mode.

## Structure

Each topic is sorted by unit, with files required for the main functioning of the
site living in the root folder, and demonstrations held inside the demo folder.

```text
wdd331R_aCSS
├── css/
├── demo/
├── dist/
├── unit-1/
├── unit-2/
├── ...
└── index.html
```

## Main Pages

- [Home](index.html)
- [Custom Properties and Nesting](unit-1/custom-properties/index.html)
- [Layered Components](unit-2/layered-components/index.html)
- [Visual Effects](unit-3/visual-effects/index.html)
- [Editorial Layout](unit-4/grid-layouts/editorial.html)
- [Grid Layouts](unit-4/grid-layouts/cards.html)

## Demo Pages

- [Attribute Selectors](demo/attributeSelectors.html)
- [::Part and ::Slotted](unit-2/part-and-slotted/index.html)
- [Contrast Color](demo/contrastColor.html)
- [Display: Contents](demo/displayContents.html)
- [Container Queries](demo/containerQuery.html)

## CSS

CSS is organized into layers(vendor, tokens, base, layout, components, utilities)
and then processed via lightningcss-cli into a minified styles.css. This is built
manually through a pnpm build command, which is also done automatically once the
site is deployed via github's deploy-website.yml.

```text
css/
├── base/
├── components/
├── layout/
├── tokens/
├── utilities/
├── vendors/
└── main.css
```
