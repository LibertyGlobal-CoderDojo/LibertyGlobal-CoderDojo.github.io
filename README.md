CoderDojo@LibertyGlobal site
============================

Jekyll theme based on [Freelancer bootstrap theme ](http://startbootstrap.com/templates/freelancer/)

## How to use

### Add a page

 - Place an image in `img/posts/`
 - Create posts in `_posts/` to display your projects or events. Use the following as an example:

```txt
---
title: My Project
layout: post
img: cabin.png
alt: My Project
categories: project
thread_id: my-project
---

The post Markdown content here
```

- The file should be named using a date at the start of the filename, ie: `YYYY-MM-DD-title.md`
  - The title from the file name will be used in the URL to the page
  - The date from the file name will be used to order the items on the front page
    - If more fine grained ordering is required then the date can be overriden in the yaml front matter of the post [docs](http://jekyllrb.com/docs/frontmatter/#predefined-variables-for-posts)
- The `title` field will overide the title in the file name when the content is rendered (not in the URL though)
- The `layout` should always be set to `post`
- the `img` should be a file path relative to `img/posts/`
- the `alt` should be the `alt` text to associate with the `img`
- Adding `project` to the `categories` will ensure that the post is listed under projects. Adding `event` to the `categories` will list the post under events
  - Any categories added will also be used in the URL to the page
- Add a unique `thread_id` (without spaces, etc) to add a [muut](https://muut.com/) comment thread to the post

### To preview locally

Install prerequisites

```
./prepare.sh
```

Launch local server

```
./start.sh
```
