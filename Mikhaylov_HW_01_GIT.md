## __GIT Group_27 15.02.2022 01__

### __1. Создайте текстоовый файл как в первом ДЗ по Terminal.__
```$ vim Mikhaylov_HW_01_GIT.txt```

### __2. Сценарий перенесите в этот файл.__
### __3. На против каждого действия - напишите команду в GitBash__

_Файл со сценарием и ссылку на свой гит хаб отправляйте менторам на проверку._


### __JSON__
### __4. Создать внешний репозиторий c названием JSON.__
* _https://github.com/MikhaylovVitaliy_
* _-> Repositories_
* _-> New_
* _-> MikhaylovVitaliy/JSON_
* _v Pablic_
* _v Add a README file_
* _-> Create repository_

### __5. Клонировать репозиторий JSON на локальный компьютер.__
* _https://github.com/MikhaylovVitaliy/JSON_
* _-> Code_
* _-> Copy https://github.com/MikhaylovVitaliy/JSON.git_
```$ git clone https://github.com/MikhaylovVitaliy/JSON.git```

### __6. Внутри локального JSON создать файл “new.json”.__
```$ vim new.json```

### __7. Добавить файл под гит.__
```$ git add new.json```

### __8. Закоммитить файл.__
```$ git commit -m "16.02.2022 add new.json"```

### __9. Отправить файл на внешний GitHub репозиторий.__
```$ git push```

### __10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.__
```$ vim new.json```

```
{
        "last_name": "Михайлов",
        "first_name": "Виталий",
        "patronymic": "Сергеевич",
        "age": 44,
        "pets": 2,
        "salary": 60000
}
```

### __11. Отправить изменения на внешний репозиторий.__
```
$ git commit -am "16.02.2022 mod new.json"
$ git push
```

### __12. Создать файл preferences.json__
```$ vim preferences.json```

### __13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.__
```
{
        "favorite_movie": "Forrest Gump",
        "favorite_TV_series": "Brigada",
        "favorite_food": "chicken",
        "favorite_season": "summer",
        "country_to_visit": "Greece"
}
```

### __14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON__
```$ vim skills.json```
```
{
        "skill_1": "JSON",
        "skill_2": "Postman",
        "skill_3": "Fiddler",
        "skill_4": "Dev Tools",
        "skill_5": "Android Studio",
        "skill_6": "Linux terminal",
        "skill_7": "SQL",
        "skill_8": "Jmeter",
        "skill_9": "Python"
}
```

### __15. Отправить сразу 2 файла на внешний репозиторий.__
```
$ git add .
$ git commit -am "16.02.2022 add preferences.json and skills.json"
$ git push
```

### __16. На веб интерфейсе создать файл bug_report.json.__
* _https://github.com/MikhaylovVitaliy/JSON_
* _-> Add file_
* _-> Create new file_
* _-> JSON/bug_report.json_
* _-> Commit new file_

### __17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.__
* _-> Add file_
* _-> Upload files_
* _-> Commit changes_

### __18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.__
* _https://github.com/MikhaylovVitaliy/JSON/blob/main/bug_report.json_
```
{
	"Summary": "Login: Error messages in the login form are displayed in English",
	"Environment": "All browsers/devices",
	"Severity": "Major",
	"Steps to reproduce": [
		"1. Open front end https://www.roga&copita.vit",
		"2. Follow Inloggen  link",
		"3. Fill required fields with invalid data",
		"4. Click Inloggen button",
		"5. Pay attention to error messages"
	],
	"Actual result": "Error messages in the login form are displayed in English",
	"Expected result": "Error messages in the login form are displayed in the chosen language",
	"Attachment": "http://..."
}
```

 
### __19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.__
* _-> Commit changes_

### __20. Синхронизировать внешний и локальный репозиторий JSON__
```$ git pull```



