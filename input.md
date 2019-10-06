---
title: My Package ABC
---


Pandoc understands a number of useful markdown syntax extensions, including document metadata (title, author, date); footnotes; tables; definition lists; superscript and subscript; strikeout; enhanced ordered lists (start number and numbering style are significant); running example lists; delimited code blocks with syntax highlighting; smart quotes, dashes, and ellipses; markdown inside HTML blocks; and inline LaTeX. If strict markdown compatibility is desired, all of these extensions can be turned off.

LaTeX math (and even macros) can be used in markdown documents. Several different methods of rendering math in HTML are provided, including MathJax and translation to MathML. LaTeX math is converted (as needed by the output format) to unicode, native Word equation objects, MathML, or roff eqn.

Pandoc includes a powerful system for automatic citations and bibliographies, using pandoc-citeproc (which derives from Andrea Rossato’s citeproc-hs). This means that you can write a citation like

```python
import os

x = 7

print(x * 9)
```

## Introduction

$$f(x)=\sum_{n=0}^\infty\frac{f^{(n)}(a)}{n!}(x-a)^n$$

Amet minim nulla laboris exercitation culpa. Commodo consectetur in ullamco culpa sint excepteur sit aliqua anim amet qui. Est velit incididunt id do do fugiat sint. Excepteur voluptate ut amet amet culpa exercitation occaecat elit ipsum aliquip. Excepteur nulla ut ex laborum sunt in nostrud cupidatat labore ea consectetur sunt.

Commodo eiusmod laborum qui eu irure voluptate nisi ea pariatur veniam aliqua dolore minim. Nostrud irure consectetur occaecat dolor minim elit Lorem cillum esse ipsum consectetur. Id commodo reprehenderit magna occaecat. Enim eiusmod laboris velit magna cillum pariatur. Et irure esse nulla sunt cillum esse.

Laborum ad irure id tempor amet elit officia id minim. Velit ad ad excepteur esse velit adipisicing ipsum proident ex. Eiusmod ea adipisicing sint occaecat nisi exercitation nulla non cupidatat. Mollit sint consectetur aute ut minim tempor. Non eiusmod veniam qui dolore dolore.

Commodo esse nisi culpa magna veniam. Culpa reprehenderit labore labore reprehenderit reprehenderit reprehenderit voluptate nostrud in adipisicing. Lorem ea do proident pariatur sit in in quis elit Lorem irure. Ea est consectetur ut velit laboris irure qui.


do. Reprehenderit tempor eiusmod aute irure velit pariatur.

```python
import os

x = 73243232

print(x * 239)
```

$$f(x)=\sum_{n=0}^\infty\frac{f^{(n)}(a)}{n!}(x-a)^n + \cdots$$

Amet minim nulla laboris exercitation culpa. Commodo consectetur in ullamco culpa sint excepteur sit aliqua anim amet qui. Est velit incididunt id do do fugiat sint. Excepteur voluptate ut amet amet culpa exercitation occaecat elit ipsum aliquip. Excepteur nulla ut ex laborum sunt in nostrud cupidatat labore ea consectetur sunt.

Commodo eiusmod laborum qui eu irure voluptate nisi ea pariatur veniam aliqua dolore minim. Nostrud irure consectetur occaecat dolor minim elit Lorem cillum esse ipsum consectetur. Id commodo reprehenderit magna occaecat. Enim eiusmod laboris velit magna cillum pariatur. Et irure esse nulla sunt cillum esse.

Laborum ad irure id tempor amet elit officia id minim. Velit ad ad excepteur esse velit adipisicing ipsum proident ex. Eiusmod ea adipisicing sint occaecat nisi exercitation nulla non cupidatat. Mollit sint consectetur aute ut minim tempor. Non eiusmod veniam qui dolore dolore.

Commodo esse nisi culpa magna veniam. Culpa reprehenderit labore labore reprehenderit reprehenderit reprehenderit voluptate nostrud in adipisicing. Lorem ea do proident pariatur sit in in quis elit Lorem irure. Ea est consectetur ut velit laboris irure qui.