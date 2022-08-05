[  this is a comment. ]::

`[  this is a hidden-ish comment. ]::`

<link href="styles.css" rel="stylesheet"></link>

> [Appendices](./Appendices-Top/Markdown-00-Appendices.md) | [WTF](./Appendices-Top/Markdown-01-WTF.md) | [Motivate](./Appendices-Top/Markdown-02-Motivate.md) |
> [Overview](./Appendices-Top/Markdown-03-Overview.md) | [Definitions](./Appendices-Top/Markdown-04-Definitions.md) | [Memes](./Appendices-Top/Markdown-05-Memes.md) 
> [Admin](./Appendices-Top/Markdown-06-Admin.md) | [TT4N](./Appendices-Top/Markdown-07-TT4N.md) | [Bibliography](./Appendices-Top/Markdown-99-Bibliography.md) | [Hosts](./Appendices-Top/Markdown-08-Hosts.md)

# Header 1

menu: | [top](#header-1) | [text](#text) | [code](#code) | [list](#list) | [link](#link) | [table](#table) | [esc](#escaping) | [img](#images)

***

> prepend 1 hash \# + 1 space

Set some properties:

`<link href="styles.css" rel="stylesheet"/>`

*Note:* all headers are markdown links / anchors

Change your document's end of line character(s) (EOL) from DOS (`\r\n`) to Linux (`\n`) style.
	
## Header 2

> prepend 2 hash + 1 space

  paragraph

### Header 3

> prepend 3 hash + 1 space

  paragraph

## Text

menu: | [top](#header-1) | [text](#text) | [code](#code) | [list](#list) | [link](#link) | [table](#table) | [esc](#escaping) | [img](#images) |

***

asterisk *italics* asterisk \*
 abc
2 asterisks **bold** 2 asterisks
 abc
3 asterisks 
***bold italics*** 
3 asterisks
 abc
2 tildes ~~strikethrough~~ 2 tildes \~
 abc, 10 line breaks

Single\s\s\s\s  
Line Break with four trailing spaces above

Paragraph -enter key- -enter key-

Line Break

horizontal rule, not always rendered, 3 asterisks

> ` add one blank line before the rule`

***

> ` add one blank line after the rule`

paragraph

> Quoted Text prepend 1 greater than sign \>
>> 2^nd^ Quoted Text prepend 2 greater than
signs \>\>. superscript caret ^nd^ caret \^

## Code

menu: | [top](#header-1) | [text](#text) | [code](#code) | [list](#list) | [link](#link) | [table](#table) | [esc](#escaping) | [img](#images) |

***

Note: Markdown text automatically wraps, fitting in the available horizontal space, except when enclosed in triple back-ticks \`\`\`.

``` LongLinesOfUnbrokenTextWillRequireScrollingToSeeTheRightMostSections.```
```
Code Text - triple back tick ```
     at line before
   and line after
   text, not ignoring
     line breaks nor spacing
   end
end
```
Paragraph backtick `call sqrt()` backtick

## List
menu: | [top](#header-1) | [text](#text) | [code](#code) | [list](#list) | [link](#link) | [table](#table) | [esc](#escaping) | [img](#images) |

***

* Item 1
* Item 2 - a `+` `-` or `*`, a space then text
   + Item A - 3 spaces then a `+` `-` or `*`
   + Item 2

1. Numbered Item 1
2. Numbered Item 2 - a number, a `.` then text
   1. Numbered Item 2.1
   2. Numbered Item 2.2
   3. three spaces prepended

## Link

menu: | [top](#header-1) | [text](#text) | [code](#code) | [list](#list) | [link](#link) | [table](#table) | [esc](#escaping) | [img](#images) |

***

A link within this page:

> `bracket [label] bracket paren (header-text) paren`

> [Label](#external-link)


Replace spaces with dashes in header text.

## External Link

[Reddit](http://reddit.com) – bracket \[Reddit\] bracket paren \(http...\) paren

## Relative Link

The following should work in Reddit:

> [Reddit user link](u/reddit) - u/reddit

> [Reddit group link](r/AskReddit) - r/AskReddit

The following should work in GitHub:

> [Local link](./Appendices-Top/README.md) - ./README.md

## Table

menu: | [top](#header-1) | [text](#text) | [code](#code) | [list](#list) | [link](#link) | [table](#table) | [esc](#escaping) | [img](#images) |

***

> ` add one blank line before the table`

 | left - - - | center - - - | right - - - - |
 | ------ |:--------:| -------:|
 | row 1  | label    |   $1.00 |
 | row 2  | label    |   $2.00 |
 | row 3  | label    |   $3.00 |

> `add one blank line after the table`

- Vertical bars set columns, no extra line breaks;
- dashes and colons before and after vertical bars in the 1st row specify alignment. `|:---:|` centers contents
- tables fail to display when:
   - no blank lines before and after the table
   - EOL characters are DOS `\r\n` vs Linux `\n`
   - unequal number of `|` vertical bars

## Escaping

menu: | [top](#header-1) | [text](#text) | [code](#code) | [list](#list) | [link](#link) | [table](#table) | [esc](#escaping) | [img](#images) |

***

Special & reserved characters

>`prepend a back slash`

- \* Asterisk
- \\ Backslash
- \` Backtick
- \. Dot
- \! Exclamation mark
- \# Hash symbol
- \_ Underscore
- \- Negative sign
- \+ Plus sign
- \( \)  Parentheses
- \[ Square bracket
- \] Square bracket
- \{ \}  Curly braces

## Images

menu: | [top](#header-1) | [text](#text) | [code](#code) | [list](#list) | [link](#link) | [table](#table) | [esc](#escaping) | [img](#images) |

***

Local `./images` directory

> `![ImageLabel](./images/filename.jpg)`

![Image](./images/img-stick-figures-474x498.jpg)
