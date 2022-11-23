### 👉 *S T A R T* 💙💛
### *1. На локальном репозитории сделать ветки для:*
*** 
- Postman - **git branch Postman**
- Jmeter - **git branch Jmeter**
- CheckLists - **git branch CheckLists**
- Bug Reports - **git branch Bug_reports**
- SQL - **git branch SQL**
- Charles - **git branch Charles**
- Mobile testing - **git branch Mobile_testing**
*** 

### *2. Запушить все ветки на внешний репозиторий*

- **git push --all**
or
- **git push -u origin** Postman Jmeter CheckLists Bug_reports SQL Charles Mobile_testing  

***
### *3. В ветке Bug Reports сделать текстовый документ со структурой баг репорта*
- **git checkout** bug_report.txt
- **vim** bug_report.txt
- **insert**

***
ID: 

Date submited: 

Date updated:

Reporter: 

Assigned to: 

Title: 

Invironment: Browser + Version, OS + Version 

Severity: blocker/critical/major/minor/trivial

Priority: high/normal/low

Reproducibility: always/rearly

Status: assigned

Resolution: opened/new/assigned/resolved/reopened/verified/closed

STR: write steps how to reproduce the bug

AR: actual result

ER: expected result

Additional info: 

Attachments:
- link_video,
- link_screenshort

***
- **Esc:wq**
### 4. *Запушить структуру багрепорта на внешний репозиторий*

- **git add** bug_report.txt
- **git commit -m "add bug_report.txt"**
- **git push**
***
### 5. *Вмержить ветку Bug Reports в Main*
- **git checkout** main
- **git merge** Bug_reports
***
### 6. *Запушить main на внешний репозиторий.*
- **git push -u origin** main
***
### 7.*В ветке CheckLists набросать структуру чек листа.*
- **git checkout** CheckLists
- **touch** checkList.txt
- **vim** checklist.txt
- **insert**
***
Checklist
Type:
Date:
Invironment:
Project:
Project version:
Tester:
Title:
ER:
Result: passed/skipped/failed/not run
AR:
Bug link:
***
**Esc:wq**
### 8. *Запушить структуру на внешний репозиторий*
- **git add** checkList.txt
- **git commit -m "add checkList.txt"**
- **git push -origin** CheckLists
***
### 9. *На внешнем репозитории сделать Pull Request ветки CheckLists в main*
- click on **Compare&Pull request button** on the external repository
- type the **Branch is ready to be merged** message in the comment field
- click on **Create pull request** button
- click on **"Merge pull request"** button
- click on **Confirm merge** button
***
### 10. *Синхронизировать Внешнюю и Локальную ветки Main*
- **git checkout** main
- **git fetch**
- **git pull**

###  👉 *F I N I S H* 








