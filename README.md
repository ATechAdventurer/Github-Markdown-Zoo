# 🦒 GitHub Markdown Zoo

A comprehensive demonstration of GitHub Flavored Markdown features and how they render.

## 📚 Table of Contents
- [Basic Text Formatting](#-basic-text-formatting)
- [Headers](#-headers)
- [Lists](#-lists)
  - [Unordered Lists](#unordered-lists)
  - [Ordered Lists](#ordered-lists)
  - [Task Lists](#task-lists)
- [Links & References](#-links--references)
  - [Direct Links](#direct-links)
  - [Reference Links](#reference-links)
  - [Section Links](#section-links)
  - [URLs and Email](#urls-and-email)
- [Images](#-images)
  - [Direct Image](#direct-image)
  - [Reference Image](#reference-image)
- [Blockquotes](#-blockquotes)
- [Horizontal Rules](#-horizontal-rules)
- [Code](#-code)
  - [Inline Code](#inline-code)
  - [Code Blocks](#code-blocks)
  - [Syntax Highlighted Code](#syntax-highlighted-code)
- [Tables](#-tables)
  - [Aligned Tables](#aligned-tables)
- [Extended Features](#-extended-features)
  - [Alerts (GitHub-specific Callouts)](#alerts-github-specific-callouts)
  - [Footnotes](#footnotes)
  - [Emoji](#emoji)
  - [Keyboard Keys](#keyboard-keys)
  - [Details/Summary](#detailssummary-collapsible-content)
  - [Mermaid Diagrams](#mermaid-diagrams)
  - [Syntax Highlighting with Diff](#syntax-highlighting-with-diff)
- [Advanced Tips](#-advanced-tips)
  - [Escaping Characters](#escaping-characters)
  - [HTML Support](#html-support)
- [Contributing](#-contributing)

## 📝 Basic Text Formatting

Plain text looks like this.

*This text is italicized* or _this too_

**This text is bold** or __this too__

***This text is bold and italic*** or ___this too___

~~This text is crossed out~~

This text has a `code span` in it

<details>
<summary>View Markdown source</summary>

```markdown
Plain text looks like this.

*This text is italicized* or _this too_

**This text is bold** or __this too__

***This text is bold and italic*** or ___this too___

~~This text is crossed out~~

This text has a `code span` in it
```
</details>

## 🔤 Headers

# H1 Header
## H2 Header
### H3 Header
#### H4 Header
##### H5 Header
###### H6 Header

<details>
<summary>View Markdown source</summary>

```markdown
# H1 Header
## H2 Header
### H3 Header
#### H4 Header
##### H5 Header
###### H6 Header
```
</details>

## 📋 Lists

### Unordered Lists
* Item 1
* Item 2
  * Nested item 2.1
  * Nested item 2.2
* Item 3

<details>
<summary>View Markdown source</summary>

```markdown
* Item 1
* Item 2
  * Nested item 2.1
  * Nested item 2.2
* Item 3
```
</details>

### Ordered Lists
1. First item
2. Second item
   1. Nested item 2.1
   2. Nested item 2.2
3. Third item

<details>
<summary>View Markdown source</summary>

```markdown
1. First item
2. Second item
   1. Nested item 2.1
   2. Nested item 2.2
3. Third item
```
</details>

### Task Lists
- [x] Completed task
- [ ] Uncompleted task
- [ ] Another task

<details>
<summary>View Markdown source</summary>

```markdown
- [x] Completed task
- [ ] Uncompleted task
- [ ] Another task
```
</details>

## 🔗 Links & References

### Direct Links
[Visit GitHub](https://github.com)

### Reference Links
[GitHub][1]
[Markdown Guide][2]

[1]: https://github.com
[2]: https://www.markdownguide.org

<details>
<summary>View Markdown source</summary>

```markdown
### Direct Links
[Visit GitHub](https://github.com)

### Reference Links
[GitHub][1]
[Markdown Guide][2]

[1]: https://github.com
[2]: https://www.markdownguide.org
```
</details>

### Section Links
[Go to Basic Text Formatting](#basic-text-formatting)

<details>
<summary>View Markdown source</summary>

```markdown
[Go to Basic Text Formatting](#basic-text-formatting)
```
</details>

### URLs and Email
Auto-linked URL: https://github.com
Auto-linked email: example@github.com

<details>
<summary>View Markdown source</summary>

```markdown
Auto-linked URL: https://github.com
Auto-linked email: example@github.com
```
</details>

## 📸 Images

### Direct Image
![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

### Reference Image
![Git Logo][git-logo]

[git-logo]: https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png

<details>
<summary>View Markdown source</summary>

```markdown
### Direct Image
![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

### Reference Image
![Git Logo][git-logo]

[git-logo]: https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png
```
</details>

## 💭 Blockquotes

> This is a blockquote
> 
> It can span multiple lines
>> And can be nested

<details>
<summary>View Markdown source</summary>

```markdown
> This is a blockquote
> 
> It can span multiple lines
>> And can be nested
```
</details>

## 📏 Horizontal Rules

---
***
___

<details>
<summary>View Markdown source</summary>

```markdown
---
***
___
```
</details>

## 💻 Code

### Inline Code
Use `git status` to list all files that haven't been committed.

<details>
<summary>View Markdown source</summary>

```markdown
Use `git status` to list all files that haven't been committed.
```
</details>

### Code Blocks
```
This is a code block
No syntax highlighting
```

### Syntax Highlighted Code

```python
def hello_world():
    print("Hello, Markdown Zoo!")
```

```javascript
function helloWorld() {
    console.log("Hello, Markdown Zoo!");
}
```

```json
{
    "greeting": "Hello, Markdown Zoo!",
    "type": "JSON"
}
```

<details>
<summary>View Markdown source</summary>

````markdown
```
This is a code block
No syntax highlighting
```

```python
def hello_world():
    print("Hello, Markdown Zoo!")
```

```javascript
function helloWorld() {
    console.log("Hello, Markdown Zoo!");
}
```

```json
{
    "greeting": "Hello, Markdown Zoo!",
    "type": "JSON"
}
```
````
</details>

## 📊 Tables

| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Row 1, Col 1 | Row 1, Col 2 | Row 1, Col 3 |
| Row 2, Col 1 | Row 2, Col 2 | Row 2, Col 3 |

<details>
<summary>View Markdown source</summary>

```markdown
| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Row 1, Col 1 | Row 1, Col 2 | Row 1, Col 3 |
| Row 2, Col 1 | Row 2, Col 2 | Row 2, Col 3 |
```
</details>

### Aligned Tables

| Left | Center | Right |
|:-----|:------:|------:|
|Left|Center|Right|
|Aligned|Aligned|Aligned|

<details>
<summary>View Markdown source</summary>

```markdown
| Left | Center | Right |
|:-----|:------:|------:|
|Left|Center|Right|
|Aligned|Aligned|Aligned|
```
</details>

## 🎨 Extended Features

### Alerts (GitHub-specific Callouts)

> [!NOTE]  
> Highlights information that users should take into account, even when skimming. For example, this is how you notify users about prerequisites or general information they shouldn't skip.

> [!TIP]
> Optional information to help a user be more successful. For instance, here's a faster way to complete this task using keyboard shortcuts.

> [!IMPORTANT]  
> Crucial information necessary for users to succeed. For example, you must have administrator privileges to perform these actions.

> [!WARNING]  
> Critical content demanding immediate user attention due to potential risks. For example, proceeding with this action will permanently delete your data.

> [!CAUTION]
> Negative potential consequences of an action. For example, this API will be deprecated in the next release, consider using the new endpoint instead.

<details>
<summary>View Markdown source</summary>

```markdown
> [!NOTE]  
> Highlights information that users should take into account, even when skimming. For example, this is how you notify users about prerequisites or general information they shouldn't skip.

> [!TIP]
> Optional information to help a user be more successful. For instance, here's a faster way to complete this task using keyboard shortcuts.

> [!IMPORTANT]  
> Crucial information necessary for users to succeed. For example, you must have administrator privileges to perform these actions.

> [!WARNING]  
> Critical content demanding immediate user attention due to potential risks. For example, proceeding with this action will permanently delete your data.

> [!CAUTION]
> Negative potential consequences of an action. For example, this API will be deprecated in the next release, consider using the new endpoint instead.
```
</details>

### Footnotes
Here's a sentence with a footnote[^1] (See the bottom of the rendered page).

[^1]: This is the footnote content.

<details>
<summary>View Markdown source</summary>

```markdown
Here's a sentence with a footnote[^1].

[^1]: This is the footnote content.
```
</details>

### Emoji
:smile: :rocket: :octocat:

<details>
<summary>View Markdown source</summary>

```markdown
:smile: :rocket: :octocat:
```
</details>

### Keyboard Keys
Press <kbd>Ctrl</kbd> + <kbd>C</kbd> to copy

<details>
<summary>View Markdown source</summary>

```markdown
Press <kbd>Ctrl</kbd> + <kbd>C</kbd> to copy
```
</details>

### Details/Summary (Collapsible Content)
<details>
<summary>Click to expand!</summary>

This content is hidden by default but can be revealed by clicking!
</details>

<details>
<summary>View Markdown source</summary>

```markdown
<details>
<summary>Click to expand!</summary>

This content is hidden by default but can be revealed by clicking!
</details>
```
</details>

### Mermaid Diagrams
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

<details>
<summary>View Markdown source</summary>

````markdown
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
````
</details>

### Syntax Highlighting with Diff
```diff
- This line was removed
+ This line was added
```

<details>
<summary>View Markdown source</summary>

````markdown
```diff
- This line was removed
+ This line was added
```
````
</details>

## 📌 Advanced Tips

### Escaping Characters
\*This text has literal asterisks\*

\# This is not a header

<details>
<summary>View Markdown source</summary>

```markdown
\*This text has literal asterisks\*

\# This is not a header
```
</details>

### HTML Support
<sup>Superscript</sup> and <sub>subscript</sub>

<div align="center">
Centered text using HTML
</div>

<details>
<summary>View Markdown source</summary>

```markdown
<sup>Superscript</sup> and <sub>subscript</sub>

<div align="center">
Centered text using HTML
</div>
```
</details>

---

## 🎉 Contributing

Feel free to contribute to this Markdown Zoo by:
1. Forking the repository
2. Creating a new branch
3. Making your changes
4. Submitting a pull request
