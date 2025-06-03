# css_basic

This project is part of the ALX Software Engineering HTML & CSS curriculum. It introduces the basics of styling web pages using external CSS files and applies CSS Flexbox for layout.

## Description

In this task, we copied HTML files from the previous `html_basic` project and added styling to improve their appearance and layout. The focus here is on using CSS Flexbox to arrange page elements effectively.

Two CSS files are used:

- `base.css`: Contains default styles to reset and normalize elements.
- `styles.css`: Contains custom styles including Flexbox properties to create a responsive layout.

## File Structure

```
css_basic/
├── base.css        # Default CSS rules
├── styles.css      # Custom styles including Flexbox layout
├── index.html      # Home page HTML
├── tweets.html     # Tweets page HTML
└── README.md       # Project documentation
```

## Layout and Styling with Flexbox

The layout aims to achieve the following structure visually:

```
<header>
  <!-- Header content -->
</header>

<main>
  <article>
    <!-- Main content area taking 2/3 of the width -->
  </article>
  <aside>
    <!-- Sidebar taking 1/3 of the width -->
  </aside>
</main>

<footer>
  <!-- Footer content -->
</footer>
```

### CSS Flexbox Rules Applied in `styles.css`

- Both `<body>` and `<main>` are set as flex containers using `display: flex`.
- `<body>` arranges its children (`<header>`, `<main>`, `<footer>`) in a column using `flex-direction: column`.
- `<main>` arranges its children (`<article>`, `<aside>`) in a row using `flex-direction: row`.
- `<main>` has flexible sizing with `flex: auto` to adjust its height and width automatically.
- `<article>` and `<aside>` have `flex: 2` and `flex: 1` respectively to create a 2/3 and 1/3 width split.
- Both `<article>` and `<aside>` have `overflow-y: auto` to enable vertical scrolling if content overflows.

## How to Use

Open `index.html` or `tweets.html` in a web browser. Ensure the CSS files are in the same folder as the HTML files. Both HTML files link to these CSS files in their `<head>`:

```html
<link href="base.css" rel="stylesheet">
<link href="styles.css" rel="stylesheet">
```

## Requirements

- All files end with a new line.
- No external libraries or frameworks are used.
- The code is W3C compliant and validates with the [W3C Validator](https://validator.w3.org/).

## Author

Project by Mmesoma Chukwumezie for the ALX Software Engineering program.
