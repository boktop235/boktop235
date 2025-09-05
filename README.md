<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Profile README</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #0d1117 0%, #161b22 100%);
            color: #c9d1d9;
            line-height: 1.6;
            padding: 20px;
            max-width: 900px;
            margin: 0 auto;
        }
        
        .container {
            background-color: #0d1117;
            border-radius: 12px;
            border: 1px solid #30363d;
            overflow: hidden;
            box-shadow: 0 8px 30px rgba(0, 0, 0, 0.4);
        }
        
        .header {
            background: linear-gradient(90deg, #238636 0%, #2ea043 100%);
            padding: 30px 20px;
            text-align: center;
            border-bottom: 1px solid #30363d;
        }
        
        .header h1 {
            color: white;
            font-size: 2.5rem;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
        }
        
        .content {
            padding: 30px;
        }
        
        .profile {
            display: flex;
            align-items: center;
            margin-bottom: 30px;
            flex-wrap: wrap;
            gap: 20px;
        }
        
        .profile-img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 4px solid #30363d;
            background: linear-gradient(45deg, #58a6ff, #bc8cff);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 50px;
            color: white;
        }
        
        .profile-info {
            flex: 1;
            min-width: 250px;
        }
        
        .profile-info h2 {
            color: #58a6ff;
            margin-bottom: 10px;
            font-size: 1.8rem;
        }
        
        .profile-info p {
            color: #8b949e;
            margin-bottom: 15px;
        }
        
        .stats {
            display: flex;
            gap: 15px;
            flex-wrap: wrap;
            margin: 20px 0;
        }
        
        .stat {
            background: #161b22;
            border: 1px solid #30363d;
            border-radius: 8px;
            padding: 15px;
            flex: 1;
            min-width: 200px;
            text-align: center;
        }
        
        .stat h3 {
            color: #58a6ff;
            margin-bottom: 10px;
        }
        
        .stat p {
            font-size: 1.8rem;
            font-weight: bold;
            color: #f0f6fc;
        }
        
        .languages {
            background: #161b22;
            border: 1px solid #30363d;
            border-radius: 8px;
            padding: 20px;
            margin: 30px 0;
        }
        
        .languages h2 {
            color: #58a6ff;
            margin-bottom: 20px;
            text-align: center;
            font-size: 1.5rem;
        }
        
        .lang-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
            gap: 15px;
        }
        
        .lang-item {
            display: flex;
            align-items: center;
            gap: 10px;
            padding: 10px;
            background: #0d1117;
            border-radius: 6px;
            border: 1px solid #30363d;
        }
        
        .lang-icon {
            width: 24px;
            height: 24px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 18px;
        }
        
        .lang-name {
            flex: 1;
            color: #f0f6fc;
        }
        
        .lang-percent {
            color: #8b949e;
            font-weight: bold;
        }
        
        .github-stats {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            margin: 30px 0;
        }
        
        .github-stats img {
            flex: 1;
            min-width: 300px;
            border: 1px solid #30363d;
            border-radius: 8px;
        }
        
        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
            flex-wrap: wrap;
        }
        
        .social-link {
            display: flex;
            align-items: center;
            gap: 8px;
            color: #58a6ff;
            text-decoration: none;
            padding: 10px 20px;
            border: 1px solid #30363d;
            border-radius: 6px;
            transition: all 0.3s ease;
        }
        
        .social-link:hover {
            background-color: #161b22;
            transform: translateY(-2px);
        }
        
        .footer {
            text-align: center;
            margin-top: 40px;
            color: #8b949e;
            font-size: 0.9rem;
            padding: 20px;
            border-top: 1px solid #30363d;
        }
        
        @media (max-width: 768px) {
            .profile {
                justify-content: center;
                text-align: center;
            }
            
            .profile-info {
                width: 100%;
            }
            
            .header h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Привет всем! 👋</h1>
        </div>
        
        <div class="content">
            <div class="profile">
                <div class="profile-img">
                    <i class="fas fa-user"></i>
                </div>
                <div class="profile-info">
                    <h2>Добро пожаловать на мой GitHub профиль!</h2>
                    <p>Я увлеченный разработчик, который любит создавать интересные проекты с использованием современных технологий.</p>
                </div>
            </div>
            
            <div class="stats">
                <div class="stat">
                    <h3><i class="fas fa-code-branch"></i> Репозитории</h3>
                    <p>24</p>
                </div>
                <div class="stat">
                    <h3><i class="fas fa-star"></i> Звезды</h3>
                    <p>128</p>
                </div>
                <div class="stat">
                    <h3><i class="fas fa-code"></i> Вклад</h3>
                    <p>1,254</p>
                </div>
            </div>
            
            <div class="languages">
                <h2><i class="fas fa-code"></i> Мои технологии</h2>
                <div class="lang-grid">
                    <div class="lang-item">
                        <div class="lang-icon" style="color: #f7df1e;">
                            <i class="fab fa-js-square"></i>
                        </div>
                        <div class="lang-name">JavaScript</div>
                        <div class="lang-percent">35%</div>
                    </div>
                    <div class="lang-item">
                        <div class="lang-icon" style="color: #61dafb;">
                            <i class="fab fa-react"></i>
                        </div>
                        <div class="lang-name">React</div>
                        <div class="lang-percent">25%</div>
                    </div>
                    <div class="lang-item">
                        <div class="lang-icon" style="color: #4479a1;">
                            <i class="fab fa-python"></i>
                        </div>
                        <div class="lang-name">Python</div>
                        <div class="lang-percent">20%</div>
                    </div>
                    <div class="lang-item">
                        <div class="lang-icon" style="color: #e34f26;">
                            <i class="fab fa-html5"></i>
                        </div>
                        <div class="lang-name">HTML</div>
                        <div class="lang-percent">10%</div>
                    </div>
                    <div class="lang-item">
                        <div class="lang-icon" style="color: #2965f1;">
                            <i class="fab fa-css3-alt"></i>
                        </div>
                        <div class="lang-name">CSS</div>
                        <div class="lang-percent">10%</div>
                    </div>
                </div>
            </div>
            
            <div class="github-stats">
                <img src="https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark" alt="GitHub Stats">
                <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=compact&theme=dark" alt="Top Languages">
            </div>
            
            <div class="social-links">
                <a href="#" class="social-link">
                    <i class="fab fa-github"></i>
                    <span>GitHub</span>
                </a>
                <a href="#" class="social-link">
                    <i class="fab fa-linkedin"></i>
                    <span>LinkedIn</span>
                </a>
                <a href="#" class="social-link">
                    <i class="fab fa-telegram"></i>
                    <span>Telegram</span>
                </a>
                <a href="#" class="social-link">
                    <i class="fas fa-envelope"></i>
                    <span>Email</span>
                </a>
            </div>
        </div>
        
        <div class="footer">
            <p>Создано с ❤️ с использованием HTML и CSS | Обновлено: Сентябрь 2023</p>
        </div>
    </div>
</body>
</html>