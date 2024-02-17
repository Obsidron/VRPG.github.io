**<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            margin: 0;
            padding: 0;
        }
        .header {
            background-color: #333; /* Цвет полосы наверху */
            width: 100%; /* Ширина полосы наверху */
            height: 50px; /* Высота полосы наверху */
            position: fixed; /* Фиксированное позиционирование */
            top: 0; /* Размещение сверху */
            left: 0; /* Размещение слева */
            z-index: 1000; /* Индекс слоя, чтобы был над остальными элементами */
            display: flex;
            justify-content: center; /* Выравнивание содержимого по центру */
            align-items: center; /* Выравнивание по вертикали по центру */
        }
        .logo {
            width: 100px; /* Ширина логотипа */
            height: auto; /* Автоматическая высота */
        }
    </style>
</head>
<body>
    <div class="header">
        <img src="путь_к_вашему_логотипу.png" alt="Логотип" class="logo">
    </div>
</body>
</html>
**
