<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
        <style>
        body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    background-color: var(--tg-theme-bg-color)
}

.button-container {
    text-align: center;
}

.oval-button {
    background-color: var(--tg-theme-bg-color);
    color: var(--tg-theme-text-color);
    border: none;
    padding: 15px 30px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    border-radius: 25px;
    transition: background-color 0.3s, transform 0.2s;
    cursor: pointer;
}

.oval-button:hover {
    background-color: #45a049;
    transform: scale(1.05);
}
    </style>

</head>
<body>


    <div class="button-container">
        <button class="oval-button">Создать новый кошелёк</button>
    </div>


    <script src="https://telegram.org/js/telegram-web-app.js"></script>
</body>
</html>
