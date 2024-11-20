<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>БГУИР - Расписание занятий</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Расписание занятий</h1>
        <h3>Кафедра ПОИТ</h3>
    </header>
    <main>
        <table>
            <thead>
                <tr>
                    <th>Время</th>
                    <th>Группа</th>
                    <th>Предмет</th>
                    <th>Преподаватель</th>
                    <th>Аудитория</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>9:00 - 11:00</td>
                    <td>ПОИТ-01</td>
                    <td><a href="details.html#databases">Базы данных</a></td>
                    <td>Иванов И.И.</td>
                    <td>412</td>
                </tr>
                <tr>
                    <td>9:00 - 11:00</td>
                    <td>ПОИТ-02</td>
                    <td><a href="details.html#graphics">Компьютерная графика</a></td>
                    <td>Петров П.П.</td>
                    <td>414</td>
                </tr>
                <tr>
                    <td>11:10 - 13:10</td>
                    <td>ПОИТ-01</td>
                    <td><a href="details.html#networks">Компьютерные сети</a></td>
                    <td>Сидоров С.С.</td>
                    <td>508</td>
                </tr>
                <tr>
                    <td>11:10 - 13:10</td>
                    <td>ПОИТ-02</td>
                    <td><a href="details.html#informatics">Информатика</a></td>
                    <td>Курочка С.П.</td>
                    <td>506</td>
                </tr>
                <tr>
                    <td>13:20 - 14:20</td>
                    <td>ПОИТ-01</td>
                    <td><a href="details.html#informatics">Информатика</a></td>
                    <td>Курочка С.П.</td>
                    <td>506</td>
                </tr>
                <tr>
                    <td>13:20 - 14:20</td>
                    <td>ПОИТ-02</td>
                    <td><a href="details.html#networks">Компьютерные сети</a></td>
                    <td>Сидоров С.С.</td>
                    <td>508</td>
                </tr>
                <tr>
                    <td>15:30 - 17:30</td>
                    <td>ПОИТ-01</td>
                    <td><a href="details.html#algorithms">Алгоритмизация</a></td>
                    <td>Дмитриев Д.Д.</td>
                    <td>202</td>
                </tr>
                <tr>
                    <td>17:40 - 19:40</td>
                    <td>ПОИТ-02</td>
                    <td><a href="details.html#design">Проектирование</a></td>
                    <td>Сергеенко С.С.</td>
                    <td>412</td>
                </tr>
                <tr>
                    <td>19:50 - 21:50</td>
                    <td>ПОИТ-01</td>
                    <td><a href="details.html#graphics">Компьютерная графика</a></td>
                    <td>Петров П.П.</td>
                    <td>414</td>
                </tr>
                <tr>
                    <td>19:50 - 21:50</td>
                    <td>ПОИТ-02</td>
                    <td><a href="details.html#databases">Базы данных</a></td>
                    <td>Иванов И.И.</td>
                    <td>412</td>
                </tr>
            </tbody>
        </table>
    </main>
    <footer>
        <p>© Все права защищены. 2016 год</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>БГУИР - Курс лекций</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Курс лекций</h1>
    </header>
    <main>
        <section id="databases">
            <h3>Базы данных (Иванов И.И.)</h3>
            <p>Темы: определение БД, классификация, проектирование баз данных, первичный и вторичный ключи.</p>
        </section>
        <section id="graphics">
            <h3>Компьютерная графика (Петров П.П.)</h3>
            <p>Темы: алгоритмы графической визуализации, трёхмерные проекции, устранение невидимых линий.</p>
        </section>
        <section id="networks">
            <h3>Компьютерные сети (Сидоров С.С.)</h3>
            <p>Темы: структура Интернета, P2P-сети, коммутация пакетов, многоуровневые сетевые модели.</p>
        </section>
        <section id="informatics">
            <h3>Информатика (Курочка С.П.)</h3>
            <p>Темы: кодирование данных, структура современных вычислительных систем, этапы развития ИТ.</p>
        </section>
        <section id="algorithms">
            <h3>Алгоритмизация (Дмитриев Д.Д.)</h3>
            <p>Темы: алгоритмические конструкции, обработка массивов, история создания языков программирования.</p>
        </section>
        <section id="design">
            <h3>Проектирование (Сергеенко С.С.)</h3>
            <p>Темы: основы интерфейсов, этапы разработки, функциональные требования, прототипирование.</p>
        </section>
    </main>
    <footer>
        <p>© Все права защищены. 2016 год</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f9f9f9;
    color: #333;
}

header {
    background-color: #007BFF;
    color: white;
    padding: 20px;
    text-align: center;
}

main {
    padding: 20px;
}

table {
    width: 100%;
    border-collapse: collapse;
    margin: 20px 0;
    background: white;
}

table th, table td {
    border: 1px solid #ddd;
    padding: 10px;
    text-align: left;
}

table th {
    background-color: #007BFF;
    color: white;
}

table a {
    color: #007BFF;
    text-decoration: none;
}

table a:hover {
    text-decoration: underline;
}

section {
    margin-bottom: 20px;
    padding: 10px;
    background: white;
    border: 1px solid #ddd;
    border-radius: 5px;
}

footer {
    text-align: center;
    padding: 10px;
    background: #f4f4f4;
    color: #777;
    font-size: 0.9em;
}
