# Iniciar Tarefa

> git pull --rebase origin master
> git checkout -b "fb_nome_ramo"

# Subir Alterações

> git add .
> git commit -am "Mensagem do commit"
> git pull --rebase origin master
> git push origin master

# Para baixa um branch que não existe na sua máquina

> git fetch origin nome_branch

# Comandos para sair do VIM

> CTRL + C
> :qa!

# Workflow para pull

> git checkout nome_branch
> git pull --rebase origin nome_branch

# Passar um commit apenas de um branch para outro

> git checkout branch_destino
> git cherry-pick hash_commit

# Comentários:

- Fazer pull sempre da master
> git pull --rebase origin master

- Criar branch sempre da master
> git branch nome_branch
> git checkout -b nome_branch (cria a branch já fazendo o checkout)
