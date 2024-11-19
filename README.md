# Docker

На зображенні показано вікно Docker Desktop. Запущений один контейнер під назвою "welcome-to-docker", який використовує порт 8088 та працює в даний момент.

<p align="center"> <img src="screenshots/01.png" alt=""/> </p>

У самому контейнері можна переглядати роботу цього контейнера, його налаштування та інший функціонал.

<p align="center"> <img src="screenshots/02.png" alt=""/> </p>

У необхідній папці створюємо клон репозиторія для навчання та переходимо до потрібної папки.

<p align="center"> <img src="screenshots/03.png" alt=""/> </p>

Далі за допомогою команди "docker compose watch" ми вмикаємо спостереження за файлами в директорії.

<p align="center"> <img src="screenshots/04.png" alt=""/> </p>

Після виконання можна побачити, що з'явився Docker контейнер.

<p align="center"> <img src="screenshots/05.png" alt=""/> </p>

Закінчення команди "docker compose watch".

<p align="center"> <img src="screenshots/06.png" alt=""/> </p>

Бачимо, що програма запустилась і все працює.

<p align="center"> <img src="screenshots/07.png" alt=""/> </p>

Тепер внесемо деякі зміни у файл "backend/src/routes/getGreeting.js".

<p align="center"> <img src="screenshots/08.png" alt=""/> </p>

Можна побачити, що зміни були внесені в загальний проєкт.

<p align="center"> <img src="screenshots/09.png" alt=""/> </p>

Далі внесемо зміну плейсхолдера за шляхом "client/src/components/AddNewItemForm.jsx".

<p align="center"> <img src="screenshots/10.png" alt=""/> </p>

На зображенні видно, що зміни були внесені.

<p align="center"> <img src="screenshots/11.png" alt=""/> </p>

Так само змінимо колір заднього фону на зелений. При збереженні всі зміни вносяться автоматично.

<p align="center"> <img src="screenshots/12.png" alt=""/> </p>