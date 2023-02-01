<h1 align="center">Comandos Git que utilizo no dia dia.</h1>
<h2>Iniciar Tarefa</h2>
> git pull --rebase origin master
<br>
> git checkout -b "nome_branch"
<br>
<h2>Subir Alterações</h2>
> git add .
<br>
> git commit -am "Mensagem do commit" ('-a' realizar o comando 'git add .' junto ao commit)
<br>
> git pull --rebase origin master
<br>
> git push origin master
<br>
<h2>Para baixa um branch que não existe na sua máquina</h2>
> git fetch origin nome_branch
<br>
<h2>Comandos para sair do VIM</h2>
> CTRL + C
<br>
> :qa!
<br>
<h2>Workflow para pull</h2>
> git checkout nome_branch
<br>
> git pull --rebase origin nome_branch
<br>
<h2>Passar um commit apenas de um branch para outro</h2>
> git checkout branch_destino
<br>
> git cherry-pick hash_commit
<br>
<h2>Comentários:</h2>
<h3>- Fazer pull sempre da master</h3>
> git pull --rebase origin master
<br>
<h3>- Criar branch sempre da master</h3>
> git branch nome_branch
<br>
> git checkout -b nome_branch (cria a branch já fazendo o checkout)