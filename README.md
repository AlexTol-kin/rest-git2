1. git status - отображает какие файлы подключены к GIT
2. git add (files) - подготавляивает файл к записи в GIT(stage)
   2.1 git add . - подготавляивае все файлы
3. git commit -m "comment" - записывает файлы в GIT, так же необходимо указывать комментариии в ""
4. git log - Отображает данные об авторе, дату последних изменений и комментарий / git log --oneline - Отображает id commita и сам комментарий
5. git push [rep_link] [branch_name] - отпраялем изменения на удаленный(локальный) репозиторий [ссылка на репозиторий] [название нашей ветки] "git push origin master"
   5.1 git remote -v - ссылка на репозиторий

6. git reset - позволяет удалить некоторые файлы из промежуточной области

7. git diff - позволяет просмотреть те строки которые мы изменяли или добавляли

8. git reset --hard - Обнуляет изменения из промежуточной области

<!-- Ветки нужны чтобы разделять наш код -->

9. git branch - показывает все доступные ветки

10. git branch [branch_name] - создаем новую ветку

10.1 git branch -D [branch_name] - удаляем ветку из репозитория

11. git checkout [branch_name]- переключаемся между ветками

12. git pull [rep_link] [branch_name] - изменения из ветки которой нам нужно и добавляет в нашу локальную ветку

<!--  Чтобы перенести изменения из одной ветки в другую есть 2 способа:
1. Pull requests в GitHub - чтобы разработчики могли проверять код друг у друга, в reviewers добавляется GitHub человека, кто будет смотреть  код
в Files changet показываются все изменения в файла, можно сотавлять комментарии в коде
Resolve conversation - нажимаем чтобы удалить комментарии и замечания после исправления. Затем merged, обычно после merged удаляют ветку из которой вносились изменения Delete branch

2. git merge - помощью терминала, переключаемся на ветку в которую нужно переместить изменения
git merge [branch_name] - название ветки чей код хотим перенести
далее пушим ветку и удаляем в gitHub ветку с которой вносили изменения
и удаляем в VSCode
-->

Current Change - сохранить прошлые изменения
Incoming Change - принять новые изменения
Both Change - сохранятся все изменения