### __XML__
### __21. Создать внешний репозиторий c названием XML.__
* _https://github.com/MikhaylovVitaliy_
* _ -> Repositories_
* _-> New_
* _-> MikhaylovVitaliy/XML_
* _v Pablic_
* _v Add a README file_
* _-> Create repository_

### __22. Клонировать репозиторий XML на локальный компьютер.__
* _https://github.com/MikhaylovVitaliy/XML_
* _-> Code_
* _-> Copy https://github.com/MikhaylovVitaliy/XML.git_
* _$ git clone https://github.com/MikhaylovVitaliy/XML.git_

### __23. Внутри локального XML создать файл “new.xml”.__
```$ vim new.xml```

### __24. Добавить файл под гит.__
```$ git add new.xml```

### __25. Закоммитить файл.__
```$ git commit -m "17.02.2022 add new.xml"```

### __26. Отправить файл на внешний GitHub репозиторий.__
```$ git push```

### __27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.__
```xml
<?xml version="1.0" encoding="utf-8"?>
<root>
	<book>
		<title>XML_about_me</title>
		<author>Mikhaylov Vitaliy</author>
		<year>2022</year>
	</book>

	<about_me>
		<last_name>Михайлов</last_name>
		<first_name>Виталий</first_name>
		<patronymic>Сергеевич</patronymic>
		<age>44</age>
		<pets>2</pets>
		<salary>60000</salary>
	</about_me>
</root>
```


### __28. Отправить изменения на внешний репозиторий.__
```
$ git commit -am "17.02.2022 mod new.xml"
$ git push
```

### __29. Создать файл preferences.xml__
```$ vim preferences.xml```

### __30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.__
```xml
<?xml version="1.0" encoding="utf-8"?>
<root>
        <book>
                <title>XML_preferences</title>
                <author>Mikhaylov Vitaliy</author>
                <year>2022</year>
        </book>

        <preferences>
                <favorite_movie>Forrest Gump</favorite_movie>
                <favorite_TV_series>Brigada</favorite_TV_series>
                <favorite_food>chickenn</favorite_food>
                <favorite_season>summer</favorite_season>
                <country_to_visit>Greece</country_to_visit>
        </preferences>
</root>
```

### __31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML__
```$ vim skills.xml```
```xml
<?xml version="1.0" encoding="utf-8"?>
<root>
        <book>
                <title>XML_skills</title>
                <author>Mikhaylov Vitaliy</author>
                <year>2022</year>
        </book>

        <skills>
                <skill_1>JSON</skill_1>
                <skill_2>Postman</skill_2>
                <skill_3>Fiddler</skill_3>
                <skill_4>Dev Tools</skill_4>
                <skill_5>Android Studio</skill_5>
                <skill_6>Linux terminal</skill_6>
                <skill_7>SQL</skill_7>
                <skill_8>Jmeter</skill_8>
                <skill_9>Python</skill_9>
        </skills>
</root>
```
### __32. Сделать коммит в одну строку.__
```$ git add . && git commit -m "17.02.2022 add preferences.xml and skills.xml"```

### __33. Отправить сразу 2 файла на внешний репозиторий.__
```$ git push```

### __34. На веб интерфейсе создать файл bug_report.xml.__
* _https://github.com/MikhaylovVitaliy/XML_
* _-> Add file_
* _-> Create new file_
* _-> XML/bug_report.xml_
* _-> Commit new file_

### __35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.__
* _-> Add file_
* _-> Upload files_
* _-> Commit changes_

