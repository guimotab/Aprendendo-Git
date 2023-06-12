GITHUB.IO (para entender mais detalhado)

git branch (mostra as branchs)

git branch {nomeNovaBranch} (cria nova branch)

git checkout {nomeDaBranch} (muda de branchs)

--------UNINDO BRANCHS (MERGE)--------
    /----?----?----? X   (ramificação)
----|--(merge) -?---     (master)
(O merge junta os trabalhos e gera um merge commit)

(entra na branch principal)

git merge {nomeDaBranchQueVaiJuntar}

:x (para concluir)

git log --graph

--------UNINDO BRANCHS (REBASE)--------
    /------(REBASE)                            (master)
 ---|----?----?------?---(master)              (ramificação)

 (aplica os commits da outra branch para branch atual)

 git rebase {nomeDaBranchQueVaiJuntar}