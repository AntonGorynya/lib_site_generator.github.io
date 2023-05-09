# Генерация сайта библиотеки

Перед началом работы рекомендуется скачать книги с помщью 
скрипта доступного по ссылке https://github.com/AntonGorynya/lib_parser 

### Как установить

Python3 должен быть уже установлен. 
Затем используйте `pip` (или `pip3`, есть конфликт с Python2) для установки зависимостей:
```
pip install -r requirements.txt
```
### Подготовка к запуску
убедитесь в наличие файла **book.json** вида
```commandline
[
    {
        "id": "239",
        "author": "ИВАНОВ Сергей",
        "title": "Алиби",
        "img": "test\\239.jpg",
        "description": "Фантастический детективные рассказ опубликованный в журнале \"Юный техник\", 1991, © 8, С. 30 – 34.OCR В. КузьминSept. 2001Проект \"Старая фантастика\"http://sf.nm.ru",
        "comments": [
            "Детский вариант анекдотов про Шерлока Холмса)",
            "Загадки я люблю.)))",
            "А мне понравилось, люблю, знаете ли, всякие загадочки, головоломочки, кроссвордики, Гимнастика ума, одним словом... \nВо всём можно найти положительные моменты, не разгадал загадку, так хоть гренки научился готовить отменные... :-)",
            "Очень поучительное для ребенка 10 лет."
        ],
        "genre": "Научная фантастика",
        "book_path": "test\\239. Алиби.txt"
    },
]
```


### Пример запуска
```commandline
> python.exe .\main.py
```

### Цель проекта

Код написан в образовательных целях на онлайн-курсе для веб-разработчиков [dvmn.org](https://dvmn.org/).