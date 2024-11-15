<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Keep Smiling</title>
    <style>
        body {
            background-color: black;
            color: white;
            font-family: 'Pixel', monospace;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            font-size: 48px;
        }
        @keyframes flicker {
            0%, 100% { opacity: 1; }
            50% { opacity: 0; }
        }
        .flicker {
            animation: flicker 3s infinite;
        }
    </style>
</head>
<body>
    <div class="flicker">KEEP SMILING.</div>
</body>
</html>
