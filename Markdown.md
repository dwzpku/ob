# Markdown Writing

## Basic formatting syntax

### Paragraphs

Use a **blank line** to  separate blocks of text. Multiple adjacent blank spaces within and between paragraphs collapse into a single space when displayed in **Reading view**. 

### Line breaks

When **Strict Line Breaks** is enabled in Obsidian, line reaks have three distinct behaviors depending on how the lines are separated:

**Single return with no space**: will combine the two separate lines into a single line when rendered.

**Single return with two or more trailing spaces**: the two lines remain part of the same paragraph, but are broken by a line break.

**Double return (with or without trailing spaces)**: separates the lines into two distinct paragraphs, regardless of whether you add spaces at the end of the first line.

### Headings

To create a heading, add up to six `#` symbols before your heading text.
The number of `#` symbols determines the size of the heading.

### Bold, italics, highlights

**Bold** can be applied using shortcut `ctrl-b`.
*Italic* is applied using `* *`.
==Highlight== is applied using `== ==`.

### Internal links

Obsidian support two formats for internal links between notes:

- Wikilink: [[README]]
- Markdown: [Go to README](README.md)

### External links

If you want to link to an external URL, you can create an inline link by surrounding the link text in brackets `[ ]`, and then the URL in parentheses `( )`.

[Obsidian Help](https://help.obsidian.md)

If your URL contains blank spaces, you must escape them by replacing them with `%20`.

### Embed an image in a note

to embed an image:

```
![[image file]]
```

### Quotes

>You can quote text by adding a `>` symbols before the text.

### Lists

You can create an unordered list by adding a `-`, `*`, or `+` before the text.

To create an ordered list, start each line with a number followed by a `.` or `)` symbol.

You can use `shift + enter` to insert a **line break** whithin an list.

### Task lists

To create a task list, start each list item with a hyphen and space followed by `[ ]`.  

- [x] This is a complete task.
- [ ] This is an incomplete task.

You can toggle a task in Reading view by selecting the checkbox.

### Nesting lists

To create a nested list, indent one or more list items.

Use `Tab` or `Shift + Tab` to indent or unindent selected list items.

### Horizontal rule

You can use three or more stars, hyphens, or underscore on its own line to add a horizontal bar. You can also separate symbols using spaces.

* * *
### Code

#### Inline code

You can format code within a setence using single backticks. If you want to put backticks in an inline code block, surround it with double backticks like so: ``code with a backstick ` inside``.

#### Code blocks

To format code as a block, enclose it with three backticks or three tildes. You can add syntax highlighting to a code block, by adding a language code after the first set of backticks.

```latex
\begin{document}
	\begin{equation}
		E=mc^2
	\end{equation}
\end{document}
```

### Footnotes

You can add footnotes to your notes using the following syntax:

This is a simple footnote[^1].

[^1]: This is the referenced text.

[^note]: Named footnotes still appears as numbers, but can make it easier to identify and link references.

You can also use inline footnotes. ^[This is an inline footnote.]

Here we go[^note].

### Comments

You can add comments by wrapping text with `%%`.

### Escaping markdown syntax

To display the formatting characters literally, place a backslash `\` before them.

## Advanced formatting syntax

### Tables

Here's an example:

| **First name** | **Last name** |
| -------------- | ------------- |
| Wei-Zhen       | Deng          |
| Xiang-Hua      | Hu            |

You can insert a table by right-clicking and selecting *Insert $\to$ Table*. Align text in columns by adding colons `:`  to the header row.

### Math

You can add math expression to your notes using **MathJax** and the LaTeX notation.

To add a MathJax expression to your note, surround it with double dollar signs.

You can also inline math expressions by wrapping it in `$` symbols.
