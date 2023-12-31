## Фреймворки Flask и FastAPI (семинары)
### Урок 5. Знакомство с FastAPI
<hr>

**Задание 6**

Создать веб-страницу для отображения списка пользователей.<br> Приложение
должно использовать шаблонизатор Jinja для динамического формирования HTML
страницы.
* Создайте модуль приложения и настройте сервер и маршрутизацию.
* Создайте класс User с полями id, name, email и password.
* Создайте список users для хранения пользователей.
* Создайте HTML шаблон для отображения списка пользователей. Шаблон должен
  * содержать заголовок страницы, 
  * таблицу со списком пользователей и 
  * кнопку для добавления нового пользователя.
* Создайте маршрут для отображения списка пользователей (метод GET).
* Реализуйте вывод списка пользователей через шаблонизатор Jinja.

<hr>

**Задание 7**

Создать RESTful API для управления списком задач.<br> Приложение должно
использовать FastAPI и поддерживать следующие функции:
* Получение списка всех задач.
* Получение информации о задаче по её ID.
* Добавление новой задачи.
* Обновление информации о задаче по её ID.
* Удаление задачи по её ID.

Каждая задача должна содержать следующие поля: 
* ID (целое число),
* Название (строка), 
* Описание (строка), 
* Статус (строка): "todo", "in progress", "done".
