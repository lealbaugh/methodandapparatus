Posts go in `_posts` and are formatted thusly:
```
---
layout: post
title: "Title"
date: yyyy-mm-dd hh:mm:ss -0500
preview-image: "nameofimage.jpg"
---
Whatever you want to say, in Markdown.
```
Where "preview-image" is an image in `img`.

`jekyll serve -w --baseurl=` to build and serve locally (at `http://localhost:4000/`); `jekyll build` to build the site for deployment elsewhere.