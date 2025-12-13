<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub README Profile</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            background-color: #0d1117;
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;
            color: #c9d1d9;
            padding: 10px;
        }
        .readme-container {
            max-width: 900px;
            margin: 0 auto;
            background-color: #0d1117;
        }
        .header {
            text-align: center;
            margin-bottom: 15px;
            padding-bottom: 10px;
            border-bottom: 1px solid #30363d;
        }
        .header h1 {
            font-size: 28px;
            margin-bottom: 5px;
            color: #58a6ff;
            text-shadow: 0 0 10px rgba(88, 166, 255, 0.3);
        }
        .header p {
            font-size: 13px;
            color: #8b949e;
            margin-bottom: 2px;
        }
        .section {
            margin-bottom: 15px;
        }
        .section-title {
            font-size: 16px;
            font-weight: 600;
            color: #58a6ff;
            margin-bottom: 10px;
            padding-bottom: 5px;
            border-bottom: 2px solid #30363d;
            display: flex;
            align-items: center;
            gap: 8px;
        }
        .section-title::before {
            content: "▶";
            font-size: 14px;
        }
        .stats-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 12px;
            margin-bottom: 10px;
        }
        .stats-card {
            background-color: #161b22;
            border: 1px solid #30363d;
            border-radius: 6px;
            padding: 10px;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 200px;
            transition: all 0.3s ease;
        }
        .stats-card:hover {
            border-color: #58a6ff;
            box-shadow: 0 0 10px rgba(88, 166, 255, 0.2);
        }
        .stats-card img {
            max-width: 100%;
            height: auto;
            border-radius: 4px;
            background-color: #0d1117;
        }
        .full-width-card {
            background-color: #161b22;
            border: 1px solid #30363d;
            border-radius: 6px;
            padding: 12px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            min-height: 220px;
            transition: all 0.3s ease;
        }
        .full-width-card:hover {
            border-color: #58a6ff;
            box-shadow: 0 0 10px rgba(88, 166, 255, 0.2);
        }
        .full-width-card img {
            max-width: 100%;
            height: auto;
            border-radius: 4px;
            background-color: #0d1117;
        }
        .section-content {
            display: flex;
            flex-direction: column;
            gap: 12px;
        }
        .section-description {
            font-size: 13px;
            color: #8b949e;
            line-height: 1.6;
            padding: 8px;
            background-color: rgba(88, 166, 255, 0.05);
            border-left: 3px solid #58a6ff;
            border-radius: 4px;
        }
        /* Two-column block: languages (left) and socials (right) */
        .mid-grid {
            display: grid;
            grid-template-columns: 1fr 280px;
            gap: 12px;
            align-items: start;
        }
        /* Make social column stack vertically */
        .social-grid {
            display: grid;
            grid-template-columns: 1fr;
            gap: 8px;
            margin-bottom: 0;
        }
        .social-card {
            background-color: #161b22;
            border: 1px solid #30363d;
            border-radius: 6px;
            padding: 10px;
            text-align: center;
            cursor: pointer;
            transition: all 0.22s ease;
            text-decoration: none;
            display: flex;
            flex-direction: row;
            justify-content: flex-start;
            align-items: center;
            gap: 12px;
        }
        .social-card:hover {
            border-color: #58a6ff;
            background-color: rgba(88, 166, 255, 0.06);
            box-shadow: 0 0 8px rgba(88, 166, 255, 0.18);
            transform: translateY(-2px);
        }
        .social-icon {
            font-size: 18px;
            width: 28px;
            text-align: center;
        }
        .social-label {
            font-size: 13px;
            color: #c9d1d9;
            font-weight: 600;
        }
        .social-card .social-hint {
            font-size: 11px;
            color: #8b949e;
        }
        .social-card:hover .social-label {
            color: #58a6ff;
        }
        @media (max-width: 768px) {
            .stats-grid {
                grid-template-columns: 1fr;
            }
            .header h1 {
                font-size: 24px;
            }
            .section-title {
                font-size: 18px;
            }
            /* Collapse mid-grid to single column on small screens */
            .mid-grid {
                grid-template-columns: 1fr;
            }
            .social-card {
                width: 100%;
                padding: 10px;
            }
        }
    </style>
