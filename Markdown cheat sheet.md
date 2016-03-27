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
  ```
  > Block quote line 1!
  > Block quote line 2!
  ``` 
  Output is,
  > Block quote line 1!
  
  > Block quote line 2!
  
*  Lazy Block quotes
  It include this `>` at the beginning of first line
  ```
  > With Block quote line 1!
   Without Block quote line 2!
  ``` 
  Output is,
  > With Block quote line 1!
    Without Block quote line 2!

---

# Web Links

You can make links to other web sites on the world wide web with two different link types in Markdown, but both of them render the exact same way. 

* The first link style is called an inline link. To create an inline link, you wrap the link text in brackets ( [ ] ), and then you wrap the link in parenthesis ( ( ) ).

  For example, to create a hyperlink to www.github.com, with a link text that says, Visit GitHub!

    you'd write this in Markdown: `[Visit GitHub!](www.github.com)`.

    Output is,

    [Visit GitHub!](www.github.com)

* The second link type is called a reference link. As the name implies, the link is actually a reference to another place in the document. 

  Example:

      [I'm an inline-style link](https://www.google.com)
      
      [I'm an inline-style link with title](https://www.google.com "Google's Homepage")
      
      [I'm a reference-style link][Arbitrary case-insensitive reference text]
      
      [I'm a relative reference to a repository file](../blob/master/LICENSE)
      
      [You can use numbers for reference-style link definitions][1]
      
      Or leave it empty and use the [link text itself].
      
      URLs and URLs in angle brackets will automatically get turned into links. 
      http://www.example.com or <http://www.example.com> and sometimes 
      example.com (but not on Github, for example).
      
      Some text to show that the reference links can follow later.
      
      [arbitrary case-insensitive reference text]: https://www.mozilla.org
      [1]: http://slashdot.org
      [link text itself]: http://www.reddit.com

  Output is,

  [Visit GitHub!][github]
  
  [Visit Google!][google]

  [github]: www.github.com
  [google]: www.google.com
  

  The "references" above are the second set of brackets: [another place] and [another-link]. At the bottom of a Markdown document, these brackets are defined as proper links to outside websites. An advantage of the reference link style is that multiple links to the same place only need to be updated once. For example, if we decide to make all of the [another place] links go somewhere else, we only have to change the single reference link.

Reference links don't appear in the rendered Markdown. You define them by providing the same tag name wrapped in brackets, followed by a colon, followed by the link.

In the box below, we've started writing out some reference links. You'll need to finish them up! Call the first reference tag "a fun place", and make it link to www.zombo.com; make the second link out to www.stumbleupon.com.

Skip
You now know how to make links in Markdown!

On to the next lesson!

---
### For Button Icon

  `<kbd>Button</kbd>` = <kbd>Button</kbd>

### For subscript and superscript

`<sub>sub</sub>Script` = <sub>sub</sub>Script

`Super<sup>script</sup>` = Super<sup>script</sup>

### For dagger & Dagger icon

`&Dagger;` = &Dagger;

`&dagger;` = &dagger;
