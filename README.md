# demo-Portfolio
<!DOCTYPE html>
<html>
<head>
    <title>Mohamed Ashraf - Portfolio</title>
    <style>
        /* Universal reset as taught in slides */
        * {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
        }

        body {
            background-color: #f7f7f7;
            text-align: center;
        }

        /* Header styles */
        .header {
            background-color: #222222;
            color: white;
            padding: 40px 20px;
        }

        .header h1 {
            font-size: 32px;
            margin-bottom: 20px;
        }

        .header p {
            color: #cccccc;
            margin-bottom: 20px;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 14px;
        }

        /* General section styling */
        .section {
            padding: 50px 20px;
        }

        .section h2 {
            font-size: 24px;
            margin-bottom: 20px;
        }

        .about-text {
            max-width: 650px;
            margin: 0 auto;
            line-height: 1.6;
            color: #555555;
        }

        /* LinkedIn link styling */
        .linkedin-link {
            display: inline-block;
            margin-top: 15px;
            color: #0077b5;
            text-decoration: none;
            font-weight: bold;
        }

        /* Projects Section using inline-block as explained in the lab */
        .project-card {
            display: inline-block;
            width: 200px;
            background-color: white;
            border: 1px solid #e0e0e0;
            border-radius: 8px;
            padding: 20px;
            margin: 10px;
            text-align: left;
            vertical-align: top;
        }

        .project-card h3 {
            font-size: 16px;
            margin-bottom: 10px;
        }

        .project-card p {
            font-size: 13px;
            color: #666666;
            line-height: 1.4;
        }

        /* Project link inside card */
        .project-card a {
            display: inline-block;
            margin-top: 12px;
            color: #0077b5;
            text-decoration: none;
            font-size: 13px;
            font-weight: bold;
        }

        /* Contact form styling */
        .contact-box {
            display: inline-block;
            width: 350px;
            text-align: center;
        }

        .contact-box input,
        .contact-box textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 12px;
            border: 1px solid #cccccc;
            border-radius: 4px;
            display: block;
            box-sizing: border-box;
        }

        .contact-box textarea {
            height: 90px;
        }

        .contact-box button {
            background-color: #222222;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            width: 100%;
        }

        /* Footer */
        .footer {
            background-color: #222222;
            color: #aaaaaa;
            padding: 20px;
            font-size: 12px;
            margin-top: 40px;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <div class="header">
        <h1>Mohamed Ashraf</h1>
        <p>Web Developer | Designer | Freelancer</p>
        <div class="nav-links">
            <a href="#about">About</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
            <a href="https://www.linkedin.com/in/mohamed-ashraf-68b669430/" target="_blank">LinkedIn</a>
        </div>
    </div>

    <!-- About Me Section -->
    <div id="about" class="section">
        <h2>About Me</h2>
        <p class="about-text">
            Hello! I'm Mohamed Ashraf, a passionate web developer with experience in creating responsive and
            interactive websites. I love coding, designing, and bringing ideas to life on the web.
        </p>
        <p>
            <a class="linkedin-link" href="https://www.linkedin.com/in/mohamed-ashraf-68b669430/" target="_blank">View My LinkedIn Profile &rarr;</a>
        </p>
    </div>

    <!-- Projects Section -->
    <div id="projects" class="section">
        <h2>Projects</h2>
        <div>
            <!-- Project One linked to LinkedIn -->
            <div class="project-card">
                <h3>Project One</h3>
                <p>A brief description of the project goes here.</p>
                <a href="https://www.linkedin.com/in/mohamed-ashraf-68b669430/" target="_blank">View on LinkedIn &rarr;</a>
            </div>

            <!-- Project Two -->
            <div class="project-card">
                <h3>Project Two</h3>
                <p>A brief description of the project goes here.</p>
            </div>

            <!-- Project Three -->
            <div class="project-card">
                <h3>Project Three</h3>
                <p>A brief description of the project goes here.</p>
            </div>
            <div>
            
    </div>

    <!-- Contact Me Section -->
    <div id="contact" class="section">
        <h2>Contact Me</h2>
        <div class="contact-box">
            <form>
                <input type="text" placeholder="Your Name">
                <input type="email" placeholder="Your Email">
                <textarea placeholder="Your Message"></textarea>
                <button type="submit">Send Message</button>
            </form>
        </div>
    </div>

    <!-- Footer Section -->
    <div class="footer">
        <p>&copy; 2026 Mohamed Ashraf. All Rights Reserved.</p>
    </div>

</body>
</html>
