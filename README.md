# Pierwsze remote repo git!

To jest moje repo i proszę nie ruszać.


zaczynamy od katalogu z projektami
mkdir git22
git init
touch A
git add .
git commit -m A
touch B
git add .
git commit -m B
git checkout -b develop
touch C
git add .
git commit -m C
git checkout master
touch D
git add .
git commit -m D

git checkout develop
git rebase master 