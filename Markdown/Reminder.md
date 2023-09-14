# Markdown Reminder (_CHEAT SHEET_)
## Essential
### Headings
```
# Heading 1
## Heading 2
### Heading 3
...
```
---

### Paragraphs
**Example**

```
Will be same paragraph
if only one new line used

New paragraph if two or more new lines are used
```
**Output**

Will be same paragraph
if only one new line used

New paragraph if two or more new lines are used

---

### Line Breaks
**Example**

```
Two spaces␣␣
at end of line will make
a line break
```
**Output**

Two spaces
at end of line will make
a line break

---

### Styling
|Style|Syntax|Example|Output|
|-----|------|-------|------|
|Bold|`** **` or `__ __`|\*\*This is bold text\*\*`|**This is bold text**|
|Italic|`* *` or `_ _`|\_This text is italicized\_|_This text is italicized_|
|Inline Code|<code>\` \`</code>|\`This is inline code\`|`This is inline code`|
|Strikethrough|`~~ ~~`|\~\~This was mistaken text\~\~|~~This was mistaken text~~|
|Bold and Italic|`*** ***`|\*\*\*All this text is important\*\*\*|***All this text is important***|
|Superscript|`<sup> </sup>`|This is a \<sup>superscript\</sup> text|This is a <sup>superscript</sup> text|
|Subscript|`<sub> </sub>`|This is a \<sub>subscript\</sub> text|This is a <sub>subscript</sub> text|
|Emoji|`:EMOJICODE:`|I am happy \:smile:|I am happy :smile:|

---

### Quoting
**Example**

```
> This is a quote
>> Nested Quote
```
**Output**

> This is a quote
>> Nested Quote

---

### Ordered List
**Example**

```
1. Ordered
2. List
    1. Numbers
    1. Don't matter
```
**Output**

1. Ordered
2. List
    1. Numbers
    1. Don't matter

---

### Unordered List
**Example**

```
* Unordered
* List
    * Asterisk
    + Plus sign
    - Dash
```
**Output**

* Unordered
* List
    * Asterisk
    + Plus sign
    - Dash

---

### Checklist
**Example**

```
- [ ] Must include space
- [x] Completed
```
**Output**

- [ ] Must include space
- [x] Completed

---

### Linking

|Type|Example|Output|
|----|-------|------|
|URL|`[GitHub](https://github.com/)`|[GitHub](https://github.com/)|
|Relative|`[Other](docs/Other.md)`|[Other](docs/Other.md)|

---

### Images
**Example**

```
![Image](https://myoctocat.com/assets/images/base-octocat.svg)
```

**Output**

![Image](https://myoctocat.com/assets/images/base-octocat.svg)

---

### Tables
**Example**

```
| First Header  | Second Header |
|-|-|
| Content | Content |
| Content | Content |

| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |
```

**Output**

| First Header  | Second Header |
|-|-|
| Content | Content |
| Content | Content |

| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |

---

### Collapsed section
**Example**

```
<details>

<summary>Tips for collapsed sections</summary>

#### You can add a header

You can add text within a collapsed section.

</details>
```
**Output**

<details>

<summary>Tips for collapsed sections</summary>

#### You can add a header

You can add text within a collapsed section.

</details>

---

### Code Blocks
**Example**
````
```
Multiple lines
of code
```

```cpp
// Some c++ highlighted syntax
std::cout << "Hello World!";
```
````

**Output**

```
Multiple lines
of code
```

```cpp
// Some c++ highlighted syntax
std::cout << "Hello World!";
```

## Github
### Footnotes
**Example**

```
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.
```

**Output**

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.

---

### Alerts
**Example**

```
> [!NOTE]
> Highlights information that users should take into account, even when skimming.

> [!IMPORTANT]
> Crucial information necessary for users to succeed.

> [!WARNING]
> Critical content demanding immediate user attention due to potential risks.
```

**Output**

> [!NOTE]
> Highlights information that users should take into account, even when skimming.

> [!IMPORTANT]
> Crucial information necessary for users to succeed.

> [!WARNING]
> Critical content demanding immediate user attention due to potential risks.

---
