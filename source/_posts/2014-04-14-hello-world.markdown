---
layout: post
title: "Hello World"
date: 2014-04-14 15:30:33 -0500
comments: true
categories: General
---

This is my first post using Octopress. I'm still trying to get the hang of it, *and* I don't know markup well enough at the moment. So, let's give it a test-run.
<!-- more -->

I chose Octopress because it offers some handy plugins and its use of Github Flavored Markdown (GFM). So, let's test it out.

## Headers
Let's start with something easy.
# h1 - This is quite large
## h2 - I think I like this one the best
### h3 - Blah blah blah
#### h4 - Getting smaller now...
##### h5 - Almost gone...
###### h6 - And the grand finale

It appears that the h2 header is preceeded by a nice section break, which I like.

## Emphasis
OK, what about *emphasis* and _underscores_? Or maybe **strong emphasis**? What about **_combined emphasis_**? I know, cool ~~story, bro~~.

## Lists
Let's make a list of things I'd rather do that listen to Contemporary Christian music:

1. Get castrated using a butter-knife.
2. Just about anything, including:
* first item in unordered sub-list  _(this is supposed to be a ul li, but it won't work -\_\_\_-)_
  * second item in unordered sub-list
  * this doesn't seem to be working at all

## Links
[I'm an inlike-style link](http://www.google.com)<br>
[I'm an inlike-style link with a title; hover over me!](http://www.google.com "See, I told you.")

## Images
![alt text](https://i.imgur.com/Jx8SJmu.jpg "lolerskates")

## Code and Syntax Highlighting
Inline code is done with a single backtick: `ls -la | grep deeznutz`.  A single line of code can be instantiated by indenting a line with 4 spaces.
    
    String myString = "I'm not used to using markdown and stuff. Note that I don't have syntax highighting :("

Alternatively, you can use three backticks, which will also gives you line numbering and syntax highlighting.  

``` 
$ git clone https://github.com/kbarre123/kbarre123.github.io.git
```

Larger code blocks are also fenced in with three backticks. 

```java Here's some Java code http://www.google.com Link
String myString = "Here's another string."
if (myString.length() > 0)
{
    System.out.printf("%s%n", myString);
}
```

<!--## Tables
Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

The outer pipes (|) are optional, and you don't need to make the raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell -->

## Blockquotes
> This is a blockquote.  
> This is part of the same blockquote b/c I used two spaces after the first line.

## Horizontal Rule
Three or more hyphens, asterisks or underscores will do.

---
***
___

## YouTube Videos
These can't be added directly, but you can add an image with a link to the video like this:  
<a href="https://www.youtube.com/watch?v=dw2vg9xzb4w" target="blank"><img src="https://img.youtube.com/vi/dw2vg9xzb4w/hqdefault.jpg"></a>