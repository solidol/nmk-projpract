# Лабораторна робота №20. Робота з репозиторієм в IDE Visual Studio Code

[Перелік усіх робіт](README.md)

## Мета роботи

Отримати навички роботи з репозиторієм через Visual Studio Code

## Теоретичні відомості

### Ініціалізація репозиторію

Якщо у вас ще немає Git репозиторія, ви можете його проініціалізувати наступним чином:

1. Створіть на комп'ютері папку;
2. У Visual Studio Code відкрийте меню **"Файл"** і виберіть пункт **"Відкрити папку"**;
3. Виберіть папку, створену на етапі 1.

### Клонування віддаленого репозиторію

Якщо віддалений Git репозиторій **вже наявний** на GitHub, то його можна склонувати за таким чином:

1. Відкрийте новое окно Visual Studio Code. У пошуковому рядку натиснути **"Клонувати репозиторій"**. Ви побачите варіант, який дозволить вам виконати клонування з GitHub.

![](img/20-01.png)

2. У списку, що розкривається, виберіть **"Клонувати з GitHub"**, і ви побачите список репозиторіїв.
3. Виберіть на комп'ютері розташування для клонованого репозиторію.
4. Натисніть кнопку **"Відкрити у спливаючому вікні"**, яке з'явиться після того, як Visual Studio Code клонує репозиторій.

![](img/20-02.png)

### Коміт (commit) змін в репозиторії

Для виконання коміту змін в репозиторії потрібно зробити наступне:

1. Відкрийте вікно **"Зміни Git"** для перегляду змін. Натисніть кнопку зі знаком "+" поруч із файлом, щоб підготувати файл.
2. Тепер, коли зміни проміжного збереження, введіть повідомлення фіксації в текстовому полі, де відображається **"Оновити вихідне повідомлення"**, і натисніть **"Зафіксувати збережені зміни"**.

Перегляньте одну вихідну фіксацію, створену у графі фіксації поточної гілки, щоб переконатися, що вона створена.

![](img/20-03.png)

### Заливання (push) змін в репозиторії

Щоб перший раз (надалі потрібно буде тільки підтверджувати посилання на репозиторій) залити локальний репозиторій з комітом на GitHub потрібно:

1. У вікні Зміни Git клацніть посилання **"1 вихідна/0 вхідних"**.
2. У вікні **"Репозиторій Git"** у розділі **"Вихідні"** двічі клацніть фіксацію.
3. У вікні **"Відомості про фіксацію"** виберіть файл, щоб переглянути різницю між базовою версією файлу та фіксацією.
4. У вікні **"Репозиторій Git"** у розділі Вихідні натисніть кнопку **"Надіслати"**.

![](img/20-04.png)

5. Перегляньте операцію, що виконується у фоновому режимі, за допомогою повідомлення **"Центру стану завдань"**.
6. Перевірте успішне завершення операції, переглянувши інформаційну панель у вікні **"Репозиторій Git"**.

![](img/20-05.png)
