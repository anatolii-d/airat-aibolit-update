# airat-aibolit-update
Скрипт для быстрой установки и/или обновления [ai-bolit](https://revisium.com/ai/) от Айрата Халитова

## Установка и запуск:
```bash
git clone https://github.com/AiratHalitov/airat-aibolit-update

cd airat-aibolit-update

./airat-mysqltuner-update.sh

cd ai-bolit

./run-aibolit.sh
```

**Примечания:** 
- Свои файлы для сканирования нужно копировать в папку `ai-bolit`, а уже потом запускать в ней скрипт `./run-aibolit.sh`
- Скрипт `./run-aibolit.sh` запускает по очереди два режима сканирования: обычный (`--mode=1`) и параноидальный (`--mode=2`)
- В параноидальном режиме возможны ложные срабатывания, т.к. он более чувствительный
