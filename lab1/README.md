[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Dyender/BeginningAI/blob/main/lab1/notebooks/lab1.ipynb)

# Практическое занятие 1. Рабочее окружение

Автор: Карелин Иван Анатольевич, группа 251-952

## Структура папки lab1

Папка data содержит данные, папка notebooks – ноутбук lab1.ipynb, файл requirements.txt – список библиотек.

## Запуск на локальном компьютере

В папке lab1:

1. Создать окружение: python -m venv .venv
2. Включить окружение: .venv\Scripts\activate (macOS и Linux: source .venv/bin/activate)
3. Установить библиотеки: pip install -r requirements.txt
4. Открыть notebooks/lab1.ipynb в PyCharm и выбрать интерпретатор .venv\Scripts\python.exe

## Сравнение PyCharm и Google Colab

| Параметр | PyCharm (локально) | Google Colab |
|---|---|---|
| Версия Python | 3.14.8 | 3.13.18 |
| Версия pandas | 3.1.1 | 2.2.3 |
| Где хранятся файлы | На компьютере, в папке BeginningAI/lab1 | На удалённой Linux-машине Colab; файлы среды временные |
| Что потребовалось для запуска | Python, Git, PyCharm, окружение .venv, pandas, matplotlib и ipykernel | Браузер, аккаунт Google, открытие ноутбука из GitHub и подключение к среде выполнения |
