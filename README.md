# AI USM Telegram Bot

AI USM Telegram Bot для прогнозов валют, акций и анализа новостей.

## Описание

Этот бот предназначен для предоставления прогнозов валютных курсов и цен на акции, а также анализа новостей с использованием методов машинного обучения.

## Функции

- Прогноз валютных курсов с использованием моделей ARIMA, Prophet и LSTM.
- Прогноз цен на акции с использованием модели Prophet.
- Фундаментальный анализ данных.
- Общий прогноз с использованием всех доступных моделей.

## Установка

1. Клонируйте репозиторий:
    ```bash
    git clone https://github.com/Lykman/AI-USM-tg.git![ai_usm_forecasting](https://github.com/user-attachments/assets/f494c6ff-dfce-493e-baa9-fea7aa6c6bd1)

    cd AI-USM-tg
    ```

2. Создайте и активируйте виртуальное окружение:
    ```bash
    python -m venv venv
    source venv/bin/activate
    ```

3. Установите зависимости:
    ```bash
    pip install -r requirements.txt
    ```

4. Создайте файл `.env` и добавьте в него ваш токен Telegram API:
    ```
    TELEGRAM_TOKEN=your_telegram_token
    AUTHORIZED_USER_IDS=comma_separated_list_of_user_ids
    ```

## Использование

Запустите бота:
```bash
python bot_main.py
