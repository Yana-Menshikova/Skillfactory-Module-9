1_ git status (git status -s) - инфоблок, где была выведена информация о неотслеживаемых файлах
2_git add . - чтобы файл попал под версионный контроль и впоследствии в нём можно было зафиксировать изменения
3_git commit -m 'любой коммент' - зафиксировать файл
4_ git rm 'название файла' - удалить файл
5_ git log - показывает историю изменений
6_ git branch имя ветки - создание новой ветки 
7_ Команду git branch --list Выведет список веток, которые существуют в вашем локальном репозитории. Текущая ветка master будет выделена зелёным цветом.

8_  git branch --list -v . Вы увидите информацию о последних коммитах каждой из веток. Так как коммитов в ветку testbranch00 ещё не было, то она указывает на коммит в мастере, от которого была создана.

9_ git checkout необходимо выполнить для переключения на созданную ветку. Выполняя команду git checkout, укажите после неё имя ветки, на которую вы хотите переключиться. Например, git checkout testbranch00. Вы получите сообщение о переключении на ветку testbranch00.
git push --set-upstream origin testbranch00
