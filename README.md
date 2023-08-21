# Ahanaf writes

This is a lightweight Next.js (v12+) Markdown Blog.

## The nitty gritty

If you'd like to work with this project locally, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

If you'd like to write a new blog post, write it in Markdown in the `posts` directory.

### Installation options

**Option two:** Manual clone

1. Clone this repo: `git clone https://github.com/ahanafasir/portfolio-blog.git`
2. Navigate to the directory and run `npm run dev`
3. Deploy to Netlify

### Styling

Included are some basic styles with [styled-jsx](https://github.com/vercel/styled-jsx), which is included out of the box with Next.js. There's also built-in Sass support and CSS Module support, if you'd prefer to use those.

The font used is [Inter](https://fonts.google.com/specimen/Inter).

### Hero images

You may include an optional hero image in your posts. Put the images in `public/static/`, and then include in your blog .md file like so:

```
---
title: 'Post title'
author: 'Post author'
date: '2023-08-31'
---
```
