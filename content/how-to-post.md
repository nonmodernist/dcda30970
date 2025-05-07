---
title: "How to Post"
---
# How to post to this site

When it's your turn to contribute a blog post, use these instructions:

## 1. Create your .md file

In VSC, create a new file and name it something unique having to do with your topic, for example, `ocean-swimming.md`. The file name determines the URL your post will eventually live at, so it needs to be appropriate, short, and unique. It also has to end in `.md`, which makes sure it's in Markdown. 


## 2. Add your front matter

The [front matter] is a little piece of code right at the beginning that contains the metadata for your post. It determines things like the title, date, author, and tags that will be shown on the site. 

Your front matter needs to contain:

- your name (first name or nickname only is fine)   
- the title of your post
- the date of your post
- a short description of your post
- at least 2 tags

You may choose to include the filename of a featured image, but you don't have to.

For example, here is the front matter from my first blog post:

```
+++
author = "Dr. Edwards"
title = "Week 1: Introduction / Infrastructure"
date = "2025-08-19"
description = "Notes on the first week of DCDA 30970"
tags = [
    "week notes",
]
image = ['share.webp']
+++
```

## 3. Write your post in Markdown

As you write your post, you will want to use [Markdown](https://daringfireball.net/projects/markdown/syntax) to style the text and add links and images. 

For example, putting an asterisk `*` on either side of a word or phrase will make that text italic.

So this:

```
This is an activity adapted from Ingrid Burrington's *Networks of New York*.
```

becomes this: 

This is an activity adapted from Ingrid Burrington's *Networks of New York*.

---

To create a link, wrap a word or phrase in square brackets `[ ]` and put the link in parentheses `( )` immediately after the closing bracket.

So this:

```
This is an [example link](http://example.org).
```

becomes this: 

This is an [example link](http://example.org).


---

To add an image, you'll need to save the image with a short, unique file name, such as `fire.jpg`. Then you can use our site's [shortcode] to call the image and record the metadata. 

So this:

```

 <img src="share.jpg"
  alt="The top of building featuring cell towers and a small steam stack, silhouetted against a smoggy orange sunset."
  caption="A smoggy urban sunset matches the color scheme of our site. Credit: Pixabay." >

```

becomes this:

<img
  src="share.jpg"
  alt="The top of building featuring cell towers and a small steam stack, silhouetted against a smoggy orange sunset."
  caption="A smoggy urban sunset matches the color scheme of our site. Credit: Pixabay."
  >

The `alt` text should describe the image for sight-impaired people who may use a screen reader to access the internet. The caption should contextualize the image and include credit. 

## 4. Upload your .md file and images to Github

Go to [our Github repository](https://github.com/nonmodernist/dcda30970) and navigate to the correct folder (also called a directory). Click the `Add File` button and then choose `Upload Files`. Follow the instructions on the page to upload your files. 

**IMPORTANT:** your files must go into the correct folders for the site to work. 

- Your `.md` file needs to go into [/content/blog]
- If you have images, they need to go into [static]. 

Once you have committed your changes, the site should automatically rebuild and publish your post within a few minutes, thanks to some complicated stuff on the backend that Dr. Edwards has set up. 


## 5. If you need to make changes

If you've already uploaded your files and then realize that you need to change something, like a typo, you can navigate to your `.md` file in our repository and click the pencil icon on the right. This will let you edit the text right there and commit your changes. 