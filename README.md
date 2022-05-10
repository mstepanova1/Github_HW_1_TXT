# Github_HW_1_TXT

1. Создать внешний репозиторий c названием TXT
- <https://github.com/mstepanova1/Github_HW_1_TXT.git>

 2. Клонировать репозиторий TXT на локальный компьютер
- `git clone https://github.com/mstepanova1/Github_HW_1_TXT.git`

 3. Внутри локального TXT создать файл “new.txt”
- `cd Github_HW_1_TXT`
- `touch new.txt`

 4. Добавить файл под гит
- `git add new.txt`

 5. Закоммитить файл
- `git commit -m "add new.txt"`

 6. Отправить файл на внешний GitHub репозиторий
- `git push`

 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT
- `vim new.txt`
- <pre><kbd>i</kbd></pre>
```
name: John
surname: Smith
age: 27
pets: 1 cat Klaus
desired_salary: 10000$
```
- <pre><kbd>esc</kbd></pre>
- `:wq`

 8. Отправить изменения на внешний репозиторий
- `git add new.txt ; git commit -m "update new.txt" ; git push`

 9. Создать файл preferences.txt
- `touch preferences.txt`

 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT
- `vim preferences.txt`
- <pre><kbd>i</kbd></pre>
```
movie: Fight club
series: Friends
food: borsch
season: spring
country: Portugal
```
- <pre><kbd>esc</kbd></pre>
- `:wq`
 
 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
- `touch skills.txt`
- `vim skills.txt`
- <pre><kbd>i</kbd></pre>
```
soft_skills: patiens
hard_skills: - software testing theory
	     - client-server architecture
	     - scrum development methodology
```
- <pre><kbd>esc</kbd></pre>
- `:wq`

 12. Сделать коммит в одну строку
- `git add . ; git commit -m "add 2 files: preferences.txt, skills.txt"`

 13. Отправить сразу 2 файла на внешний репозиторий
- `git push`

 14. На веб интерфейсе создать файл bug_report.txt
- `Add file` >> `Create new file` >> `bug_report.txt`

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе
- `Commit new file`

 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT
- `Edit this file`
```
ID: 1
Project: esculab.com
Summary: The text colour of the 'Get result' button merges with the background colour of the button when the cursor is hovered over the service page
Actual result: The text colour of the 'Get result' button merges with the background colour of the button when the cursor is hovered over the service page
Expected result: The colour of the 'Get result' button text becomes white when the cursor is hovered over the service page
Pre-conditions: Open the service page. Example https://...
Steps to reproduce: Place the cursor on the 'Get result' button
Environment: macOS BigSur v:11.2.3 Google Chrome v:94.0.4606.71 (x86_64)
Severity: Trivial
Priority: Low
Status: Submitted
Attachments: Video link
Workaround: No 
Reproducibility: Always
```

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе
- `Commit changes`

 18. Синхронизировать внешний и локальный репозиторий TXT
- `git pull`
