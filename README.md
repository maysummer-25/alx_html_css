# CSS Basic

This directory contains the early styling implementation for the **ALX HTML & CSS** project. It builds upon the `html_basic` project by introducing external CSS files to improve the visual layout of the HTML pages.

## Project Structure

```
css_basic/
├── base.css
├── styles.css
├── index.html
└── tweets.html
```

## Files Description

- **index.html**: The main homepage copied from the previous `html_basic` project.
- **tweets.html**: A secondary HTML page showcasing tweet samples.
- **base.css**: Contains common default CSS rules to enhance base styling.
- **styles.css**: Empty for now, but will be used for custom styles as the project progresses.

## Setup Instructions

To ensure your HTML files render with styles:

1. Make sure both `base.css` and `styles.css` are in the same directory as your HTML files.
2. Ensure the following lines are added to the `<head>` tag of both HTML files:

```html
<link href="base.css" rel="stylesheet">
<link href="styles.css" rel="stylesheet">
```

## Notes

- This project is part of the **ALX Software Engineering** curriculum.
- The goal is to progressively build styling skills by layering CSS onto static HTML files.

---

Feel free to update `styles.css` as you learn more advanced CSS techniques.
