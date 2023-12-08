# Templating Engines in JavaScript: Pug, Handlebars (HBS), and EJS

Web development often involves generating HTML dynamically, and JavaScript templating engines make this task more manageable. Let's dive into three popular ones: Pug (formerly Jade), Handlebars (HBS), and Embedded JavaScript Templates (EJS).

## Pug

Pug is a high-performance template engine heavily influenced by Haml and implemented with JavaScript for Node.js and browsers.

### Advantages:

- **Simplified Syntax**: Pug uses whitespace and indentation, meaning no closing tags are necessary.
- **Code reusability**: Includes mixins and template inheritance.
- **Powerful**: Offers conditional statements, loops, and template inheritance.

### Disadvantages:

- **Learning Curve**: Developers must learn its unique syntax.
- **Error Handling**: Can be less clear with its stack trace on errors.

### Installation:

Install Pug via npm:

```bash
npm install pug
```
### Example:
```pug
doctype html
html(lang="en")
  head
    title= pageTitle
  body
    h1 Pug - node template engine
    #container.col
      if youAreUsingPug
        p You are amazing!
```
