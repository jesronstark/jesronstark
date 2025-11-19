<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jesron - MERN Stack Developer</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #1a1a2e 0%, #16213e 100%);
            color: #fff;
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .header {
            text-align: center;
            padding: 40px 0;
        }
        
        .header h1 {
            font-size: 3rem;
            margin-bottom: 10px;
            background: linear-gradient(90deg, #4cc9f0, #4361ee);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }
        
        .header h3 {
            font-size: 1.5rem;
            font-weight: 400;
            opacity: 0.9;
            margin-bottom: 20px;
        }
        
        .profile-views {
            display: inline-block;
            background: rgba(255, 255, 255, 0.1);
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
        }
        
        .skills-section {
            background: rgba(255, 255, 255, 0.05);
            border-radius: 15px;
            padding: 30px;
            margin-bottom: 30px;
        }
        
        .skills-section h2 {
            text-align: center;
            margin-bottom: 25px;
            color: #4cc9f0;
            font-size: 1.8rem;
        }
        
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .skill-category {
            background: rgba(255, 255, 255, 0.08);
            border-radius: 10px;
            padding: 20px;
        }
        
        .skill-category h3 {
            color: #4361ee;
            margin-bottom: 15px;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
            padding-bottom: 8px;
        }
        
        .skill-category ul {
            list-style-type: none;
        }
        
        .skill-category li {
            margin-bottom: 8px;
            padding-left: 15px;
            position: relative;
        }
        
        .skill-category li:before {
            content: "▹";
            position: absolute;
            left: 0;
            color: #4cc9f0;
        }
        
        .social-section {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(500px, 1fr));
            gap: 30px;
            margin-bottom: 30px;
        }
        
        .social-card {
            background: rgba(255, 255, 255, 0.05);
            border-radius: 15px;
            padding: 25px;
            text-align: center;
        }
        
        .social-card h3 {
            color: #4cc9f0;
            margin-bottom: 20px;
            font-size: 1.5rem;
        }
        
        .social-icons {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
        }
        
        .social-icons a {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            width: 50px;
            height: 50px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 50%;
            transition: all 0.3s ease;
        }
        
        .social-icons a:hover {
            background: rgba(76, 201, 240, 0.3);
            transform: translateY(-3px);
        }
        
        .tool-icons {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
        }
        
        .tool-icons a {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            width: 60px;
            height: 60px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            transition: all 0.3s ease;
        }
        
        .tool-icons a:hover {
            background: rgba(67, 97, 238, 0.3);
            transform: translateY(-3px);
        }
        
        .support-section {
            text-align: center;
            margin: 40px 0;
        }
        
        .stats-section {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-bottom: 30px;
        }
        
        .stat-card {
            background: rgba(255, 255, 255, 0.05);
            border-radius: 15px;
            padding: 20px;
            text-align: center;
        }
        
        .trophy-section {
            text-align: center;
            margin: 40px 0;
        }
        
        @media (max-width: 768px) {
            .social-section {
                grid-template-columns: 1fr;
            }
            
            .skills-grid {
                grid-template-columns: 1fr;
            }
            
            .header h1 {
                font-size: 2.2rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header Section -->
        <div class="header">
            <h1>Hi 👋, I'm Jesron</h1>
            <h3>A passionate MERN Stack Developer from India</h3>
            <div class="profile-views">
                <img src="https://komarev.com/ghpvc/?username=jesronstark&label=Profile%20views&color=0e75b6&style=flat" alt="jesronstark" />
            </div>
        </div>
        
        <!-- Skills Section -->
        <div class="skills-section">
            <h2>Technical Skills</h2>
            <div class="skills-grid">
                <div class="skill-category">
                    <h3>🖥️ Frontend</h3>
                    <ul>
                        <li>ReactJS (Hooks, Context, Redux)</li>
                        <li>Styled-components & TailwindCSS</li>
                        <li>HTML5, CSS3, JavaScript (ES6+)</li>
                    </ul>
                </div>
                
                <div class="skill-category">
                    <h3>🔙 Backend</h3>
                    <ul>
                        <li>Java (Spring Boot)</li>
                        <li>Node.js (Express, NestJS)</li>
                        <li>PostgreSQL, MongoDB</li>
                        <li>Kafka, Elasticsearch</li>
                    </ul>
                </div>
                
                <div class="skill-category">
                    <h3>☁️ DevOps</h3>
                    <ul>
                        <li>AWS (EC2, Lambda, S3, RDS)</li>
                        <li>Docker, Terraform</li>
                        <li>CI/CD (GitHub Actions, CodePipeline)</li>
                    </ul>
                </div>
            </div>
        </div>
        
        <!-- Trophy Section -->
        <div class="trophy-section">
            <a href="https://github.com/ryo-ma/github-profile-trophy">
                <img src="https://github-profile-trophy.vercel.app/?username=jesronstark" alt="jesronstark" />
            </a>
        </div>
        
        <!-- Social & Tools Section -->
        <div class="social-section">
            <div class="social-card">
                <h3>Connect with me</h3>
                <div class="social-icons">
                    <a href="https://codepen.io/jesronstark" target="_blank">
                        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/codepen.svg" alt="Codepen" height="30" width="30" />
                    </a>
                    <a href="https://dev.to/jesron" target="_blank">
                        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/devto.svg" alt="Dev.to" height="30" width="30" />
                    </a>
                    <a href="https://twitter.com/jesron643834" target="_blank">
                        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="Twitter" height="30" width="30" />
                    </a>
                    <a href="https://linkedin.com/in/jesron" target="_blank">
                        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="30" width="30" />
                    </a>
                    <a href="https://stackoverflow.com/users/jesron" target="_blank">
                        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/stack-overflow.svg" alt="Stack Overflow" height="30" width="30" />
                    </a>
                    <a href="https://kaggle.com/jesron28" target="_blank">
                        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/kaggle.svg" alt="Kaggle" height="30" width="30" />
                    </a>
                    <a href="https://fb.com/jesronstark" target="_blank">
                        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="Facebook" height="30" width="30" />
                    </a>
                    <a href="https://instagram.com/jesronnn" target="_blank">
                        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="Instagram" height="30" width="30" />
                    </a>
                    <a href="https://www.youtube.com/c/@jesron9609" target="_blank">
                        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="YouTube" height="30" width="30" />
                    </a>
                    <a href="https://www.hackerrank.com/@jesronstark" target="_blank">
                        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/hackerrank.svg" alt="HackerRank" height="30" width="30" />
                    </a>
                    <a href="https://www.leetcode.com/jesron" target="_blank">
                        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" alt="LeetCode" height="30" width="30" />
                    </a>
                    <a href="https://discord.gg/jesron28" target="_blank">
                        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg" alt="Discord" height="30" width="30" />
                    </a>
                </div>
            </div>
            
            <div class="social-card">
                <h3>Languages & Tools</h3>
                <div class="tool-icons">
                    <a href="https://aws.amazon.com/amplify/" target="_blank">
                        <img src="https://docs.amplify.aws/assets/logo-dark.svg" alt="Amplify" width="30" height="30" />
                    </a>
                    <a href="https://www.arduino.cc/" target="_blank">
                        <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="Arduino" width="30" height="30" />
                    </a>
                    <a href="https://getbootstrap.com" target="_blank">
                        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="Bootstrap" width="30" height="30" />
                    </a>
                    <a href="https://www.cprogramming.com/" target="_blank">
                        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="C" width="30" height="30" />
                    </a>
                    <a href="https://www.w3schools.com/css/" target="_blank">
                        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3" width="30" height="30" />
                    </a>
                    <a href="https://expressjs.com" target="_blank">
                        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="Express" width="30" height="30" />
                    </a>
                    <a href="https://git-scm.com/" target="_blank">
                        <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="Git" width="30" height="30" />
                    </a>
                    <a href="https://www.w3.org/html/" target="_blank">
                        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5" width="30" height="30" />
                    </a>
                    <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank">
                        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" width="30" height="30" />
                    </a>
                    <a href="https://www.mongodb.com/" target="_blank">
                        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="MongoDB" width="30" height="30" />
                    </a>
                    <a href="https://www.mysql.com/" target="_blank">
                        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL" width="30" height="30" />
                    </a>
                    <a href="https://nodejs.org" target="_blank">
                        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="Node.js" width="30" height="30" />
                    </a>
                    <a href="https://www.python.org" target="_blank">
                        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="30" height="30" />
                    </a>
                    <a href="https://reactjs.org/" target="_blank">
                        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="React" width="30" height="30" />
                    </a>
                    <a href="https://redux.js.org" target="_blank">
                        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redux/redux-original.svg" alt="Redux" width="30" height="30" />
                    </a>
                    <a href="https://tailwindcss.com/" target="_blank">
                        <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="Tailwind" width="30" height="30" />
                    </a>
                </div>
            </div>
        </div>
        
        <!-- Support Section -->
        <div class="support-section">
            <h3>Support My Work</h3>
            <p>
                <a href="https://www.buymeacoffee.com/jesron" target="_blank">
                    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="Buy Me A Coffee" />
                </a>
            </p>
        </div>
        
        <!-- Stats Section -->
        <div class="stats-section">
            <div class="stat-card">
                <img src="https://github-readme-stats.vercel.app/api?username=jesronstark&show_icons=true&locale=en&theme=radical" alt="jesronstark" />
            </div>
            <div class="stat-card">
                <img src="https://github-readme-streak-stats.herokuapp.com/?user=jesronstark&theme=radical" alt="jesronstark" />
            </div>
            <div class="stat-card">
                <img src="https://github-readme-stats.vercel.app/api/top-langs?username=jesronstark&show_icons=true&locale=en&layout=compact&theme=radical" alt="jesronstark" />
            </div>
        </div>
    </div>
</body>
</html>
