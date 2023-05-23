Primeiro devemos transformar uma pasta num repositório .git com o comando git init
Depois disso devemos cirar uma nova branch, com o comando git checkout -b nome-da-branch
Após feita as alterações necessárias damos um git add nome-do-arquivo ou git add . se for pra commitar tudo.
Ai usamos o git commit -m "mensagem" pra fazer o commit e deixar tudo nos trinks.
Quando quisermos juntar essa branch nova com a main, é só ir na main e dar um git merge nome-da-branch, dai vai juntar as duas.