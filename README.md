1. Создать внешний репозиторий c названием JSON. 
Repositories --> New --> Name:JSON --> Check "Add a README file" --> Press "Create repository"
 
 2. Клонировать репозиторий JSON на локальный компьютер. 
 Копируем ссылку https://github...
  В терминале Bash вводим команду
 Git clone https://github...
 
 3. Внутри локального JSON создать файл “new.json”. 
 1)cd JSON/
2). touch new.json 

4. Добавить файл под гит.1) git init 2).Git add . 
 5. Закоммитить файл. Git commit -m “First”
 6. Отправить файл на внешний GitHub репозиторий. 1). проверка есть ли связь? Git remote -v 2). git push
 7. Отредактировать содержание файла “new.json” - написать информацию о себе. Всё написать в формате JSON.
Cat >new.json ИЛИ vim new.json
{"name": "Inna";
"surname": Pyl;
"age": 35;
"gender": "female";
"profesion": qa
}
 8. Отправить изменения на внешний репозиторий. 1). git add . 2). commit -m "Second" 3). git push
 9. Создать файл preferences.json -- 1) touch preferences.json 2). cat > preferences.json ИЛИ vim preferences.json
 10. В файл preferences.json добавить информацию о своих предпочтениях в формате JSON 
 {"my favorive movie": "AmelY";
"my farourite serial" : "Sex in the city"; 
"my favourite dish": "pasta";
"my favourite city": "Barselona"
}
 11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON 
 1). touch sklls.json 2). cat > sklls.json
 { "skill1": "postman";
 "skill2": "bash"
 }
 12. Отправить сразу 2 файла на внешний репозиторий.
 1). git add . 2). commit -m "Third" 3). git push
 13. На веб интерфейсе создать файл bug_report.json.
Add file --> Create new file --> Name: bug_report.json
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 Скролить вниз, добавить имя, нажать Commit
 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
 Choose bug_report.json --> Edit this file
{"id": "b1";
"enviroment": "Samsung Galaxy s8";
"summary": "button Log out is on left at page Profile";
"steps to reproduse": "open app";
"ER": "button is on right";
"AR": "button in on left"
}
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 Скролить вниз, добавить имя, нажать Commit
 27. Синхронизировать внешний и локальный репозиторий JSON -- git pull
