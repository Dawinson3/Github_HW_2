##HW_2_Github

1. На локальном репозитории сделать ветки для:
- Postman: `git branch Postman` сделал ветку Postman.
- Jmeter: `git branch Jmeter` сделал ветку Jmeter.
- CheckLists: `git branch CheckLists` сделал ветку CheckLists.
- Bag Reports: `git branch Bug Reports` ,сделал ветку Bug_Reports.
- Charles: `git branch Charles` сделал ветку Charles.
- Mobile testing: `git branch Mobile_testing` сделал ветку Mobile_testing.

2. Запушить все ветки на внешний репозиторий:
- Можно запушить все ветки сразу: `git push origin --all`, либо `git push -u origin` и через пробел имена веток.
- Я пушил каждую ветку отдельно `git push -u origin ...`,` где ... имя ветки`.


3. В ветке Bug Reports сделать текстовый документ со структурой баг репорта. 
- `git checkout Bug_Reports`, переходим в нужную нам ветку, `touch (имя файла)`, `vim (имя файла)`, клавиша `i`, редактируем, затем `Esc + :wq` сохраняем и закрываем редактор.

:
4. Запушить структуру багрепорта на внешний репозиторий.
- Находяс в ветке  Bug_Reports, применяем команды: `git status`, `git add`,  `git commit -m "...."`, `git push`.

5.  Вмержить ветку Bug Reports в Main.
- Проверяем, находимся ли мы в нужной ветке(принимающей), `git branch `.
- Если нужно переходим в нуную ветку,  `git ckeckout main`.
- Находясь в ветке main, пишем команду `git merge Bug_Reports`.

6. Запушить main на внешний репозиторий.
- ` git push -u origin main`.

7. В ветке CheckLists набросать структуру чек листа.
- Переходим в нужную ветку, `git checkout CheckLists`, `touch (имя файла)`, `vim (имя файла)`, клавиша `i`, редактируем, затем `Esc + :wq` сохраняем и закрываем редактор.

8. Запушить структуру на внешний репозиторий.
- Находяс в ветке  CheckLists, применяем команды: `git status`, `git add`, `git commit -m "...."`, `git push`.

9. На внешнем репозитории сделать Pull Request ветки CheckLists в main.
- Открываем GitHub.
- Нажимаем `Compare & pull request`.
- Выбираем в выпадающих списках нужные нам ветки.
- Нажимаем `Create pull request`.
- Нажимаем `Merge pull request`,  тем самым вливая изменения из ветки CheckList в main.
- `Confirm merge`.

10. Синхронизировать Внешнюю и Локальную ветки Main.
- В консоли вводим команду `git pull`.
