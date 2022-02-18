# TXT
## Homework GitBash 

1. Создать внешний репозиторий c названием TXT
* GitHub -> Create repository 
2. Клонировать репозиторий TXT на локальный компьютер
* git clone [https://github.com/AngelinaTomashenko/TXT_HW2.git]
3. Внутри локального TXT создать файл “new.txt”
* touch new.txt [https://github.com/AngelinaTomashenko/TXT_HW2/blob/371ab665fe0cccc8a784c2b3b511e0c081071d2a/new.txt]
4. Добавить файл под гит 
* git add new.txt
5. Закоммитить файл 
* git commit -m "create file new.txt"
6. Отправить файл на внешний GitHub репозитори
* git push
7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст,количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT
* nano new.txt
8. Отправить изменения на внешний репозиторий 
* git commit -am "add info to file" -> git push
9. Создать файл preferences.txt 
* touch preferences.txt [https://github.com/AngelinaTomashenko/TXT_HW2/blob/371ab665fe0cccc8a784c2b3b511e0c081071d2a/preferences.txt]
10. В файл preferences.txt добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON
* nano preferences.txt
11. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате TXT
* touch skills.txt -> nano skills.txt [https://github.com/AngelinaTomashenko/TXT_HW2/blob/371ab665fe0cccc8a784c2b3b511e0c081071d2a/skills.txt]
12. Сделать коммит в одну строку
* git add .; git commit -m "add files"
13. Отправить сразу 2 файла на внешний репозиторий
* git push
14. На веб интерфейсе создать файл bug_report.txt.
* GitHub -> Add File -> Upload file
15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
* Commit changes
16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате.
* GitHub -> change
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе
* Commit changes
18. Синхронизировать внешний и локальный репозиторий TXT
* git pull
