<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Blog</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
        }
        header {
            background-color: #007bff;
            color: #ffffff;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #343a40;
            color: #ffffff;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: #ffffff;
            text-decoration: none;
            margin: 0 10px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px 0;
        }
        .post {
            background-color: #ffffff;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 5px;
        }
        .post h2 {
            color: #007bff;
        }
        .post p {
            line-height: 1.6;
        }
        footer {
            background-color: #007bff;
            color: #ffffff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>My Blog</h1>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
</nav>

<div class="container">
    <div class="post">
        <h2>Sample Blog Post 1</h2>
        <p>This is a sample blog post. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam vitae justo vel purus posuere vestibulum. Fusce euismod ipsum at libero fermentum, sed viverra lorem convallis. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Nulla facilisi.</p>
    </div>

    <div class="post">
        <h2>Sample Blog Post 2</h2>
        <p>This is another sample blog post. Phasellus sit amet turpis eu purus pulvinar vehicula. Pellentesque vitae consectetur velit, eget feugiat libero. Quisque eget ullamcorper ligula, ac tempus elit.</p>
    </div>
</div>

<footer>
    &copy; 2024 My Blog
</footer>

</body>
</html>
