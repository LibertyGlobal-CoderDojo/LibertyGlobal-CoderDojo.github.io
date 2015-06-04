CoderDojo@LibertyGlobal site
============================

Jekyll theme based on [Freelancer bootstrap theme ](http://startbootstrap.com/templates/freelancer/)

## How to use

### Add a project

 - Place an image in `/img/posts/`
 - Create posts to display your projects. Use the follow as an example:

```txt
---
title: My Project
layout: post
img: cabin.png
alt: image-alt
categories: project
---

The post Markdown content here
```

- The file should be named using a date at the start of the filename, ie: `dd-mm-yyyy-title.md`
  - The title from the file name will be used in the URL to the page
  - The date from the file name will be used to order the projects on the front page
- The `title` field will overide the title in the file name when the content is rendered (not in the URL though)
- The `layout` should always be set to `post`
- the `img` should be a file path relative to `/img/posts`
- Adding `project` to the `categories` will ensure that the post is listed under projects
  - Any categories added will also be used in the URL to the page

### Add an event

 - Place an image in `/img/posts/`
 - Create posts to display your events. Use the follow as an example:

```txt
---
title: My Event
layout: post
img: cabin.png
alt: image-alt
categories: event
---

The post Markdown content here
```

- The file should be named using a date at the start of the filename, ie: `dd-mm-yyyy-title.md`
  - The title from the file name will be used in the URL to the page
  - The date from the file name will be used to order the events on the front page
- The `title` field will overide the title in the file name when the content is rendered (not in the URL though)
- The `layout` should always be set to `post`
- the `img` should be a file path relative to `/img/posts`
- Adding `event` to the `categories` will ensure that the post is listed under events
  - Any categories added will also be used in the URL to the page

### To preview locally

Install prerequisites

```
./prepare.sh
```

Launch local server

```
./start.sh
```
