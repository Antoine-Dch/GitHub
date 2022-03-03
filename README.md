# GitHub HW№1

## JSON

 1. Создать внешний репозиторий c названием JSON.

```https://github.com/ account/ repositories/ new/ Repository name: JSON, choose Public or Private, Initialize (если требуется)/ create repository```

 2. Клонировать репозиторий JSON на локальный компьютер.

```Repositories/ JSON/ Code/ Https/ Копировать ссылку на репозиторий/ На компьютере открыть GitBash/ git clone вставить ссылку на репозиторий```

 3. Внутри локального JSON создать файл “new.json”.

```cd JSON```

```touch new.json```

 4. Добавить файл под гит.

```git add new.json```

 5. Закоммитить файл.

```git commit -m "add new file"```

 6. Отправить файл на внешний GitHub репозиторий.

```git push```

 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.

```vim new.json```

{

        "name": "Anton"
	
        "age": 33
	
        "number_of_pets": 0
	
        "future desired salary,$": 5000
	
}

 8. Отправить изменения на внешний репозиторий.

```git commit -am "change file new.json"```

```git push```

 9. Создать файл preferences.json

```touch preferences.json```

 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
 
```vim preferences.json```

{

        "Favorite movie": "?",
	
        "Favorite TV series": "Family guy",
	
        "Favorite food": "?",
	
        "Favorite time of the year": "?",
	
        "The country you would like to visit": "Georgia"
	
}

 11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON

```touch skills.json```

```vim skills.json```

{

        "JSON skills":[
	
                "What is JSON",
		
                "Json Structure",
		
                "API Testing"
		
        ]
	
}

 12. Отправить сразу 2 файла на внешний репозиторий.

```git add {preferences.json,skills.json}```

```git commit {preferences.json,skills.json} -m "add new files"```

```git push```

 13. На веб интерфейсе создать файл bug_report.json.

```В репозитории: Add file/ Create new file/ ввести имя/ внести изменения/ ввести комментари```

 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

```Нажать кнопку Commit new file```

 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.

```Открыть файл bug_report.json/ Перейти в режим редактирования. Ввести текст```

 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

```Нажать кнопку Commit changes```

 17. Синхронизировать внешний и локальный репозиторий JSON

```git pull```


## XML

 1. Создать внешний репозиторий c названием XML.

```https://github.com/ account/ repositories/ new/ Repository name: XML, choose Public or Private, Initialize (если требуется)/ create repository```

 2. Клонировать репозиторий XML на локальный компьютер.

```Repositories/ XML/ Code/ Https/ Копировать ссылку на репозиторий/ На компьютере открыть GitBash/ git clone вставить ссылку на репозиторий```

 3. Внутри локального XML создать файл “new.xml”.

```cd XML```

```touch new.xml```

 4. Добавить файл под гит.

```git add new.xml```

 5. Закоммитить файл.

```git commit -m "add new file"```

 6. Отправить файл на внешний GitHub репозиторий.

```git push```

 7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
 
\<aboutme\>

	<Name>Anton</Name>
	
	<age>33</age>
	
	<numberofpets>0</numberofpets>
	
	<futuredesiredsalary>5000$</futuredesiredsalary>
	
\</aboutme\>

 8. Отправить изменения на внешний репозиторий.

```git commit -am "change file new.xml"```

```git push```

 9. Создать файл preferences.xml

```touch preferences.xml```

 10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
 
```vim preferences.xml```

\<aboutme\>

	<Favoritemovie>?</Favoritemovie>
	
	<FavoriteTVseries>Family Guy</FavoriteTVseries>
	
	<Favoritefood>?</Favoritefood>
	
	<Favoritetimeoftheyear>?</Favoritetimeoftheyear>
	
	<Thecountryyouwouldliketovisit>Georgia</Thecountryyouwouldliketovisit>
	
\</aboutme\>

 11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML

```touch skills.xml```

```vim skills.xml```

\<skills\>

        <one>What is XML</one>
	
        <two>Syntax XML</two>
	
        <three>Scope of XML</three>
	
\</skills\>

 12. Сделать коммит в одну строку.

```git add . ; git commit {preferences.xml,skills.xml} -m "add new files"```

 13. Отправить сразу 2 файла на внешний репозиторий.

```git push```

 14. На веб интерфейсе создать файл bug_report.xml.

```В репозитории: Add file/ Create new file/ ввести имя/ внести изменения/ ввести комментари```

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

```Нажать кнопку Commit new file```

 16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.

```Открыть файл bug_report.xml/ Перейти в режим редактирования. Ввести текст```

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

```Нажать кнопку Commit changes```

 18. Синхронизировать внешний и локальный репозиторий XML

```git pull```


## TXT

 1. Создать внешний репозиторий c названием TXT.

```https://github.com/ account/ repositories/ new/ Repository name: TXT, choose Public or Private, Initialize (если требуется)/ create repository```

 2. Клонировать репозиторий TXT на локальный компьютер.

```Repositories/ TXT/ Code/ Https/ Копировать ссылку на репозиторий/ На компьютере открыть GitBash/ git clone вставить ссылку на репозиторий```

 3. Внутри локального TXT создать файл “new.txt”.

```cd TXT```

```touch new.txt```

 4. Добавить файл под гит.

```git add new.txt```

 5. Закоммитить файл.

```git commit -m "add new file"```

 6. Отправить файл на внешний GitHub репозиторий.

```git push```

 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
 
```vim new.txt```

        Name: Anton
	
        Age: 33
	
        Number of pets: 0
	
        Future desired salary,$: 5000

 8. Отправить изменения на внешний репозиторий.

```git commit -am "change file new.txt"```

```git push```

 9. Создать файл preferences.txt

```touch preferences.txt```

 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
 
```vim new.txt```

         Favorite movie: -
	 
         Favorite TV series: Family Guy
	 
         Favorite food: -
	 
         Favorite time of the year: -
	 
         The country you would like to visit: Georgia

 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT

```touch skills.txt```

```vim skills.txt```

         What is TXT
	 
         Syntax TXT
	 
         Scope of TXT

 12. Сделать коммит в одну строку.

```git add . ; git commit {preferences.txt,skills.txt} -am "add new files"```

 13. Отправить сразу 2 файла на внешний репозиторий.

```git push```

 14. На веб интерфейсе создать файл bug_report.txt.

```В репозитории: Add file/ Create new file/ ввести имя/ внести изменения/ ввести комментари```

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

```Нажать кнопку Commit new file```

 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.

```Открыть файл bug_report.xml/ Перейти в режим редактирования. Ввести текст```

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

```Нажать кнопку Commit changes```

 18. Синхронизировать внешний и локальный репозиторий TXT

```git pull```
