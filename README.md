<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mouad Elattar - Full-Stack Developer</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: #fff;
            min-height: 100vh;
            padding: 40px 20px;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            padding: 40px;
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3);
        }

        .header {
            text-align: center;
            margin-bottom: 40px;
        }

        .header h1 {
            font-size: 3em;
            margin-bottom: 10px;
            animation: fadeInDown 1s;
        }

        .header h2 {
            font-size: 1.5em;
            font-weight: 300;
            opacity: 0.9;
        }

        .content-wrapper {
            display: grid;
            grid-template-columns: 1fr 400px;
            gap: 40px;
            margin-bottom: 40px;
        }

        .main-content {
            display: flex;
            flex-direction: column;
            gap: 30px;
        }

        .coding-gif {
            text-align: center;
        }

        .coding-gif img {
            max-width: 100%;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
        }

        .section {
            background: rgba(255, 255, 255, 0.05);
            padding: 25px;
            border-radius: 15px;
            border-left: 4px solid #ff6b6b;
        }

        .section h3 {
            font-size: 1.8em;
            margin-bottom: 15px;
            color: #ffd93d;
        }

        .section p, .section ul {
            font-size: 1.1em;
            line-height: 1.8;
        }

        .section ul {
            list-style: none;
            padding-left: 0;
        }

        .section ul li {
            margin-bottom: 10px;
            padding-left: 25px;
            position: relative;
        }

        .section ul li:before {
            content: "▹";
            position: absolute;
            left: 0;
            color: #ff6b6b;
            font-size: 1.5em;
        }

        .tech-stack {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .tech-category {
            background: rgba(255, 255, 255, 0.08);
            padding: 20px;
            border-radius: 10px;
        }

        .tech-category h4 {
            color: #ffd93d;
            margin-bottom: 15px;
            font-size: 1.2em;
        }

        .tech-icons {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            margin-top: 20px;
            justify-content: center;
        }

        .tech-icons img {
            width: 50px;
            height: 50px;
            transition: transform 0.3s;
        }

        .tech-icons img:hover {
            transform: scale(1.2) rotate(5deg);
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
        }

        .social-links a {
            display: inline-block;
            background: linear-gradient(45deg, #ff6b6b, #ffd93d);
            padding: 12px 30px;
            border-radius: 25px;
            text-decoration: none;
            color: #fff;
            font-weight: bold;
            transition: all 0.3s;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
        }

        .social-links a:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.3);
        }

        .stats {
            text-align: center;
            margin-top: 40px;
        }

        .stats img {
            border-radius: 10px;
            margin: 10px;
        }

        .quote {
            text-align: center;
            font-style: italic;
            opacity: 0.8;
            margin-top: 30px;
            padding: 20px;
            background: rgba(255, 255, 255, 0.05);
            border-radius: 10px;
        }

        @keyframes fadeInDown {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @media (max-width: 968px) {
            .content-wrapper {
                grid-template-columns: 1fr;
            }
            
            .coding-gif {
                order: -1;
            }

            .header h1 {
                font-size: 2em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Hi 👋, I'm Mouad Elattar</h1>
            <h2>Full-Stack Developer | Morocco 🇲🇦</h2>
        </div>

        <div class="content-wrapper">
            <div class="main-content">
                <div class="section">
                    <h3>👨‍💻 About Me</h3>
                    <p>I'm a passionate full-stack developer specializing in building scalable web applications with modern technologies. I love turning complex problems into simple, beautiful, and intuitive solutions.</p>
                </div>

                <div class="section">
                    <h3>🚀 Currently Exploring</h3>
                    <ul>
                        <li><strong>Angular</strong> - Building dynamic single-page applications</li>
                        <li><strong>Spring Boot</strong> - Developing robust enterprise solutions</li>
                        <li><strong>Go</strong> - Learning efficient backend development</li>
                    </ul>
                </div>

                <div class="section">
                    <h3>💡 Tech Stack</h3>
                    <div class="tech-stack">
                        <div class="tech-category">
                            <h4>Frontend</h4>
                            <p>React.js • JavaScript •
