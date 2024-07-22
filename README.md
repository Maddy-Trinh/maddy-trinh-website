<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fashion Magazine</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f0ff;
            color: #4a0e4e;
        }
        header {
            background-color: #8a2be2;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            color: #fff;
            margin: 0;
        }
        nav {
            background-color: #9b59b6;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            margin: 0 10px;
            text-decoration: none;
            color: #fff;
            font-weight: bold;
        }
        nav a:hover {
            color: #e0e0e0;
        }
        .main-content {
            display: grid;
            grid-template-columns: 2fr 1fr;
            gap: 20px;
            padding: 20px;
        }
        .article {
            margin-bottom: 20px;
            background-color: #fff;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .sidebar {
            background-color: #d8bfd8;
            padding: 20px;
            border-radius: 5px;
        }
        h2, h3 {
            color: #4b0082;
        }
    </style>
</head>
<body>
    <header>
        <h1>Fashion Magazine</h1>
    </header>
    <nav>
        <a href="#">Fashion</a>
        <a href="#">Beauty</a>
        <a href="#">Culture</a>
        <a href="#">Living</a>
        <a href="#">Shopping</a>
    </nav>
    <div class="main-content">
        <main>
            <article class="article">
                <h2>Featured Article</h2>
                <p>Content of the featured article goes here.</p>
            </article>
            <article class="article">
                <h2>Latest News</h2>
                <p>Content of the latest news article goes here.</p>
            </article>
        </main>
        <aside class="sidebar">
            <h3>Trending</h3>
            <ul>
                <li>Trending item 1</li>
                <li>Trending item 2</li>
                <li>Trending item 3</li>
            </ul>
        </aside>
    </div>
</body>
</html>
