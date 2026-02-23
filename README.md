[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=22821278&assignment_repo_type=AssignmentRepo)
# 🌐 HTML & CSS Walkthrough – Artificial Intelligence Webpage

This document walks you through the structure and styling of the AI webpage we built in class.

---

# 🧠 PART 1: Understanding index.html

HTML gives your webpage its structure.

Think of HTML as the skeleton of the website.

---

## 1️⃣ The Document Structure

```html
<!DOCTYPE html>
<html>
<head>
    <title>Introduction to Artificial Intelligence</title>
    <link rel="stylesheet" href="style.css">
</head>
```

- `<!DOCTYPE html>` tells the browser we are using HTML5.
- `<html>` wraps the entire webpage.
- `<head>` contains invisible page information.
- `<title>` sets the browser tab title.
- `<link>` connects the HTML file to the CSS file.

Without the `<link>` tag, your styling will not work.

---

## 2️⃣ The Header Section

```html
<header>
    <h1>Artificial Intelligence</h1>
    <p class="subtitle">The Future of Technology</p>
</header>
```

- `<header>` groups top content.
- `<h1>` is the main heading.
- `<p>` is a paragraph.
- `class="subtitle"` allows CSS styling.

Classes connect HTML to CSS.

---

## 3️⃣ The Introduction Section

```html
<section class="intro">
    <h2>What is AI?</h2>
    <p>Artificial Intelligence (AI) is the simulation of human intelligence in machines.</p>
    <img src="IMAGE_URL" alt="AI Robot" class="main-image">
</section>
```

- `<section>` groups related content.
- `<h2>` is a secondary heading.
- `<img>` adds an image.
- `alt` improves accessibility.
- `class="main-image"` connects to CSS styling.

---

## 4️⃣ The Cards Section

```html
<div class="card-container">
    <div class="card">
        <h3>Healthcare</h3>
        <p>AI helps doctors detect diseases faster.</p>
        <button>Learn More</button>
    </div>
</div>
```

- `<div>` creates containers.
- `class="card-container"` groups cards.
- `class="card"` styles each card.
- `<button>` adds interactivity.

---

## 5️⃣ Lists

```html
<ul>
    <li>AI can recognize faces.</li>
    <li>AI can generate art.</li>
</ul>
```

- `<ul>` creates an unordered list.
- `<li>` creates list items.

---

## 6️⃣ Footer

```html
<footer>
    <p>Created by Future Developers 🚀</p>
    <a href="https://openai.com" target="_blank">Visit OpenAI</a>
</footer>
```

- `<footer>` holds bottom content.
- `<a>` creates links.
- `target="_blank"` opens in a new tab.

---

# 🎨 PART 2: Understanding style.css

CSS controls the design of the webpage.

Think of CSS as the clothes and design of your website.

---

## 1️⃣ Page Styling

```css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    background-color: #f4f6f9;
    color: #333;
}
```

- `font-family` changes font.
- `margin: 0` removes default spacing.
- `background-color` sets page color.
- `color` sets default text color.

---

## 2️⃣ Header Styling

```css
header {
    background-color: #1f2937;
    color: white;
    text-align: center;
    padding: 30px;
}
```

- `background-color` changes background.
- `color` changes text color.
- `text-align` centers text.
- `padding` adds spacing inside the box.

---

## 3️⃣ Styling Classes

```css
.subtitle {
    font-style: italic;
    color: #9ca3af;
}
```

The `.` indicates a class selector.

---

## 4️⃣ Layout with Flexbox

```css
.card-container {
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
}
```

- `display: flex` activates flex layout.
- `justify-content` aligns items horizontally.
- `gap` creates space between items.
- `flex-wrap` allows wrapping on smaller screens.

---

## 5️⃣ Card Styling

```css
.card {
    background-color: white;
    padding: 20px;
    width: 250px;
    border-radius: 10px;
    box-shadow: 0px 4px 8px rgba(0,0,0,0.1);
}
```

- `border-radius` creates rounded corners.
- `box-shadow` adds depth.
- `width` controls card size.

---

## 6️⃣ Buttons

```css
button {
    background-color: #2563eb;
    color: white;
    border: none;
    padding: 10px 15px;
    border-radius: 5px;
    cursor: pointer;
}
```

Hover effect:

```css
button:hover {
    background-color: #1e40af;
}
```

---

# 🏫 In-Class Assignment (Required)

Modify the page and make it about **you or your interests**.

Ideas:
- Your hobbies
- A favorite sport
- A favorite video game
- Music you enjoy
- Your future career goals

Be creative and personalize your design.

---

# 🚀 Final Reminder

HTML = Structure  
CSS = Design  

Together, they create complete websites.
