# HTML: HyperText Markup Language

## What is HTML?

HTML is the main markup language for creating web pages and web applications.

It is the code used to structure a web page and its content. HTML was created by Tim Berners-Lee in 1991 and is a markup language, not a programming language.

## What does HTML stand for?

- **HyperText**: This refers to links. A link can be text, an image, or media that takes you to another page or part of the page.
- **Markup Language**: This is a way to add structure and meaning to content using tags.

HTML uses tags to tell browsers how to display content like headings, paragraphs, images, and links.

## HTML structure

A simple HTML page has a basic structure with these parts:

- `<!DOCTYPE html>`: Tells the browser that the page uses HTML5.
- `<html>`: The root element that wraps the whole page.
- `<head>`: Contains page settings, title, and links to styles or scripts.
- `<title>`: Sets the page title shown in the browser tab.
- `<body>`: Contains the visible content for the page, such as text, images, and links.

Example structure:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Page</title>
  </head>
  <body>
    <h1>Welcome</h1>
    <p>This is a simple page.</p>
  </body>
</html>
```

## What is HTML used for?

HTML is used for:

- Building the structure of web pages.
- Adding headings, paragraphs, lists, and links.
- Showing images, videos, and other media.
- Creating forms for user input.
- Making content ready for CSS styling and JavaScript behavior.

With HTML, you create the content and layout that users see in a browser.

---

## Important HTML Text Tags

### `<strong>` - Strong Importance

**Explanation:** The `<strong>` tag is used to define text with strong importance. Content inside `<strong>` is typically displayed in bold.

**Example:**
```html
<p>This is <strong>very important</strong> information.</p>
```

**Result:** This is **very important** information.

---

### `<em>` - Emphasis

**Explanation:** The `<em>` tag is used to define emphasized text. Content inside `<em>` is typically displayed in italic.

**Example:**
```html
<p>This is <em>emphasized</em> text.</p>
```

**Result:** This is *emphasized* text.

---

### `<mark>` - Marked/Highlighted Text

**Explanation:** The `<mark>` tag is used to highlight or mark text. Content is typically displayed with a yellow background.

**Example:**
```html
<p>This is <mark>highlighted</mark> text.</p>
```

**Result:** This is ==highlighted== text.

---

### `<small>` - Small Text

**Explanation:** The `<small>` tag is used to define smaller text, such as fine print or disclaimer text.

**Example:**
```html
<p>Price: $100 <small>(Plus tax)</small></p>
```

**Result:** Price: $100 _(Plus tax)_

---

### `<del>` - Deleted Text

**Explanation:** The `<del>` tag represents text that has been deleted or removed. Content is typically displayed with a strikethrough.

**Example:**
```html
<p>Original price: <del>$200</del> Now: $100</p>
```

**Result:** Original price: ~~$200~~ Now: $100

---

### `<ins>` - Inserted Text

**Explanation:** The `<ins>` tag represents text that has been inserted or added. Content is typically displayed with an underline.

**Example:**
```html
<p>New feature: <ins>Dark Mode</ins></p>
```

**Result:** New feature: <u>Dark Mode</u>

---

### `<sub>` - Subscript Text

**Explanation:** The `<sub>` tag defines subscript text, displayed below the baseline (smaller and lower). Used for chemical formulas and mathematical expressions.

**Example:**
```html
<p>Chemical formula: H<sub>2</sub>O</p>
```

**Result:** Chemical formula: H₂O

---

### `<sup>` - Superscript Text

**Explanation:** The `<sup>` tag defines superscript text, displayed above the baseline (smaller and higher). Used for exponents and citations.

**Example:**
```html
<p>E = mc<sup>2</sup></p>
```

**Result:** E = mc²

---

### `<code>` - Code Text

**Explanation:** The `<code>` tag is used to display computer code. Content is displayed in a monospace font, making it look like programming code.

**Example:**
```html
<p>Use <code>console.log()</code> to debug.</p>
```

**Result:** Use `console.log()` to debug.

---

### `<kbd>` - Keyboard Input

**Explanation:** The `<kbd>` tag represents user keyboard input. It's useful for documentation and instructions.

**Example:**
```html
<p>Press <kbd>Ctrl</kbd> + <kbd>S</kbd> to save.</p>
```

**Result:** Press Ctrl + S to save.

---

### `<var>` - Variable

**Explanation:** The `<var>` tag defines a variable in mathematics or programming.

**Example:**
```html
<p>The variable <var>x</var> represents the unknown value.</p>
```

**Result:** The variable *x* represents the unknown value.

---

### `<abbr>` - Abbreviation

**Explanation:** The `<abbr>` tag defines an abbreviation or acronym. When you hover over the text, the full explanation appears in a tooltip.

**Example:**
```html
<p><abbr title="HyperText Markup Language">HTML</abbr> is essential for web development.</p>
```

**Result:** HTML is essential for web development. (Hover to see the full form)

---

### `<cite>` - Citation

**Explanation:** The `<cite>` tag defines the title of a creative work (book, movie, song, research paper, etc.).

**Example:**
```html
<p>I love reading <cite>The Great Gatsby</cite>.</p>
```

**Result:** I love reading *The Great Gatsby*.

---

### `<blockquote>` - Block Quotation

**Explanation:** The `<blockquote>` tag defines a long quotation. It's typically displayed with indentation and represents content quoted from another source.

**Example:**
```html
<blockquote>
  <p>The only way to do great work is to love what you do. - Steve Jobs</p>
</blockquote>
```

**Result:**
> The only way to do great work is to love what you do. - Steve Jobs

---

### `<q>` - Inline Quotation

**Explanation:** The `<q>` tag defines a short inline quotation. Browsers usually insert quotation marks around the text automatically.

**Example:**
```html
<p>Albert Einstein said <q>Imagination is more important than knowledge.</q></p>
```

**Result:** Albert Einstein said "Imagination is more important than knowledge."

---

## Summary

These text tags help you:
- **Add semantic meaning** to your content (screen readers and search engines understand better)
- **Style text** without using CSS
- **Improve accessibility** for users with assistive technologies
- **Make code more readable** and maintainable


