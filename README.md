my-blog/
├── index.html         ← Homepage with blog post links
├── style.css          ← CSS styling
└── posts/
    ├── post1.html     ← First blog post
    └── post2.html     ← Second blog post
    <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Blog</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Welcome to My Blog</h1>
    <p>Thoughts, stories & ideas.</p>
  </header>

  <main>
    <article>
      <h2><a href="posts/post1.html">My First Blog Post</a></h2>
      <p>This is a short preview of the first blog post.</p>
    </article>

    <article>
      <h2><a href="posts/post2.html">Another Day, Another Post</a></h2>
      <p>Thoughts from another day...</p>
    </article>
  </main>

  <footer>
    <p>&copy; 2025 My Blog</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>My First Blog Post</title>
  <link rel="stylesheet" href="../style.css" />
</head>
<body>
  <header>
    <h1>My First Blog Post</h1>
  </header>

  <main>
    <p>This is the content of my very first blog post. I'm learning to build websites using GitHub Pages!</p>
    <a href="../index.html">← Back to Home</a>
  </main>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Another Day, Another Post</title>
  <link rel="stylesheet" href="../style.css" />
</head>
<body>
  <header>
    <h1>Another Day, Another Post</h1>
  </header>

  <main>
    <p>Here’s another post. The journey of learning web development continues!</p>
    <a href="../index.html">← Back to Home</a>
  </main>
</body>
</html>
