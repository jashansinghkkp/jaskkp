- 👋 Hi, I’m @Jashandeep
- 👀 I’m interested in Hacking/Developing 
- 🌱 I’m currently learning cyber.
- 📫 How to reach me ig ="jashan_singh_kkp
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Profile</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --bg-primary: #0d1117;
            --bg-secondary: #161b22;
            --accent-green: #0be881;
            --text-primary: #c9d1d9;
            --text-secondary: #8b949e;
            --card-bg: #21262d;
            --border-color: #30363d;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg-primary);
            color: var(--text-primary);
            line-height: 1.6;
            padding: 0;
            overflow-x: hidden;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 2rem;
        }
        
        header {
            text-align: center;
            padding: 3rem 0;
            position: relative;
            overflow: hidden;
        }
        
        header::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, var(--accent-green) 0%, transparent 70%);
            opacity: 0.05;
            z-index: 0;
        }
        
        .profile-ascii {
            font-family: monospace;
            font-size: 1.5rem;
            color: var(--accent-green);
            margin-bottom: 1.5rem;
            line-height: 1.2;
            white-space: pre;
            text-align: center;
            animation: pulse 2s infinite alternate;
        }
        
        @keyframes pulse {
            from { opacity: 0.7; }
            to { opacity: 1; }
        }
        
        h1 {
            font-size: 3rem;
            margin-bottom: 0.5rem;
            background: linear-gradient(90deg, var(--text-primary), var(--accent-green));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-shadow: 0 0 10px rgba(11, 232, 129, 0.2);
        }
        
        .tagline {
            font-size: 1.2rem;
            color: var(--accent-green);
            margin-bottom: 2rem;
            font-weight: 300;
        }
        
        .social-links {
            display: flex;
            justify-content: center;
            gap: 1.5rem;
            margin: 2rem 0;
        }
        
        .social-icon {
            width: 45px;
            height: 45px;
            border-radius: 50%;
            background: var(--bg-secondary);
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--accent-green);
            font-size: 1.5rem;
            transition: all 0.3s ease;
            border: 1px solid var(--border-color);
        }
        
        .social-icon:hover {
            background: var(--accent-green);
            color: var(--bg-primary);
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(11, 232, 129, 0.4);
        }
        
        .section {
            background: var(--bg-secondary);
            border-radius: 12px;
            padding: 2rem;
            margin: 2rem 0;
            border: 1px solid var(--border-color);
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease;
        }
        
        .section:hover {
            transform: translateY(-5px);
        }
        
        .section-title {
            font-size: 1.8rem;
            margin-bottom: 1.5rem;
            padding-bottom: 0.5rem;
            border-bottom: 2px solid var(--accent-green);
            color: var(--accent-green);
        }
        
        .skills {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(120px, 1fr));
            gap: 1rem;
        }
        
        .skill {
            background: var(--card-bg);
            padding: 0.8rem;
            border-radius: 8px;
            text-align: center;
            border: 1px solid var(--border-color);
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .skill:hover {
            background: var(--accent-green);
            color: var(--bg-primary);
            transform: scale(1.05);
        }
        
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 1.5rem;
        }
        
        .project-card {
            background: var(--card-bg);
            border-radius: 10px;
            overflow: hidden;
            border: 1px solid var(--border-color);
            transition: transform 0.3s ease;
            padding: 1.5rem;
        }
        
        .project-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 20px rgba(11, 232, 129, 0.2);
        }
        
        .project-title {
            font-size: 1.3rem;
            margin-bottom: 0.5rem;
            color: var(--accent-green);
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        
        .project-desc {
            color: var(--text-secondary);
            margin-bottom: 1rem;
            font-size: 0.9rem;
        }
        
        .project-links {
            display: flex;
            gap: 1rem;
        }
        
        .project-btn {
            padding: 0.5rem 1rem;
            background: transparent;
            border: 1px solid var(--accent-green);
            color: var(--accent-green);
            border-radius: 5px;
            text-decoration: none;
            font-size: 0.9rem;
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        
        .project-btn:hover {
            background: var(--accent-green);
            color: var(--bg-primary);
        }
        
        .stats {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 1rem;
            text-align: center;
        }
        
        .stat {
            background: var(--card-bg);
            padding: 1.5rem 1rem;
            border-radius: 8px;
            border: 1px solid var(--border-color);
        }
        
        .stat-value {
            font-size: 2rem;
            font-weight: bold;
            color: var(--accent-green);
            margin-bottom: 0.5rem;
            font-family: monospace;
        }
        
        .stat-label {
            color: var(--text-secondary);
            font-size: 0.9rem;
        }
        
        footer {
            text-align: center;
            padding: 2rem 0;
            color: var(--text-secondary);
            font-size: 0.9rem;
            margin-top: 3rem;
            border-top: 1px solid var(--border-color);
        }
        
        .neon-glow {
            animation: neon 1.5s ease-in-out infinite alternate;
        }
        
        @keyframes neon {
            from {
                text-shadow: 0 0 5px #fff, 0 0 10px #fff, 0 0 15px var(--accent-green), 
                             0 0 20px var(--accent-green), 0 0 25px var(--accent-green);
            }
            to {
                text-shadow: 0 0 10px #fff, 0 0 20px #fff, 0 0 30px var(--accent-green), 
                             0 0 40px var(--accent-green), 0 0 50px var(--accent-green);
            }
        }
        
        .terminal {
            background: var(--card-bg);
            border-radius: 8px;
            padding: 1rem;
            font-family: monospace;
            border: 1px solid var(--border-color);
            margin: 1rem 0;
        }
        
        .terminal-header {
            display: flex;
            gap: 0.5rem;
            margin-bottom: 0.5rem;
            color: var(--accent-green);
        }
        
        .terminal-content {
            color: var(--text-primary);
        }
        
        .typing-effect {
            overflow: hidden;
            border-right: 0.15em solid var(--accent-green);
            white-space: nowrap;
            margin: 0 auto;
            animation: typing 3.5s steps(40, end), blink-caret 0.75s step-end infinite;
        }
        
        @keyframes typing {
            from { width: 0 }
            to { width: 100% }
        }
        
        @keyframes blink-caret {
            from, to { border-color: transparent }
            50% { border-color: var(--accent-green) }
        }
        
        .badge {
            display: inline-block;
            background: var(--accent-green);
            color: var(--bg-primary);
            padding: 0.2rem 0.5rem;
            border-radius: 4px;
            font-size: 0.8rem;
            margin-right: 0.5rem;
            margin-bottom: 0.5rem;
        }
        
        .progress-bar {
            height: 8px;
            background: var(--bg-secondary);
            border-radius: 4px;
            margin-top: 0.5rem;
            overflow: hidden;
        }
        
        .progress-fill {
            height: 100%;
            background: var(--accent-green);
            border-radius: 4px;
            transition: width 1s ease-in-out;
        }
        
        @media (max-width: 768px) {
            .container {
                padding: 1rem;
            }
            
            h1 {
                font-size: 2.2rem;
            }
            
            .projects {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="profile-ascii">
 ███████╗██╗████████╗██╗   ██╗███████╗
██╔════╝██║╚══██╔══╝╚██╗ ██╔╝██╔════╝
█████╗  ██║   ██║    ╚████╔╝ █████╗  
██╔══╝  ██║   ██║     ╚██╔╝  ██╔══╝  
███████╗██║   ██║      ██║   ███████╗
╚══════╝╚═╝   ╚═╝      ╚═╝   ╚══════╝
            </div>
            <h1 class="neon-glow">Your Name</h1>
            <p class="tagline">Full Stack Developer | Open Source Contributor | Tech Enthusiast</p>
            
            <div class="social-links">
                <a href="#" class="social-icon"><i class="fab fa-github"></i></a>
                <a href="#" class="social-icon"><i class="fab fa-linkedin"></i></a>
                <a href="#" class="social-icon"><i class="fab fa-twitter"></i></a>
                <a href="#" class="social-icon"><i class="fab fa-dev"></i></a>
            </div>
        </header>
        
        <section class="section">
            <h2 class="section-title"><i class="fas fa-terminal"></i> About Me</h2>
            <div class="terminal">
                <div class="terminal-header">
                    <span>user@github:~$</span>
                    <span>cat about_me.txt</span>
                </div>
                <div class="terminal-content">
                    <p class="typing-effect">Passionate developer with expertise in building scalable web applications. I love contributing to open-source projects and solving complex problems. Currently working on improving my DevOps skills and exploring machine learning.</p>
                </div>
            </div>
        </section>
        
        <section class="section">
            <h2 class="section-title"><i class="fas fa-code"></i> Skills</h2>
            <div class="skills">
                <div class="skill"><i class="fab fa-js"></i> JavaScript</div>
                <div class="skill"><i class="fab fa-react"></i> React</div>
                <div class="skill"><i class="fab fa-node-js"></i> Node.js</div>
                <div class="skill"><i class="fab fa-python"></i> Python</div>
                <div class="skill"><i class="fab fa-docker"></i> Docker</div>
                <div class="skill"><i class="fab fa-aws"></i> AWS</div>
                <div class="skill"><i class="fas fa-database"></i> MongoDB</div>
                <div class="skill"><i class="fas fa-sitemap"></i> GraphQL</div>
                <div class="skill"><i class="fas fa-code"></i> TypeScript</div>
            </div>
        </section>
        
        <section class="section">
            <h2 class="section-title"><i class="fas fa-chart-line"></i> GitHub Stats</h2>
            <div class="stats">
                <div class="stat">
                    <div class="stat-value">120+</div>
                    <div class="stat-label">Contributions</div>
                </div>
                <div class="stat">
                    <div class="stat-value">15</div>
                    <div class="stat-label">Public Repos</div>
                </div>
                <div class="stat">
                    <div class="stat-value">8</div>
                    <div class="stat-label">Projects</div>
                </div>
                <div class="stat">
                    <div class="stat-value">4</div>
                    <div class="stat-label">Years Exp</div>
                </div>
            </div>
        </section>
        
        <section class="section">
            <h2 class="section-title"><i class="fas fa-project-diagram"></i> Featured Projects</h2>
            <div class="projects">
                <div class="project-card">
                    <h3 class="project-title"><i class="fas fa-code-branch"></i> Project One</h3>
                    <p class="project-desc">A full-stack web application built with React and Node.js. Features real-time updates and authentication.</p>
                    <div class="project-links">
                        <a href="#" class="project-btn"><i class="fas fa-external-link-alt"></i> Live Demo</a>
                        <a href="#" class="project-btn"><i class="fab fa-github"></i> Source Code</a>
                    </div>
                </div>
                
                <div class="project-card">
                    <h3 class="project-title"><i class="fas fa-robot"></i> Project Two</h3>
                    <p class="project-desc">An AI-powered tool that helps developers optimize their code for better performance.</p>
                    <div class="project-links">
                        <a href="#" class="project-btn"><i class="fas fa-external-link-alt"></i> Live Demo</a>
                        <a href="#" class="project-btn"><i class="fab fa-github"></i> Source Code</a>
                    </div>
                </div>
                
                <div class="project-card">
                    <h3 class="project-title"><i class="fas fa-mobile-alt"></i> Project Three</h3>
                    <p class="project-desc">A mobile app built with React Native that helps users track their daily activities.</p>
                    <div class="project-links">
                        <a href="#" class="project-btn"><i class="fas fa-external-link-alt"></i> Live Demo</a>
                        <a href="#" class="project-btn"><i class="fab fa-github"></i> Source Code</a>
                    </div>
                </div>
            </div>
        </section>
        
        <section class="section">
            <h2 class="section-title"><i class="fas fa-trophy"></i> Achievements</h2>
            <div>
                <div style="margin-bottom: 1rem;">
                    <span class="badge">Open Source</span>
                    <span class="badge">Hackathon Winner</span>
                    <span class="badge">Tech Speaker</span>
                </div>
                
                <div style="margin-bottom: 1rem;">
                    <span>JavaScript Expert</span>
                    <div class="progress-bar">
                        <div class="progress-fill" style="width: 95%;"></div>
                    </div>
                </div>
                
                <div style="margin-bottom: 1rem;">
                    <span>Backend Development</span>
                    <div class="progress-bar">
                        <div class="progress-fill" style="width: 85%;"></div>
                    </div>
                </div>
                
                <div style="margin-bottom: 1rem;">
                    <span>DevOps</span>
                    <div class="progress-bar">
                        <div class="progress-fill" style="width: 75%;"></div>
                    </div>
                </div>
            </div>
        </section>
        
        <footer>
            <p>Designed with ❤️ using HTML and CSS | © 2023 Your Name</p>
        </footer>
    </div>
    
    <script>
        // Add typing effect animation
        document.addEventListener('DOMContentLoaded', function() {
            const typingElements = document.querySelectorAll('.typing-effect');
            
            typingElements.forEach(element => {
                const text = element.textContent;
                element.textContent = '';
                
                setTimeout(() => {
                    element.textContent = text;
                }, 500);
            });
        });
    </script>
</body>
</html>
