# Mentor_Seminar

## Mentor Seminar — n8n Workflow

### Описание
Это рабочий workflow на n8n, развернутый через Docker, который выполняет следующие задачи:

- Получение текста через Webhook (HTTP POST)
- Обработка текста и маршрутизация через условный узел (IF)
- Генерация краткого резюме текста с помощью LLM (OpenAI / DeepSeek)
- Отправка результата в Telegram
