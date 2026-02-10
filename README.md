[M Furqan Asif (1).html](https://github.com/user-attachments/files/25216659/M.Furqan.Asif.1.html)# Furqanhaker

[Uploading M Furqan Asif (1).html<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>M Furqan Asif | Personal Website</title>
    <style>
        :root {
            --color-bg-primary: #0a0e27;
            --color-bg-secondary: #1a1f3a;
            --color-text-primary: #ffffff;
            --color-text-secondary: #a0aec0;
            --color-accent: #667eea;
            --color-accent-light: #764ba2;
            --color-glow: rgba(102, 126, 234, 0.3);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', 'Oxygen', 'Ubuntu', 'Cantarell', sans-serif;
            background: linear-gradient(135deg, var(--color-bg-primary) 0%, var(--color-bg-secondary) 100%);
            color: var(--color-text-primary);
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 20px;
            overflow-x: hidden;
        }

        .container {
            max-width: 900px;
            width: 100%;
            position: relative;
            z-index: 1;
        }

        .background-decoration {
            position: fixed;
            width: 500px;
            height: 500px;
            border-radius: 50%;
            background: radial-gradient(circle, var(--color-glow) 0%, transparent 70%);
            pointer-events: none;
            z-index: 0;
        }

        .decoration-1 {
            top: -250px;
            right: -250px;
            animation: float 20s ease-in-out infinite;
        }

        .decoration-2 {
            bottom: -250px;
            left: -250px;
            animation: float 25s ease-in-out infinite reverse;
        }

        @keyframes float {
            0%, 100% { transform: translate(0, 0) scale(1); }
            33% { transform: translate(50px, -50px) scale(1.1); }
            66% { transform: translate(-50px, 50px) scale(0.9); }
        }

        header {
            text-align: center;
            margin-bottom: 60px;
            animation: fadeInDown 1s ease-out;
        }

        @keyframes fadeInDown {
            from {
                opacity: 0;
                transform: translateY(-30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        h1 {
            font-size: 3.5rem;
            font-weight: 700;
            background: linear-gradient(135deg, var(--color-accent) 0%, var(--color-accent-light) 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            margin-bottom: 10px;
            letter-spacing: -1px;
        }

        .tagline {
            font-size: 1.2rem;
            color: var(--color-text-secondary);
            font-weight: 300;
            margin-top: 10px;
        }

        .birth-info {
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 20px;
            padding: 30px;
            margin-bottom: 40px;
            animation: fadeInUp 1s ease-out 0.2s both;
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .birth-details {
            display: flex;
            justify-content: center;
            gap: 40px;
            flex-wrap: wrap;
            margin-bottom: 20px;
        }

        .birth-detail {
            text-align: center;
        }

        .birth-label {
            font-size: 0.85rem;
            color: var(--color-text-secondary);
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-bottom: 8px;
        }

        .birth-value {
            font-size: 1.5rem;
            font-weight: 600;
            color: var(--color-accent);
        }

        .age-counter {
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 20px;
            padding: 40px 30px;
            margin-bottom: 40px;
            animation: fadeInUp 1s ease-out 0.4s both;
        }

        .counter-title {
            text-align: center;
            font-size: 1.3rem;
            margin-bottom: 30px;
            color: var(--color-text-secondary);
            font-weight: 300;
        }

        .time-units {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
            gap: 20px;
        }

        .time-unit {
            text-align: center;
            padding: 20px;
            background: rgba(102, 126, 234, 0.1);
            border-radius: 15px;
            border: 1px solid rgba(102, 126, 234, 0.2);
            transition: all 0.3s ease;
        }

        .time-unit:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 30px rgba(102, 126, 234, 0.2);
        }

        .time-value {
            font-size: 2.5rem;
            font-weight: 700;
            color: var(--color-text-primary);
            display: block;
            margin-bottom: 5px;
            font-variant-numeric: tabular-nums;
        }

        .time-label {
            font-size: 0.85rem;
            color: var(--color-text-secondary);
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .quote-section {
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 20px;
            padding: 40px;
            text-align: center;
            animation: fadeInUp 1s ease-out 0.6s both;
            margin-bottom: 40px;
        }

        .quote-text {
            font-size: 1.3rem;
            line-height: 1.8;
            color: var(--color-text-primary);
            font-weight: 300;
            font-style: italic;
            margin-bottom: 20px;
        }

        .quote-author {
            font-size: 1rem;
            color: var(--color-accent);
            font-weight: 500;
        }

        .message-cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-bottom: 40px;
            animation: fadeInUp 1s ease-out 0.8s both;
        }

        .message-card {
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 15px;
            padding: 25px;
            transition: all 0.3s ease;
        }

        .message-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 30px rgba(102, 126, 234, 0.15);
            border-color: var(--color-accent);
        }

        .message-icon {
            font-size: 2rem;
            margin-bottom: 15px;
        }

        .message-title {
            font-size: 1.1rem;
            font-weight: 600;
            margin-bottom: 10px;
            color: var(--color-accent);
        }

        .message-text {
            font-size: 0.95rem;
            line-height: 1.6;
            color: var(--color-text-secondary);
        }

        footer {
            text-align: center;
            padding: 30px 0;
            color: var(--color-text-secondary);
            font-size: 0.9rem;
            animation: fadeInUp 1s ease-out 1s both;
        }

        .footer-heart {
            color: #e74c3c;
            animation: heartbeat 1.5s ease-in-out infinite;
        }

        @keyframes heartbeat {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.1); }
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 2.5rem;
            }

            .tagline {
                font-size: 1rem;
            }

            .birth-details {
                gap: 20px;
            }

            .time-units {
                grid-template-columns: repeat(2, 1fr);
            }

            .time-value {
                font-size: 2rem;
            }

            .quote-text {
                font-size: 1.1rem;
            }

            .message-cards {
                grid-template-columns: 1fr;
            }
        }

        @media (max-width: 480px) {
            h1 {
                font-size: 2rem;
            }

            .birth-info, .age-counter, .quote-section, .message-card {
                padding: 20px;
            }

            .time-value {
                font-size: 1.8rem;
            }
        }
    </style>
</head>
<body>
    <div class="background-decoration decoration-1"></div>
    <div class="background-decoration decoration-2"></div>

    <div class="container">
        <header>
            <h1>M Furqan Asif</h1>
            <p class="tagline">Every moment is a new beginning</p>
        </header>

        <section class="birth-info">
            <div class="birth-details">
                <div class="birth-detail">
                    <div class="birth-label">Date of Birth</div>
                    <div class="birth-value">4 March 2007</div>
                </div>
                <div class="birth-detail">
                    <div class="birth-label">Time of Birth</div>
                    <div class="birth-value">5:00 AM</div>
                </div>
            </div>
        </section>

        <section class="age-counter">
            <h2 class="counter-title">My Journey Through Time</h2>
            <div class="time-units">
                <div class="time-unit">
                    <span class="time-value" id="years">0</span>
                    <span class="time-label">Years</span>
                </div>
                <div class="time-unit">
                    <span class="time-value" id="months">0</span>
                    <span class="time-label">Months</span>
                </div>
                <div class="time-unit">
                    <span class="time-value" id="days">0</span>
                    <span class="time-label">Days</span>
                </div>
                <div class="time-unit">
                    <span class="time-value" id="hours">0</span>
                    <span class="time-label">Hours</span>
                </div>
                <div class="time-unit">
                    <span class="time-value" id="minutes">0</span>
                    <span class="time-label">Minutes</span>
                </div>
                <div class="time-unit">
                    <span class="time-value" id="seconds">0</span>
                    <span class="time-label">Seconds</span>
                </div>
            </div>
        </section>

        <section class="quote-section">
            <p class="quote-text">"The purpose of life is not to be happy. It is to be useful, to be honorable, to be compassionate, to have it make some difference that you have lived and lived well."</p>
            <p class="quote-author">— Ralph Waldo Emerson</p>
        </section>

        <section class="message-cards">
            <div class="message-card">
                <div class="message-icon">🌱</div>
                <h3 class="message-title">Growth</h3>
                <p class="message-text">Every second that passes is a moment of growth, learning, and becoming a better version of yourself.</p>
            </div>
            <div class="message-card">
                <div class="message-icon">✨</div>
                <h3 class="message-title">Moments</h3>
                <p class="message-text">Life isn't measured by the breaths we take, but by the moments that take our breath away.</p>
            </div>
            <div class="message-card">
                <div class="message-icon">🎯</div>
                <h3 class="message-title">Purpose</h3>
                <p class="message-text">Each day brings new opportunities to make a positive impact and pursue your dreams with passion.</p>
            </div>
        </section>

        <footer>
            <p>Made with <span class="footer-heart">♥</span> by M Furqan Asif</p>
            <p style="margin-top: 10px; font-size: 0.85rem;">Born on 4 March 2007 • Growing every second</p>
        </footer>
    </div>

    <script>
        // Birth date and time: 4 March 2007, 5:00 AM
        const birthDate = new Date(2007, 2, 4, 5, 0, 0); // Months are 0-indexed in JavaScript

        function updateAge() {
            const now = new Date();
            const diff = now - birthDate;

            // Calculate total time units
            const totalSeconds = Math.floor(diff / 1000);
            const totalMinutes = Math.floor(totalSeconds / 60);
            const totalHours = Math.floor(totalMinutes / 60);
            const totalDays = Math.floor(totalHours / 24);

            // Calculate years and remaining days
            let years = now.getFullYear() - birthDate.getFullYear();
            let months = now.getMonth() - birthDate.getMonth();
            let days = now.getDate() - birthDate.getDate();
            let hours = now.getHours() - birthDate.getHours();
            let minutes = now.getMinutes() - birthDate.getMinutes();
            let seconds = now.getSeconds() - birthDate.getSeconds();

            // Adjust for negative values
            if (seconds < 0) {
                seconds += 60;
                minutes--;
            }
            if (minutes < 0) {
                minutes += 60;
                hours--;
            }
            if (hours < 0) {
                hours += 24;
                days--;
            }
            if (days < 0) {
                // Get days in previous month
                const prevMonth = new Date(now.getFullYear(), now.getMonth(), 0);
                days += prevMonth.getDate();
                months--;
            }
            if (months < 0) {
                months += 12;
                years--;
            }

            // Update DOM
            document.getElementById('years').textContent = years;
            document.getElementById('months').textContent = months;
            document.getElementById('days').textContent = days;
            document.getElementById('hours').textContent = hours;
            document.getElementById('minutes').textContent = minutes;
            document.getElementById('seconds').textContent = seconds;
        }

        // Update immediately and then every second
        updateAge();
        setInterval(updateAge, 1000);

        // Add smooth scroll behavior
        document.documentElement.style.scrollBehavior = 'smooth';
    </script>
</body>
</html>

…]()


















[M Furqan Asif (1).zip](https://github.com/user-attachments/files/25216622/M.Furqan.Asif.1.zip)

file:///C:/Users/shafi%20laptop/Downloads/Year%20Progress%20Tracker%20(6).html
[index.html.zip](https://github.com/user-attachments/files/25216154/index.html.zip)
[Year Progress Tracker (6).html](https://github.com/user-attachments/files/25216381/Year.Progress.Tracker.6.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Year Progress Tracker - Time Waits For No One</title>
    <style>
        :root {
            --color-bg-primary: #0a0a0f;
            --color-bg-secondary: #13131a;
            --color-bg-card: #1a1a24;
            --color-text-primary: #f1f5f9;
            --color-text-secondary: #94a3b8;
            --color-accent: #38bdf8;
            --color-accent-glow: rgba(56, 189, 248, 0.3);
            --color-success: #22c55e;
            --color-warning: #f59e0b;
            --color-purple: #a78bfa;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', 'Oxygen', sans-serif;
            background: linear-gradient(135deg, var(--color-bg-primary) 0%, #0f0f1a 100%);
            color: var(--color-text-primary);
            min-height: 100vh;
            overflow-x: hidden;
        }

        .stars {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 0;
        }

        .background-logo {
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            font-size: 6rem;
            font-weight: 900;
            color: rgba(56, 189, 248, 0.05);
            pointer-events: none;
            z-index: 0;
            user-select: none;
            letter-spacing: 0.1em;
            font-family: 'Segoe UI', 'Roboto', sans-serif;
            text-transform: uppercase;
        }

        .star {
            position: absolute;
            width: 2px;
            height: 2px;
            background: white;
            border-radius: 50%;
            opacity: 0.3;
            animation: twinkle 3s infinite;
        }

        @keyframes twinkle {
            0%, 100% { opacity: 0.3; }
            50% { opacity: 0.8; }
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            position: relative;
            z-index: 1;
        }

        header {
            text-align: center;
            padding: 40px 20px;
            margin-bottom: 40px;
        }

        .dedication {
            text-align: center;
            font-size: 1rem;
            color: var(--color-text-secondary);
            margin-bottom: 30px;
            font-style: italic;
            opacity: 0.8;
        }

        h1 {
            font-size: 3rem;
            font-weight: 800;
            background: linear-gradient(135deg, var(--color-accent) 0%, var(--color-purple) 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            margin-bottom: 10px;
            text-shadow: 0 0 30px var(--color-accent-glow);
        }

        .tagline {
            font-size: 1.1rem;
            color: var(--color-text-secondary);
            font-weight: 400;
            margin-top: 10px;
        }

        .main-stats {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
            margin-bottom: 50px;
        }

        .stat-card {
            background: var(--color-bg-card);
            border-radius: 20px;
            padding: 30px;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.4);
            border: 1px solid rgba(56, 189, 248, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .stat-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 50px rgba(56, 189, 248, 0.2);
        }

        .stat-label {
            font-size: 0.9rem;
            color: var(--color-text-secondary);
            text-transform: uppercase;
            letter-spacing: 1.5px;
            margin-bottom: 15px;
            font-weight: 600;
        }

        .stat-value {
            font-size: 3.5rem;
            font-weight: 800;
            color: var(--color-accent);
            line-height: 1;
            margin-bottom: 10px;
        }

        .stat-subtext {
            font-size: 0.95rem;
            color: var(--color-text-secondary);
            margin-top: 10px;
        }

        .progress-section {
            background: var(--color-bg-card);
            border-radius: 20px;
            padding: 40px;
            margin-bottom: 50px;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.4);
            border: 1px solid rgba(56, 189, 248, 0.1);
        }

        .progress-header {
            text-align: center;
            margin-bottom: 40px;
        }

        .progress-header h2 {
            font-size: 2rem;
            margin-bottom: 10px;
            color: var(--color-text-primary);
        }

        .progress-percentage {
            font-size: 4rem;
            font-weight: 800;
            background: linear-gradient(135deg, var(--color-success) 0%, var(--color-accent) 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .progress-bar-container {
            position: relative;
            width: 100%;
            height: 30px;
            background: var(--color-bg-secondary);
            border-radius: 15px;
            overflow: hidden;
            margin: 30px 0;
            box-shadow: inset 0 2px 10px rgba(0, 0, 0, 0.3);
        }

        .progress-bar {
            height: 100%;
            background: linear-gradient(90deg, var(--color-success) 0%, var(--color-accent) 100%);
            border-radius: 15px;
            transition: width 1s ease-in-out;
            box-shadow: 0 0 20px var(--color-accent-glow);
            position: relative;
            overflow: hidden;
        }

        .progress-bar::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.3), transparent);
            animation: shimmer 2s infinite;
        }

        @keyframes shimmer {
            0% { left: -100%; }
            100% { left: 100%; }
        }

        .circular-progress {
            display: flex;
            justify-content: center;
            align-items: center;
            margin: 40px 0;
        }

        .circle-container {
            position: relative;
            width: 200px;
            height: 200px;
        }

        .circle-bg, .circle-progress {
            fill: none;
            stroke-width: 12;
            transform: rotate(-90deg);
            transform-origin: 50% 50%;
        }

        .circle-bg {
            stroke: var(--color-bg-secondary);
        }

        .circle-progress {
            stroke: url(#gradient);
            stroke-linecap: round;
            transition: stroke-dashoffset 1s ease-in-out;
        }

        .circle-text {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            text-align: center;
        }

        .circle-percentage {
            font-size: 2.5rem;
            font-weight: 800;
            color: var(--color-accent);
        }

        .circle-label {
            font-size: 0.85rem;
            color: var(--color-text-secondary);
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .motivation-section {
            background: var(--color-bg-card);
            border-radius: 20px;
            padding: 40px;
            margin-bottom: 50px;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.4);
            border: 1px solid rgba(167, 139, 250, 0.2);
            text-align: center;
        }

        .motivation-icon {
            font-size: 3rem;
            margin-bottom: 20px;
        }

        .motivation-quote {
            font-size: 1.5rem;
            font-weight: 600;
            line-height: 1.6;
            color: var(--color-text-primary);
            margin-bottom: 15px;
            font-style: italic;
        }

        .motivation-author {
            font-size: 1rem;
            color: var(--color-text-secondary);
        }

        .sidhu-section {
            background: linear-gradient(135deg, #1e1b4b 0%, #312e81 100%);
            border-radius: 20px;
            padding: 50px;
            margin-bottom: 50px;
            box-shadow: 0 20px 60px rgba(167, 139, 250, 0.3);
            border: 2px solid rgba(167, 139, 250, 0.3);
            position: relative;
            overflow: hidden;
        }

        .sidhu-section::before {
            content: '';
            position: absolute;
            top: -50%;
            right: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(167, 139, 250, 0.1) 0%, transparent 70%);
            animation: rotate 20s linear infinite;
        }

        @keyframes rotate {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }

        .sidhu-content {
            position: relative;
            z-index: 1;
        }

        .sidhu-header {
            text-align: center;
            margin-bottom: 40px;
        }

        .sidhu-image-container {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-bottom: 30px;
            flex-wrap: wrap;
        }

        .sidhu-image {
            width: 180px;
            height: 180px;
            border-radius: 15px;
            object-fit: cover;
            border: 3px solid var(--color-purple);
            box-shadow: 0 10px 30px rgba(167, 139, 250, 0.4);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .sidhu-image:hover {
            transform: scale(1.05);
            box-shadow: 0 15px 40px rgba(167, 139, 250, 0.6);
        }

        .sidhu-title {
            font-size: 2.5rem;
            font-weight: 800;
            color: var(--color-purple);
            margin-bottom: 15px;
            text-shadow: 0 0 20px rgba(167, 139, 250, 0.5);
        }

        .sidhu-subtitle {
            font-size: 1.1rem;
            color: #cbd5e1;
            font-style: italic;
        }

        .sidhu-quotes {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
            margin-top: 30px;
        }

        .sidhu-quote-card {
            background: rgba(30, 27, 75, 0.6);
            border-radius: 15px;
            padding: 25px;
            border: 1px solid rgba(167, 139, 250, 0.3);
            backdrop-filter: blur(10px);
            transition: transform 0.3s ease;
        }

        .sidhu-quote-card:hover {
            transform: translateY(-5px);
            border-color: var(--color-purple);
        }

        .sidhu-quote-text {
            font-size: 1.1rem;
            line-height: 1.7;
            color: #e2e8f0;
            font-weight: 500;
            margin-bottom: 15px;
        }

        .sidhu-quote-icon {
            font-size: 2rem;
            color: var(--color-purple);
            margin-bottom: 15px;
        }

        .current-date-section {
            background: var(--color-bg-card);
            border-radius: 20px;
            padding: 30px;
            text-align: center;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.4);
            border: 1px solid rgba(56, 189, 248, 0.1);
        }

        .current-date {
            font-size: 1.8rem;
            color: var(--color-text-primary);
            margin-bottom: 10px;
        }

        .current-time {
            font-size: 2.5rem;
            font-weight: 700;
            color: var(--color-accent);
            font-variant-numeric: tabular-nums;
        }

        footer {
            text-align: center;
            padding: 40px 20px;
            color: var(--color-text-secondary);
            font-size: 0.9rem;
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 2rem;
            }

            .stat-value {
                font-size: 2.5rem;
            }

            .progress-percentage {
                font-size: 3rem;
            }

            .motivation-quote {
                font-size: 1.2rem;
            }

            .sidhu-title {
                font-size: 1.8rem;
            }

            .sidhu-section {
                padding: 30px 20px;
            }

            .progress-section {
                padding: 30px 20px;
            }
        }
    </style>
</head>
<body>
    <div class="stars" id="stars"></div>
    <div class="background-logo">FURQAN</div>
    
    <div class="container">
        <p class="dedication">This motivation for you, Furqan</p>
        <header>
            <h1>Year Progress Tracker 2026</h1>
            <p class="tagline">Every moment counts. Make today matter.</p>
        </header>

        <div class="main-stats">
            <div class="stat-card">
                <div class="stat-label">Days Passed</div>
                <div class="stat-value" id="daysPassed">0</div>
                <div class="stat-subtext">Days into the year</div>
            </div>

            <div class="stat-card">
                <div class="stat-label">Days Remaining</div>
                <div class="stat-value" id="daysRemaining">0</div>
                <div class="stat-subtext">Days left to make an impact</div>
            </div>

            <div class="stat-card">
                <div class="stat-label">Total Days</div>
                <div class="stat-value" id="totalDays">365</div>
                <div class="stat-subtext" id="leapYearText">Regular year</div>
            </div>
        </div>

        <div class="progress-section">
            <div class="progress-header">
                <h2>Year Completion</h2>
                <div class="progress-percentage" id="progressPercentage">0%</div>
            </div>

            <div class="progress-bar-container">
                <div class="progress-bar" id="progressBar" style="width: 0%"></div>
            </div>

            <div class="circular-progress">
                <div class="circle-container">
                    <svg width="200" height="200">
                        <defs>
                            <linearGradient id="gradient" x1="0%" y1="0%" x2="100%" y2="100%">
                                <stop offset="0%" style="stop-color:#22c55e;stop-opacity:1" />
                                <stop offset="100%" style="stop-color:#38bdf8;stop-opacity:1" />
                            </linearGradient>
                        </defs>
                        <circle class="circle-bg" cx="100" cy="100" r="85"></circle>
                        <circle class="circle-progress" cx="100" cy="100" r="85" id="circleProgress"></circle>
                    </svg>
                    <div class="circle-text">
                        <div class="circle-percentage" id="circlePercentage">0%</div>
                        <div class="circle-label">Complete</div>
                    </div>
                </div>
            </div>
        </div>

        <div class="motivation-section">
            <div class="motivation-icon" id="motivationIcon">⚡</div>
            <div class="motivation-quote" id="motivationQuote">Loading inspiration...</div>
            <div class="motivation-author" id="motivationAuthor"></div>
        </div>

        <div class="sidhu-section">
            <div class="sidhu-content">
                <div class="sidhu-header">
                    <h2 class="sidhu-title">Legends Never Die</h2>
                    <p class="sidhu-subtitle">Inspired by the mindset of Sidhu Moose Wala</p>
                    <div class="sidhu-image-container">
                        <img src="https://agi-prod-file-upload-public-main-use1.s3.amazonaws.com/00d95e47-ee8e-489f-ad4c-a5b233b843ad" alt="Sidhu Moose Wala" class="sidhu-image">
                    </div>
                </div>

                <div class="sidhu-quotes">
                    <div class="sidhu-quote-card">
                        <div class="sidhu-quote-icon">🔥</div>
                        <div class="sidhu-quote-text">"Success is not final, failure is not fatal: it is the courage to continue that counts."</div>
                    </div>

                    <div class="sidhu-quote-card">
                        <div class="sidhu-quote-icon">💪</div>
                        <div class="sidhu-quote-text">"Always keep moving forward in life, never stop. To make an identity, hard work is necessary."</div>
                    </div>

                    <div class="sidhu-quote-card">
                        <div class="sidhu-quote-icon">👑</div>
                        <div class="sidhu-quote-text">"Keep faith in yourself, never turn back. The success achieved after a struggle is a different game altogether."</div>
                    </div>

                    <div class="sidhu-quote-card">
                        <div class="sidhu-quote-icon">⭐</div>
                        <div class="sidhu-quote-text">"In life, don't imitate someone else, create your own color. Those with a big mindset have a big world."</div>
                    </div>

                    <div class="sidhu-quote-card">
                        <div class="sidhu-quote-icon">💎</div>
                        <div class="sidhu-quote-text">"When you want to achieve something big in life, hard work is necessary. Those who chose the short paths in life, never reached big destinations."</div>
                    </div>

                    <div class="sidhu-quote-card">
                        <div class="sidhu-quote-icon">🎯</div>
                        <div class="sidhu-quote-text">"Obstacles will come in the path of success, but overcoming them is the real victory."</div>
                    </div>
                </div>
            </div>
        </div>

        <div class="current-date-section">
            <div class="current-date" id="currentDate">Loading...</div>
            <div class="current-time" id="currentTime">00:00:00</div>
        </div>

        <footer>
            <p>&copy; 2026 Year Progress Tracker | Time waits for no one</p>
        </footer>
    </div>

    <script>
        // Create star background
        function createStars() {
            const starsContainer = document.getElementById('stars');
            const numStars = 100;
            
            for (let i = 0; i < numStars; i++) {
                const star = document.createElement('div');
                star.className = 'star';
                star.style.left = Math.random() * 100 + '%';
                star.style.top = Math.random() * 100 + '%';
                star.style.animationDelay = Math.random() * 3 + 's';
                starsContainer.appendChild(star);
            }
        }

        // Check if year is leap year
        function isLeapYear(year) {
            return (year % 4 === 0 && year % 100 !== 0) || (year % 400 === 0);
        }

        // Calculate year progress
        function calculateYearProgress() {
            const now = new Date();
            const currentYear = now.getFullYear();
            const startOfYear = new Date(currentYear, 0, 1);
            const endOfYear = new Date(currentYear, 11, 31, 23, 59, 59, 999);
            
            const totalDaysInYear = isLeapYear(currentYear) ? 366 : 365;
            const millisecondsInDay = 1000 * 60 * 60 * 24;
            
            const daysPassed = Math.floor((now - startOfYear) / millisecondsInDay) + 1;
            const daysRemaining = totalDaysInYear - daysPassed;
            const progressPercentage = ((daysPassed / totalDaysInYear) * 100).toFixed(2);
            
            return {
                currentYear,
                totalDaysInYear,
                daysPassed,
                daysRemaining,
                progressPercentage,
                isLeap: isLeapYear(currentYear)
            };
        }

        // Update UI with calculations
        function updateUI() {
            const progress = calculateYearProgress();
            
            document.getElementById('daysPassed').textContent = progress.daysPassed;
            document.getElementById('daysRemaining').textContent = progress.daysRemaining;
            document.getElementById('totalDays').textContent = progress.totalDaysInYear;
            document.getElementById('leapYearText').textContent = progress.isLeap ? 'Leap year' : 'Regular year';
            
            document.getElementById('progressPercentage').textContent = progress.progressPercentage + '%';
            document.getElementById('circlePercentage').textContent = Math.round(progress.progressPercentage) + '%';
            
            document.getElementById('progressBar').style.width = progress.progressPercentage + '%';
            
            const circumference = 2 * Math.PI * 85;
            const offset = circumference - (progress.progressPercentage / 100) * circumference;
            const circleProgress = document.getElementById('circleProgress');
            circleProgress.style.strokeDasharray = circumference;
            circleProgress.style.strokeDashoffset = offset;
            
            updateDateTime();
        }

        // Update current date and time
        function updateDateTime() {
            const now = new Date();
            const options = { weekday: 'long', year: 'numeric', month: 'long', day: 'numeric' };
            const dateString = now.toLocaleDateString('en-US', options);
            
            document.getElementById('currentDate').textContent = dateString;
            
            const hours = String(now.getHours()).padStart(2, '0');
            const minutes = String(now.getMinutes()).padStart(2, '0');
            const seconds = String(now.getSeconds()).padStart(2, '0');
            document.getElementById('currentTime').textContent = `${hours}:${minutes}:${seconds}`;
        }

        // Motivational quotes rotation
        const motivationalQuotes = [
            {
                quote: "Time is passing — what you do today matters.",
                author: "",
                icon: "⚡"
            },
            {
                quote: "These remaining days can still change everything.",
                author: "",
                icon: "🌟"
            },
            {
                quote: "Don't watch the clock; do what it does. Keep going.",
                author: "Sam Levenson",
                icon: "⏰"
            },
            {
                quote: "The time for action is now. It's never too late to do something.",
                author: "Antoine de Saint-Exupéry",
                icon: "🚀"
            },
            {
                quote: "Yesterday's the past, tomorrow's the future, but today is a gift.",
                author: "Bil Keane",
                icon: "🎁"
            },
            {
                quote: "You may delay, but time will not.",
                author: "Benjamin Franklin",
                icon: "⏳"
            },
            {
                quote: "The future depends on what you do today.",
                author: "Mahatma Gandhi",
                icon: "🌅"
            },
            {
                quote: "Time flies. It's up to you to be the navigator.",
                author: "Robert Orben",
                icon: "✈️"
            },
            {
                quote: "Never give up on a dream just because of the time it will take to accomplish it. The time will pass anyway.",
                author: "Earl Nightingale",
                icon: "💫"
            },
            {
                quote: "Your time is limited, don't waste it living someone else's life.",
                author: "Steve Jobs",
                icon: "🎯"
            }
        ];

        let currentQuoteIndex = 0;

        function updateMotivationalQuote() {
            const quote = motivationalQuotes[currentQuoteIndex];
            document.getElementById('motivationQuote').textContent = quote.quote;
            document.getElementById('motivationAuthor').textContent = quote.author ? `— ${quote.author}` : '';
            document.getElementById('motivationIcon').textContent = quote.icon;
            
            currentQuoteIndex = (currentQuoteIndex + 1) % motivationalQuotes.length;
        }

        // Initialize
        createStars();
        updateUI();
        updateMotivationalQuote();

        // Update time every second
        setInterval(updateDateTime, 1000);

        // Update progress every hour
        setInterval(updateUI, 3600000);

        // Rotate quotes every 10 seconds
        setInterval(updateMotivationalQuote, 10000);

        // Update progress at midnight
        const now = new Date();
        const tomorrow = new Date(now.getFullYear(), now.getMonth(), now.getDate() + 1, 0, 0, 1);
        const timeUntilMidnight = tomorrow - now;
        setTimeout(() => {
            updateUI();
            setInterval(updateUI, 86400000); // Daily updates
        }, timeUntilMidnight);
    </script>
</body>
</html>
