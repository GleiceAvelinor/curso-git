# O que é o GIT?
Sistema de versionamento de códigos.
# O que é GITHUB?
Uma plataforma para hospedagem de arquivos/códigos através de repositório

# Criando um repositório:
# Enviando arquivo para o repositório
git init
git add .
git commit -m "first commit"
git push -u origin master

# Gerencie o conjunto de repositórios ("remotos") cujos branches você monitora.
git remote
#verificar o estado do git 
git status

# Clonando repositório
git clone <nome do repositório>
ex: git clone https://github.com/GleiceAvelinor/curso-git.git

# Verifcando as linhas que foram modificadas:
git diff
git staged 

# Criando uma branche

# Atualizando o repositório remoto para máquina
git pull

# Atualizando o repositório remoto para máquina, esse comando aguarda o dev analisar o código antes de fazer o git pull.
git fetch -
git diff fetch origin/master(mostra a linha que foi alterado)



# Gravando alterações no repositório
git commit -m 

# Histórico dos commit
git log
PS C:\Users\ednar\OneDrive\Documentos\Curso_GIT> git log
commit 146a5f2984d10918ed1ec0f1a778a1f031b462d1 (HEAD -> master, origin/master)
Author: GleiceAvelinor <gleiceavelinor@gmail.com>
Date:   Thu Feb 19 23:26:24 2026 -0300

    gravando alteração no código com o git commit -m

commit 22ac59f92d1af88a584de97aeeafcae3e3fffcc4
Author: Gleice Avelino <gleiceavelinor@gmail.com>
Date:   Thu Feb 19 23:18:31 2026 -0300

    Update README with git pull command

    Added instructions for pulling updates from the remote repository.

:
# Uso do comando
git restore 
git restore --staged
