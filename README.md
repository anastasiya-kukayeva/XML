# XML

## GitHub. HW_1
|ToDo|Commands|
|:---------------|:-----|
|1. Создать внешний репозиторий c названием XML|Создаем новый репозиторий с названием XML на внешнем репозитории(New), во вкладке `<> Code` копируем `HTTPS`|
|2. Клонировать репозиторий XML на локальный компьютер|`git clone` `ctrl + V` (вставили скопированный `HTTPS`)|
|3. Внутри локального XML создать файл “new.xml”||`cd XML` `touch new.xml`|
|4. Добавить файл под гит|`git add .`|
|5. Закоммитить файл|`git commit -m "new"`|
|6. Отправить файл на внешний GitHub репозиторий|`git push`|
|7. Отредактировать содержание файла “new.xml”, написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML|`vim new.xml`|  
| |Нажать `i`|
| |`<about_me>`|
| |`<person_name>Nastya</person_name>`|
| |`<person_age>29</person_age>`|
| |`<amount_of_pets>1</amount_of_pets>`|
| |`<type_of_pet>cat</type_of_pet>`|
| |`<cat_name>Zhorik</cat_name>`|
| |`<desired_Salary>2000$</desired_Salary>`|
| |`</about_me>`|
| |Нажать `Esc :wq Enter`|
|8. Отправить изменения на внешний репозиторий|`git commit -m "new"` `git push`|
|9. Создать файл preferences.xml|`touch preferences.xml`|
|10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML|`vim preferences.xml`|
| |Нажать `i`|
| |`<favorites>`|	
| |`<favorite_film>Stories_about_Harry_Potter></favorite_film>`|
| |`<favorite_series>Game_of_Thrones</favorite_series>`|
| |`<favorite_food>pizza</favorite_food>`|
| |`<favorite_season>summer</favorite_season>`|
| |`<want_to_travel>Italy</want_to_travel>`|
| |`<favorite_book>Theodore_Dreiser_American_tragedy</favorite_book>`|
| |`</favorites>`|
| |Нажать `Esc :wq Enter`|
|11. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML|`vim skills.xml`|
| |Нажать `i`|
| |`<skills_of_junior_QA>`|
| |`SQL`|
| |`Postman`|
| |`Git`|
| |`Client_server_arhitecture`|
| |`Theory_of_testing`|
| |`Testing_documentation`|
| |`Mobile_testing`|
| |`Terminal`|
| |`</skills_of_junior_QA>`|
| |Нажать `Esc :wq Enter`|
|12. Отправить сразу 2 файла на внешний репозиторий|`git add .` `git commit -m "preferences and skills"` `git push`|
|13. На веб интерфейсе создать файл bug_report.json|Нажать `Add file` > `Create new file` > имя `bug_report.xml`|
|14. Сделать Commit changes (сохранить) изменения на веб интерфейсе|Нажать `Commit new file`|
|15. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML|Нажать `Edit this file`|
| |`<Bug_report_structure`>
| |`<ID>123</ID>`|
| |`<Title>Что?Где?Когда?</Title>`|
| |`<Version>1.2.19</Version>`|
| |`<Severity>Trivial</Severity>`|
| |`<Priority>Low</Priority>`|
| |`<Precondition>Steps</Precondition>`|
| |`<Environment>Devices,Browser</Environment>`|
| |`<STR>Steps to reproduce</STR>`|
| |`<ER>Expected result</ER>`|
| |`<AR>Actual Result</AR>`|
| |`<Attachments>links</Attachments>`|
| |`</Bug_report_structure>`|
|16. Сделать Commit changes (сохранить) изменения на веб интерфейсе|Нажать `Commit changes`|
|17. Синхронизировать внешний и локальный репозиторий XML|в git bush ввести команду`git pull`|
