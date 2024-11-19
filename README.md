<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>БГУИР - Расписание занятий</title>
    <style>
        /* Встроенные стили */
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
            background: #fff;
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
    </style>
</head>
<body>
    <header>
        <h1>БГУИР - Расписание занятий</h1>
    </header>
    <main>
        <!-- Раздел с расписанием -->
        <section>
            <h2>Расписание занятий</h2>
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
                        <td><a href="#databases">Базы данных</a></td>
                        <td>Иванов И.И.</td>
                        <td>412</td>
                    </tr>
                    <tr>
                        <td>9:00 - 11:00</td>
                        <td>ПОИТ-02</td>
                        <td><a href="#graphics">Компьютерная графика</a></td>
                        <td>Петров П.П.</td>
                        <td>414</td>
                    </tr>
                    <tr>
                        <td>11:10 - 13:10</td>
                        <td>ПОИТ-01</td>
                        <td><a href="#networks">Компьютерные сети</a></td>
                        <td>Сидоров С.С.</td>
                        <td>508</td>
                    </tr>
                    <tr>
                        <td>11:10 - 13:10</td>
                        <td>ПОИТ-02</td>
                        <td><a href="#informatics">Информатика</a></td>
                        <td>Курочка С.П.</td>
                        <td>506</td>
                    </tr>
                    <tr>
                        <td>15:30 - 17:30</td>
                        <td>ПОИТ-01</td>
                        <td><a href="#algorithms">Алгоритмизация</a></td>
                        <td>Дмитриев Д.Д.</td>
                        <td>202</td>
                    </tr>
                    <tr>
                        <td>17:40 - 19:40</td>
                        <td>ПОИТ-02</td>
                        <td><a href="#design">Проектирование</a></td>
                        <td>Сергеенко С.С.</td>
                        <td>412</td>
                    </tr>
                </tbody>
            </table>
        </section>

        <!-- Раздел с описанием предметов -->
        <section id="databases">
            <h3>Базы данных (Иванов И.И.)</h3>
            <p>Определение БД, ключи, классификация, типы архитектур доступа, индексы, этапы проектирования.</p>
        </section>
        <section id="graphics">
            <h3>Компьютерная графика (Петров П.П.)</h3>
            <p>История компьютерной графики, алгоритмы преобразования, трехмерные проекции, устранение невидимых линий.</p>
        </section>
        <section id="networks">
            <h3>Компьютерные сети (Сидоров С.С.)</h3>
            <p>Классификация сетей, структура Интернета, P2P-сети, коммутация пакетов, многоуровневые модели.</p>
        </section>
        <section id="informatics">
            <h3>Информатика (Курочка С.П.)</h3>
            <p>Понятие информации, кодирование, развитие информационных технологий, структура вычислительных систем.</p>
        </section>
        <section id="algorithms">
            <h3>Алгоритмизация (Дмитриев Д.Д.)</h3>
            <p>Этапы решения задач, свойства алгоритмов, циклы, обработка массивов, Turbo Pascal, типы данных.</p>
        </section>
        <section id="design">
            <h3>Проектирование (Сергеенко С.С.)</h3>
            <p>Человеко-машинный интерфейс, этапы разработки интерфейса, функциональные требования, прототипирование.</p>
        </section>
    </main>
    <footer>
        <p>© Все права защищены. 2016 год</p>
    </footer>
</body>
</html>

