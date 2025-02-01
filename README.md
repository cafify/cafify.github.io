# cafify.github.io
<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cafify - カフェイン認証</title>
    <style>
        /* Google Font for a Japanese-friendly style */
        @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@300;400;700&display=swap');

        /* General Styles */
        body {
            margin: 0;
            padding: 0;
            font-family: 'Noto Sans JP', sans-serif;
            background: url('https://source.unsplash.com/1600x900/?japan,cafe,tea') no-repeat center center/cover;
            color: #e6e6e6;
            text-align: center;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            backdrop-filter: blur(4px);
        }

        .container {
            max-width: 600px;
            padding: 30px;
            background: rgba(0, 51, 25, 0.8); /* Deep Green with transparency */
            border-radius: 12px;
            box-shadow: 0px 4px 15px rgba(0, 0, 0, 0.4);
            transition: transform 0.3s ease;
        }

        .container:hover {
            transform: scale(1.02);
        }

        h1 {
            font-size: 2rem;
            margin-bottom: 10px;
            color: #b7d4a8; /* Light green */
        }

        p {
            font-size: 1rem;
            line-height: 1.6;
            opacity: 0.9;
        }

        a {
            display: inline-block;
            margin-top: 15px;
            padding: 10px 20px;
            text-decoration: none;
            background: #b7d4a8;
            color: #003319;
            font-weight: bold;
            border-radius: 5px;
            transition: background 0.3s;
        }

        a:hover {
            background: #98c494;
        }

        /* Responsive Design */
        @media (max-width: 600px) {
            h1 {
                font-size: 1.8rem;
            }
            p {
                font-size: 0.9rem;
            }
            .container {
                width: 90%;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>CAFIFY</h1>
        <h1>カフェイン認証</h1>
        <p>日本初のカフェイン認証機関。透明性と品質を保証し、安心できるコーヒー文化を広めます。</p>
        <p>お問い合わせ: <a href="mailto:info@cafify.com">info@cafify.com</a></p>
    </div>

</body>
</html>
