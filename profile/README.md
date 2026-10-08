<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://pagepaint.dev/brand/pagepaint-wordmark-light.svg">
  <img alt="Pagepaint" width="280" src="https://pagepaint.dev/brand/pagepaint-wordmark.svg">
</picture>

### Review the page. Show the bug.

Open-source visual feedback for developers and QA. Draw on your app, capture a screenshot or short video, leave a comment, and save the context where your coding agent can read it.

**[Install & demo](https://pagepaint.dev/) · [Source](https://github.com/pagepaint/pagepaint) · [Report an issue](https://github.com/pagepaint/pagepaint/issues) · [Agent guide](https://pagepaint.dev/llms.txt)**

One CDN script or the Chrome / Edge extension. Feedback stays in browser storage, a repo folder you choose, or a ZIP you export. No feedback backend, analytics, or automatic sync. Optional GitHub sharing happens after review.

```html
<script src="https://pagepaint.dev/v0.4.1/pagepaint.js" data-pagepaint defer></script>
```

Repo saves write ordinary files into `.annotations/`. Add to your agent instructions:

> Check `.annotations/` for open items; set status to resolved when done.

Built in plain JavaScript. Free to use, change, and share under the MIT license. Maintained by [DevPlant](https://github.com/DevPlant).
