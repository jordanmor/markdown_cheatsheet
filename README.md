# Markdown Cheat Sheet

## Headlines, Paragraphs, and Basic Formatting
```
# Heading Level 1
## Heading Level 2
### Heading Level 3
#### Heading Level 4
##### Heading Level 5
###### Heading Level 6
```
# Heading Level 1
## Heading Level 2
### Heading Level 3
#### Heading Level 4
##### Heading Level 5
###### Heading Level 6

### Paragraphs and Line Breaks

Hit return twice to start another paragraph.

#### Line Breaks

To add just a line break without a space, type two spaces at the end of a 
line, then press return once.

### Emphasis and Bolding

#### Italics

`*One Asterick*`  

*Word*

#### Bolding

`**Surround word or phrase with Two Astericks**`

**Word**

#### Bolding and Emphasis Together

`***Surround word or phrase with Three Astericks***`

***Word***

### Blockquotes
```
>Format a blockquote using the greater than symbol. 
>
>If you want a blockquote to span multiple paragraphs, add the greater than 
symbol to the line between paragraphs too.
```

>Format a blockquote using the greater than symbol. 
>
>If you want a blockquote to span multiple paragraphs, add the greater than 
symbol to the line between paragraphs too.

### Horizontal Rule

Type 3 hyphens. `---`

---

## Lists

### Numbered Lists

Type the number, a period, a space, and the item label


1. Item 1
2. Item 2
3. Item 3

```
1. Item One
    1. Nested Level Two
    2. Nested Level Two
        1. Nested Level Three
        2. Nested Level Three
```

1. Item One
    1. Nested Level Two
    2. Nested Level Two
        1. Nested Level Three
        2. Nested Level Three

### Bulleted Lists

Use the asterick. Leave space between the asterick and the word.

```
* Item One
* Item Two


* Item One
    * Nested Item One
    * Nested Item Two
```

* Item One
* Item Two


* Item One
    * Nested Item One
    * Nested Item Two

---

### Mixed Examples

* ***Bold Italicized Bulleted Item***

```
1. Mixed Lists
    * Nested Item
    * Nested Item
2. Item Two
    * Nested Item
    * Nested Item
        1. Deep Nested Item One
        2. Deep Nested Item Two
            * Super Deep Nested Item
            * Super Deep Nested Item
```

1. Mixed Lists
    * Nested Item
    * Nested Item
2. Item Two
    * Nested Item
    * Nested Item
        1. Deep Nested Item One
        2. Deep Nested Item Two
            * Super Deep Nested Item
            * Super Deep Nested Item

---

## Code

Use a single backtick to create inline code.

Ex. To install the latest version of NPM, you can type,  `npm install npm@latest -g`

For multiple lines of code, use three backticks above and below the code block. 
Some sites and editors also support syntax highlighting by language. 
Add it by typing the name of the coding language immediately after the top three backticks.

```JavaScript
let exampleFunction = () => {
  let foo = 'foo';
  let bar = 'bar';

  return foo + bar;
}
```


## Links

For a link, put the text in square brackets. Then, add the link in parenthesis.

`[Jordan Mor](https://jordanmor.com/)`

[Jordan Mor](https://jordanmor.com/)

To provide a title, which appears when you hover the mouse cursor over the link, 
type a space after the url and close the label in quotes. 
Both the url and the title should be inside the parenthesis.

`[Jordan Mor](https://jordanmor.com/ "Jordan Mor's Portfolio")`

[Jordan Mor](https://jordanmor.com/ "Jordan Mor's Portfolio")

To link to a reference at the bottom of a section or page like a footnote,
start with the text in square brackets, but don’t add the parenthesis. 
Instead, add a number to reference in another set of square brackets.

`[Jordan Mor][1]`

[Jordan Mor][1]

Now at another place in the document, add the reference number in square brackets 
and follow it with a colon, a space, and the link url. You can add an optional title 
with a space and quotes to this type of link too. Reference links don’t require parenthesis.

`[1]: https://jordanmor.com "Jordan Mor's Portfolio"`

[1]: https://jordanmor.com "Jordan Mor's Portfolio"


## Images

Type some alt text in square brackets in case the image cannot be shown for any reason. 
Follow that with the url for the image in parenthesis 
and an exclamation mark in front of the square brackets.

`![Alt Text](https://example.com/image)`

If you want the image to link to something, add square brackets around your whole image code. 
At the end of the new square brackets, put the link url in parenthesis.

`[![Alt Text](https://example.com/image)](https://example.com)`

If you want your image to have a title, add a space and put the title in quotes after the image url.

`[![Alt Text](https://example.com/image "Picture Title")](https://example.com)`

























