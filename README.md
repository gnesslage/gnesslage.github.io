# gnesslage.github.io

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Associate Research Professor | University Maryland Center for Environmental Science</title>
    <style>
        :root {
            --primary-color: #2c3e50; /* Professional Navy */
            --accent-color: #e74c3c;  /* University Red */
            --bg-color: #f4f7f6;
            --text-color: #333;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            margin: 0;
            background-color: var(--bg-color);
        }

        header {
            background: var(--primary-color);
            color: white;
            padding: 2rem 10%;
            text-align: center;
        }

        nav {
            background: #fff;
            padding: 1rem 10%;
            display: flex;
            justify-content: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            position: sticky;
            top: 0;
        }

        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: var(--primary-color);
            font-weight: bold;
        }

        .container {
            max-width: 900px;
            margin: 2rem auto;
            padding: 0 20px;
            background: white;
            padding: 40px;
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
        }

        h2 {
            border-bottom: 2px solid var(--primary-color);
            padding-bottom: 10px;
            color: var(--primary-color);
        }

        .profile-section {
            display: flex;
            align-items: center;
            gap: 30px;
            margin-bottom: 40px;
        }

        .profile-img {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            background: #ddd; /* Placeholder */
            object-fit: cover;
        }

        .publication-list {
            list-style: none;
            padding: 0;
        }

        .publication-list li {
            margin-bottom: 15px;
            padding-left: 15px;
            border-left: 3px solid var(--accent-color);
        }

        footer {
            text-align: center;
            padding: 2rem;
            font-size: 0.9rem;
            color: #777;
        }

        @media (max-width: 600px) {
            .profile-section { flex-direction: column; text-align: center; }
        }
    </style>
</head>
<body>

<header>
    <h1>Dr. Geneviève Nesslage</h1>
    <p>Associate Research Professor | University Maryland Center for Environmental Science Chesapeake Biological Laboratory</p>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#research">Research</a>
    <a href="#publications">Publications</a>
    <a href="#teaching">Teaching</a>
    <a href="#contact">Contact</a>
</nav>

<div class="container">
    
    <section id="about" class="profile-section">
        <img src="https://via.placeholder.com/200" alt="Dr. Jane Smith" class="profile-img">
        <div>
            <h2>Biography</h2>
            <p>I am a Professor in the Department of Physics specializing in quantum mechanics and string theory. My work focuses on the intersection of theoretical models and observed phenomena in the early universe.</p>
        </div>
    </section>

    <section id="research">
        <h2>Research Interests</h2>
        <ul>
            <li>Quantum Field Theory</li>
            <li>Dark Matter Distribution Models</li>
            <li>Computational Astrophysics</li>
        </ul>
    </section>

    <section id="publications">
        <h2>Selected Publications</h2>
        <ul class="publication-list">
            <li><strong>Smith, J.</strong>, & Doe, R. (2025). "The Expansion of Sub-atomic Particles in Vacuum." <em>Journal of Physics</em>.</li>
            <li>Brown, A., & <strong>Smith, J.</strong> (2023). "Advancements in String Theory." <em>Science Review Quarterly</em>.</li>
        </ul>
    </section>

    <section id="teaching">
        <h2>Teaching</h2>
        <p><strong>Spring 2026:</strong> PHYS 401 - Advanced Quantum Mechanics</p>
        <p><strong>Fall 2025:</strong> PHYS 101 - Introduction to Modern Physics</p>
    </section>

    <section id="contact">
        <h2>Contact Information</h2>
        <p><strong>Email:</strong> j.smith@university.edu</p>
        <p><strong>Office:</strong> Science Hall, Room 402</p>
        <p><strong>Office Hours:</strong> Tuesdays 2:00 PM - 4:00 PM</p>
    </section>

</div>

<footer>
    &copy; 2026 Dr. Genny Nesslage. Built with clean HTML & CSS.
</footer>

</body>
</html>
