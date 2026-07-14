# OIBSIP_Web-development-and-designing-_task-no-1
Task 1: Landing Page | Oasis Infobyte Internship. A sleek, interactive landing page designed to showcase modern frontend web development practices. Optimized for all screen sizes with a strong focus on clean visual hierarchy. Built with HTML5, CSS3, and JavaScript.
 below I'll share the codes i have written. 
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Dev Journey</title>
    <style>
        :root {
            --primary: #0cefaf;
            --brand-accent: #00b312;
            --btn-color: #2c5ea7;
            --btn-hover: #e60000;
            --text-main: #19575ed6;
            --bg-light: #f9f9f9;
        }

        /* basic reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            line-height: 1.6;
            color: var(--text-main);
            background: var(--bg-light);
        }

        /* navbar */
        header {
            background: #fff;
            padding: 20px 10%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 1px 3px rgba(0,0,0,0.05);
        }

        .brand-logo {
            font-size: 1.5rem;
            font-weight: 700;
            color: var(--brand-accent);
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 24px;
        }

        nav a {
            text-decoration: none;
            color: var(--text-main);
            font-weight: 500;
            transition: color 0.2s ease;
        }

        nav a:hover {
            color: var(--brand-accent);
        }

        /* intro / hero */
        .intro-section {
            background-color: var(--primary);
            color: white;
            padding: 100px 10%;
            text-align: center;
        }

        .intro-section h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
            line-height: 1.2;
        }

        .intro-section p {
            font-size: 1.25rem;
            margin: 0 auto 2rem auto;
            max-width: 600px;
            opacity: 0.9;
        }

        .cta-button {
            display: inline-block;
            background-color: var(--btn-color);
            color: white;
            padding: 14px 28px;
            text-decoration: none;
            font-size: 1.1rem;
            border-radius: 6px;
            font-weight: 600;
            transition: background 0.2s ease, transform 0.1s ease;
        }

        .cta-button:hover {
            background-color: var(--btn-hover);
            transform: translateY(-2px);
        }

        /* perks */
        .perks {
            padding: 5rem 10%;
            text-align: center;
        }

        .perks h2 {
            font-size: 2.25rem;
            margin-bottom: 3rem;
        }

        .perks-wrapper {
            display: flex;
            justify-content: space-between;
            gap: 2rem;
        }

        .perk-card {
            background: #fff;
            padding: 2.5rem 1.5rem;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.08);
            flex: 1;
        }

        .perk-card h3 {
            margin-bottom: 1rem;
            color: #83b300;
        }

        footer {
            background-color: var(--text-main);
            color: white;
            text-align: center;
            padding: 1.5rem 0;
            font-size: 0.9rem;
        }

        @media (max-width: 768px) {
            .perks-wrapper {
                flex-direction: column; 
            }
            header {
                flex-direction: column;
                gap: 1rem;
            }
        }
    </style>
</head>
<body>

    <header>
        <div class="brand-logo">My First Landing Page </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#perks">Features</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="intro-section" id="home">
            <h1>Build Something Amazing</h1>
            <p>This is a beginner-friendly landing page. Let's dive into the era of web development.</p>
            <a href="#" class="cta-button">Get Started</a>
        </section>

        <section class="perks" id="perks">
            <h2>Why choose web dev?</h2>
            <div class="perks-wrapper">
                
                <div class="perk-card">
                    <h3>Instant Visual Feedback</h3>
                    <p>Write code and immediately see the results on your screen. It makes the learning process incredibly rewarding.</p>
                </div>
                
                <div class="perk-card">
                    <h3>Easy to Showcase</h3>
                    <p>A working website is the easiest way to share your ideas, projects, or portfolio with anyone in the world.</p>
                </div>
                
                <div class="perk-card">
                    <h3>High Demand</h3>
                    <p>Every industry relies on the web, meaning these foundational skills open doors to countless careers.</p>
                </div>

            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Developed by Ayushi .</p>
    </footer>

</body>
</html> 

I will share the screenshots of output below .

<img width="1920" height="1080" alt="InShot_20260714_104824208(1)" src="https://github.com/user-attachments/assets/71a98303-84d5-46e6-a781-765c3b97a21f" />
 
