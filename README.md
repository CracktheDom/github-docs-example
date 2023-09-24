Here is a tutorial on using GitHub Flavored Markdown (GFM) [^1]:

# GitHub Flavored Markdown Tutorial

GFM is a version of Markdown supported across GitHub for simple text formatting. This guide will cover the basics.

## Headings

Headings use the `#` symbol followed by a space:

```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
```

# Kingdom
## Phylum
### Class
#### Order

You can go up to 6 levels by increasing the number of `#` symbols.

## Text Formatting

**Bold** text uses two asterisks: `**bold**`.

*Italic* text uses one asterisk `*italic*`. 

~~Strikethrough~~ uses two tildes `~~text~~`.

## Lists

Unordered lists use `-`, `*`, or `+`:
```
- Item 1
- Item 2
* Item 3 
+ Item 4
```

- 1 Idea
- Then another
* ... and another
+ Last one
  
Numbered lists use numbers followed by `.`:

```
1. First item
2. Second item
3. Third item 
```
1. Measure twice
2. Cut once
3. Repeat
   
Task lists use `- [ ]` for unchecked and `- [x]` for checked:

```
- [x] Completed task
- [ ] Incomplete task
```
- [x] Buy low
- [ ] Sell high

## Code Blocks 

Inline code uses single backticks: `` `code` ``.

Code blocks use triple backticks:

```
```
Code block
here
```
```

Specify language for syntax highlighting:

```
```python
print('Hello world!) 
```
```
```python
import this
print(f"My name is {name}") 
```

## Images

```
![Alt text](image_url)
```

## Links 

```
[Text](http://url.com)
```
[www.example.com](http://www.example.com)

## Tables

Use pipes and hyphens:

```
| Column 1 | Column 2 |
|-|-|
| Row 1 | Data |
| Row 2 | Data |
```
| Column 1 | Column 2 |
|-|-|
| Row 1 | Data |
| Row 2 | Data |

## Emoji

``:emoji_name:`` e.g. :smile:

See Emoji Cheat Sheet for codes. [^2]

## Footnotes

```
Text[^1]

[^1]: Footnote text
```

## Superscript 

+ Use ``<sup></sup>`` tags e.g. ``2<sup>10</sup>``
2<sup>10</sup>

### References
[^1]: See the [GFM Docs](https://github.github.com/gfm/) for more information!
[^2]: [Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet/)
