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
	<NSF>
		<name>Olesya</name>
		<surname>Mashukova</surname>
		<age>40</age>
		<pets>1</pets>
		<salary>1000</salary>
	</NSF>
</root>
```

8. Отправить изменения на внешний репозиторий
```
git push
```
 
