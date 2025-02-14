<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hafsa Waseem | React Native Developer</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #0d1117;
            color: white;
            text-align: center;
        }

        header {
            background: linear-gradient(90deg, #1f1f1f, #3a3a3a);
            padding: 50px 20px;
        }

        h1 {
            font-size: 2.5em;
            display: inline-block;
        }

        .highlight {
            color: #61dafb;
        }

        .tagline {
            font-size: 1.2em;
            font-weight: 300;
        }

  
        .about, .tech-stack, .contact {
            margin: 40px 0;
            padding: 20px;
            background-color: #161b22;
            width: 80%;
            margin-left: auto;
            margin-right: auto;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(255, 255, 255, 0.1);
        }

       
        .stack-icons {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            margin-top: 20px;
        }

        .stack-icons span {
            background-color: #3a3a3a;
            padding: 10px 15px;
            margin: 5px;
            border-radius: 5px;
            font-weight: bold;
        }

      
        .social-links {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-top: 20px;
        }

        .social-links a {
            color: #61dafb;
            text-decoration: none;
            font-size: 1.2em;
            transition: 0.3s;
        }

        .social-links a:hover {
            color: #ffffff;
            text-shadow: 0px 0px 10px rgba(255, 255, 255, 0.8);
        }

      
        .image-container {
            margin: 20px 0;
        }

        .image-container img {
            width: 70%;
            max-width: 500px;
            border-radius: 10px;
            box-shadow: 0px 0px 15px rgba(255, 255, 255, 0.2);
        }

        
        .about-container {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }

        .about-text {
            flex: 1;
            text-align: left;
        }

        .about-image {
            flex: 1;
            max-width: 300px;
        }

        .about-image img {
    width: 200px; 
    height: 200px; 
    border-radius: 50%; 
    object-fit: cover; 
    box-shadow: 0px 0px 15px rgba(255, 255, 255, 0.2);
}


    
        footer {
            margin-top: 30px;
            padding: 20px;
            background-color: #1f1f1f;
        }
    </style>
</head>
<body>

    <header>
        <div class="container">
            <h1>Hello, I'm <span class="highlight">Hafsa Waseem</span> 👋</h1>
            <p class="tagline">🚀 Software Developer | React Native Specialist</p>
        </div>
    </header>

    <!-- Welcome Image -->
    <div class="image-container">
        <img src="https://raw.githubusercontent.com/Hafsa-Waseem/HafsaWaseem/main/Lux-NUfRMexXUNXom4NuA-removebg-preview.png" alt="Welcome to my profile">
    </div>

    <section class="about">
        <div class="about-container">
            <div class="about-text">
                <h2>About Me</h2>
                <p>
                    I’m a <b>React Native Developer</b> with a passion for building high-performance and visually appealing mobile apps.  
                    My core expertise lies in <b>React Native</b>, but I also have strong experience in <b>HTML, CSS, JavaScript, and React</b> for frontend development.  
                    Additionally, I have experience with <b>Java and XML</b> for native Android development.  
                    <br><br>
                    🔥 I specialize in <b>UI/UX optimization, API integrations, and performance tuning</b>.  
                    💾 For backend and database management, I work with <b>Firebase</b> and <b>SQLite</b> to ensure smooth data handling.  
                    🚀 Always exploring new tech to build innovative and user-friendly applications!
                </p>
            </div>
            <!-- Girl with Lollipop on Right Side -->
            <div class="about-image">
                <img src="https://raw.githubusercontent.com/Hafsa-Waseem/HafsaWaseem/main/UJDtpl8tScW7tR8zR7dagw.png" alt="Girl with Laptop">
            </div>
        </div>
    </section>

    <section class="tech-stack">
        <h2>🛠️ Tech Stack</h2>
        <div class="stack-icons">
            <span>⚛️ React Native</span>
            <span>💙 TypeScript</span>
            <span>🎨 UI/UX Design</span>
            <span>🔗 API Integration</span>
            <span>🔥 Firebase</span>
            <span>💾 SQLite</span>
            <span>🌐 HTML, CSS, JavaScript</span>
            <span>⚙️ React</span>
            <span>📱 Java & XML (Android)</span>
        </div>
    </section>

    <section class="contact">
        <h2>📫 Connect with Me</h2>
        <div class="social-links">
            <a href="https://www.linkedin.com/in/hafsa-waseem4" target="_blank">LinkedIn</a>
            <a href="https://github.com/Hafsa-Waseem" target="_blank">GitHub</a>
        </div>
    </section>

    <footer>
        <p>✨ Fun Fact: "I talk to my code more than I talk to people!" 😆</p>
    </footer>

</body>
</html>
