<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>صفحه ورود</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #1f1f1f;
            font-family: 'Tahoma', sans-serif;
        }
        .circle {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            background-color: #61dafb;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 24px;
            color: #fff;
            cursor: pointer;
            transition: transform 0.3s ease;
        }
        .circle:hover {
            transform: scale(1.1);
        }
    </style>
</head>
<body>

    <div class="circle" onclick="startApp()">
        ورود
    </div>

    <script>
        function startApp() {
            alert("به اپلیکیشن خوش آمدید!");
        }
    </script>

</body>
</html># Samir
