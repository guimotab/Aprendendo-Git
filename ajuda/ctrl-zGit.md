--------DESFAZER ANTES DE DAR O GIT ADD--------

git restore --{arquivo} (desfaz modificação do arquivo)

--------DESFAZER APÓS O GIT ADD--------

git reset HEAD {arquivo}

git restore --{arquivo} (desfaz modificação do arquivo)

--------DESFAZER APÓS O COMMIT--------

(pega o hash do commit com git log)

git revert {log do commit}