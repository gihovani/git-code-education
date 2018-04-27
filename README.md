# GG2 - Curso de GIT Code Education!

Este é um repositório de testes para salvar os arquivos do curso de git estudado na **code.education** 

- Alguns commandos:
````
git log
git push :novobranch
git push origin :novobranch
git branch
git branch -d novobranch
git status
git log
echo "novo arquivo de teste branch master" > teste.txt
git add .
git commit -m "criado um novo txt"
git checkout funcionalidade1
echo "novo arquivo de teste branch funcionalidade" > teste.txt
git checkout teste.txt
git add .
git commit -m "adicionado um teste.txt no branch funcionalidade1"
git log
git status
git checkout master
git status
git checkout funcionalidade1
git merge master
git push origin funcionalidade1
git log
git checkout master
git push origin :funcionalidade1
git branch
git branch -d funcionalidade1
git branch -D funcionalidade1
git checkout -b dev
touch func.php
vi func
vi func.php 
cp func.php func2.php
vi func2.php 
git add . 
git commit -m "adicionada nova funcionalidade"
git push origin dev
git merge master
git merge dev
git push origin master
git push master origin
git checkout dev
vi func2.php 
git push origin dev
git add .
git commit -m "alterado o arquivo func2"
git push origin dev
