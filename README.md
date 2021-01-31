# Comandos - Explicação

git init - Inicia repositório

# *arquivo* é um exemplo
git add *arquivo" - adiciona o arquivo ao git

git commit -m "adicionado *arquivo*" - commita as alterações e cria um ponto na história

# "q" para sair do git log, "h" para ajuda
git log - mostra os pontos na história

git status - mostra o estado do dev no git

git show - mostra o ultimo commit, o que excluiu e adicionou

git show *nº arquivo* - mostra o commit que foi citado

git branch *nome branch* - cria uma nova branch, um "universo paralelo"

git checkout *nome branch* - seleciona uma branch

git branch - mostra todas as branchs

# criando uma nova branch, é como se criasse um universo paralelo, tudo que é criado ou alterado não é mostrado nas outras branchs

git merge *nome branch* - une a branch atual com outra

git branch -D *nome branch* - deleta uma branch

git remote add origin *link repositório* - adiciona um repositório remoto

git push -u origin master - primeiro push ao repositório