# Quotes Parser

Скрипт собирает цитаты, авторов и теги с сайта [quotes.toscrape.com](https://quotes.toscrape.com/) и сохраняет результат в форматированный документ Word.

## Возможности

- Сбор цитат, авторов и тегов с помощью `requests` + `BeautifulSoup`
- Парсинг HTML-структуры (теги, классы)
- Автоматическое создание папки для отчётов (через `pathlib`)
- Сохранение результата в `.docx` с помощью `python-docx`
- Вывод данных в консоль в читаемом виде
- Экспорт в CSV и Excel через pandas
- Автоматическая сортировка по количеству тегов
- Подсчёт аналитики (число тегов на цитату)

## Технологии

- Python 3.10+
- requests
- beautifulsoup4
- lxml
- python-docx

## Установка

```bash
pip install requests beautifulsoup4 lxml python-docx pandas openpyxl
