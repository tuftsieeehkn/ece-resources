# GitHub Markdown Tutorial

If you are trying to get familiar with GitHub, learning Markdown is a great place to start. Markdown is the styling "language" that GitHub and many other technical places use to provide formatting in a plain text file.

This file is written in Markdown! If you want to see how the source code looks, you can click the "code" tab for this file on GitHub, or view it as a raw text file using the "Raw" button.

The goal of this file is to give a quick introduction to using markdown. GitHub has a [full markdown tutorial](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) if you are interested in learning more.


## Headings
Headings (like the one above) are a way to separate your document into sections and are especially useful for long documents. They provide hierarchy for the documents through different levels.

This document is structured as follows:
```
# GitHub Markdown Tutorial
(A level one heading. All other headings are level 2 and therefore "children" of this heading)

## Headings

## Bold and Italic

...etc
```

In general, a headings level corresponds to how many `#`s it has before it.

```
# First level heading
## Second level heading
(Is a child of the first level heading)

### Third level heading
## Another second level heading
```

## **Bold** and *Italic*
*Italic* text can be created by surrounding the desired text with `*one star*` or `_one underscore_`.

**Bold** text can be created by surrounded the desired text with `**two stars**` or `__two underscores__`.

## Lists
You can create both numbered and bulleted lists very easily.

### Numbered Lists
A numbered list is written like this:
```
1. Item one
2. Item two
3. Item three
```

And displayed like this:
1. Item one
2. Item two
3. Item three

### Bulleted Lists
A bulleted list is written like this:
```
- Item one
- Item two
- Item three
```
And displayed like this:
- Item one
- Item two
- Item three

## Code
As you have probably noticed, I've been inserting code snippets throughout this document. `Inline code formatting` is done with a `` `backtick on both sides` ``.

Multiline code formatting is done with three backticks on the first and last lines
~~~
```
Some code here
```
~~~

You can also specify languages for syntax highlighting:
~~~
```python
def hello():
    print("Hello world!")
```
~~~

Renders as:
```python

def hello():
    print("Hello world!")

```