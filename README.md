<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vitneni Vishnu - Final Year Student Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background: #f4f6fb url('bg-shape.png') repeat top left, url('dots.png') repeat bottom right;
        }
        header { background: #222 url('header-bg.png') no-repeat center/cover; color: #fff; padding: 30px 0; text-align: center; }
        .profile-img {
            width: 140px;
            height: 140px;
            object-fit: cover;
            border-radius: 50%;
            border: 4px solid #fd6e6a;
            margin-bottom: 16px;
            box-shadow: 0 4px 16px rgba(0,0,0,0.12);
        }
        nav { background: #fd6e6a; padding: 10px 0; }
        nav ul { list-style: none; margin: 0; padding: 0; display: flex; justify-content: center; }
        nav ul li { margin: 0 15px; }
        nav ul li a { color: #fff; text-decoration: none; font-weight: bold; }
        main { max-width: 900px; margin: 30px auto; background: #fff; padding: 30px; border-radius: 12px; box-shadow: 0 2px 12px rgba(0,0,0,0.08);}
        section { margin-bottom: 40px; }
        h1, h2, h3 { color: #fd6e6a; }
        .projects { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
        .project-card { background: #f6d365; padding: 18px; border-radius: 10px; box-shadow: 0 2px 8px rgba(0,0,0,0.07);}
        .skills-list { margin-bottom: 24px; }
        .skill-bar { margin-bottom: 12px; }
        .skill-label { font-weight: bold; margin-bottom: 4px; display: block; }
        .bar-bg { background: #eee; border-radius: 6px; height: 18px; width: 100%; }
        .bar-fill { height: 100%; border-radius: 6px; background: #fd6e6a; display: block; }
        .skills ul { display: flex; flex-wrap: wrap; gap: 12px; list-style: none; padding: 0; }
        .skills li { background: #fd6e6a; color: #fff; padding: 8px 16px; border-radius: 6px; }
        .blog-list { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; }
        .blog-card { background: #f4f6fb; border-radius: 10px; box-shadow: 0 2px 8px rgba(0,0,0,0.07); padding: 18px; }
        .blog-card h3 { margin-top: 0; color: #fd6e6a; }
        .blog-card p { color: #444; }
        form { display: flex; flex-direction: column; gap: 12px; max-width: 400px; }
        label { font-weight: bold; }
        input, textarea { padding: 8px; border-radius: 6px; border: 1px solid #ccc; }
        button { background: #fd6e6a; color: #fff; border: none; padding: 10px; border-radius: 6px; font-weight: bold; cursor: pointer; }
        footer { background: #222; color: #fff; text-align: center; padding: 18px 0; margin-top: 40px; }
        @media (max-width: 800px) {
            .blog-list { grid-template-columns: 1fr; }
        }
        @media (max-width: 600px) {
            main { padding: 10px; }
            .projects { grid-template-columns: 1fr; }
        }
    </style>
</head>
<body>
    <header>
        <img src="your-image.jpg" alt="Vitneni Vishnu" class="profile-img">
        <h1>Vitneni Vishnu</h1>
        <p>Final Year Student | Frontend Developer</p>
    </header>
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#blog">Blog</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>Hello! I'm Vitneni Vishnu, a final year engineering student passionate about frontend development. I enjoy building responsive and interactive web applications, and I'm eager to learn new technologies and frameworks.</p>
        </section>
        <section id="projects">
            <h2>Final Year Projects</h2>
            <div class="projects">
                <div class="project-card">
                    <h3>Online Exam Portal</h3>
                    <p>A secure web application for conducting online exams with real-time results and analytics.</p>
                    <a href="#" target="_blank">Live Demo</a> | <a href="#" target="_blank">GitHub</a>
                </div>
                <div class="project-card">
                    <h3>Student Attendance System</h3>
                    <p>Automated attendance tracking using QR codes and a web dashboard for teachers.</p>
                    <a href="#" target="_blank">Live Demo</a> | <a href="#" target="_blank">GitHub</a>
                </div>
                <div class="project-card">
                    <h3>Portfolio Website</h3>
                    <p>My personal portfolio built with HTML, CSS, and JavaScript to showcase my skills and projects.</p>
                    <a href="#" target="_blank">Live Demo</a> | <a href="#" target="_blank">GitHub</a>
                </div>
            </div>
        </section>
        <section id="skills" class="skills">
            <h2>Skills</h2>
            <div class="skills-list">
                <div class="skill-bar">
                    <span class="skill-label">HTML5</span>
                    <div class="bar-bg">
                        <span class="bar-fill" style="width: 95%;"></span>
                    </div>
                </div>
                <div class="skill-bar">
                    <span class="skill-label">CSS3</span>
                    <div class="bar-bg">
                        <span class="bar-fill" style="width: 90%;"></span>
                    </div>
                </div>
                <div class="skill-bar">
                    <span class="skill-label">JavaScript</span>
                    <div class="bar-bg">
                        <span class="bar-fill" style="width: 85%;"></span>
                    </div>
                </div>
                <div class="skill-bar">
                    <span class="skill-label">React</span>
                    <div class="bar-bg">
                        <span class="bar-fill" style="width: 80%;"></span>
                    </div>
                </div>
                <div class="skill-bar">
                    <span class="skill-label">Bootstrap</span>
                    <div class="bar-bg">
                        <span class="bar-fill" style="width: 75%;"></span>
                    </div>
                </div>
                <div class="skill-bar">
                    <span class="skill-label">Git & GitHub</span>
                    <div class="bar-bg">
                        <span class="bar-fill" style="width: 70%;"></span>
                    </div>
                </div>
                <div class="skill-bar">
                    <span class="skill-label">Responsive Design</span>
                    <div class="bar-bg">
                        <span class="bar-fill" style="width: 90%;"></span>
                    </div>
                </div>
                <div class="skill-bar">
                    <span class="skill-label">UI/UX Design</span>
                    <div class="bar-bg">
                        <span class="bar-fill" style="width: 80%;"></span>
                    </div>
                </div>
            </div>
            <ul>
                <li>HTML5</li>
                <li>CSS3</li>
                <li>JavaScript</li>
                <li>React</li>
                <li>Bootstrap</li>
                <li>Git & GitHub</li>
                <li>Responsive Design</li>
                <li>UI/UX Design</li>
            </ul>
        </section>
        <section id="blog">
            <h2>Blog</h2>
            <div class="blog-list">
                <div class="blog-card">
                    <h3>My Final Year Project Journey</h3>
                    <p>Sharing my experience, challenges, and learnings while building my final year projects.</p>
                    <a href="#">Read More</a>
                </div>
                <div class="blog-card">
                    <h3>Tips for Student Developers</h3>
                    <p>Advice and resources for students starting out in web development and project work.</p>
                    <a href="#">Read More</a>
                </div>
                <div class="blog-card">
                    <h3>React Basics for Beginners</h3>
                    <p>Introduction to React and how it helped me build interactive UIs for my projects.</p>
                    <a href="#">Read More</a>
                </div>
                <div class="blog-card">
                    <h3>How to Ace Campus Placements</h3>
                    <p>My strategies for preparing for interviews and landing my dream job as a developer.</p>
                    <a href="#">Read More</a>
                </div>
            </div>
        </section>
        <section id="contact">
            <h2>Contact Me</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="4" required></textarea>
                
                <button type="submit">Send Message</button>
            </form>
        </section>
    </main>
    <footer>
        &copy; 2025 Vitneni Vishnu. All rights reserved.
    </footer>
</body>
</html>
