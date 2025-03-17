<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Blog</title>
    <link rel="stylesheet" href="styles.css">
</head>
<style>
/* Basic Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

header h1 {
    font-size: 2.5rem;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 1.2rem;
}

main {
    padding: 20px;
}

.blog-posts {
    display: flex;
    flex-direction: column;
    gap: 20px;
}

.post {
    background: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

.post h2 {
    font-size: 2rem;
    margin-bottom: 10px;
}

.date {
    color: #888;
    font-size: 0.9rem;
    margin-bottom: 15px;
}

.read-more {
    text-decoration: none;
    color: #007BFF;
    font-weight: bold;
}

footer {
    text-align: center;
    padding: 15px;
    background: #333;
    color: #fff;
    position: absolute;
    width: 100%;
    bottom: 0;
}
</style>
<body>
    <!-- Header Section -->
    <header>
        <nav>
            <ul>
                <li> <a href="#home">Home</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#experience">Experience</a></li><br>
            </ul>
        </nav> <br>
		 <a href="#contact-form" class="contact">Contact Us</a>
    </header>


    <!-- Main Content Section -->
    <main>
        <section class="blog-posts">
            <article class="post">
                <h2>Feona Lovitos</h2>
                <p class="date">March 17, 2025</p>
                <p>Hello! I’m Feona Lovitos, an IT student passionate about technology and problem-solving. 
				<br>My journey in IT has allowed me to explore various areas like software development, web design, and data analysis.</p>
                <a href="#" class="read-more">Read more</a>
            </article>

            <article class="post">
                <h2>Beveymae Mina</h2>
                <p class="date">March 17, 2025</p>
                <p>an IT student with a strong interest in technology and innovation. I’m passionate about learning new programming languages,
				<br> building software, and solving complex problems. Throughout my studies, I’ve worked on various projects that have allowed me to <br>develop my skills in areas like coding, databases, and system administration.</p>
                <a href="#" class="read-more">Read more</a>
            </article>

            <!-- Add more posts here -->
        </section>
    </main>

    <!-- Footer Section -->
    <footer>
        <p>2025 Feona Lovitos | Beveymae Mina BSIT Sec 4. All Rights Reserved.</p>
    </footer>
</body>
</html>
