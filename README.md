# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨
Sure! Here's an example of how to create a `style.css` file and apply it to a simple HTML page. I'll use at least three different selectors, style an image, and include margin, padding, and borders to improve readability and aesthetics. I'll also use a different font and link the external CSS file.

### 1. **style.css**

```css
/* style.css */

/* Apply a different font to the whole page */
body {
    font-family: 'Arial', sans-serif;
    background-color: #f4f4f4;
    color: #333;
    margin: 0;
    padding: 0;
}

/* Styling for a header with ID */
#main-header {
    background-color: #4CAF50;
    color: white;
    text-align: center;
    padding: 20px;
    margin-bottom: 20px;
}

/* Class selector to style paragraph elements */
.text-center {
    text-align: center;
    font-size: 1.2em;
    color: #555;
}

/* Apply padding and border to an image */
img {
    display: block;
    margin: 20px auto;
    border: 5px solid #ddd;
    padding: 10px;
    width: 80%;
}

/* Style for a footer with a class selector */
.footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 15px;
    margin-top: 20px;
}
```



```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header id="main-header">
        <h1>Welcome to My Styled Page</h1>
    </header>

    <section>
        <h2 class="text-center">This is a sample section</h2>
        <p class="text-center">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce vehicula lacus ac tortor sodales, ut elementum purus scelerisque.</p>
        <img src="https://via.placeholder.com/600x400" alt="Sample Image">
    </section>

    <footer class="footer">
        <p>&copy; 2025 My Website</p>
    </footer>
</body>
</html>
