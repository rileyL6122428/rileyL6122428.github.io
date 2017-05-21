---
  markdown: kramdown
  highlighter: rouge
  lsi:         false
  excerpt_separator: "\n\n"
  incremental: false

  kramdown:
    auto_ids:       true
    entity_output:  as_char
    toc_levels:     1..6
    smart_quotes:   lsquo,rsquo,ldquo,rdquo
    input:          GFM
    hard_wrap:      false
    footnote_nr:    1
---

Hello world
===========

Hello World
-----------

Hello world
=

# Hello World

## Hello World

### Hello World

~~~ ruby
def what?
  42
end
~~~

~~~ JavaScript
conole.log("hello world")
~~~


> Hello World

*Hello world*

**Hello World**

```JavaScript
  console.log("hello world");
```

- hello world
- hello world

- [ ] hello world
- [ ] hello world
- [x] hello world


  * let's
  * see
  * if
  * this
  * is
  * rendered
  * as
  * markdown


1. hello world
2. hello world


definition term 1
definition term 2
: This is the first line. Since the first non-space characters appears in
column 3, all other lines have to be indented 2 spaces (or lazy syntax may
  be used after an indented line). This tells kramdown that the lines
  belong to the definition.
:       This is the another definition for the same term. It uses a
        different number of spaces for indentation which is okay but
        should generally be avoided.
   : The definition marker is indented 3 spaces which is allowed but
     should also be avoided.

| table header 1 | table header 2 |
| -------------- | -------------- |
| content        | content        |
| content        | content        |
