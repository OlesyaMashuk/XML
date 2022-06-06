# XML

1. Создать внешний репозиторий c названием XML.

![Screenshot_7](https://user-images.githubusercontent.com/91422609/169956272-ac680b8e-b61a-42bd-8507-a9a10888dea3.png)

![Screenshot_8](https://user-images.githubusercontent.com/91422609/169956291-54d0c328-42db-48b1-b449-76e344aee97f.png)

 2. Клонировать репозиторий XML на локальный компьютер.
 
 ``` git clone https://github.com/OlesyaMashuk/XML ```
 
 3. Внутри локального XML создать файл “new.xml”.
  
 ```
 cd XML
 touch new.xml 
 ```

 4. Добавить файл под гит.
 
 ``` git add . ```
 
 5. Закоммитить файл.
 
 ``` git commit -m "Добавление файла на внеш.репозиторий" ```
 
 6. Отправить файл на внешний GitHub репозиторий.
 
 ``` git push ```
 
 7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата).
 Всё написать в формате XML.
 ```
 vim new.xml
<?xml version="1.0" encoding="UTF-8"?>
<root>
		<name>Olesya</name>
		<surname>Mashukova</surname>
		<age>40</age>
		<pets>1</pets>
		<salary>1000</salary>
</root>

esc :wg enter 
```


8. Отправить изменения на внешний репозиторий
```
git push
```
9. Создать файл preferences.xml
```
touch preferences.xml
```
10. В файл preferences.xml добавить информацию о своих предпочтениях 
(Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML
```
vim preferences.xml
i
<?xml version="1.0" encoding="UTF-8"?>
<root>
  <fav_movie>Terminator</fav_movie>
  <fav_TV_series>12 moments of spring</fav_TV_series>
  <fav_food>salad</fav_food>
  <fav_season>Summer</fav_season>
  <country>Iceland</country>
</root>

esc :wq enter
```
11.  Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
``` 
vim skills.json
i
<?xml version="1.0" encoding="UTF-8"?>
<root>
  <skill_1>Terminal</skill_1>
  <skill_2>GitBash</skill_2>
  <skill_3>GitHub</skill_3>
  <skill_4>Postman</skill_4>
  <skill_5>API</skill_5>
  <skill_6>Test case</skill_6>
  <skill_7>Charles</skill_7>
  <skill_8>DevTools</skill_8>
  <skill_9>SQL</skill_9>
<root>	

esc :wq enter
```
 12. Сделать коммит в одну строку.
```
git add -A && git commit -m "Добавление нескольких файлов в репозиторий"
```
 13. Отправить сразу 2 файла на внешний репозиторий.
 ```
 git push
 ```
 14. На веб интерфейсе создать файл bug_report.xml.
 ```
 В репозитории XML >> клик Add file >> клик Creat new file >> в Name your file пишу bug_report.xml
 ```
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 ```
 после ввода названия файла внизу >> клик Commit new file
 ```
 16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
 ```
 В репозитории XML выбираем файл bug_report.xml >> клик внизу ![image](https://user-images.githubusercontent.com/91422609/172226338-6c37bbc7-9267-46fc-99da-b12a2ce4d6f5.png) >> 
 <?xml version="1.0" encoding="UTF-8"?>
 <root>
     <ID>BR_1</ID>
     <Title>В поле 'Номер заказа' можно вводить любое количество цифр</Title>
     <Steps>
     	<Step_1>Зайти на главную страницу сайта</Step_1>
	<Step_2>В поле 'Номер заказа' ввести слишком длинную строку 12345678901234567890465484512151212121212121218989</Step_2>
     <Steps>
     <Actual_result>В поле можно вводить слишком длинные строки</Actual_result>
     <Expected_result>В поле нельзя ввести слишком длинную строку, есть ограничение по количеству цифр</Expected_result>
 </root>
 ```
     
 	
 
 
 
 ```

На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML. В репозитории XML находим нужный файл и кликаем по его названию --> справа кликаем на значок карандаша (редактирование) --> прописываем
 
