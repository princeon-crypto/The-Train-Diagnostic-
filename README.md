# The-Train-Diagnostic-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>THE TRAIN Business Focus Diagnostic</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .container {
            max-width: 600px;
            background: white;
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            text-align: center;
            margin: 20px;
        }
        
        .train-icon {
            font-size: 4rem;
            margin-bottom: 20px;
            animation: moveRight 2s ease-in-out infinite alternate;
        }
        
        @keyframes moveRight {
            0% { transform: translateX(-10px); }
            100% { transform: translateX(10px); }
        }
        
        h1 {
            color: #2c3e50;
            margin-bottom: 10px;
            font-size: 2.5rem;
            font-weight: bold;
        }
        
        .subtitle {
            color: #7f8c8d;
            font-size: 1.2rem;
            margin-bottom: 30px;
        }
        
        .benefits {
            text-align: left;
            margin: 30px 0;
            background: #f8f9fa;
            padding: 25px;
            border-radius: 10px;
            border-left: 5px solid #667eea;
        }
        
        .benefits h3 {
            color: #2c3e50;
            margin-bottom: 15px;
        }
        
        .benefits ul {
            list-style: none;
        }
        
        .benefits li {
            margin: 10px 0;
            position: relative;
            padding-left: 25px;
        }
        
        .benefits li:before {
            content: '✅';
            position: absolute;
            left: 0;
        }
        
        .form-group {
            margin: 20px 0;
            text-align: left;
        }
        
        label {
            display: block;
            margin-bottom: 8px;
            font-weight: bold;
            color: #2c3e50;
        }
        
        input[type="email"], input[type="text"] {
            width: 100%;
            padding: 15px;
            border: 2px solid #e1e8ed;
            border-radius: 8px;
            font-size: 16px;
            transition: border-color 0.3s ease;
        }
        
        input[type="email"]:focus, input[type="text"]:focus {
            outline: none;
            border-color: #667eea;
            box-shadow: 0 0 0 3px rgba(102, 126, 234, 0.1);
        }
        
        .cta-button {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 18px 40px;
            border: none;
            border-radius: 50px;
            font-size: 18px;
            font-weight: bold;
            cursor: pointer;
            width: 100%;
            margin-top: 20px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px rgba(102, 126, 234, 0.3);
        }
        
        .coach-info {
            margin-top: 30px;
            padding-top: 20px;
            border-top: 1px solid #e1e8ed;
            color: #7f8c8d;
            font-size: 14px;
        }
        
        .trust-badges {
            display: flex;
            justify-content: space-around;
            margin: 20px 0;
            flex-wrap: wrap;
        }
        
        .badge {
            background: #667eea;
            color: white;
            padding: 8px 15px;
            border-radius: 20px;
            font-size: 12px;
            margin: 5px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="train-icon">🚂</div>
        
        <h1>THE TRAIN</h1>
        <p class="subtitle">Business Focus Diagnostic</p>
        
        <div class="benefits">
            <h3>Get Crystal Clear On Your Business in 15 Minutes</h3>
            <ul>
                <li>Discover exactly what's causing your business confusion</li>
                <li>Get your personalized clarity score</li>
                <li>Receive a 90-day action plan to focus your growth</li>
                <li>Learn the 3-pillar framework used by 100+ successful entrepreneurs</li>
                <li>Stop wasting time and money on scattered strategies</li>
            </ul>
        </div>
        
        <div class="trust-badges">
            <span class="badge">📈 100+ Businesses Helped</span>
            <span class="badge">⚡ 15-Min Diagnostic</span>
            <span class="badge">🎯 Instant Results</span>
        </div>
        
        <form action="YOUR_GOOGLE_FORM_URL_HERE" method="POST" target="_blank">
            <div class="form-group">
                <label for="firstName">First Name</label>
                <input type="text" name="entry.XXXXXXXXX" required placeholder="Enter your first name">
            </div>
            
            <div class="form-group">
                <label for="email">Email Address</label>
                <input type="email" name="entry.YYYYYYYYY" required placeholder="Enter your email address">
            </div>
            
            <button type="submit" class="cta-button">
                🚂 GET MY FREE DIAGNOSTIC NOW
            </button>
        </form>
        
        <div class="coach-info">
            <strong>Coach Prince Nwaribe</strong><br>
            Business Clarity Expert & Founder of THE TRAIN<br>
            <em>"Helping Business Owners Get From Confusion to Clarity to Cash"</em>
        </div>
    </div>
    
    <script>
        document.querySelector('form').addEventListener('submit', function() {
            setTimeout(function() {
                alert('Thanks! Check your email for THE TRAIN Business Focus Diagnostic. We\'ll be in touch soon!');
            }, 1000);
        });
    </script>
</body>
</html>
