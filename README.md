1. Создать внешний репозиторий c названием JSON. 
```
Repositories --> New --> Name:JSON --> Check "Add a README file" --> Press "Create repository"
```
 
 2. Клонировать репозиторий JSON на локальный компьютер. 
 Копируем ссылку https://github...
  В терминале Bash вводим команду
```
1. git init
2. git clone https://github...
```
 3. Внутри локального JSON создать файл “new.json”. 
 ``` 
1. cd JSON/
2. touch new.json 
 ```

4. Добавить файл под гит.
```
git add . 
```
 5. Закоммитить файл. 
 ```
 git commit -m “First”
 ```
 7. Отправить файл на внешний GitHub репозиторий. 
 ```
 1. проверка есть ли связь? git remote -v 
 2. git push 
 ```
 10. Отредактировать содержание файла “new.json” - написать информацию о себе. Всё написать в формате JSON.
```
Cat >new.json ИЛИ vim new.json
{"name": "Inna",
"surname": "Pyl",
"age": 35,
"gender": "female",
"profesion": "qa"
}
```
 8. Отправить изменения на внешний репозиторий. 
 ```
 1. git add . 
 2. commit -m "Second" 
 3. git push
 ```
 10. Создать файл preferences.json
 ```
 1. touch preferences.json 
 2. cat > preferences.json ИЛИ vim preferences.json
 ```
 11. В файл preferences.json добавить информацию о своих предпочтениях в формате JSON 
 ```
 {"my favorive movie": "AmelY",
"my farourite serial" : "Sex in the city",
"my favourite dish": "pasta",
"my favourite city": "Barselona"
}
```
 12. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON 
 ```
 1. touch sklls.json
 2. cat > sklls.json
 { "Skill1": "Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC.",
"Skill2": "Что такое клиент-серверная архитектура",
"Skill3": "HTTP Методы запросов на сервер",
"Skill4": "Коды ответов HTTP сервера",
"Skill5": "Структуры HTTP запросов и ответов",
"Skill6":"Что такое JSON, XML. Их структура",
"Skill7": "Тестирование API через Postman (JS, автотесты API)",
"Skill8": "Снятие и чтение логов c внешнего сервера",
"Skill9": "Снифинг http web трафика через Charles и Fiddler",
"Skill10" : "Dev Tools веб браузеров (Google Chrome, FireFox)",
"Skill11" : "VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)",
"Skill12": "Мобильное тестирование",
"Skill13": "Особенность iOS, Android, гайдлайны",
"Skill14": "Сборка iOS приложений на XCode",
"Skill15": "Сборка Android приложений на Android Studio",
"Skill16": ADB (управление андройд девайсами)",
"Skill17": Настройка прокси и vpn на iOS и Android",
"Skill18": Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android",
"Skill19": "Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)",
"Skill20": "Основы bash скриптинг, автоматизация рутинных задач на сервере",
"Skill21": "Доступ к удалённым серверам",
"Skill22": "Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join)",
"Skill23": "База данных Postgres (установка, настройка и использование)",
"Skill24": "Нереляционная база данных Redis (установка, настройка и использование)",
"Skill25": "Нагрузочное тестирование в Jmeter",
"Skill26": "Методология разработки Scrum",
"Skill27": "Python. (Изучение основ. Создание клиент серверного приложения)"
 }
 ```
 12. Отправить сразу 2 файла на внешний репозиторий.
 ```
 1. git add . 
 2. commit -m "Third" 
 3. git push
 ```
 13. На веб интерфейсе создать файл bug_report.json.
 ```
Add file --> Create new file --> Name: bug_report.json
```
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 ```
 Скролить вниз, добавить имя, нажать Commit
 ```
 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
 ```
 Choose bug_report.json --> Edit this file
{"ID": "номер",
"summary": "краткое описание",
"description": "полное описание",
"environment": "окружение",
"steps_to_reproduce": "шаги воспроизведения",
"actual_resul": "фактический результат",
"expected_result": "ожидаемый результат",
"severity": "серьезность",
"priority": "приоритет",
"additional_information": "дополнения"
}
```
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```
 Скролить вниз, добавить имя, нажать Commit
 ```
 17. Синхронизировать внешний и локальный репозиторий JSON 
 ```
 git pull
```
