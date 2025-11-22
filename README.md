## Zosma AI Blogs

Content repository for blog posts written in `.mdx`. These files are consumed by the `zosma-ai-website` and shown under Fuma Docs → Blogs.

### Add a new post
1) Create a new `.mdx` in the repo root (use kebab-case), e.g. `voice-ai-for-support-teams.mdx`.
2) Paste the frontmatter template below and fill it out.
3) Write your content using Markdown/MDX (`###` for section headings).
4) Commit and push. The website will pick it up on the next deploy.

### Frontmatter template

```mdx
---
title: "Post Title"
description: "Short 1–2 sentence summary"
date: "YYYY-MM-DD"
author: "Zosma AI Team"
authorRole: "AI Engineers"
image: "/images/blogs/your-image.jpeg"
imageAlt: "Accessible image description"
category: "AI & Machine Learning"
tags:
  - AI
  - Machine Learning
keywords:
  - ai development
  - prompt engineering
  - llm
  - machine learning
  - ai tools
featured: false
published: true
readingTime: "5 min read"
---
```

### Notes
- Use images that exist in the website repo under `/images/blogs/...`, and set meaningful `imageAlt`.
- Control visibility/order with:
  - `published: false` → hide from listings (draft)
  - `featured: true` → may be highlighted in listings
  - `date` (YYYY-MM-DD) → used for sorting

### Examples in this repo
- `benefits-of-voice-ai.mdx`
- `how-to-use-ai.mdx`


