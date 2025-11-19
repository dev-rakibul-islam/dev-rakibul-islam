<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rakibul Islam - MERN Developer</title>
    <style>
        :root {
            --primary: #6366f1;
            --secondary: #8b5cf6;
            --accent: #06b6d4;
            --dark: #0f172a;
            --light: #f8fafc;
            --gray: #64748b;
            --border: #e2e8f0;
        }
        body {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
            line-height: 1.6;
            color: var(--dark);
            background: linear-gradient(135deg, var(--light) 0%, #e0f2fe 100%);
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }
        .hero {
            text-align: center;
            padding: 4rem 0;
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            color: white;
            border-radius: 1rem;
            margin-bottom: 3rem;
            box-shadow: 0 20px 40px rgba(99, 102, 241, 0.3);
        }
        .hero h1 {
            font-size: 3.5rem;
            margin: 0;
            font-weight: 700;
            background: linear-gradient(45deg, white, #e0f2fe);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        .hero p {
            font-size: 1.25rem;
            margin: 1rem 0;
            opacity: 0.9;
        }
        .stats {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin: 3rem 0;
        }
        .stat-card {
            background: white;
            padding: 2rem;
            border-radius: 1rem;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            text-align: center;
            transition: transform 0.3s ease;
        }
        .stat-card:hover {
            transform: translateY(-5px);
        }
        .stat-card h3 {
            color: var(--primary);
            margin-bottom: 0.5rem;
        }
        .projects {
            margin: 4rem 0;
        }
        .project-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 2rem;
        }
        .project-card {
            background: white;
            border-radius: 1rem;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            transition: all 0.3s ease;
        }
        .project-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 40px rgba(0,0,0,0.15);
        }
        .project-header {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white;
            padding: 1.5rem;
        }
        .project-body {
            padding: 1.5rem;
        }
        .tech-stack {
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem;
            margin: 1rem 0;
        }
        .tech-badge {
            background: rgba(99, 102, 241, 0.1);
            color: var(--primary);
            padding: 0.25rem 0.75rem;
            border-radius: 9999px;
            font-size: 0.875rem;
            font-weight: 500;
        }
        .contact {
            background: var(--dark);
            color: white;
            padding: 3rem 0;
            text-align: center;
            border-radius: 1rem;
            margin-top: 3rem;
        }
        .social-links {
            display: flex;
            justify-content: center;
            gap: 1rem;
            flex-wrap: wrap;
            margin-top: 2rem;
        }
        .social-link {
            display: inline-block;
            padding: 0.75rem 1.5rem;
            background: var(--primary);
            color: white;
            text-decoration: none;
            border-radius: 0.5rem;
            transition: background 0.3s ease;
        }
        .social-link:hover {
            background: var(--secondary);
        }
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2.5rem;
            }
            .container {
                padding: 1rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <section class="hero">
            <h1>Rakibul Islam</h1>
            <p>Frontend-first MERN Developer • Design Enthusiast • Performance Obsessed</p>
            <p>🚀 Building pixel-perfect, delightful web experiences</p>
        </section>

        <section class="stats">
            <div class="stat-card">
                <h3>💼 Role</h3>
                <p>MERN + Frontend Developer</p>
            </div>
            <div class="stat-card">
                <h3>🎯 Focus</h3>
                <p>React • UX • APIs</p>
            </div>
            <div class="stat-card">
                <h3>📍 Location</h3>
                <p>Chittagong, Bangladesh</p>
            </div>
            <div class="stat-card">
                <h3>🤝 Status</h3>
                <p>Open for Freelance & Remote</p>
            </div>
        </section>

        <section class="projects">
            <h2 style="text-align: center; margin-bottom: 2rem; color: var(--dark);">🚀 Featured Projects</h2>
            <div class="project-grid">
                <div class="project-card">
                    <div class="project-header">
                        <h3>Aunkur CTG North</h3>
                        <p>Scholarship Management Hub</p>
                    </div>
                    <div class="project-body">
                        <p>Comprehensive platform for NGO scholarship administration with multi-role dashboards</p>
                        <div class="tech-stack">
                            <span class="tech-badge">React</span>
                            <span class="tech-badge">Tailwind</span>
                            <span class="tech-badge">Node</span>
                            <span class="tech-badge">MongoDB</span>
                        </div>
                        <a href="https://aunkurctgnorth.org/" class="social-link">🔗 Live Site</a>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-header">
                        <h3>Roystyle</h3>
                        <p>E-Commerce Experience</p>
                    </div>
                    <div class="project-body">
                        <p>Curated boutique drops with motion-rich product showcase</p>
                        <div class="tech-stack">
                            <span class="tech-badge">React</span>
                            <span class="tech-badge">Tailwind</span>
                            <span class="tech-badge">Vite</span>
                        </div>
                        <a href="https://roystyle.com/" class="social-link">🔗 Live Site</a>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-header">
                        <h3>Plateia Airosa LDA</h3>
                        <p>Multi-Business Hub</p>
                    </div>
                    <div class="project-body">
                        <p>European collective platform managing service catalogs</p>
                        <div class="tech-stack">
                            <span class="tech-badge">React</span>
                            <span class="tech-badge">Node</span>
                            <span class="tech-badge">MongoDB</span>
                        </div>
                        <a href="https://plateiaairosalda.com/" class="social-link">🔗 Live Site</a>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-header">
                        <h3>AgroBridge</h3>
                        <p>Community Platform</p>
                    </div>
                    <div class="project-body">
                        <p>Connecting farmers and agro-enthusiasts</p>
                        <div class="tech-stack">
                            <span class="tech-badge">React</span>
                            <span class="tech-badge">Firebase</span>
                            <span class="tech-badge">Node</span>
                        </div>
                        <a href="https://agrobridge-web.netlify.app" class="social-link">🔗 Live Site</a>
                    </div>
                </div>
            </div>
        </section>

        <section class="contact">
            <h2>🤝 Let's Connect</h2>
            <p>Reach out for collaboration, feedback, or a chat about web development</p>
            <div class="social-links">
                <a href="mailto:rakibulislam.eb@gmail.com" class="social-link">📧 Email</a>
                <a href="https://www.linkedin.com/in/rakibul-islam-6258541b4/" class="social-link">💼 LinkedIn</a>
                <a href="https://x.com/dev_rakib_eb" class="social-link">🐦 Twitter</a>
                <a href="https://www.instagram.com/dev.rakibulislam" class="social-link">📷 Instagram</a>
                <a href="https://github.com/dev-rakibul-islam" class="social-link">💻 GitHub</a>
            </div>
        </section>
    </div>
</body>
</html>
