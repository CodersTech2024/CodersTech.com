<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CodersTech - Shining Star International School</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #e9ecef;
            color: #343a40;
        }

        header {
            background-color: #007bff;
            color: white;
            text-align: center;
            padding: 20px 0;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        h1 {
            margin: 0;
            font-size: 2.5em;
        }

        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            padding: 0;
            margin: 20px 0;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav a {
            text-decoration: none;
            color: white;
            padding: 10px 15px;
            border-radius: 5px;
            transition: background-color 0.3s, color 0.3s;
        }

        nav a:hover {
            background-color: #0056b3;
            color: white;
        }

        main {
            padding: 20px;
            max-width: 900px;
            margin: 20px auto;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #007bff;
            border-bottom: 2px solid #007bff;
            padding-bottom: 5px;
        }

        ul {
            list-style-type: disc;
            margin-left: 20px;
        }

        footer {
            background-color: #007bff;
            color: white;
            text-align: center;
            padding: 15px;
            position: relative;
            bottom: 0;
            width: 100%;
            margin-top: 20px;
            box-shadow: 0 -2px 8px rgba(0, 0, 0, 0.1);
        }

        form {
            display: flex;
            flex-direction: column;
            margin-top: 20px;
        }

        input, textarea {
            margin-bottom: 10px;
            padding: 10px;
            border: 1px solid #ced4da;
            border-radius: 5px;
            font-size: 16px;
            transition: border-color 0.3s;
        }

        input:focus, textarea:focus {
            border-color: #007bff;
            outline: none;
        }

        button {
            padding: 10px;
            background-color: #007bff;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
            transition: background-color 0.3s;
        }

        button:hover {
            background-color: #0056b3;
        }

        @media (max-width: 600px) {
            nav ul {
                flex-direction: column;
            }

            nav ul li {
                margin: 10px 0;
            }

            h1 {
                font-size: 2em;
            }

            main {
                padding: 10px;
            }
        }

        /* Additional styles for section spacing */
        section {
            margin-bottom: 30px;
        }

        /* Card style for achievements */
        .achievement-card {
            background-color: #f8f9fa;
            border: 1px solid #dee2e6;
            border-radius: 10px;
            padding: 15px;
            margin-bottom: 15px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to CodersTech</h1>
        <p>Shining Star International School</p>
        <nav>
            <ul>
                <li><a href="#about">About Us</a></li>
                <li><a href="#achievements">Our Achievements</a></li>
                <li><a href="#recognition">Recognition</a></li>
                <li><a href="#vision">Our Vision</a></li>
                <li><a href="#technology">Modern Technology</a></li>
                <li><a href="#contact">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="about">
            <h2>About Us</h2>
            <p>CodersTech is an innovative student team from Shining Star International School, dedicated to harnessing technology for sustainable development. Our mission is to apply modern technologies to address global challenges in education, health, and environmental awareness. We believe that technology can be a powerful tool for change, and we are committed to making a positive impact in our community and beyond.</p>
        </section>

        <section id="achievements">
            <h2>Our Achievements</h2>
            <div class="achievement-card">
                <h3>Tech-E App</h3>
                <p>An AI-driven educational app that aids students in learning various subjects effectively. It includes features like a question-answerer and step counter.</p>
            </div>
            <div class="achievement-card">
                <h3>Xplorium App</h3>
                <p>Designed to promote eco-friendly activities, this app educates users about environmental issues and encourages sustainable practices.</p>
            </div>
            <div class="achievement-card">
                <h3>Mbot Farming Project</h3>
                <p>A robotic solution to automate farming tasks, making agriculture more efficient and less labor-intensive. This project highlights the importance of technology in enhancing food production.</p>
            </div>
            <div class="achievement-card">
                <h3>Weather Finder App</h3>
                <p>Provides accurate weather forecasts with real-time data, helping communities prepare for weather changes and disasters.</p>
            </div>
            <p>Our projects align with several Sustainable Development Goals (SDGs) set by the United Nations, demonstrating our commitment to global issues.</p>
        </section>

        <section id="recognition">
            <h2>Recognition</h2>
            <p>CodersTech has been recognized both locally and nationally for our innovative projects:</p>
            <ul>
                <li><strong>Honorable Mention</strong> at the National Student Tech Competition for our Tech-E App.</li>
                <li><strong>Innovation Award</strong> for the Xplorium App at the State Technology Fair.</li>
                <li>Feature in local media highlighting our Mbot Farming Project and its impact on local farmers.</li>
                <li>Collaboration with local NGOs to promote our projects and implement them in community initiatives.</li>
            </ul>
            <p>These recognitions inspire us to continue our journey towards technological innovation and community impact.</p>
        </section>

        <section id="vision">
            <h2>Our Vision</h2>
            <p>At CodersTech, we envision a future where technology and innovation are accessible to everyone. Our goal is to empower students and communities by providing tools and resources that enable them to solve real-world problems. We are committed to fostering a culture of creativity and collaboration, ensuring that technology serves humanity and promotes sustainable development.</p>
        </section>

        <section id="technology">
            <h2>Modern Technology</h2>
            <p>We believe in leveraging modern technology to drive progress. Our team is dedicated to exploring new technological advancements and integrating them into our projects. Key areas of focus include:</p>
            <ul>
                <li><strong>Artificial Intelligence</strong>: We incorporate AI into our projects to enhance learning and provide personalized experiences.</li>
                <li><strong>Robotics</strong>: Our Mbot project showcases how robotics can streamline agricultural practices, making them more efficient and sustainable.</li>
                <li><strong>Mobile Applications</strong>: Through our apps, we aim to reach a wider audience and provide solutions that can be accessed easily.</li>
                <li><strong>Environmental Technologies</strong>: Our projects promote awareness and action towards environmental conservation and sustainable practices.</li>
            </ul>
            <p>As we continue to innovate, we remain committed to using technology responsibly and ethically.</p>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <p>If you have questions or would like to collaborate with us, please reach out!</p>
            <form action="#" method="post">
                <input type="text" placeholder="Your Name" required>
                <input type="email" placeholder="Your Email" required>
                <textarea placeholder="Your Message" required></textarea>
                <button type="
