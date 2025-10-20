# Git/GitHub Workshop - README Overview
> WiCS x DAGDC

## ☘️ About README.md files

### 💫 A README.md file is a text file that describes the project contained in a repo.
- _.md_ = a "markdown" text file -> allows special formatting and some html/css capabilities.
- Resides at the root directory of the project (not inside any folders!)
- Helps the audience understand how to install and use your project
- **Good practice**: make it the first file you create in a new project!

### 💫 It contains information, such as:
- Description & purpose of project
- Technologies used in the project
- List of key features
- How to download / run / use project
- File structure
- How to collaborate with you (if applicable)
- License information (if any)

And more!

---
## ☘️ Headers

# 🌟 Heading 1
1 hashtag: `# Heading 1`

OR text followed by at least 1 = symbol on next line:
```
Heading 1
=
```

## 🌟 Heading 2
2 hashtags: `## Heading 2`

OR text followed by at least 1 - symbol on next line:
```
Heading 2
-
```

### 🌟 Heading 3
3 hashtags: `### Heading 3`

---

## 🌸 Formatting
### ✨ Paragraphs
Created by separating text with a blank line.
```
Paragraph 1.

Paragraph 2.
```

### ✨ Bold
**Bold** with 2 asterisks on both sides of text: `**text here**` 

### ✨ Italicize
_Italicize_ with 1 underscore OR asterisk on both sides of text: `_text here_ or *text here*` 

### ✨ Code
`Code snippet` with 1 backtick (`) on both sides of text

`Code block` with 3 backticks (```) before and after a block of text, on its own lines. Can also add code language to color text.
```` python
``` python
print('hi')
```
````

### ✨ Lists
- Bulleted list with dash (-) or asterisk (*) followed by space, then text: `- text here` or `* text here`

1. Numbered list with number followed by period, space, then text.

### ✨ Quotes
Use a greater than symbol (>) followed by a space, then text: `> text here`
> This is a quote.

### ✨ Links
Put text in square brackets [], followed by the link in parentheses (): `[text here](link url here)`
- [WiCS Linktree](http://linktr.ee/deanza_wics)
- [DAGDC Linktree](http://linktr.ee/DAGAMEDEV)

### ✨ Images
<img width="1159" height="286" alt="image" src="https://github.com/user-attachments/assets/437fa586-89f1-4992-ae82-28ad85aee313" />

**2 ways to add an image**: standard markdown and raw html.
- Standard markdown: `![Image alt text here](image link here)`
   - Simpler & more readable.
   - Keeps original size, and offers limited control.
- Raw HTML: `<img alt="alt text" src="image link" width="..." height="..." align="..."/>`
   - Everything other than src is optional.
   - Provides more control over display details, like size & alignment, but sacrifices readability.

### ✨ Horizontal Rule
Add a horizontal rule (a.k.a. divider) by using 3 dashes with a blank line before and after: 
```
Section 1

---

Section 2
```

Divider pictured below:

---

Made with love by WiCS & DAGDC. 💜❤️
