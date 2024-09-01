<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A Special Message for You</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f5f5f5;
            overflow: hidden;
            font-family: 'Arial', sans-serif;
        }

        .hearts {
            position: absolute;
            width: 100%;
            height: 100%;
            overflow: hidden;
            z-index: -1;
        }

        .hearts::before,
        .hearts::after {
            content: '';
            position: absolute;
            width: 100%;
            height: 100%;
            background-image: url('https://www.pngkey.com/png/full/233-2332677_heart-outline-png-transparent-background.png');
            background-size: 50px 50px;
            background-repeat: repeat;
            opacity: 0.2;
        }

        .message-box {
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
            text-align: center;
            max-width: 600px;
            width: 80%;
        }

        .message-box h1 {
            color: #ff5a5f;
            font-size: 36px;
            margin-bottom: 20px;
        }

        .message-box p {
            font-size: 18px;
            color: #333;
            line-height: 1.6;
        }
    </style>
</head>
<body>
    <div class="hearts"></div>
    <div class="message-box">
        <h1>My Dearest [Her Name],</h1>
        <p>
            I wanted to take a moment to express just how much you mean to me. Every day with you feels like a dream come true, and I'm constantly amazed by your kindness, beauty, and strength. You are my inspiration, my confidante, and my greatest love. I can't wait to create more memories with you and continue this beautiful journey together.
        </p>
        <p>
            With all my love, <br>
            [Your Name]
        </p>
    </div>
</body>
</html>

