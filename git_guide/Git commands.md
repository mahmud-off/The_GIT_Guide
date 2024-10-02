# Git commands
1. git version # version of git
2. .git config -- global user.name --global user.email # работа с файлом настройки
3. git config -- list # просмотр настроек
4. cat ~/.gitconfig # просмотр настроек
5. git init # create repository
6. rm -rf .git # "разгитить" если что-то не так
7.  -r # ключ позволяет удалять папки вместе с их содержимым
8.  -f # избавит вас от вопросов вроде «Вы точно хотите удалить этот файл?
9. git status # проверить статус репозитория. Вывод: 1- тек. ветка, 2 - сообщение о коммитах, 3 - сообщение о требованиях коммита.
10. git add + %file_name% или + --all  (все файлы) или + "." (всю папку целиком) # подготовка к сохранению файлов в репозиторий (index)
11. git commit -m  + %message% (присваивает коммиту сообщение) # коммит
12. git remote add + %origin% + %project_URL% # ### Привязать удалённый репозиторий к локальному
13. git push + %-u% + %origin% + %master% # ### Отправить изменения на удалённый репозиторий
14. git clone + %repository_url% # клонировать репозиторий
15. git remote -v # убедиться, что репозитории связаны
16. git branch # просмотр существующих веток
17. git branch + %branch_name% # создание новой ветки
18. git checkout %branch_name% # переход на другую ветку
19. git checkout -b %branch_name% # создать ветку и сразу переключиться в неё
20. git branch -a # просмотр всех веток 
21. git diff %branch_name_1% %branch_name_2% # сравнить ветки
22. git merge %branch_name% # выполнить слияние веток (откуда запускаем команду, туда и сольются)
23. git branch -D %branch_name% # Удалить ветку после объединения
24. git pull # Забрать изменения из удалённого репозитория