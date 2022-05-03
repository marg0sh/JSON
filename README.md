# JSON
#1. Создайте текстоовый файл как в первом ДЗ по Terminal.
touch GIT_Homework_1.txt

#2. Сценарий перенесите в этот файл.
vim GIT_Homework_1.txt
#нажать i для редактирования, копирование Ctrl+C, вставка Ctrl+V

#3. На против каждого действия - напишите команду в GitBash
#Файл со сценарием и ссылку на свой гит хаб отправляйте менторам на проверку.
#https://github.com/marg0sh/JSON
#https://github.com/marg0sh/XML
#https://github.com/marg0sh/TXT

#JSON
#4. Создать внешний репозиторий c названием JSON.
#веб интерфейс github.com, залогинитьс, перейти в Repositories, создание новой репозитории New, имя JSON, Add a ReadMe file, Create repository. 

#5. Клонировать репозиторий JSON на локальный компьютер.
#в веб интерфейсе Code - HTTPS - COPY
git clone https://github.com/marg0sh/JSON.git

#6. Внутри локального JSON создать файл “new.json”.
cd JSON
touch new.json

#7. Добавить файл под гит.
git add new.json

#8. Закоммитить файл.
git commit -m 'create new.json'

#9. Отправить файл на внешний GitHub репозиторий.
git push

#10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
vim new.jsom
#(режим редактироваие i)
{
	'Full name':'Zaitseva Margarita Olegovna',
	'Age':'34',
	'Number of pets':'1',
	'Future desired salary':'50000$'
}
#(выйти из vim нажатием Esc :wq Enter)

#11. Отправить изменения на внешний репозиторий.
git commit -am 'changes in new.json' && git push

#12. Создать файл preferences.json
vim preferences.json

#13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
#(режим редактироваие i)
{
        'Favorite movie':'Queen of the Damned',
        'Favorite series':'Black Mirror',
        'Favorite food':'Fast Food',
        'Favorite time of the year':'Summer',
        'Side you would like tovisit':'USA'
}
#(выйти из vim нажатием Esc :wq Enter)

#14. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
vim skills.json
#(режим редактироваие i)
{
	'skill 1.':'Базовая теория. Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п. SDLC, STLC.',
        'skill 2.':'Что такое клиент-серверная архитектура.',
        'skill 3.':'HTTP Методы запросов на сервер.',
        'skill 4.':'Коды ответов HTTP сервера.',
        'skill 5.':'Структуры HTTP запросов и ответов.',
        'skill 6.':'Что такое JSON, XML. Их структура.',
        'skill 7.':'Тестирование API через Postman (JS, автотесты API).',
        'skill 8.':'Снятие и чтение логов c внешнего сервера.',
        'skill 9.':'Снифинг http web трафика через Charles и Fiddler.',
        'skill 10.':'Dev Tools веб браузеров (Google Chrome, FireFox).',
        'skill 11.':'VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)',
        'skill 12.':'Мобильное тестирование.',
        'skill 13.':'Особенность iOS, Android, гайдлайны.',
        'skill 14.':'Сборка iOS приложений на XCode.',
        'skill 15.':'Сборка Android приложений на Android Studio.',
        'skill 16.':'ADB (управление андройд девайсами).',
        'skill 17.':'Настройка прокси и vpn на iOS и Android.',
        'skill 18.':'Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android.',
        'skill 19.':'Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)',
        'skill 20.':'Основы bash скриптинг, автоматизация рутинных задач на сервере.',
        'skill 21.':'Доступ к удалённым серверам.',
        'skill 22.':'Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join).',
        'skill 23.':'База данных Postgres (установка, настройка и использование).',
        'skill 24.':'Нереляционная база данных Redis (установка, настройка и использование).',
        'skill 25.':'Нагрузочное тестирование в Jmeter.',
        'skill 26.':'Методология разработки Scrum.',
        'skill 27.':'Python. (Изучение основ. Создание клиент серверного приложения)'
}
#(выйти из vim нажатием Esc :wq Enter)

#15. Отправить сразу 2 файла на внешний репозиторий.
git commit -m 'changes' && git push

#16. На веб интерфейсе создать файл bug_report.json.
#веб интерфейс Add file - Create new file создание файла - название bug_report.json

#17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
#Create bug_report.json, сохранение Commit changes

#18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
#(редактирование файла) 
{
	'ID'
	'Summary'
	'Description'
	'Actual result'
	'Expected result'
	'Attachments"
	'Priority'
	'Severity'
	'Status'
}

#19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
#Update bug_report.json - Commit changes

#20. Синхронизировать внешний и локальный репозиторий JSON
git pull
