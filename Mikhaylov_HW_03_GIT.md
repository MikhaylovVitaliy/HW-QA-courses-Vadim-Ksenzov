
## __GitHub_HW_2__
_Создадим локальный репозиторий._
```shell
$ mkdir GitHub
$ cd GitHub
$ git init
```
### __1. На локальном репозитории сделать ветки для:__
* Postman
```
$ git branch Postman
```
* Jmeter
```
$ git branch Jmeter
```
* CheckLists
```
$ git branch CheckList
```
* Bag Reports
```
$ git branch Bag_Reports
```
* SQL
```
$ git branch SQL
```
* Charles
```
$ git branch Charles
```
* Mobile testing
```
$ git branch Mobile_testing
```

```
$ git branch
  Bag_Reports
  Charles
  CheckList
  Jmeter
  Mobile_testing
  Postman
  SQL
* master
```

### __2. Запушить все ветки на внешний репозиторий.__
_Создадим репозиторий на GitHub:_
```
$ curl -u 'MikhaylovVitaliy:<token>' https://api.github.com/user/repos -d '{"name":"GitHub"}'
```
_Запушим все ветки:_
```
$ git push --all
```

### __3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта.__
_Перейдем в ветку Bug_Reports:_
```
$ git checkout Bag_Reports
```
_Создаем bug_report.txt:_
```
$ vim bug_report.txt
```

* ID:
* Summary:
* Descriptions:
	* Exp:
	* Act:
	* Req:
* Steps to reproduce:
* Reproducibility:
* Severity:
* Priority:
* Symptom:
* Workaround:
* Comments:
* Attachments:

### __4. Запушить структуру багрепорта на внешний репозиторий.__
```
$ git add . && git commit -m "19.02.2022 add bug_report.txt"
$ git push -u origin Bag_Reports
```
### __5. Вмержить ветку Bag Reports в Main.__
```
$ git checkout master
$ git merge Bag_Reports
```
### __6. Запушить main на внешний репозиторий.__
```
$ git push origin master
```
### __7. В ветке CheckLists набросать структуру чек листа.__
_Перейдем в ветку CheckList:_
```
$ git checkout CheckList
```
_Создаем файл check_list.txt:_
```
$ vim check_list.txt
```

| Checking | Result |
|----------|:------:|
| C001	   |        |
| C002     |        | 
| C003     |        |
| C004     |        |
| C005     |        |

### __8. Запушить структуру на внешний репозиторий.__
```
git add . && git commit -m "19.02.2022 add check_list.txt" && git push -u origin CheckList
```
### __9. На внешнем репозитории сделать Pull Request ветки CheckLists в main.__
* _-> https://github.com/MikhaylovVitaliy/GitHub/tree/master_
* _-> Compare & pull request_
* _-> Create pull request_
* _-> Merge pull request_
* _-> Confirm merge_

### __10. Синхронизировать Внешнюю и Локальную ветки Main.__
_Переходим в основную ветку:_
```
$ git checkout master
```
_Синхронизируем:_
```
$ git pull origin master
```
