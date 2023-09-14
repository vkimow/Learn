# Markdown Reminder

## Headings

To create a heading, add one to six <kbd>#</kbd> symbols before your heading text. The number of <kbd>#</kbd> you use will determine the hierarchy level and typeface size of the heading.

```markdown
# Heading 1
## Heading 2
### Heading 3
```

## Paragraphs

You can create a new paragraph by leaving a blank line between lines of text.

## Line Breaks

Two spaces  at end of line will make a line break

## Styling

|Style|Syntax|Example|Output|
|-----|------|-------|------|
|Bold|`** **` or `__ __`|\*\*This is bold text\*\*`|**This is bold text**|
|Italic|`* *` or `_ _`|\_This text is italicized\_|_This text is italicized_|
|Inline Code|<code>\` \`</code>|\`This is inline code\`|`This is inline code`|
|Strikethrough|`~~ ~~`|\~\~This was mistaken text\~\~|~~This was mistaken text~~|
|Bold and Italic|`*** ***`|\*\*\*All this text is important\*\*\*|_**All this text is important**_|
|Superscript|`<sup> </sup>`|This is a \<sup>superscript\</sup> text|This is a <sup>superscript</sup> text|
|Subscript|`<sub> </sub>`|This is a \<sub>subscript\</sub> text|This is a <sub>subscript</sub> text|
|Emoji|`:EMOJICODE:`|I am happy \:smile:|I am happy :smile:|

## Quoting

Example

```markdown
> This is a quote
>> Nested Quote
```

Output

> This is a quote
>> Nested Quote

## Ordered List

Example

```markdown
1. Ordered
2. List
    1. Numbers
    2. Don't matter
```

Output

1. Ordered
2. List
    1. Numbers
    2. Don't matter

## Unordered List

Example

```markdown
* Unordered
* List
    * Asterisk
    + Plus sign
    - Dash
```

Output

* Unordered
* List
  * Asterisk
  * Plus sign
  * Dash

## Checklist

Example

```markdown
- [ ] Must include space
- [x] Completed
```

Output

* [ ] Must include space
* [x] Completed

## Linking

|Type|Example|Output|
|----|-------|------|
|URL|`[GitHub](https://github.com/)`|[GitHub](https://github.com/)|
|Relative|`[Other](docs/Other.md)`|[Other](docs/Other.md)|

## Images

Example

```markdown
![Image](https://myoctocat.com/assets/images/base-octocat.svg)
```

Output

![Image](https://myoctocat.com/assets/images/base-octocat.svg)

## Tables

Example

```markdown
| First Header  | Second Header |
|-|-|
| Content | Content |
| Content | Content |

| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |
```

Output

| First Header  | Second Header |
|-|-|
| Content | Content |
| Content | Content |

| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |

## Collapsed section

Example

```markdown
<details>

<summary>Tips for collapsed sections</summary>

#### You can add a header

You can add text within a collapsed section.

</details>
```

Output

<details>

<summary>Tips for collapsed sections</summary>

#### You can add a header

You can add text within a collapsed section.

</details>

## Code Blocks

Example

````markdown
```
Multiple lines
of code
```

```cpp
// Some c++ highlighted syntax
std::cout << "Hello World!";
```
````

Output

```text
Multiple lines
of code
```

```cpp
// Some c++ highlighted syntax
std::cout << "Hello World!";
```

## Footnotes

Example

```markdown
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.
```

Output

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.  
  This is a second line.

## Alerts

Example

```markdown
> [!NOTE]
> Highlights information that users should take into account, even when skimming.

> [!IMPORTANT]
> Crucial information necessary for users to succeed.

> [!WARNING]
> Critical content demanding immediate user attention due to potential risks.
```

Output

> [!NOTE]
> Highlights information that users should take into account, even when skimming.

> [!IMPORTANT]
> Crucial information necessary for users to succeed.

> [!WARNING]
> Critical content demanding immediate user attention due to potential risks.
>