</head>
<body>
    <div class="readme-container">
        <!-- HEADER -->
        <div class="header">
            <h1>👨‍💻 Welcome to My GitHub Profile</h1>
            <p>Full Stack Developer | Open Source Enthusiast</p>
            <p>Building amazing projects with passion 🚀</p>
        </div>
        <!-- STATS SECTION -->
        <div class="section">
            <div class="section-title">GitHub Statistics</div>
            <div class="stats-grid">
                <div class="stats-card">
                    <img src="https://github-readme-stats.vercel.app/api?username=PiyushVerma246&show_icons=true&theme=github_dark&hide_border=true&count_private=true" alt="GitHub Stats" />
                </div>
                <div class="stats-card">
                    <img src="https://streak-stats.demolab.com?user=PiyushVerma246&theme=dark&hide_border=true" alt="GitHub Streak" />
                </div>
            </div>
        </div>
        <div class="separator"></div>
        <!-- LANGUAGES + SOCIALS (two-column) -->
        <div class="section">
            <div class="mid-grid">
                <!-- LEFT: Languages -->
                <div>
                    <div class="section-title">Top Languages</div>
                    <div class="section-content">
                        <div class="section-description">
                            💡 <strong>Primary Tech Stack:</strong> JavaScript, Python, TypeScript and related frameworks. I focus on web apps, APIs, and automation — these languages power most of my projects.
                        </div>
                        <div class="full-width-card lang-card">
                            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=PiyushVerma246&layout=compact&theme=github_dark&hide_border=true" alt="Top Languages" />
                        </div>
                    </div>
                </div>
                <!-- RIGHT: Socials -->
                <div>
                    <div class="section-title">Connect With Me</div>
                    <div class="social-grid">
                        <a href="https://github.com/PiyushVerma246" class="social-card" target="_blank">
                            <div class="social-icon">🐙</div>
                            <div>
                                <div class="social-label">GitHub</div>
                                <div class="social-hint">@PiyushVerma246</div>
                            </div>
                        </a>
                        <a href="https://linkedin.com/in/piyush-verma" class="social-card" target="_blank">
                            <div class="social-icon">💼</div>
                            <div>
                                <div class="social-label">LinkedIn</div>
                                <div class="social-hint">/in/piyush-verma</div>
                            </div>
                        </a>
                        <a href="https://twitter.com/piyushverma" class="social-card" target="_blank">
                            <div class="social-icon">𝕏</div>
                            <div>
                                <div class="social-label">X / Twitter</div>
                                <div class="social-hint">@piyushverma</div>
                            </div>
                        </a>
                        <a href="mailto:piyush@example.com" class="social-card">
                            <div class="social-icon">✉️</div>
                            <div>
                                <div class="social-label">Email</div>
                                <div class="social-hint">piyush@example.com</div>
                            </div>
                        </a>
                        <a href="https://portfolio.example.com" class="social-card" target="_blank">
                            <div class="social-icon">🌐</div>
                            <div>
                                <div class="social-label">Portfolio</div>
                                <div class="social-hint">portfolio.example.com</div>
                            </div>
                        </a>
                        <a href="https://dev.to/piyush" class="social-card" target="_blank">
                            <div class="social-icon">📝</div>
                            <div>
                                <div class="social-label">Dev.to</div>
                                <div class="social-hint">/piyush</div>
                            </div>
                        </a>
                    </div>
                </div>
            </div>
        </div>
        <div class="separator"></div>
        <!-- CONTRIBUTION GRAPH SECTION -->
        <div class="section">
            <div class="section-title">Contribution Graph</div>
            <div class="full-width-card">
                <img src="https://github-readme-activity-graph.vercel.app/graph?username=PiyushVerma246&theme=github-dark&hide_border=true&area=false" alt="Contribution Graph" />
            </div>
        </div>
        <!-- FOOTER -->
        <div class="header" style="border-top: 1px solid #30363d; border-bottom: none; text-align: center;">
            <p style="color: #58a6ff; margin-bottom: 5px;">⭐ If you like my work, consider starring my repositories!</p>
            <p style="color: #8b949e; font-size: 12px;">Last updated: December 13, 2025</p>
        </div>
    </div>
</body>
</html>
