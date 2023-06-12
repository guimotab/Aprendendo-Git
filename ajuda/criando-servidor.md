(O servidor pode ser uma pasta, uma url, um computador na rede...)

(cria pasta para ser o servidor)

git init --bare (determina qual diretório vai ser o servidor)

git remote (lista todos os repositórios-servidor)

(dentro da pasta Guilherme)
git remote add {nomeDoRepositório} {caminhoDoRepositório(URL, Rede, pasta)} (git remote add local C:/Users/guimo/Downloads/Lógica/Git/local/)

git remote

-------ENVIANDO DADOS PARA O REPOSITÓRIO LOCAL-------
git push {nomeDoRepositório} {nomeDaBranch} (importante estar na pasta da Branch) 
(ex.:
    ./guilherme
        git push local master
)

-------PEGANDO DADOS PARA O REPOSITÓRIO LOCAL-------
(vai na pasta que vai receber os arquivos)

git clone {/c/../caminhoDoRepositorio}/ {novaPasta(opcional)} (git clone /c/.../Git/local/ arquivo)

git remote

(opcional)
git remote rename origin {novoNome}
(opcional)

//pega para o repositório a sua Branch
git pull {nomeDoRepositório} {nomeDaBranch} (importante estar na pasta da Branch) 
(ex.:
    ./ana
        git pull local master
)