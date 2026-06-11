# ML Knowledge Base

A curated collection of free, trusted AI/ML learning resources.

**Live site:** https://spironan.github.io/ml-knowledge-base/

## Adding a resource

Edit `index.html` and push an object to the `resources` array:

```js
{
  title: "Resource Title",
  author: "Author Name",
  categories: ["YouTube", "Deep Learning"],
  description: "Brief description.",
  url: "https://example.com",
  difficulty: "Beginner" // Beginner | Intermediate | Advanced
}
```

To add a new filter category, append the string to `primaryCategories`.

## Stack

Single HTML file. No build step, no dependencies.
