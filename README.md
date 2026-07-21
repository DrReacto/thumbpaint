# thumbpaint

Static site hosting privacy policies and support pages for apps
published under Thumbpaint. Served via GitHub Pages at
[thumbpaint.com](https://thumbpaint.com).

Structured per-app so new apps just add a new top-level folder:

```
neveramin/
  privacy/index.html
  support/index.html
```

When a new app ships (e.g. p23), add a matching `<app>/privacy/` and
`<app>/support/` folder and link it from `index.html`.

No build step — plain static HTML/CSS, deployed as-is.
