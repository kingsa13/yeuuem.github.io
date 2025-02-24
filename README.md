# yeuuem.github.io
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trang Tình Yêu</title>
    <style>
        body {
            text-align: center;
            background-color: #ffebf2;
            font-family: 'Arial', sans-serif;
        }
        h1 {
            color: #ff4081;
            margin-top: 50px;
        }
        button {
            background-color: #ff4081;
            color: white;
            border: none;
            padding: 15px 30px;
            font-size: 18px;
            cursor: pointer;
            border-radius: 10px;
            margin-top: 20px;
        }
        button:hover {
            background-color: #d81b60;
        }
        .message {
            font-size: 24px;
            color: #ff4081;
            display: none;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <h1>Chào em yêu! ❤️</h1>
    <button onclick="showMessage()">Nhấn vào đây</button>
    <p class="message">Anh yêu em rất nhiều! 💖</p>

    <script>
        function showMessage() {
            document.querySelector('.message').style.display = 'block';
        }
    </script>
</body>
</html>
