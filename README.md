# Project Homepage

This project includes a template HTML page with an external CSS stylesheet. The CSS uses `* { outline: 1px solid red; }` to help visualize element alignment. The color scheme ensures high contrast for accessibility.

## Files

- `index.html` — Homepage introducing yourself, projects, or hobbies.
- `style.css` — External stylesheet for layout and color scheme.

---

## Example: `index.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Homepage</title>
        <link rel="stylesheet" href="style.css">
        <!-- Logo image inserted at top left corner -->
        <img src="semester 2/images/logo.png" alt="Logo" style="position:absolute;top:0;left:0;width:100px;height:auto;">
</head>
<body>
    <nav>
        <ul>
            <li><a href="index.html">Homepage</a></li>
            <li><a href="introduction.html">Introduction Assignment</a></li>
            <li><a href="template.html">Template Page</a></li>
        </ul>
    </nav>
    <main class="content-columns">
        <section>
            <h2>About Me</h2>
            <p>Hello! I'm a developer passionate about web technologies.</p>
            <!-- Photo of me inserted below -->
            <img src="semester 2/images/photoofme.png" alt="Photo of Me" style="width:200px;height:auto;">
        </section>
        <section>
            <h2>Projects</h2>
            <p>Check out my latest coding projects and open-source contributions.</p>
        </section>
        <section>
            <h2>Hobbies</h2>
            <p>I enjoy baking, photography, gaming, and spending time with my family.</p>
            <!-- Banner photo inserted below -->
            <img src="semester 2/images/bannerphoto.png" alt="Banner Photo" style="width:100%;height:auto;">
        </section>
    </main>
</body>
</html>
```

---

## Example: `style.css`

```css
/* Outline for debugging layout */
* { outline: 1px solid red; }

/* High contrast color scheme */
body {
    background: #fa92e7ff;
    color: #000000ff;
    font-family: Century Gothic, sans-serif;
}

nav ul {
    display: flex;
    gap: 2rem;
    list-style: none;
    background: #fdbefeff;
    padding: 1rem;
}

nav a {
    color: #f7afffff;
    text-decoration: none;
    font-weight: bold;
}

nav a:hover {
    text-decoration: underline;
}

.content-columns {
    display: flex;
    gap: 2rem;
    margin: 2rem;
}

.content-columns section {
    flex: 1;
    background: #f280ffff;
    padding: 1rem;
    border-radius: 8px;
}
```

---

You can customize the content and color scheme as needed. Add images to each section for a more visual introduction.