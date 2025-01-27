<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Книга для всех</title>
    <style>
        /* Сброс стандартных отступов */
        body, h1, h2, h3, p, ul, li {
            margin: 0;
            padding: 0;
        }

        /* Основной стиль для страницы */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
        }

        /* Стили для заголовка */
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
        }

        header h1 {
            font-size: 2em;
        }

        header p {
            font-size: 1.2em;
        }

        /* Стили для основного контента */
        main {
            padding: 20px;
        }

        h2 {
            font-size: 1.8em;
            margin-bottom: 20px;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        li {
            display: flex;
            align-items: center;
            margin: 20px 0;
            padding: 15px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        li img {
            margin-right: 20px;
            border-radius: 8px;
        }

        h3 {
            font-size: 1.5em;
            margin: 0 0 10px 0;
        }

        p {
            font-size: 1em;
            line-height: 1.5;
            margin: 5px 0;
        }

        /* Стили для подвала */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Книга для всех</h1>
        <p>Добро пожаловать в мир литературы!</p>
    </header>
    <main>
        <section>
            <h2>Популярные книги</h2>
            <ul>
                <li>
                    <img src="cover1.jpg" alt="Обложка книги 1" width="150">
                    <h3>Книга 1</h3>
                    <p><strong>Автор:</strong> Автор 1</p>
                    <p><strong>Описание:</strong> Краткое описание книги 1. Эта книга рассказывает о невероятных приключениях в мире фантазий и волшебства.</p>
                </li>
                <li>
                    <img src="cover2.jpg" alt="Обложка книги 2" width="150">
                    <h3>Книга 2</h3>
                    <p><strong>Автор:</strong> Автор 2</p>
                    <p><strong>Описание:</strong> Краткое описание книги 2. Эта книга о путешествиях по миру, полном тайн и загадок.</p>
                </li>
                <li>
                    <img src="cover3.jpg" alt="Обложка книги 3" width="150">
                    <h3>Книга 3</h3>
                    <p><strong>Автор:</strong> Автор 3</p>
                    <p><strong>Описание:</strong> Краткое описание книги 3. Это исторический роман, погружающий в атмосферу прошлого века.</p>
                </li>
            </ul>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 Книга для всех</p>
    </footer>
</body>
</html>

