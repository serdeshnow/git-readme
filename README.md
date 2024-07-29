# git-readme

# база 
1. git status (тыкать в любом непонятном случае)
2. git add . (добавлять файлы в stage)
3. git commit -m "" (commit = запись)
4. git log  (посмотреть кто делал комит и его хеш)
5. git push origin main (отправить на удаленный репозиторий. origin вместо ссылки на реп, main название ветки)
# изменять файлы
1. git reset [file_name] (убрать некоторые файлы из промежуточной области для одного файла)
2. git diff (показать изменения в файлах)
3. git reset --hard (убрать изменения из ВСЕХ файлов)
# создание веток
1. git branch (просмотр всех веток и на какой ты) 
2. git branch [branch_name] (создание ветки)
3. git checkout [branch_name] (переключение между ветками)
4. git checkout -b [branch_name] (создание ветки и переключение на нее)
# слияние веток
1. git merge [branch_name] (слияние веток. [branch_name] - ветка, из которой берем изменения (находимся в той ветке, в которую закидываем изменения))
2. GitHub -> project -> Pull Request -> New pull request -> Create pull request -> Add title + comment -> Create pull request
3. add comment -> start review -> finish review
4. resolve conversation -> merge pull request
5. goood job
# разделы в pull request
1. conversation 
2. files changed
