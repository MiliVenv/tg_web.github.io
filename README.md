<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
        <style>
body {
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    align-items: center;
    height: 100vh;
    margin: 0;
    background-color: black;
}


.button-container {
    text-align: center;
    margin-bottom: 20px;
}

.title {
    font-weight: bold;
    margin-bottom: 10px;
}

.oval-button {
    background: linear-gradient(45deg, #6a5acd, #1e90ff);
    color: white;
    border: none;
    padding: 15px 30px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-weight: bold;
    font-size: 16px;
    border-radius: 25px;
    transition: background-color 0.3s, transform 0.2s;
    cursor: pointer;
}

.oval-button:hover {
    filter: brightness(0.9);
    transform: scale(1.05);
}
    </style>

</head>
<body>


    <div class="button-container">
        <h1 class="title">Создание кошелька</h1>
        <button class="oval-button">Создать новый кошелёк</button>
    </div>


    <script src="https://telegram.org/js/telegram-web-app.js"></script>
</body>
</html>
