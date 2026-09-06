---
title: "Example: A Standard Engineering Post"
date: 2026-09-05
author: "Johnson Wei"
category: "Engineering"
tags: [robotics, engineering]
read_time: 5
image: /img/hero.jpg
image_alt: "Example project hero image"
description: "A template showing the standard format for engineering blog posts."
---

Write your introduction here. Each post is now just a Markdown file with front matter at the top.

## The problem

Explain what you were trying to build, what failed, and why it mattered.

## The solution

Use normal Markdown for text, headings, lists, code, and links.

```python
print("Code blocks work normally.")
```

### Add a photo

Replace the values below with a file in your `img/` folder:

{% include image.html src="/img/project.jpg" alt="Robot prototype on the workbench" caption="The first prototype." %}

### Add a video

{% include video.html src="/media/test-run.mp4" type="video/mp4" caption="Autonomous test run." %}

### Add an embed

{% include embed.html src="https://www.youtube.com/embed/VIDEO_ID" title="Project demonstration" %}

### Add a link

{% include link.html url="https://github.com/" title="Source code" description="View the project repository." %}

## Results

Finish with measurements, results, lessons learned, and what you would change next.
