---
layout: post
title: This is another post
author: Ali Sina
summary: This is just a duplicate of the above post.
postFooter: Additional information, and maybe a <a href="#">link or two</a>
---
This document gives the coding conventions for Python code
 comprising the standard library in the main Python distribution. Please see the companion informational PEP
  describing style guidelines for the C code in the C implmentation of Python.[^1]

This doucment and [PEP 257](https://www.python.org/dev/peps/pep-0257/) (Docstring Conventions) were dapted from Guido's orignial Pythong Style Guide essay, with some additiosn from Barry's style guide.[^2]

This style guide evolves over time as additional convetions are identified and past conventions are rendeded obbsolete by chnages int he language itself.

This is line is borken into  
two with line breaks.

First level header
===============


Second level header
----------------


# H1 header
## H2 header
### H3 header
#### H4 header
##### H5 header
###### H6 header

> A sample blockquote.
>
> > Nested blockquote are also possible
>
> ## Headers work too
> This is the outer quote again.

~~~ruby
def what?
  42
end
~~~

~~~python
class Animal(object):
 pass
  # some comment here
~~~

```python
def foo(x, y):
  pass
```

* * *

---

 - - - - - -

---------------------------


1. This is a list item
2. ANd another item
2. And a third one with mor text.


* Non numbered item in list


term
: definition
: another defintion


another term
and another twitter_username
: and a def for these both terms


This *is* a term

: This will be a para

> a blockqutoe


| a simple | table |
| with multiple | lines |

| header 1 | header 2 | header 3 |
|:--------|:--------:|--------:|
| cell 1 | cell 2 | cell 3 |
| cell 4 | cell 3 | cell 6 |


This is *emphasized*, __this__ too!

This w**ork**s as expectd.


An image: ![image](http://placekitten.com/200/300)


Use `Kramdown::Document.new(text).to_html` to convert the
`text` in kramdown syntax to html.


Use backticks to markup code, e.g. `` `code` ``.


[^1]: The def goes github_username
[^2]: The other def also hgoes ehres.
