<h1 align="center">Comandos Git que utilizo no dia dia.</h1>
<br>
<h2>Iniciar Tarefa</h2>
<br>
> git pull --rebase origin master
<br>
> git checkout -b "fb_nome_ramo"
<br>
<h2>Subir Alterações</h2>
<br>
> git add .
<br>
> git commit -am "Mensagem do commit"
<br>
> git pull --rebase origin master
<br>
> git push origin master
<br>
<h2>Para baixa um branch que não existe na sua máquina</h2>
<br>
> git fetch origin nome_branch
<br>
<h2>Comandos para sair do VIM</h2>
<br>
> CTRL + C
<br>
> :qa!
<br>
<h2>Workflow para pull</h2>
<br>
> git checkout nome_branch
<br>
> git pull --rebase origin nome_branch
<br>
<h2>Passar um commit apenas de um branch para outro</h2>
<br>
> git checkout branch_destino
<br>
> git cherry-pick hash_commit
<br>
<h2>Comentários:</h2>
<br>
- Fazer pull sempre da master
<br>
> git pull --rebase origin master
<br>
- Criar branch sempre da master
> git branch nome_branch
<br>
> git checkout -b nome_branch (cria a branch já fazendo o checkout)
