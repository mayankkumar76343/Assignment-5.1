1. index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Website</title>

    <!-- Link external CSS -->
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>Welcome to My Website</h1>
        <p>This is my personal website created using HTML and CSS.</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>

    <main>
        <section id="home">
            <h2>Home</h2>
            <p>Welcome to my website! This page demonstrates how CSS
            can improve the appearance of a basic HTML page.</p>
        </section>

        <section id="about">
            <h2>About Me</h2>
            <p>I am learning web development and exploring HTML,
            CSS, and modern website design.</p>
        </section>

        <section id="services">
            <h2>Services</h2>
            <p>I enjoy creating simple, attractive, and user-friendly
            web pages.</p>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>Visit <a href="https://www.google.com">Google</a>
            to explore more information online.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 My Personal Website. All rights reserved.</p>
    </footer>

</body>
</html>
2. style.css

css

/* General page styling */
body {
    background-color: #f0f4f8;
    color: #333333;
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
}

/* Header styling */
header {
    background-color: #1e3a5f;
    color: white;
    text-align: center;
    padding: 30px 20px;
}

header h1 {
    margin-bottom: 10px;
    font-size: 32px;
}

header p {
    font-size: 16px;
}

/* Navigation styling */
nav {
    background-color: #2563eb;
    text-align: center;
    padding: 12px;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    font-weight: bold;
    display: inline-block;
    padding: 5px;
}

nav a:hover {
    color: #ffdd57;
    text-decoration: underline;
}

/* Main content styling */
main {
    max-width: 900px;
    margin: 25px auto;
    padding: 0 20px;
}

section {
    background-color: white;
    margin-bottom: 20px;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
}

/* Heading styling */
h2 {
    color: #1e3a5f;
    border-bottom: 2px solid #2563eb;
    padding-bottom: 8px;
}

/* Paragraph styling */
p {
    font-size: 16px;
}

/* Link styling */
a {
    color: #1d4ed8;
}

a:hover {
    color: #dc2626;
}

/* Footer styling */
footer {
    background-color: #1e3a5f;
    color: white;
    text-align: center;
    padding: 15px;
    margin-top: 30px;
}

footer p {
    margin: 0;
}

/* Responsive navigation */
@media (max-width: 600px) {
    nav a {
        margin: 5px;
        display: inline-block;
    }

    header h1 {
        font-size: 25px;
    }
}