[  this is a comment. all on one line. it takes up vertical space. it is not displayed ]::
<link href="styles.css" rel="stylesheet"></link>

# Header 1

prepend 1 hash \# + 1 space

`<link href="styles.css" rel="stylesheet"></link>`

*Note:* all headers are markdown links / anchors

menu: | [top](#header-1) | [text](#text) | [code](#code) | [list](#list) | [link](#link) | [table](#table) | [esc](#escaping) | [img](#images) |

  Markdown.md formatting

  Your document's end of line character(s) (EOL) may need to be changed from MS-DOS (`\r\n`) to Linux (`\n`).
	
## Header 2

  prepend 2 hash + 1 space

  paragraph

###****2**** Header 3

  prepend 3 hash + 1 space

  paragraph

## Text

menu: | [top](#header-1) | [text](#text) | [code](#code) | [list](#list) | [link](#link) | [table](#table) | [esc](#escaping) | [img](#images) |

asterisk *italics* asterisk \*
 abc
2 asterisks **bold** 2 asterisks
 abc
3 asterisks ***bold italics*** 3 asterisks
 abc
2 tildes ~~strikethrough~~ 2 tildes \~
 abc, 8 line breaks

Single\s\s\s\s    
Line Break with four trailing spaces above

Paragraph -enter key- -enter key-

Line Break

horizontal rule, not always rendered 3 asterisks
***

paragraph

> Quoted Text prepend 1 greater than sign \>
>> 2^nd^ Quoted Text prepend 2 greater than  
signs \>\>. superscript caret ^nd^ caret \^

## Code

menu: | [top](#header-1) | [text](#text) | [code](#code) | [list](#list) | [link](#link) | [table](#table) | [esc](#escaping) | [img](#images) |

```
Code Text - triple back tick \`
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


* Item 1
* Item 2
   + Item 1, three spaces prepended
   + Item 2

1. Numbered Item 1
2. Numbered Item 2
   1. Numbered Item 2.1
   2. Numbered Item 2.2
   3. three spaces prepended

## Link

menu: | [top](#header-1) | [text](#text) | [code](#code) | [list](#list) | [link](#link) | [table](#table) | [esc](#escaping) | [img](#images) |

Within this page:

`[text](#lowercase-header-text)`

Replace dashes for spaces in header text.

## External Link

[Reddit](http://reddit.com) – bracket \[ abc bracket \] \( paren http... paren \)

## Relative Link

The following should work in Reddit:

[Reddit user link](u/reddit) - u/reddit

[Reddit group link](r/AskReddit) - r/AskReddit

The following should work in GitHub:

[Local link](./README.md) - ./README.md

## Table

menu: | [top](#header-1) | [text](#text) | [code](#code) | [list](#list) | [link](#link) | [table](#table) | [esc](#escaping) | [img](#images) |

1 blank line before table.

 | left - - - | center - - - | right - - - - | 
 | ------ |:--------:| -------:| 
 | row 1  | label    |   $1.00 | 
 | row 2  | label    |   $2.00 | 
 | row 3  | label    |   $3.00 |

1 blank line after table.

Vertical bars define columns with
no extra line breaks;
dashes and colons (before and after)
vertical bars specify alignment.

## Escaping

menu: | [top](#header-1) | [text](#text) | [code](#code) | [list](#list) | [link](#link) | [table](#table) | [esc](#escaping) | [img](#images) |

Special & reserved characters

prepend a back slash

- \* Asterisk
- \\ Backslash
- \` Backtick
- \{ \}  Curly braces
- \. Dot
- \! Exclamation mark
- \# Hash symbol
- \- Hyphen symbol
- \( \)  Parentheses
- \+ Plus symbol
- \[ Square brackets
- \] Square brackets
- \_ Underscore

menu: | [top](#header-1) | [text](#text) | [code](#code) | [list](#list) | [link](#link) | [table](#table) | [esc](#escaping) | [img](#images) |

## Images

`![ImageLabel](./img/filename.jpg)`

![Image](./img/img-stick-figures-474x498.jpg)
