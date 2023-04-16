| GIT HW2 Task| Command|
|----|--:|
|  1. На локальном репозитории сделать ветки для: |  |
|  *Postman* | git branch Postman |
|  *Jmeter*| git branch Jmeter |
|  *Checklists*| git branch Checklists |
|  *Bug reports*| git branch BugReports|
|  *SQL* | git branch SQL |
|  *Charles* | git branch Charles |
|  *Mobile testing*| git branch MobileTesting |
||
|  2. Запушить все ветки на внешний репозиторий | git push --all -u|
|  3. В ветке Bug Reports сделать текстовый документ со структурой баг репорта | git checkout BugReports |
| | touch bugscheme.txt |
| | nano bugscheme.txt |
|||
|  4. Запушить структуру багрепорта на внешний репозиторий | git add .|
|| git commit -m "Added info into bugscheme.txt"|
|| git push|
|||
|  5. Вмержить ветку Bug Reports в Main| git checkout main |
||git merge BugReports|
|||
|  6. Запушить main на внешний репозиторий. | ??? its done w/o my actions|
|  7. В ветке Checklists набросать структуру чек листа. | git checkout Checklists|
|| touch checklist.txt|
|| nano checklist.txt|
|||
|  8. Запушить структуру на внешний репозиторий | git add .  |
|| git commit -m "Added info into checklist.txt"|
|| git push|
|||
|  9. На внешнем репозитории сделать Pull Request ветки CheckLists в main | done with GUI |
| 10. Синхронизировать Внешнюю и Локальную ветки Main | git checkout main |
||git pull|
