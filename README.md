# Blog
This repository contains my blog. This blog runs on jekyll.

# How to install

1. Clone this repository
2. Install the dependencies.
```bash
$ bundle
```
3. Make changes to config.yml to make it personal.
4. Add posts to in _posts.
5. Compile the site using command.
```bash
$ jekyll build
```
6. Push code to git.

# Add links to Navigation

1. Goto _data/navigation.yml
2. Edit navigation.yml
3. To add links
```
main:
  - title: "title"
    url: link
```
# Add blog posts

The blog posts are written using markdown.
1. Create a md file and name it using 'year-month-day-blog-post-title.md'
2. Add the following lines at the top.
```markdown
---
title:  "Title"
search: true
categories: 
  - category1
  - category2
last_modified_at: year-month-day Time
header:
  teaser: image-location
---
content
```

# Config.yml

Configuring the file will be easy. Just replace my content with yours.

# Breadcrumbs

It is already activated. So you won't have an issue with it.
