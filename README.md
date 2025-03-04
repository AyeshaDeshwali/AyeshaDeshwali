<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ayesha's GitHub Profile</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f4;
            color: #333;
            padding: 20px;
        }
        .container {
            max-width: 1200px;
            margin: auto;
            background: #fff;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }
        h1, h3 {
            text-align: center;
            margin-bottom: 20px;
        }
        .intro {
            text-align: center;
            margin-bottom: 40px;
        }
        .skills-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .skill {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .skill h4 {
            margin-bottom: 10px;
        }
        .progress-bar {
            background: #ddd;
            border-radius: 5px;
            overflow: hidden;
        }
        .progress {
            height: 20px;
            text-align: right;
            line-height: 20px;
            padding-right: 10px;
            font-size: 14px;
            color: #fff;
        }
        .html .progress { background: #f16529; width: 85%; }
        .css .progress { background: #2965f1; width: 80%; }
        .javascript .progress { background: #f7df1e; color: #000; width: 90%; }
        .node .progress { background: #68a063; width: 80%; }
        .mongodb .progress { background: #4db33d; width: 75%; }
        .react .progress { background: #61dafb; color: #000; width: 70%; }
        .bootstrap .progress { background: #563d7c; width: 72%; }
        .github .progress { background: #24292e; width: 75%; }

        .github-stats img {
            width: 100%;
            border-radius: 8px;
        }
        .stats-container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
            margin-top: 40px;
        }
        .stat-card {
            flex: 1 1 300px;
            max-width: 350px;
        }
        @media (max-width: 768px) {
            .skills-container, .stats-container {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Hi 👋 I'm Ayesha</h1>
        <h3>I am ❤️ devoted to the art of coding.</h3>

        <div class="skills-container">
            <div class="skill html">
                <h4>HTML</h4>
                <div class="progress-bar">
                    <div class="progress">85%</div>
                </div>
            </div>
            <div class="skill css">
                <h4>CSS</h4>
                <div class="progress-bar">
                    <div class="progress">80%</div>
                </div>
            </div>
            <div class="skill javascript">
                <h4>JavaScript</h4>
                <div class="progress-bar">
                    <div class="progress">90%</div>
                </div>
            </div>
            <div class="skill node">
                <h4>Node.js</h4>
                <div class="progress-bar">
                    <div class="progress">80%</div>
                </div>
            </div>
            <div class="skill mongodb">
                <h4>MongoDB</h4>
                <div class="progress-bar">
                    <div class="progress">75%</div>
                </div>
            </div>
            <div class="skill react">
                <h4>React</h4>
                <div class="progress-bar">
                    <div class="progress">70%</div>
                </div>
            </div>
            <div class="skill bootstrap">
                <h4>Bootstrap</h4>
                <div class="progress-bar">
                    <div class="progress">72%</div>
                </div>
            </div>
            <div class="skill github">
                <h4>GitHub</h4>
                <div class="progress-bar">
                    <div class="progress">75%</div>
                </div>
            </div>
        </div>

        <div class="stats-container">
            <div class="stat-card">
                <img src="https://github-readme-stats.vercel.app/api?username=ayesha&show_icons=true&theme=radical" alt="Ayesha's GitHub Stats">
            </div>
            <div class="stat-card">
                <img src="https://github-readme-streak-stats.herokuapp.com/?user=ayesha&theme=radical" alt="GitHub Streak">
            </div>
            <div class="stat-card">
                <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ayesha&layout=compact&theme=radical" alt="Top Languages">
            </div>
        </div>
    </div>
</body>
</html>
