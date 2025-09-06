
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>Математика - Задание 1</title>
    <style>
        body { font-family: Arial, sans-serif; background: #f0f0f0; }
        .task { background: #fff; padding: 20px; margin: 50px auto; width: 300px; border-radius: 8px; }
        button { margin-top: 10px; }
    </style>
</head>
<body>
    <div class="task">
        <h2>Сколько будет 2 + 2?</h2>
        <input type="number" id="answer">
        <button onclick="checkAnswer()">Проверить</button>
        <p id="result"></p>
    </div>
    <script>
        function checkAnswer() {
            const answer = document.getElementById('answer').value;
            const result = document.getElementById('result');
            if (answer == 4) {
                result.textContent = "Верно!";
                result.style.color = "green";
            } else {
                result.textContent = "Неправильно, попробуйте ещё!";
                result.style.color = "red";
            }
        }
    </script>
</body>
</html>

