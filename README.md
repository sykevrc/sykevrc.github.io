# My Engineering Blog

Jekyll-powered GitHub Pages site.

## Add a post

Create `_posts/YYYY-MM-DD-title.md` with front matter:

```yaml
---
title: "My Project"
date: 2026-09-05
author: "John Doe"
category: "Robotics"
tags: [VEX, PROS]
read_time: 6
image: /img/project-hero.jpg
image_alt: "Robot during testing"
description: "Short description for search and the home page."
---
```

Then write normal Markdown below it.

## Standard media

Use the provided includes so every post gets consistent styling:

- Photo: `{% include image.html src="/img/photo.jpg" alt="Description" caption="Optional caption" %}`
- Video: `{% include video.html src="/media/run.mp4" type="video/mp4" caption="Optional caption" %}`
- Embed: `{% include embed.html src="https://www.youtube.com/embed/VIDEO_ID" title="Video title" %}`
- Link: `{% include link.html url="https://example.com" title="Project documentation" description="Optional description" %}`

Put local photos in `img/` and local videos in `media/`.
