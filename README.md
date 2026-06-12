# ML Shelf

A curated collection of free, trusted AI/ML learning resources.

**Live site:** https://spironan.github.io/ml-knowledge-base/

## Adding a resource

Edit `index.html` and push an object to the `resources` array:

```js
{
  title: "Resource Title",
  author: "Author Name",
  categories: ["Explainers", "Transformers"], // first = section/filter placement
  description: "Brief description.",
  url: "https://example.com"
}
```

- First category determines filter grouping: `Explainers`, `University Course`, `Projects`, or `Articles`. Remaining categories are topic tags.
- Entries auto-sort by category → author → title; array order doesn't matter.
- To add a new filter category, append the string to `primaryCategories` and (optionally) a strip color to `categoryColor`.

## Curation bar

Resources must be free, from a reputable source, and actively available. Prefer deep links to the specific series/course over channel or site roots.

## Stack

Single HTML file. No build step, no dependencies.

## Attribution

Resource curation by [spironan](https://github.com/spironan). Page design and code were created with AI assistance (Anthropic's Claude).
