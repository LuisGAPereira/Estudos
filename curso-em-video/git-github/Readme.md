# Git e Github

# Comandos 
 * **git init**: cria um novo repositório local;
 * **git remote**: permite criar(add + nome + url), ver e excluir conexões com outros repositórios;
 * **git add**: (nome do arquivo ou .) adiciona algo na "lista de preparação" para o commit;
 * **git commit**:(-m + "mensagem") salva as alterações(uma versão) no repositório local;
 * **git merge**: mescla uma das branches disponíveis para a atual (recomenda-se utilizar git pull antes do merge);
 * **git fetch**: informa que há alterações disponíveis no repositório remoto sem trazer as alterações para o repositório local;
 * **git pull**: traz as alterações de um repositório remoto para o local para manter o código atualizado(git fetch + git merge);
 * **git push**: leva as alterações de um repositório local para o remoto;
 * **git reflog**: verifica o histórico de atualizações e fornece o id;
 * **git branch**: mostra quais branches estão disponíveis;
 * **git branch** nome: adiciona um branch com o nome escolhido;
 * **git checkou -b nome main** : adiciona um branch com o nome escolhido baseado, nesse caso, na main, e já muda pra ela;
 * **git checkout nome**: muda para o branch escolhido.

# Pull Request
 O que é? uma pull democrática
 &nbsp;
 fazer alteração em uma branch
 &nbsp;
 fazer o commit da alteração e o push
 &nbsp;
 no github fazer o pull request de uma branch para a outra
 &nbsp;
 colocar o título e descrever as novas alterações
 &nbsp;
 esperar ser aprovado ou não.
 &nbsp;

# Gitignore
 O que é? um meio de não subir um arquivo indesejado para o git add
 **touch .gitignore** (cria um arquivo  **.gitignore** na pasta)
 colocar o nome do arquivo ou pasta dentro do arquivo **.gitignore**
 no caso de pasta, colocar **nomedapasta/**

 
