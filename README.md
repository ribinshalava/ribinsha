
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>RIBINSHA L | Portfolio</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, sans-serif;
            background: #f8fafc;
            color: #1e293b;
            line-height: 1.6;
        }

        header {
            background: #ffffff;
            padding: 18px 8%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 10px #00000010;
        }

        .logo {
            color: #2563eb;
            font-size: 23px;
            font-weight: bold;
        }

        nav a {
            color: #334155;
            text-decoration: none;
            margin-left: 22px;
            font-size: 15px;
        }

        nav a:hover {
            color: #2563eb;
        }

        section {
            padding: 80px 8%;
        }

        .hero {
            min-height: 85vh;
            display: flex;
            align-items: center;
            justify-content: space-between;
            gap: 40px;
        }

        .hero-text {
            max-width: 600px;
            animation: slideIn 1s ease;
        }

        .hero-text h3 {
            color: #2563eb;
            font-size: 22px;
        }

        .hero-text h1 {
            font-size: clamp(36px, 5vw, 58px);
            margin: 10px 0;
            line-height: 1.2;
        }

        .hero-text h2 {
            font-size: 25px;
            color: #475569;
            margin-bottom: 15px;
        }

        .hero-text p {
            color: #64748b;
            margin-bottom: 25px;
        }

        .btn {
            display: inline-block;
            background: #2563eb;
            color: white;
            padding: 12px 25px;
            border-radius: 7px;
            text-decoration: none;
            margin-right: 10px;
            transition: 0.3s;
        }

        .btn:hover {
            background: #1d4ed8;
            transform: translateY(-3px);
        }

        .profile-img {
            width: 280px;
            height: 280px;
            border-radius: 50%;
            object-fit: cover;
            border: 6px solid #dbeafe;
            box-shadow: 0 10px 30px #2563eb20;
        }

        .section-title {
            text-align: center;
            font-size: 32px;
            margin-bottom: 35px;
        }

        .section-title span {
            color: #2563eb;
        }

        .about-card, .skill-card, .contact-card {
            background: white;
            padding: 30px;
            border-radius: 14px;
            box-shadow: 0 5px 25px #00000008;
        }

        .about-card {
            max-width: 800px;
            margin: auto;
            text-align: center;
        }

        .about-card p {
            color: #64748b;
        }

        .skills-container {
            display: flex;
            justify-content: center;
            gap: 25px;
            flex-wrap: wrap;
        }

        .skill-card {
            width: 230px;
            text-align: center;
            transition: 0.3s;
        }

        .skill-card:hover {
            transform: translateY(-8px);
        }

        .skill-icon {
            font-size: 38px;
            margin-bottom: 10px;
        }

        .skill-card h3 {
            color: #2563eb;
        }

        .contact-card {
            max-width: 600px;
            margin: auto;
            text-align: center;
        }

        .contact-card p {
            margin: 12px 0;
            overflow-wrap: anywhere;
        }

        .contact-card a {
            color: #2563eb;
            text-decoration: none;
        }

        footer {
            background: #0f172a;
            color: white;
            text-align: center;
            padding: 22px;
        }

        @keyframes slideIn {
            from {
                opacity: 0;
                transform: translateY(25px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @media (max-width: 700px) {
            header {
                flex-direction: column;
                gap: 12px;
            }

            nav a {
                margin: 0 7px;
                font-size: 13px;
            }

            .hero {
                flex-direction: column-reverse;
                text-align: center;
                padding-top: 50px;
            }

            .profile-img {
                width: 210px;
                height: 210px;
            }

            section {
                padding: 60px 6%;
            }

            .hero-text h2 {
                font-size: 21px;
            }
        }
    </style>
</head>

<body>

    <header>
        <div class="logo">RIBINSHA L</div>

        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section class="hero" id="home">

        <div class="hero-text">
            <h3>Hello, Welcome to My Portfolio!</h3>

            <h1>I'm <span style="color:#2563eb;">Ribinsha L</span></h1>

            <h2>BCA Second Year Student</h2>

            <p>
                I am a BCA student interested in learning new technologies
                and developing my computer skills. Welcome to my personal
                portfolio website!
            </p>

            <a href="#about" class="btn">About Me</a>
            <a href="#contact" class="btn">Contact Me</a>
        </div>

        <div>
            <img src="profile.jpg"
                 alt="Ribinsha's Profile Photo"
                 class="profile-img">
        </div>

    </section>

    <section id="about">
        <h2 class="section-title">About <span>Me</span></h2>

        <div class="about-card">
            <p>
                Hello! My name is Ribinsha L. I am currently pursuing
                my Bachelor of Computer Applications (BCA), second year.
                I enjoy learning computer applications and improving my
                technical knowledge. I am interested in developing my
                skills and building a successful career in technology.
            </p>
        </div>
    </section>

    <section id="skills">
        <h2 class="section-title">My <span>Skills</span></h2>

        <div class="skills-container">

            <div class="skill-card">
                <div class="skill-icon">📊</div>
                <h3>Microsoft Excel</h3>
                <p>Working with spreadsheets and organizing data.</p>
            </div>

            <div class="skill-card">
                <div class="skill-icon">💻</div>
                <h3>Computer Applications</h3>
                <p>Learning computer applications and technology.</p>
            </div>

            <div class="skill-card">
                <div class="skill-icon">📚</div>
                <h3>Continuous Learning</h3>
                <p>Exploring new skills and improving my knowledge.</p>
            </div>

        </div>
    </section>

    <section id="contact">
        <h2 class="section-title">Contact <span>Me</span></h2>

        <div class="contact-card">
            <p><strong>Name:</strong> Ribinsha L</p>

            <p>
                <strong>Email:</strong>
                <a href="mailto:ribinshalava@gmail.com">
                    ribinshalava@gmail.com
                </a>
            </p>

            <p>
                Feel free to contact me through email.
            </p>

            <a href="mailto:ribinshalava@gmail.com" class="btn">
                Send Email
            </a>
        </div>
    </section>

    <footer>
        <p>© 2026 RIBINSHA L | Personal Portfolio</p>
    </footer>

</body>
</html>
