!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Htoi Lu Ra | Professional CV</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;600;800&family=Plus+Jakarta+Sans:wght@300;400;600;700&display=swap" rel="stylesheet">
</head>
<body>
    <div class="edit-mode-toggle" id="editToggle">
        <span>Edit Mode</span>
        <label class="switch">
            <input type="checkbox" id="editCheckbox">
            <span class="slider round"></span>
        </label>
    </div>

    <nav>
        <div class="logo">HLR<span>.</span></div>
        <ul class="nav-links">
            <li><a href="#about">About</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#experience">Experience</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <header id="about">
        <div class="container hero-content">
            <div class="hero-text">
                <h1 id="name" contenteditable="false">Htoi Lu Ra</h1>
                <p class="subtitle" id="dob" contenteditable="false">Born: 20.06.2005</p>
                <p class="bio" id="bio" contenteditable="false">A dedicated professional with a strong foundation in liberal arts and English, committed to personal growth and excellence in communication and problem-solving.</p>
                <div class="hero-cta">
                    <a href="#contact" class="btn primary">Get In Touch</a>
                    <a href="#education" class="btn secondary">View Journey</a>
                </div>
            </div>
            <div class="hero-visual">
                <div class="circle-gradient"></div>
            </div>
        </div>
    </header>

    <section id="education" class="container">
        <h2 class="section-title">Education Journey</h2>
        <div class="timeline">
            <div class="timeline-item">
                <div class="timeline-dot"></div>
                <div class="timeline-content card">
                    <span class="year">2025 - 2026</span>
                    <h3>Diploma in Liberal Arts</h3>
                    <p>Advanced studies focusing on critical thinking and broad-based knowledge.</p>
                </div>
            </div>
            <div class="timeline-item">
                <div class="timeline-dot"></div>
                <div class="timeline-content card">
                    <span class="year">2024 - 2025</span>
                    <h3>Diploma in English</h3>
                    <p>Enhanced linguistic proficiency and communication skills.</p>
                </div>
            </div>
            <div class="timeline-item">
                <div class="timeline-dot"></div>
                <div class="timeline-content card">
                    <span class="year">2023 - 2024</span>
                    <h3>Grade-10</h3>
                    <p>Completed foundational secondary education.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="skills" class="container">
        <div class="skills-grid">
            <div class="skills-column">
                <h2 class="section-title">Professional Skills</h2>
                <div class="skill-tags">
                    <span class="skill-tag">Communication</span>
                    <span class="skill-tag">Problem Solving</span>
                    <span class="skill-tag">Critical Thinking</span>
                </div>
            </div>
            <div class="skills-column">
                <h2 class="section-title">Personality</h2>
                <div class="skill-tags">
                    <span class="skill-tag">Patience</span>
                    <span class="skill-tag">Resilience</span>
                    <span class="skill-tag">Optimism</span>
                </div>
            </div>
            <div class="skills-column">
                <h2 class="section-title">Languages</h2>
                <div class="skill-tags">
                    <span class="skill-tag">Kachin (Native)</span>
                    <span class="skill-tag">Burmese (Fluent)</span>
                    <span class="skill-tag">English (Proficient)</span>
                </div>
            </div>
        </div>
    </section>

    <section id="experience" class="container">
        <h2 class="section-title">Experience</h2>
        <div class="card experience-card">
            <h3>Teaching Experience</h3>
            <span class="duration">1 Month</span>
            <p>Gained valuable practical experience in educational settings, developing instructional and classroom management skills.</p>
        </div>
    </section>

    <footer id="contact">
        <div class="container">
            <h2 class="section-title">Contact Information</h2>
            <div class="contact-grid">
                <div class="contact-item">
                    <span class="label">Phone</span>
                    <p id="phone" contenteditable="false">09 684197124</p>
                </div>
                <div class="contact-item">
                    <span class="label">Email</span>
                    <p id="email" contenteditable="false">htoilurawaje151@gmail.com</p>
                </div>
                <div class="contact-item">
                    <span class="label">Location</span>
                    <p id="location" contenteditable="false">Man Wein Gyi</p>
                </div>
            </div>
            <div class="footer-note">
                <p>&copy; 2026 Htoi Lu Ra. Built for professional excellence.</p>
            </div>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
