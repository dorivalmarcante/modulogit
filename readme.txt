meu primeiro sistema no git
alteração no readme pra descrever o sistema melhor


git branch - saber qual branch vc esta
git log - ver o log de commits feitos
git status - ver o status das modificações (arquivos modificados e adicionados)
git add -A - adicione todos os arquivos modificados e inseridos no git
git add nomedoarquivo - adiciona um arquivo especifico
git commit -m "Descrição" - Cria uma nova versão dos arquivos modificados
git commit -am "Descrição" - adiciona os arquivos novos e modificados e Cria uma nova versão dos arquivos modificados

existe 3 tipos de reset no git: soft, mixed e hard
o soft desfaz o commit, mantendo as alterações no arquivo em um estagio antes do commit, permitindo corrigir o erro e commitar novamente
o mixed desfaz o commit e o add. Então voce tera que adicionar e commitar o arquivo novamente
o hard desfaz o commit, o add e as modificações, voltando literalmente a um estagio anterior da pasta
o comando de reset é 
git reset --soft e a hash do commit
git reset --mixed e a hash do commit
git reset --hard e a hash do commit

git branch nomedobranch - cria um novo branch
git checkout nomedobranch - muda para o branch escolhido

git diff - mostra a diferença entre o ultimo commit e as ultimas modificações sem commitar