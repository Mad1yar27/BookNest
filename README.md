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
            font-size: 2.5em;
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
            width: 150px;
            height: auto;
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

        /* Стили для формы контактов */
        form {
            display: flex;
            flex-direction: column;
            max-width: 600px;
            margin: 20px auto;
        }

        label {
            margin-bottom: 8px;
            font-weight: bold;
        }

        input, textarea {
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        button {
            padding: 10px;
            background-color: #333;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        button:hover {
            background-color: #555;
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
        <p>Добро пожаловать в мир литературы! Здесь вы найдете самые популярные книги для всех.</p>
    </header>

    <main>
        <section>
            <h2>Популярные книги</h2>
            <ul>
                <!-- Книга 1 -->
                <li>
                    <img src="https://imo10.labirint.ru/books/852492/cover.jpg/2000-0" alt="Обложка книги 1">
                    <div>
                        <h3>Книга 1: «Волшебный мир»</h3>
                        <p><strong>Автор:</strong> Иван Иванов</p>
                        <p><strong>Описание:</strong> Эта книга рассказывает о невероятных приключениях в магическом мире, полном чудес и опасностей. Главный герой — молодой волшебник, который должен спасти мир от зла.</p>
                        <p><strong>Жанр:</strong> Фэнтези, Приключения</p>
                    </div>
                </li>

                <!-- Книга 2 -->
                <li>
                    <img src="https://images-na.ssl-images-amazon.com/images/I/91t8gPy58aL.jpg" alt="Обложка книги 2">
                    <div>
                        <h3>Книга 2: «Путеводитель по Вселенной»</h3>
                        <p><strong>Автор:</strong> Сергей Петров</p>
                        <p><strong>Описание:</strong> В этой книге описаны самые удивительные уголки вселенной. Автор делится увлекательными фактами о космосе, путешествиях между звездами и необъяснимых явлениях.</p>
                        <p><strong>Жанр:</strong> Научная фантастика, Путеводитель</p>
                    </div>
                </li>

                <!-- Книга 3 -->
                <li>
                    <img src="https://m.media-amazon.com/images/I/51Jt7gY4z5L._SX326_BO1,204,203,200_.jpg" alt="Обложка книги 3">
                    <div>
                        <h3>Книга 3: «Мистические тайны»</h3>
                        <p><strong>Автор:</strong> Мария Сергеева</p>
                        <p><strong>Описание:</strong> История о старинных тайнах, скрытых в глубинах леса. Главные герои, столкнувшись с мистическими существами, начинают расследование древних происшествий, которые могут изменить их жизни.</p>
                        <p><strong>Жанр:</strong> Мистика, Триллер</p>
                    </div>
                </li>
            </ul>
        </section>

        <!-- Секция контактов -->
        <section>
            <h2>Контакты</h2>
            <p>Если у вас есть вопросы или предложения, не стесняйтесь связаться с нами! Заполните форму ниже, и мы обязательно ответим:</p>
            <form action="mailto:youremail@example.com" method="post" enctype="text/plain">
                <label for="name">Ваше имя:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Ваш email:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Сообщение:</label>
                <textarea id="message" name="message" rows="4" required></textarea>

                <button type="submit">Отправить</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Книга для всех — все права защищены</p>
    </footer>
</body>
</html>
