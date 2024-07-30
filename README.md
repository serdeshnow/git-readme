# git-readme

# база 
1. git status (тыкать в любом непонятном случае)
2. git add . (добавлять файлы в stage)
3. git commit -m "" (commit = запись)
4. git log  (посмотреть кто делал комит и его хеш)
5. git push origin main (отправить на удаленный репозиторий. origin вместо ссылки на реп, main название ветки)
6. git pull (подтягивает изменения с удаленного репозитория)
# изменять файлы
1. git reset [file_name] (убрать некоторые файлы из промежуточной области для одного файла)
2. git diff (показать изменения в файлах)
3. git reset --hard (убрать изменения из ВСЕХ файлов)
# создание веток
1. git branch (просмотр всех веток и на какой ты) 
2. git branch [branch_name] (создание ветки)
3. git checkout [branch_name] (переключение между ветками)
4. git checkout -b [branch_name] (создание ветки и переключение на нее)
# удаление веток
1. git branch -d [branch_name] (флаг -d это удаление ветки)
# слияние веток
1. git merge [branch_name] (слияние веток. [branch_name] - ветка, из которой берем изменения (находимся в той ветке, в которую закидываем изменения))
2. GitHub -> project -> Pull Request -> New pull request -> Create pull request -> Add title + comment -> Create pull request
3. add comment -> start review -> finish review
4. resolve conversation -> merge pull request
5. goood job
# разделы в pull request
1. conversation 
2. files changed
# решение конфликтов
1. git merge -> conflict -> зелегая полоска (current change - это где находишься), синяя полоска (incoming change - другая ветка, в которой тоже меняли этот файл) -> надпись сверху (accept current change / accept incoming change / accept all change) -> git add . -> git commit -m [message] -> git log
# Работа с GitFlow
1. создать репозиторий на github и клонировать на компуктер
2. создать ветку разработки development от главной ветки
3. создать от ветки development feature-ветки и мержить feature-ветки в development, когда фичи готовы
4. создание ветки release/0.1.0 от development
5. когда ветки release/0.1.0 закончена, то она мержиться в development и main и затем удаляется
6. если в ветке main обнаруживается ошибка, то создается hotfix-ветка
7. когда работа над hotfix-веткой завершается, ее нужно мержить с development и main, а затем удалить 
