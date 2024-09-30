# Technical-Documentation-page

Solution for Build a Technical Documentation Page
Close
×
HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Technical Documentation</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <nav id="navbar">
    <header>Technical Documentation</header>
    <a class="nav-link" href="#Introduction">Introduction</a>
    <a class="nav-link" href="#Section_1">Section 1</a>
    <a class="nav-link" href="#Section_2">Section 2</a>
    <a class="nav-link" href="#Section_3">Section 3</a>
    <a class="nav-link" href="#Section_4">Section 4</a>
    <a class="nav-link" href="#Section_5">Section 5</a>
  </nav>

  <main id="main-doc">
    <section class="main-section" id="Introduction">
      <header>Introduction</header>
      <p>This is an introduction to the technical documentation page.</p>
      <p>It contains sections, paragraphs, lists, and code snippets.</p>
      <p>This project is a part of the FreeCodeCamp curriculum.</p>
    </section>

    <section class="main-section" id="Section_1">
      <header>Section 1</header>
      <p>This section covers the basics.</p>
      <code>console.log('Hello, World!');</code>
      <p>This is a basic code snippet for logging text to the console.</p>
      <ul>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
      </ul>
    </section>

    <section class="main-section" id="Section_2">
      <header>Section 2</header>
      <p>This section dives deeper into the documentation.</p>
      <code>let x = 10;</code>
      <p>Another code example showing variable declaration.</p>
      <ul>
        <li>Item 4</li>
        <li>Item 5</li>
      </ul>
    </section>

    <section class="main-section" id="Section_3">
      <header>Section 3</header>
      <p>This section explains more advanced topics.</p>
      <code>function add(a, b) { return a + b; }</code>
      <p>Example of a function definition.</p>
    </section>

    <section class="main-section" id="Section_4">
      <header>Section 4</header>
      <p>Here we explore more content.</p>
      <code>const result = add(5, 3);</code>
      <p>Example usage of a function call.</p>
    </section>

    <section class="main-section" id="Section_5">
      <header>Section 5</header>
      <p>This is the final section.</p>
      <code>document.querySelector('main');</code>
      <p>Example of DOM manipulation in JavaScript.</p>
    </section>
  </main>
</body>
</html>
CSS
/* General Styles */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.6;
  display: flex;
}

header {
  font-size: 1.5em;
  margin-bottom: 15px;
}

/* Navbar Styles */
#navbar {
  background-color: #333;
  color: white;
  width: 200px;
  position: fixed;
  top: 0;
  left: 0;
  height: 100%;
  padding: 20px;
}

#navbar header {
  font-size: 1.2em;
  margin-bottom: 20px;
}

.nav-link {
  color: white;
  text-decoration: none;
  display: block;
  margin-bottom: 10px;
}

.nav-link:hover {
  text-decoration: underline;
}

/* Main content styles */
#main-doc {
  margin-left: 220px;
  padding: 20px;
  max-width: 1000px;
}

.main-section {
  margin-bottom: 40px;
}

code {
  display: block;
  background-color: #f4f4f4;
  padding: 10px;
  border-radius: 5px;
  margin-top: 10px;
}

/* Media Query */
@media (max-width: 768px) {
  #navbar {
    position: relative;
    width: 100%;
    height: auto;
  }

  #main-doc {
    margin-left: 0;
  }
}
Close
