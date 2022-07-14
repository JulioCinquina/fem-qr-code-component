# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

This is a simple project in which a card component appears centered in the page. Despite being simple, some important concepts and tools are implemented, such as **semantic HTML**, **accessibility**, **Flexbox**, **CSS relative units**, **CSS custom properties**, the **BEM naming convention**, and **universal box sizing with inheritance**.

### Screenshot

![web page with a light gray/blue background and a centered card with a white QR code over a dark blue background and text underneath it](./screenshot.png)

### Links

- [Solution on Frontend Mentor]()
- [Live Site on GitHub Pages]()

## My process

### Built with

- Semantic HTML5 markup
- WCAG level AA contrast ratios
- Flexbox
- CSS relative units
- CSS custom properties
- BEM naming convention
- "Universal box sizing with inheritance" reset

### What I learned

Despite being a simple project, it allowed me to practice aspects of **semantic HTML** — with the `<main>` and `<footer>` tags — and **accessibility** — using colors with a minimum contrast ratio of 4.5:1, required by WCAG level AA for normal text.

**Flexbox** was used to lay out the _main content_ and _footer_ in the page. As a flex item, the _main content_ element is centered vertically by `margin-block: auto`, and the card is centered horizontally by `margin-inline: auto`.

**CSS relative units** ensure the text is scaled according to the user browser's font size settings.

**CSS custom properties** make the page more maintainable: colors can be easily changed by modifying the values of custom properties in the root element, and the **BEM naming convention** makes the CSS code more readable and reusable.

Finally, the **"universal box sizing with inheritance"** reset method is used, since it is regarded as best practice (see references to [CSS-Tricks](https://css-tricks.com/) articles below).

### Continued development

In future projects, I want to keep working on writing **semantic HTML** and **accessible websites**, since I believe that great developers must strive to make their applications accessible to everyone.

### Useful resources

- [_Contrast Checker_ tool by WebAIM](https://webaim.org/resources/contrastchecker/) — Excellent tool that makes it easy to check if color contrast ratios in the page meet WCAG standards and adjust them if necessary.
- [_Box Sizing_ by Marie Mosley](https://css-tricks.com/box-sizing/) — Article about the box model, how its behavior is changed by the `box-sizing` property and the different reset methods.
- [_Inheriting box-sizing Probably Slightly Better Best-Practice_ by Chris Coyier](https://css-tricks.com/inheriting-box-sizing-probably-slightly-better-best-practice/) — Article explaining why the "universal box sizing with inheritance" reset might be preferable.

## Author

- Frontend Mentor - [@JulioCinquina](https://www.frontendmentor.io/profile/JulioCinquina)
