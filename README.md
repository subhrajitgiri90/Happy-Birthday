<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday Swagatika Dash!</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #ff9a9e, #fecfef);
            color: #333;
            text-align: center;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }
        .container {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
            background: rgba(255, 255, 255, 0.9);
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        h1 {
            font-size: 3em;
            color: #ff6b6b;
            margin-bottom: 20px;
        }
        p {
            font-size: 1.2em;
            line-height: 1.6;
        }
        .gift {
            font-size: 2em;
            margin: 20px 0;
            transition: transform 0.3s;
        }
        .gift:hover {
            transform: scale(1.1);
        }
        .confetti {
            position: absolute;
            width: 10px;
            height: 10px;
            background: #ffd700;
            animation: fall 3s linear infinite;
        }
        @keyframes fall {
            to {
                transform: translateY(100vh);
            }
        }
        img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            margin: 20px 0;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Happy Birthday, Swagatika Dash! 🎉</h1>
        <p>Dear Swagatika Dash, on this special day, I wanted to create something just for you. You're amazing, kind, and bring so much joy to everyone around you. Here's a little virtual gift to celebrate you!</p>
        <div class="gift">🎁 Your Gift: [Describe a personalized gift, e.g., "A promise of endless adventures" or link to a real gift]</div>
        <p>May this year bring you happiness, success, and all the wonderful things you deserve. Let's create new memories together!</p>
        <!-- Optional: Add an image here if you find one later, e.g., <img src="path/to/photo.jpg" alt="A birthday image" /> -->
        <p>With all my love,<br>[Your Name]</p>
    </div>

    <!-- Simple Confetti Animation -->
    <script>
        function createConfetti() {
            const confetti = document.createElement('div');
            confetti.className = 'confetti';
            confetti.style.left = Math.random() * 100 + 'vw';
            confetti.style.animationDelay = Math.random() * 3 + 's';
            document.body.appendChild(confetti);
            setTimeout(() => confetti.remove(), 3000);
        }
        setInterval(createConfetti, 200);
    </script>
</body>
</html>
