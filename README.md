# Проект ChatBot

## Описание
Проект представляет собой чат-бот для поддержки Service Desk, который взаимодействует с OpenAI API через прокси.

## Установка

1. Клонируйте репозиторий:
    ```bash
    git clone https://github.com/yourusername/your-repository.git
    ```

2. Перейдите в папку проекта:
    ```bash
    cd your-repository
    ```

3. Создайте виртуальное окружение:
    ```bash
    python -m venv venv
    ```

4. Активируйте виртуальное окружение:
    - Для Windows:
        ```bash
        .\venv\Scripts\activate
        ```
    - Для macOS/Linux:
        ```bash
        source venv/bin/activate
        ```

5. Установите зависимости:
    ```bash
    pip install -r requirements.txt
    ```

## Запуск

1. Активируйте виртуальное окружение (если оно не активировано).
   
2. Запустите приложение:
    ```bash
    python chatbot.py
    ```

3. Откройте браузер и перейдите по адресу `http://127.0.0.1:5000`.

## Примечание
Не забудьте указать свои API-ключи OpenAI в файле `config.py`.