### __36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.__
* _https://github.com/MikhaylovVitaliy/XML/edit/main/bug_report.xml_
```xml
<?xml version="1.0" encoding="utf-8"?>
<root>
	<book>
		<title>XML_bug_report</title>
		<author>Mikhaylov Vitaliy</author>
		<year>2022</year>
	</book>
	<bug_report>
        <Summary>Login: Error messages in the login form are displayed in English</Summary>
        <Environment>All browsers/devices</Environment>
        <Severity>Major</Severity>
            <Steps_to_reproduce>
                <number_1>1. Open front end https://www.roga_i_copita.vit</number_1>
                <number_2>2. Follow Inloggen  link</number_2>
                <number_3>3. Fill required fields with invalid data</number_3>
                <number_4>4. Click Inloggen button</number_4>
                <number_5>5. Pay attention to error messages</number_5>
            </Steps_to_reproduce>
        <Actual_result>Error messages in the login form are displayed in English</Actual_result>
        <Expected_result>Error messages in the login form are displayed in the chosen language</Expected_result>
        <Attachment>http://...</Attachment>
	</bug_report>
</root>
```

### __37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.__
* _-> Commit changes_

### __38. Синхронизировать внешний и локальный репозиторий XML__
```$ git pull```



### __TXT__
### __1. Создать внешний репозиторий c названием TXT.__
* _https://github.com/MikhaylovVitaliy_
* _-> Repositories_
* _-> New_
* _-> MikhaylovVitaliy/TXT_
* _v Pablic_
* _v Add a README file_
* _-> Create repository_

### __2. Клонировать репозиторий TXT на локальный компьютер.__
* _https://github.com/MikhaylovVitaliy/TXT_
* _-> Code_
* _-> Copy https://github.com/MikhaylovVitaliy/TXT.git_
```$ git clone https://github.com/MikhaylovVitaliy/TXT.git```

### __3. Внутри локального TXT создать файл “new.txt”.__
```$ vim new.txt```

### __4. Добавить файл под гит.__
```$ git add new.txt```

### __5. Закоммитить файл.__
```$ git commit -m "17.02.2022 add new.txt"```

### __6. Отправить файл на внешний GitHub репозиторий.__
```$ git push```

### __7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.__
```$ vim new.txt```
```
last_name: Михайлов
first_name: Виталий
patronymic: Сергеевич
age: 44
pets: 2
salary: 60000
```
### __8. Отправить изменения на внешний репозиторий.__
```
$ git commit -am "17.02.2022 mod new.txt"
$ git push
```
### __9. Создать файл preferences.txt__
```$ vim preferences.txt```

### __10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.__
```$ vim preferences.txt```
```
favorite_movie: Forrest Gump
favorite_TV_series: Brigada
favorite_food: chicken
favorite_season: summer
country_to_visit: Greece
```
### __11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT__
```$ vim sklls.txt```
```
skill_1: JSON
skill_2: Postman
skill_3: Fiddler
skill_4: Dev Tools
skill_5: Android Studio
skill_6: Linux terminal
skill_7: SQL
skill_8: Jmeter
skill_9: Python
```
### __12. Сделать коммит в одну строку.__
```$ git add . && git commit -m "17.02.2022 add preferences.txt and sklls.txt"```

### __13. Отправить сразу 2 файла на внешний репозиторий.__
```$ git push```

### __14. На веб интерфейсе создать файл bug_report.txt.__
* _https://github.com/MikhaylovVitaliy/TXT_
* _-> Add file_
* _-> Create new file_
* _-> TXT/bug_report.txt_
* _-> Commit new file_

### __15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.__
* _-> Add file_
* _-> Upload files_
* _-> Commit changes_

### __16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.__
* _https://github.com/MikhaylovVitaliy/TXT/blob/main/bug_report.txt_
```
Summary: Login: Error messages in the login form are displayed in English
Environment: All browsers/devices
Severity: Major
Steps to reproduce:
	1. Open front end https://www.roga&copita.vit
	2. Follow Inloggen  link
	3. Fill required fields with invalid data
	4. Click Inloggen button
	5. Pay attention to error messages
Actual result: Error messages in the login form are displayed in English
Expected result: Error messages in the login form are displayed in the chosen language
Attachment: http://...
```
### __17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.__
* _-> Commit changes_

### __18. Синхронизировать внешний и локальный репозиторий TXT__
```$ git pull```

