# blog-page-website

this is a project

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Random HTML Page</title>
    <style> 
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        header, footer {
            background-color: #f8f9fa;
            padding: 10px;
            text-align: center;
        }
        nav {
            margin-bottom: 20px;
        }
        nav a {
            margin: 0 10px;
            text-decoration: none;
            color: #007bff;
        }
        section {
            margin-bottom: 20px;
        }
        img {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to the Random HTML Page</h1>
</header>

<nav>
    <a href="#section1">Section 1</a>
    <a href="#section2">Section 2</a>
    <a href="#section3">Section 3</a>
</nav>

<section id="section1">
    <h2>Section 1: Introduction</h2>
    <p>This is a random paragraph to demonstrate HTML elements. HTML stands for HyperText Markup Language and is used to create web pages.</p>
    <p>Here is an example of a link to <a href="https://www.example.com" target="_blank">Example.com</a>.</p>
</section>

<section id="section2">
    <h2>Section 2: Images and Lists</h2>
    <p>Below is an example of an image:</p>
    <img src="https://via.placeholder.com/600x400" alt="Placeholder Image">
    <p>Here is an unordered list:</p>
    <ul>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
    </ul>
    <p>And here is an ordered list:</p>
    <ol>
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
    </ol>
</section>

<section id="section3">
    <h2>Section 3: Form Example</h2>
    <center><p>Please fill out the form below:</p></center>
    <form action="#" method="POST">
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name" required><br><br>
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" required><br><br>
        <label for="message">Message:</label><br>
        <textarea id="message" name="message" rows="4" cols="50" required></textarea><br><br>
        <input type="submit" value="Submit">
    </form>
</section>

<footer>
    <p>&copy; 2024 Random HTML Page. All rights reserved.</p>
</footer>

</body>
</html>
