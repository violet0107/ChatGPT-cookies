<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>通知</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f0f0;
        }
        .notification {
            background-color: rgba(255, 255, 255, 0.8);
            border: 1px solid #ccc;
            border-radius: 10px;
            padding: 20px;
            max-width: 400px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .notification h1 {
            margin-top: 0;
            font-size: 24px;
        }
        .notification a {
            color: #007BFF;
            text-decoration: none;
        }
        .notification a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="notification">
        <h1>通知</h1>
        <p>目前版本可能不稳定,若有问题请去GitHub提交issue: <a href="https://github.com/violet0107/ChatGPT-cookies" target="_blank">GitHub</a></p>
        <p>目前最新版本为v1.0</p>
    </div>
</body>
</html>
