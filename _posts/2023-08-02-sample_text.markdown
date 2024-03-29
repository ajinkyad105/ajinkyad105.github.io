---
layout: post
title: "Markdown syntax guide"
date:   2023-08-02 18:58:09 +0530
categories: jekyll update
---
<!---*#* layout: archive, single, home, none, default, blog, page-->
<!---*#* excerpt: "In this post, we'll explore..."-->
<!---*#* image: /path/to/featured-image.jpg , Specifies a featured image or thumbnail for the content. This image can be displayed alongside the content or when sharing on social media.
author: John Doe
categories: [Jekyll, Tutorial]
tags: [web development, static site generator]-->

## Headers

# This is a Heading h1
## This is a Heading h2 
###### This is a Heading h6

## Emphasis

*This text will be italic*  
_This will also be italic_

**This text will be bold**  
__This will also be bold__

_You **can** combine them_


newline 
<br />
new\
line
## Lists

### Unordered

* Item 1
* Item 2
* Item 2a
* Item 2b

### Ordered

1. Item 1
1. Item 2
1. Item 3
  1. Item 3a
  1. Item 3b

## Images

![This is an alt text.](/image/sample.png "This is a sample image.")

## Links

You may be using [Markdown Live Preview](https://markdownlivepreview.com/).

## Blockquotes

> Markdown is a lightweight markup language with plain-text-formatting syntax, created in 2004 by John Gruber with Aaron Swartz.
>
>> Markdown is often used to format readme files, for writing messages in online discussion forums, and to create rich text using a plain text editor.

## Tables

| Left columns  | Right columns |
| ------------- |:-------------:|
| left foo      | right foo     |
| left bar      | right bar     |
| left baz      | right baz     |

## Blocks of code

```
let message = 'Hello world';
alert(message);
```

## Inline code

This web site is using `markedjs/marked`.
