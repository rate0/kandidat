# DataVista

DataVista — это веб-приложение на базе Flask, предназначенное для генерации, сортировки и отображения данных. Приложение включает аутентификацию пользователей, визуализацию данных с помощью Chart.js, функционал поиска с пагинацией и обновление данных.

## Особенности

- **Аутентификация пользователей:** Безопасный вход и выход из системы с использованием Flask-Login.
- **Генерация и сортировка данных:** Автоматизированные процессы генерации и сортировки данных.
- **Топ-10 записей:** Отображение топ-10 записей с интерактивными графиками.
- **Поиск с пагинацией:** Фильтрация и навигация по данным с удобной разбивкой на страницы.
- **Обновление данных:** Обновление данных в реальном времени.

## Технологии

- **Backend:** Python, Flask, Flask-Login, Flask-Caching
- **Frontend:** HTML, CSS, Bootstrap, JavaScript, Chart.js
- **Прочее:** Git, C++ (для сортировочного исполняемого файла)

## Установка

1. **Клонирование репозитория:**

    ```bash
    git clone https://github.com/rate0/datavista.git
    cd datavista
    ```

2. **Установка зависимостей:**

    ```bash
    pip install -r requirements.txt
    ```

3. **Настройка переменных окружения:**

    В файле `.env` в корневой директории проекта измените секретный ключ на свой:

    ```
    SECRET_KEY=ваш_секретный_ключ
    ```
## Использование

1. **Запуск приложения:**

    ```bash
    cd /datavista/web_app
    python app.py
    ```

2. **Доступ в браузере:**

    Перейдите по адресу [http://127.0.0.1:5000/](http://127.0.0.1:5000/).

3. **Стандартные учетные данные для входа:**

    - **Имя пользователя:** admin
    - **Пароль:** password
