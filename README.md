# Ex01 PORTFOLIO

## NAME: M.CHARAN LATHIKA
## REG NO: 212224040052

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
### index.html

```
<!DOCTYPE html>
<html>
<head>
    <title>My Portfolio - Home</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<header>
    <h1>My Portfolio</h1>

    <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About Me</a>
        <a href="projects.html">Projects</a>
        <a href="contact.html">Contact</a>
    </nav>
</header>

<section class="home">
    <div>
        <h2>Hello, I'm</h2>
        <h1>Charanlathika</h1>
        <h3>CSE Engineering Student</h3>
        <p>Welcome to my personal portfolio website.</p>
    </div>

    <div class="photo">
        <img src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?w=500" alt="Profile">
    </div>
</section>

<footer>
    <p>© 2026 My Portfolio</p>
</footer>

</body>
</html>
</html>
```


## about.html

```
<!DOCTYPE html>
<html>
<head>
    <title>About Me</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<header>
    <h1>My Portfolio</h1>

    <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About Me</a>
        <a href="projects.html">Projects</a>
        <a href="contact.html">Contact</a>
    </nav>
</header>

<section class="page">
    <h2>About Me</h2>

    <p>
        I am a third-year CSE Engineering student interested in
        technology, web development and creative projects.
    </p>

    <h3>Education</h3>
    <p>B.E Computer Science and Engineering</p>

    <h3>Skills</h3>
    <p>HTML, CSS, JavaScript, C and Python</p>

    <h3>Interests</h3>
    <p>Web Development, Photography and Creative Projects</p>
</section>

<footer>
    <p>© 2026 My Portfolio</p>
</footer>

</body>
</html>
```

## projects.html
```
<!DOCTYPE html>
<html>
<head>
    <title>My Projects</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<header>
    <h1>My Portfolio</h1>

    <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About Me</a>
        <a href="projects.html">Projects</a>
        <a href="contact.html">Contact</a>
    </nav>
</header>

<section class="page">
    <h2>My Projects</h2>

    <div class="project">
        <h3>Food Rescue Connect</h3>
        <p>
            A project that helps connect surplus food with
            people in need.
        </p>
    </div>

    <div class="project">
        <h3>Portfolio Website</h3>
        <p>
            A personal portfolio website created using HTML and CSS.
        </p>
    </div>
</section>

<footer>
    <p>© 2026 My Portfolio</p>
</footer>

</body>
</html>
```

## contact.html

```
<!DOCTYPE html>
<html>
<head>
    <title>Contact Me</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<header>
    <h1>My Portfolio</h1>

    <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About Me</a>
        <a href="projects.html">Projects</a>
        <a href="contact.html">Contact</a>
    </nav>
</header>

<section class="page">
    <h2>Contact Me</h2>

    <p>Email: myemail@example.com</p>
    <p>Instagram: @myinstagram</p>
    <p>LinkedIn: My Profile</p>
</section>

<footer>
    <p>© 2026 My Portfolio</p>
</footer>

</body>
</html>
```
## style.css

```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background: #fdf7f4;
    color: #333;
}

header {
    background: #252936;
    color: white;
    padding: 20px;
    text-align: center;
}

header h1 {
    margin-bottom: 15px;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    font-size: 17px;
}

nav a:hover {
    color: #ff9a9e;
}

.home {
    min-height: 75vh;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 100px;
    padding: 50px;
}

.home h2 {
    font-size: 28px;
}

.home h1 {
    font-size: 50px;
    margin: 10px 0;
}

.home h3 {
    font-size: 24px;
    color: #d66b72;
}

.home p {
    margin-top: 15px;
    font-size: 18px;
}

.photo img {
    width: 300px;
    height: 300px;
    object-fit: cover;
    border-radius: 50%;
}

.page {
    min-height: 75vh;
    padding: 70px;
    text-align: center;
}

.page h2 {
    font-size: 40px;
    color: #d66b72;
    margin-bottom: 30px;
}

.page h3 {
    margin-top: 30px;
    color: #555;
}

.page p {
    margin: 15px auto;
    max-width: 700px;
    line-height: 1.7;
    font-size: 18px;
}

.project {
    background: white;
    max-width: 600px;
    margin: 25px auto;
    padding: 30px;
    border-radius: 15px;
    box-shadow: 0 4px 15px #ddd;
}

.project:hover {
    transform: scale(1.03);
    transition: 0.3s;
}

footer {
    background: #252936;
    color: white;
    text-align: center;
    padding: 20px;
}
```

## OUTPUT


<img width="1907" height="1188" alt="image" src="https://github.com/user-attachments/assets/fa2e59b2-4f50-4384-8c96-d8a1ac66f008" />


<img width="1903" height="900" alt="image" src="https://github.com/user-attachments/assets/e49f10a8-da5c-4526-9f1e-c550da6b1437" />


<img width="1892" height="907" alt="image" src="https://github.com/user-attachments/assets/aed0b36e-ad7c-4540-845e-428edb58ec0b" />


<img width="1899" height="890" alt="image" src="https://github.com/user-attachments/assets/28337e2c-e58d-46df-a651-c0e79dde4385" />




## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
