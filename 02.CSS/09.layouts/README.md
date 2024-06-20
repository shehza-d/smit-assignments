
**Question: Building a Website Header with Navigation**

**Instructions:**
You are tasked with creating a website header with navigation for an online clothing store. The header should have a logo on the left, a navigation menu on the right, and a visually appealing design. Follow these steps:

**Step 1: HTML Structure**
Use the following HTML code as a starting point:

```html
<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="logo.png" alt="Store Logo">
        </div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Shop</a></li>
                <li><a href="#">Products</a></li>
                <li><a href="#">About Us</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
    <!-- Rest of your website content goes here -->
</body>
</html>
```

**Step 2: CSS Styles**
Create a CSS file (`styles.css`) and apply the necessary styles to achieve the following:

1. Use relative positioning to position the navigation menu (`<nav>`) to the right side of the header (`<header>`).

2. Apply absolute positioning to the logo (`<div class="logo">`) to position it at the top-left corner of the header.

3. Implement fixed positioning for the header to make it stick to the top of the viewport when scrolling.

4. Utilize `z-index` to ensure that the fixed header is on top of other content when scrolling.

5. Use `float` and `clear` to create a horizontal navigation menu with floated list items.

6. Style fonts, colors, margins, and widths to create an attractive design for the header.

**Practical Application:** This exercise simulates the creation of a common website header with a logo and navigation menu. It covers essential layout techniques and basic CSS properties while allowing students to design an aesthetically pleasing and practical webpage element.