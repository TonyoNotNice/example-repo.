# example-repo.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Hobbies</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to an external stylesheet for better organization -->
</head>
<body>
    <header class="page-header">
        <h1>My Hobbies</h1>
        <nav>
            <ul>
                <li><a href="#menu">MENU</a></li>
                <li><a href="#hobby">HOBBY</a></li>
                <li><a href="#about">ABOUT</a></li>
            </ul>
        </nav>
        <hr>
    </header>
    
    <section id="hobby"> <!-- Added an ID for linking -->
        <h3>1. Being a Disk Jockey</h3>
        <div>
            <img src="img/dj.jpg" alt="A picture of me using turn table at a music festival" width="200">
            <img src="img/dj1.jpg" alt="A picture of me using turn table at a music festival" width="200">
            <img src="img/dj3.jpg" alt="A picture of me using turn table at a music festival" width="200">
        </div>
    </section>

    <article itemscope itemtype="http://schema.org/BlogPosting">
        <h2 itemprop="headline">Dlala Music Festival</h2>
        <p><time datetime="2018-12-25">December 25, 2018</time></p>
    </article>

    <main>
        <h1 style="text-align: center;">About</h1>
        <p>I'm a curious adventurer with a taste for the unknown. I live for trying new things, from flavors to experiences, and thrive on spontaneity. With an insatiable curiosity and a passion for living life to the fullest, I'm always ready to take on the next challenge and see where it takes me.</p>
    </main>

    <footer>
        <p>&copy; 2025 My Hobbies Website</p>
    </footer>
</body>
</html>
