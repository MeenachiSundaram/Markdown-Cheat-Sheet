# Italics and Bold with Markdown

To make a phrase italic in Markdown, you can surround words with an underscore or asterisk ( _ or * ).

* For example, `_this_` or `*this*` word would become italic.

  `_Italics_` = _Italics_

  or

  `*Italics*` = *Italics*

Similarly, to make phrases bold in Markdown, you can surround words with two asterisks or two underscores ( ** or __ ).
* For example, `**this**` or `__this__` word would become bold.

  `__Bold__` = __Bold__

  or

  `**Bold**` = **Bold**

Of course, you can use the following options too `both italics and bold on same line` or `together`.
* For example,

  `Both _Italics_ and **Bold**` = Both _Italics_ and **Bold**

  `**_Together_**` = **_Together_**

Place the asterisks **_on the outside_**, just to make it more legible

In general, it doesn't matter which order you place the asterisks or underscores.

---

# Headers

This can be used as a titles or subtitles.

There are six types of headers, in decreasing sizes:
```
# This is header one
## This is header two
### This is header three
#### This is header four
##### This is header five
###### This is header six
```
To do so we just add one hash mark for `(# Header One)`, while for a header two, you'd use two `(## Header Two)` and so on.

* You can also combine headers with italics and bold as shown below.
```
### **Header3 & Bold**
##### _Header4 & Italics_
```
Output is,
### **Header3 & Bold**
##### _Header4 & Italics_

-----

# Paragraph

In Markdown each paragraph are just one or more lines of consecutive text followed by one or more blank lines.

```
Paragraph one
Paragraph two```
Output is,

Paragraph one
Paragraph two

```
Paragraph one

Paragraph two```
Output is,

Paragraph one

Paragraph two

----

# Block quotes

You can show blockquotes with the `>` character.
> This is known as block quotes

There are two types,

* Classic Block quotes

  It include this `>` at the beginning of each line

      > Block quote line 1!

      > Block quote line 2!


  Output is,
  > Block quote line 1!

  > Block quote line 2!

*  Lazy Block quotes
  It include this `>` at the beginning of first line

      > With Block quote line 1!
       Without Block quote line 2!

  Output is,
  > With Block quote line 1!
    Without Block quote line 2!

---

# Web Links

In Markdown there are two different way to create a world wide web link but both of them are same.

* First link style is called an inline link.

  To create an inline link, you wrap the link text in brackets "[ ]", and then you wrap the link in parenthesis " ( ) ".

  For example,

  To create a hyperlink to www.github.com, with a link text that says, Visit GitHub! You'd write this in Markdown: `[Visit GitHub!](https://www.github.com)`.

  Output is,

  [Visit GitHub!](https://www.github.com)

  To create a hyperlink to www.github.com, with a link text that says, Visit Github! with the title GITHUB You'd write this in Markdown: `[Visit GitHub!](https://www.github.com "GITHUB")`.

  Output is,

  [Visit GitHub!](https://www.github.com "GITHUB")

* Second link type is called a reference link.

  As the name implies, the link is actually a reference to another place in the document.

  Example:

      [Reference-style link][reference text]

      [Numbers has reference-style link definitions][1]

      Or simply use the [text itself].

      Link to the references are mentioned at the end, like as follows.

      [reference text]: https://www.github.com
      [1]: https://www.github.com
      [text itself]: https://www.github.com

  Output is,

  [Reference-style link][reference text]

  [Numbers has reference-style link definitions][1]

  Or simply use the [text itself].

  [reference text]: https://www.github.com
  [1]: https://www.github.com
  [text itself]: https://www.github.com

* Reference links don't appear in the rendered Markdown. You define them by providing the same tag name wrapped in brackets, followed by a colon, followed by the link.

* Advantage of the reference link style is that multiple links to the same place only need to be updated once.

---
### For Button Icon

  `<kbd>Button</kbd>` = <kbd>Button</kbd>

### For subscript and superscript

`<sub>sub</sub>Script` = <sub>sub</sub>Script

`Super<sup>script</sup>` = Super<sup>script</sup>

### For dagger & Dagger icon

`&Dagger;` = &Dagger;

`&dagger;` = &dagger;
