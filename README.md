<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="project1.css">
</head>
<body>
    <header>
        <h1><i>My Portfolio</i></h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>Hi! I'm Vishal Dadrwal, a Student . I love creating and building things that live on the internet.</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Project Title 1</h3>
            <p>Description of project 1.</p>
            <a href="https://github.com/vishaldadrwal/project1" target="_blank">View on GitHub</a>
        </div>
        <div class="project">
            <h3>Project Title 2</h3>
            <p>Description of project 2.</p>
            <a href="https://github.com/vishaldadrwal/project2" target="_blank">View on GitHub</a>
        </div>
        <!-- Add more projects as needed -->
    </section>

    <Address>
        Address:- Phagwara,Punjab <br>
        Contact:- +91 9648476476 <br>
        Email:- <a href="">vishalnothing37@gmail.com</a>
    </Address>

    <footer>
        <p>&copy; 2024 Vishal Dadrwal. All rights reserved.</p>
    </footer>
</body>
</html>
<!--CSS-->
*{body {
    background-color: #f4f4f4;
    background-image: url(https://backiee.com/static/wallpapers/560x315/191020.jpg);
}

header {
    background: #333;
    color: #fff;
    padding: 5px;
    text-align: center;
    border-radius: 3px;
}
h3:hover{
    color: magenta;
}

nav ul {
    list-style-type: lower-greek;
    padding: 0px;
}

nav ul li {
    display: inline;
    margin: 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: double;
}

section {
    padding: 20px;
    margin: 20px;
    background: #fff;
    border-radius: 8px;
}

.project {
    margin: 15px 0;
    padding: 15px;
    border: 1px solid #ddd;
    border-radius: 5px;
    background-color: azure;
}
address{
    padding: 20px;
    margin: 20px;
    background: #fff;
    border-radius: 8px;
}

footer {
    text-align: center;
    padding: 10px;
    background: #333;
    border-radius: 3px;
    color: #fff;
    position: relative;
    bottom: 0;
    width: auto;
}
