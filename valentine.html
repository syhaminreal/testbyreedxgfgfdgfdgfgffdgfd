<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Will You Be My Valentine?</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: linear-gradient(135deg, #ff9a9e 0%, #fecfef 50%, #fecfef 100%);
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            overflow: hidden;
            position: relative;
        }

        .container {
            text-align: center;
            padding: 2rem;
            max-width: 90%;
            z-index: 10;
        }

        .headline {
            font-size: clamp(1.5rem, 5vw, 2.5rem);
            color: #e91e63;
            margin-bottom: 1rem;
            opacity: 0;
            animation: fadeInUp 1s ease forwards;
        }

        .question {
            font-size: clamp(2rem, 8vw, 3.5rem);
            color: #c2185b;
            margin-bottom: 3rem;
            opacity: 0;
            animation: fadeInUp 1s ease 0.5s forwards;
            font-weight: bold;
        }

        .buttons {
            display: flex;
            gap: 2rem;
            justify-content: center;
            flex-wrap: wrap;
            opacity: 0;
            animation: fadeInUp 1s ease 1s forwards;
        }

        .btn {
            padding: 1rem 3rem;
            font-size: 1.3rem;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.3s ease;
            font-weight: bold;
            position: relative;
            overflow: hidden;
        }

        .btn-yes {
            background: linear-gradient(135deg, #e91e63, #f06292);
            color: white;
            box-shadow: 0 4px 15px rgba(233, 30, 99, 0.4);
        }

        .btn-yes:hover {
            transform: scale(1.05);
            box-shadow: 0 6px 20px rgba(233, 30, 99, 0.6);
        }

        .btn-no {
            background: linear-gradient(135deg, #9c27b0, #ba68c8);
            color: white;
            box-shadow: 0 4px 15px rgba(156, 39, 176, 0.4);
        }

        .btn-no:hover {
            transform: scale(1.05);
            box-shadow: 0 6px 20px rgba(156, 39, 176, 0.6);
        }

        .success-message {
            display: none;
            text-align: center;
        }

        .success-message h2 {
            font-size: clamp(1.8rem, 6vw, 3rem);
            color: #e91e63;
            margin-bottom: 1rem;
            animation: pulse 1s ease infinite;
        }

        .success-message p {
            font-size: clamp(1.2rem, 4vw, 1.8rem);
            color: #c2185b;
        }

        .heart {
            position: absolute;
            font-size: 2rem;
            animation: float 6s ease-in-out infinite;
            opacity: 0.7;
            pointer-events: none;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0) rotate(0deg); }
            50% { transform: translateY(-20px) rotate(10deg); }
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

        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.05); }
        }

        @keyframes celebrate {
            0% { transform: scale(0) rotate(0deg); opacity: 1; }
            100% { transform: scale(1.5) rotate(360deg); opacity: 0; }
        }

        .confetti {
            position: fixed;
            width: 10px;
            height: 10px;
            pointer-events: none;
            animation: confetti-fall 3s ease-out forwards;
        }

        @keyframes confetti-fall {
            0% {
                transform: translateY(-100vh) rotate(0deg);
                opacity: 1;
            }
            100% {
                transform: translateY(100vh) rotate(720deg);
                opacity: 0;
            }
        }

        .flying-heart {
            position: fixed;
            font-size: 2rem;
            pointer-events: none;
            animation: flyHeart 2s ease-out forwards;
        }

        @keyframes flyHeart {
            0% {
                opacity: 1;
                transform: scale(1);
            }
            100% {
                opacity: 0;
                transform: scale(0) translateY(-100px);
            }
        }

        .proposal-container {
            display: block;
        }

        .proposal-container.hidden {
            display: none;
        }

        @media (max-width: 480px) {
            .buttons {
                gap: 1rem;
            }
            
            .btn {
                padding: 0.8rem 2rem;
                font-size: 1.1rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="proposal-container" id="proposal">
            <h1 class="headline">Hey M.J... I have something important to ask you ❤️</h1>
            <h2 class="question">Will you be my Valentine?</h2>
            <div class="buttons">
                <button class="btn btn-yes" id="yesBtn">YES ❤️</button>
                <button class="btn btn-no" id="noBtn">NO</button>
            </div>
        </div>
        
        <div class="success-message" id="success">
            <h2>I knew you'd say yes! ❤️</h2>
            <p>Can't wait for our memories together.</p>
        </div>
    </div>

    <script>
        // Create floating hearts
        function createHearts() {
            const heartSymbols = ['❤️', '💕', '💗', '💖', '💓'];
            for (let i = 0; i < 20; i++) {
                const heart = document.createElement('div');
                heart.className = 'heart';
                heart.innerHTML = heartSymbols[Math.floor(Math.random() * heartSymbols.length)];
                heart.style.left = Math.random() * 100 + 'vw';
                heart.style.top = Math.random() * 100 + 'vh';
                heart.style.animationDelay = Math.random() * 5 + 's';
                heart.style.animationDuration = (Math.random() * 3 + 4) + 's';
                document.body.appendChild(heart);
            }
        }

        // Create confetti
        function createConfetti() {
            const colors = ['#e91e63', '#f06292', '#9c27b0', '#ba68c8', '#ff5722', '#ff9800'];
            for (let i = 0; i < 100; i++) {
                setTimeout(() => {
                    const confetti = document.createElement('div');
                    confetti.className = 'confetti';
                    confetti.style.left = Math.random() * 100 + 'vw';
                    confetti.style.backgroundColor = colors[Math.floor(Math.random() * colors.length)];
                    confetti.style.borderRadius = Math.random() > 0.5 ? '50%' : '0';
                    confetti.style.width = (Math.random() * 10 + 5) + 'px';
                    confetti.style.height = confetti.style.width;
                    document.body.appendChild(confetti);
                    
                    setTimeout(() => confetti.remove(), 3000);
                }, i * 30);
            }
        }

        // Create flying hearts on YES click
        function createFlyingHearts() {
            const heartSymbols = ['❤️', '💕', '💗', '💖', '💓'];
            for (let i = 0; i < 50; i++) {
                setTimeout(() => {
                    const heart = document.createElement('div');
                    heart.className = 'flying-heart';
                    heart.innerHTML = heartSymbols[Math.floor(Math.random() * heartSymbols.length)];
                    heart.style.left = Math.random() * 100 + 'vw';
                    heart.style.top = Math.random() * 100 + 'vh';
                    document.body.appendChild(heart);
                    
                    setTimeout(() => heart.remove(), 2000);
                }, i * 50);
            }
        }

        // YES button handler
        document.getElementById('yesBtn').addEventListener('click', function() {
            document.getElementById('proposal').classList.add('hidden');
            document.getElementById('success').style.display = 'block';
            createConfetti();
            createFlyingHearts();
        });

        // NO button dodge functionality
        const noBtn = document.getElementById('noBtn');
        let isAnimating = false;

        function moveButton(e) {
            if (isAnimating) return;
            
            const btn = noBtn;
            const rect = btn.getBoundingClientRect();
            const x = e.clientX || e.touches[0].clientX;
            const y = e.clientY || e.touches[0].clientY;
            
            // Check if mouse/touch is near button
            const distanceX = Math.abs(x - (rect.left + rect.width / 2));
            const distanceY = Math.abs(y - (rect.top + rect.height / 2));
            const threshold = 100;

            if (distanceX < threshold && distanceY < threshold) {
                isAnimating = true;
                
                // Calculate new position
                let newX, newY;
                const maxX = window.innerWidth - rect.width - 40;
                const maxY = window.innerHeight - rect.height - 40;
                
                do {
                    newX = Math.random() * maxX + 20;
                    newY = Math.random() * maxY + 20;
                } while (
                    Math.abs(newX - rect.left) < 150 &&
                    Math.abs(newY - rect.top) < 150
                );

                btn.style.position = 'fixed';
                btn.style.left = newX + 'px';
                btn.style.top = newY + 'px';
                btn.style.transition = 'all 0.3s ease';
                
                // Change button text randomly
                const texts = ["Try Again ❤️", "Think Again?", "Are You Sure?", "Don't Do This 💔", "Please?", "Reconsider ❤️"];
                btn.textContent = texts[Math.floor(Math.random() * texts.length)];
                
                setTimeout(() => {
                    isAnimating = false;
                }, 300);
            }
        }

        // Mouse move handler
        document.addEventListener('mousemove', moveButton);
        
        // Touch move handler for mobile
        document.addEventListener('touchmove', moveButton, { passive: true });

        // Initialize
        createHearts();
    </script>
</body>
</html>