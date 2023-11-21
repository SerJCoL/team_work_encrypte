Documentation for new staff
•  Расположение репозитория с кодом, как посмотреть существующий код:
a)	HTTPS access: https://github.com/SerJCoL/team_work_encrypte.git
b)	SSH access: git@github.com:SerJCoL/team_work_encrypte.git

•	как устроен процесс внесения своих изменений в основную кодовую базу:
a)	Определение состояния файлов \\ git status
b)	Отслеживание новых файлов и добавление изменений из рабочей области проекта в индекс \\ git add
c)	Сделать коммит на основе индекса \\ git commit
d)	Запушить коммит в удалённый репозиторий. \\ git push

•	каковы правила именования веток
a)	Основная ветка – master
b)	Ветка для изменений - branch


•	как настроить свою среду разработки, 
1.	Installing Visual Studio Code
2.	Click on “Accounts” button
3.	Enter login and pass from GitHub site
4.	Connection and sync are successfully with GitHub repository

•	инструкция для младших сотрудников по слиянию веток, какие команды надо выполнить, чтобы: 

git clone git@github.com:SerJCoL/team_work_encrypte.git
or
https://github.com/SerJCoL/team_work_encrypte.git
cd team_work_encrypte
git status
git checkout -b team-branch
git status
touch team_first.html
touch team_second.html
git add .							
git commit -m "added team_first.html and team_second.html in team-branch”	    
git push origin team-branch	
git status
git checkout master
