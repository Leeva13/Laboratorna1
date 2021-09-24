# Laboratorna1
Мій перший репозиторій.

1.Що таке Git? 
Git — розподілена система керування версіями файлів та спільної роботи. Проєкт створив Лінус Торвальдс для керування розробкою ядра Linux, а сьогодні підтримується Джуніо Хамано.

2.У якому статусі можуть перебувати файли при роботі з Git?
Git має три основних стани, в яких можуть перебувати ваші файли: збережений у коміті (commited), змінений (modified) та індексований (staged)

3.Для чого використовується команда add?
Команда git add приймає шлях файлу або директорії. Якщо це директорія, команда додає усі файли в цій директорії рекурсивно.

4.Для чого використовується команда status?
Перевірка статусу ваших файлів
Нарешті, ця команда показує вам, в якій ви зараз гілці та інформує вас про те, що вона не розбіглася з такою ж гілкою на сервері. Поки що, ця гілка завжди буде “master”, така гілка створюється автоматично.

5.Для чого використовується команда commit?
Коли ви виходите з редактору, Git створює коміт з цим повідомленням коміту (після видалення коментарів та змін до файлів)

6.Для чого використовується команда init?
Git зберігає свої файли і історію безпосередньо в папці у вашому проекті. Для того, щоб створити новий репозиторій, потрібно відкрити термінал, перейти в каталог проекту і запустити git init . Це дасть git право на доступ до цієї папки і створить прихований каталог 

7.Що необхідно писати в комнтарях комітів?
Скомпільовані бінарні файли (програми, бібліотеки, тощо)
Тимчасові файли, що були створені у процесі компіляції, і які не належать до вихідного тесту програми
Файли, створені вашим текстовим редактором, оболонкою програмування у процесі роботи
Файли, створені вашою програмою у процесі роботи

8.Як переглянути список комітів?
Після того, як ви створили кілька коммітів або ж клонували репозиторій з уже існуючою історією коммітів, ймовірно вам знадобиться можливість подивитися що було зроблено - історію коммітів. Одним з основних і найбільш потужних інструментів для цього є команда git log.

9.Для чого використовується команда cheakout?
Це робиться за допомогою знайомої нам команди git checkout , яку ми використовували раніше для переходу між гілками. Вона також може бути використана для переходу між комітами (досить часто у git одна команда може робити багато не спільних між собою функцій).
