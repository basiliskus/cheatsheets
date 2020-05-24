# Markdown Cheatsheet

## Basic Syntax

### Headers
```
# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag

This is an <h1> tag 
===================

This is an <h1> tag 
-------------------
```

### Emphasis
```
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_
```

#### Strikethrough (GFM)
```
Any word wrapped with two tildes (like ~~this~~) will appear crossed out.
```


### Lists

#### Unordered
```
* Item 1
* Item 2
  * Item 2a
  * Item 2b
```

#### Ordered
```
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
```

#### Examples
```
1. First ordered list item
2. Another item
⋅⋅* Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
⋅⋅1. Ordered sub-list
4. And another item.

⋅⋅⋅You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

⋅⋅⋅To have a line break without a paragraph, you will need to use two trailing spaces.⋅⋅
⋅⋅⋅Note that this line is separate, but within the same paragraph.⋅⋅
⋅⋅⋅(This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

* Unordered list can use asterisks
- Or minuses
+ Or pluses
```


### Links
```
http://github.com - automatic!
[GitHub](http://github.com)
```

### Automatic linking for URLs (GFM)
```
Any URL (like http://www.github.com/) will be automatically converted into a clickable link.
```

#### Examples
```
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
```


### Images
```
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)

```

#### Examples
```
Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"
```

### Code and Syntax Highlighting

#### Inline code
```
I think you should use an
`<addr>` element here instead.
```

#### Syntax highlighting (GFM)
<pre>```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```</pre>

You can also simply indent your code by four spaces:  
<pre>
    function fancyAlert(arg) {
      if(arg) {

        $.facebox({div:'#foo'})
      }
    }
</pre>

#### Examples
<pre>
```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
 
```python
s = "Python syntax highlighting"
print s
```
 
```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```
</pre>


### Tables (GFM)
```
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
```

#### Examples
```
Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
```


### Blockquotes
```
As Kanye West said:

> We're living the future so
> the present is our past.
```


### Inline HTML
You can also use raw HTML in your Markdown, and it'll mostly work pretty well.
```
<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>
```


### Horizontal Rule
```
Three or more...

---

Hyphens

***

Asterisks

___

Underscores
```


### Line Breaks
```
Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a *separate paragraph*.

This line is also a separate paragraph, but...
This line is only separated by a single newline, so it's a separate line in the *same paragraph*.
```


### Backslash escapes
> Markdown allows you to use backslash escapes to generate literal characters which 
  would otherwise have special meaning in Markdown formatting syntax.

```
\*literal asterisks\*
```

###### Markdown provides backslash escapes for the following characters:
```text
\   backslash
`   backtick
*   asterisk
_   underscore
{}  curly braces
[]  square brackets
()  parentheses
#   hash mark
+   plus sign
-   minus sign (hyphen)
.   dot
!   exclamation mark
```


## GitHub Flavored Markdown (GFM)

### Task Lists
```
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
```

### SHA references
```
16c999e8c71134401a78d4d46435517b2271d6ac
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac
```

### Issue references within a repository
```
#1
mojombo#1
mojombo/github-flavored-markdown#1
```

### Username @mentions
```
Typing an @ symbol, followed by a username, will notify that person to come and view the comment. This is called an “@mention”, because you’re mentioning the individual. You can also @mention teams within an organization.
```

### Emoji
```
To see a list of every image we support, check out the [Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)
```


## References
* https://guides.github.com/features/mastering-markdown/
* https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf
* https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
* https://www.markdownguide.org/cheat-sheet/


## Glossary
* GSM: GitHub Flavored Markdown
