# portfolio-
A sleek, responsive portfolio website showcasing my skills, projects, and professional experience using HTML, CSS, and JavaScript. Explore my work, learn about my background, and get in touch through an interactive and visually appealing interface. Contributions are welcome!

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Niharika's Portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background-color: rgb(0, 0, 33);
            color: white;
            font-family: 'Poppins', sans-serif;
        }

        header {
            padding: 20px;
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(5px);
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav .left {
            font-size: 1.5rem;
            font-weight: 700;
        }

        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            color: aliceblue;
        }

        nav ul li {
            margin: 0 23px;
            cursor: pointer;
            color: white; /* Changed color to white */
        }

        nav ul li:hover {
            color: #3054e4;
        }

        main {
            padding: 40px 20px;
        }

        .firstSection {
            display: flex;
            justify-content: space-around;
            align-items: center;
            margin: 80px 0;
            flex-wrap: wrap;
            color: azure;
        }

        .firstSection div {
            flex: 1 1 45%;
            margin: 10px;

        }

        .leftSection {
            font-size: 2.5rem;
        }

        .leftSection span {
            display: block;
            margin-top: 10px;
            font-size: 1.2rem;
        }

        .rightSection img {
            width: 50%;
            max-width: 250px;
            margin: 50px 250px;
        }

        .section {
            margin-bottom: 40px;
        }

        .section h2 {
            margin-bottom: 20px;
            font-size: 1.5rem;
        }

        .sectionContent {
            background: rgba(255, 255, 255, 0.1);
            padding: 20px;
            border-radius: 10px;
            margin-bottom: 20px;
        }

        .secondSection {
            text-align: center;
            margin-bottom: 40px;
        }

        .secondSection h2 {
            font-size: 1.9rem;
            margin-bottom: 20px;
            width: 100%;
        }

        .box {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 20px;
        }

        .vertical {
            background: rgba(255, 255, 255, 0.1);
            padding: 20px;
            border-radius: 10px;
            width: calc(33.33% - 20px);
            margin-bottom: 20px;
            text-align: left;
        }

        .vertical img {
            max-width: 100%;
            border-radius: 10px;
        }

        .vertical-title {
            font-weight: 600;
            margin: 10px 0;
        }

        .vertical-desc {
            font-size: 0.9rem;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: rgba(255, 255, 255, 0.1);
        }

        .right a{
            color:aliceblue;
        }
    </style>
</head>

<body>
    <header>
        <nav>
            <div class="left">Niharika's Portfolio</div>
            <div class="right">
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#internships">Internships</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#contact">Contact Me</a></li>
                </ul>
            </div>
        </nav>
    </header>

    <main>
        <section id="home" class="firstSection">
            <div class="leftSection">
                Hi, My name is Niharika
                <div>I am a passionate</div>
                <span id="element"></span>
            </div>
            <div class="rightSection">
                <img src="pic 1.jpg" alt="Web Developer Background Image">
            </div>
        </section>

        <section id="about" class="section">
            <div class="sectionContent">
                <h2>About Me</h2>
                <p>I am self-motivated and disciplined, driven by a strong desire to succeed. I approach challenges with focus and determination, consistently working towards my goals.</p>
            </div>
        </section>

        <section id="skills" class="section">
            <div class="sectionContent">
                <h2>Skills</h2>
                <ul>
                    <li>C++</li>
                    <li>C</li>
                    <li>Java</li>
                    <li>HTML</li>
                    <li>CSS</li>
                    <li>JavaScript</li>
                    <li>React</li>
                </ul>
            </div>
        </section>

        <section id="internships" class="secondSection">
            <h2>Internships</h2>
            <div class="box">
                <div class="vertical">
                    <div class="vertical-title">AWS-AIML Internship. </div>
                    <div class="vertical-desc">Company-AWS </div>
                </div>
                <div class="vertical">
                    <div class="vertical-title">Google-Android development virtual Internship.</div>
                    <div class="vertical-desc">Google - 2023</div>
                </div>
                <div class="vertical">
                    <div class="vertical-title"> Juniper Networks-Networking virtual Internship. </div>
                    <div class="vertical-desc">Juniper Network - 2024</div>
                </div>
            </div>
        </section>

        <section id="projects" class="section">
            <div class="sectionContent">
                <h2>Projects</h2>
                <p>Project 1:Diabetic Detection-Machine Learning. </p>
                <p>Project 2: Guess Game-Java</p>
            </div>
        </section>

        <section id="contact" class="section">
            <div class="sectionContent">
                <h2>Contact</h2>
                <p>Email: niharikachunchu27@gmail</p>
                <p>Phone: 9177816550</p>
                <a href="https://github.com/Niharika2754">Github</a>
                <br>
                <a href="https://www.linkedin.com/in/chunchu-niharika-77400528b">linkedin</a>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Niharika's Portfolio</p>
    </footer>

    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>
    <script>
        var typed = new Typed('#element', {
            strings: ['Web Developer', 'Programmer', 'Web Designer'],
            typeSpeed: 50,
            backSpeed: 50,
            loop: true
        });
    </script>
</body>

</html>
