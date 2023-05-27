---
title: Report formatting
subtitle: How to make a report in the markdown
authors:
  - Aisha Kin
tags: []
categories: []
projects: []
date: '2023-29-03T00:00:00Z'
lastMod: '2023-29-03T00:00:00Z'
image:
  caption: ''
  focal_point: ''
---

Report formatting in the course is done using the Markdown markup language. 
In the beginning of the file type md prescribe the necessary settings of the text and the report as a whole, its content.
For example, the font size, font type, etc.
I will talk specifically about the basic rules of markdown formatting.

# Headlines

The Markdown markup language supports two header styles: underscores and underlines ("#").
Headings are underlined with equals ("=") if they are first-level headings, and hyphens ("-") if they are second-level headings.
The number of underscores is not limited. When headings are highlighted with the symbol ("#"), from one to six of these characters are used, which are set at the beginning of the line (before the header).

Headings of the first, third level, made with the symbol ("#"), are as follows:

# First level header
### Level 3 header

# Quotes

The Markdown language uses the "more" (">") sign to indicate quotations. It can be inserted either before each line of a quotation, or just before the first line of a paragraph. Markdown syntax also allows you to create nested quotations (quotations within quotations). They are marked up with extra levels of quotation marks (">"). Markdown quotes can contain all sorts of markup elements. Markdown citations look as follows:

>This is an example of a quotation 
>in which an angle bracket 
>is placed before each line.

Attachment of the quote to the quote is as follows:

> The first level of citation
>> Second level of citation
>>> The third level of citation

# Lists

Markdown supports both ordered (numbered) and unordered (unnumbered) lists.
Markers such as asterisks, pluses, and hyphens are used to form unordered lists.
All of these tokens can be used interchangeably.
For ordered lists, numbers with a dot are used as tokens.

1. Conductor
2. Semiconductor
3. Dielectric

Unordered lists are as follows:

* Conductor
* Semiconductor
* Dielectric

or
- Conductor
- Semiconductor
- Dielectric

or

+ Conductor
+ Semiconductor
+ Dielectric

# Highlighting text

Markdown recognizes asterisks "*" and underscores "_" as indications of semantic
text emphasis

In other words, text surrounded by single characters is italicized, and
text surrounded by double characters is highlighted in bold. Also, the highlighted
fragment may be in any part of the word. Text that is italicized using
Markdown syntax looks like this:

*Example*

The text in bold using Markdown syntax looks like this,
is as follows:


**Example**

Text in italic bold using the syntax of the
Markdown syntax is as follows:

***Example***