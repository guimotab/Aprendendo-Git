(salva modificações para depois de resolver, aplicar ela de volta)

(arquivo modificado)

git stash

git stash list

------TRAZENDO STASH - FORMA 1------

git stash list
git stash apply {numeroDaStash}
(tem que excluir a stash)
git stash drop {numeroDaStash}

------TRAZENDO STASH - FORMA 2------

git stash pop
(já devolve e exclui o stash)


depois dá o commit