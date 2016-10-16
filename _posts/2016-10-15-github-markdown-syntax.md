---
layout: post
title: gitgub markdown
categories: markdown
description: description and syntax of git markdown
keywords: markdown syntax
---

# introduction of Github Flavored Markdown
Markdown is a lightweight and easy-to-use syntax for styling all forms of writing on the GitHub platform.

## Syntax guide

Here’s an overview of Markdown syntax that you can use anywhere on GitHub.com or in your own text files.

### Text & Emphasis
>\*\*xxxx\*\* make some words **blod**

>\*yyyy\* make some words *italic*

>'*' = '_'



### Headers & Quotes
>#space=h1

>#######space=h6

\>this is a quotes
>this is a Quotes

### Lists
#### Ordered
>\1. itemA

1. itemA

#### Unordered
>\- itemB

- itemB

>\* itemC

* itemC

>\* itemC

>[Tab]\* itemD

* itemC
  * itemD

### Image & Links
If you want to embed images, this is how you do it:

>\!\[title](https://octodex.github.com/images/yaktocat.png)

>Format: \!\[Alt Text](url)

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)


>Format:\[GitHub](http://github.com)

http://github.com - automatic!
[GitHub](http://github.com)

### Code & Inline code
>\`\`\`perl/python/shell ...

>xxx

>\`\`\`

```perl
#!usr/bin/perl -w
use strict;
open IN,shift||die;
while(<IN>)
{
    print "Hello World!\n";
}
```
>I think you should use an

>\`xxxx\` element here instead.

I think you should use an
`<addr>` element here instead.

### Extras
>\- [x] This is a complete item

>\- [ ] This is an incomplete item

- [x] This is a complete item
- [ ] This is an incomplete item

### Tables
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

### Strikethrough

Any word wrapped with two tildes (like ~~this~~) will appear crossed out.

### Emoji

GitHub supports emoji! :sparkles: :camel: :boom:

To see a list of every image we support, check out the [Emoji Cheat Sheet](http://www.emoji-cheat-sheet.com/).

### SHA references

Any reference to a commit’s SHA-1 hash will be automatically converted into a link to that commit on GitHub.

16c999e8c71134401a78d4d46435517b2271d6ac
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac

### Issue references within a repository

Any number that refers to an Issue or Pull Request will be automatically converted into a link.

>#1

>mojombo#1

>mojombo/github-flavored-markdown#1

### Username @mentions

Typing an @ symbol, followed by a username, will notify that person to come and view the comment. This is called an “@mention”, because you’re mentioning the individual. You can also @mention teams within an organization.

### Automatic linking for URLs

Any URL (like http://www.github.com/) will be automatically converted into a clickable link.
