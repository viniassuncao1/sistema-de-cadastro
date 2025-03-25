# Comandos Git

## Adicionar e Confirmar Alterações
- `git add .` : Adiciona todas as modificações realizadas de uma só vez.
- `git commit -m "mensagem do commit"` : Captura e salva o estado atual do repositório.

## Status e Histórico
- `git status` : Lista todos os arquivos que foram modificados.
- `git log` : Exibe o histórico de commits do repositório (autor, data, hora e mensagem).
- `git log --oneline` : Mostra o log de forma resumida, em apenas uma linha.

## Envio e Sincronização
- `git push` : Envia as alterações do diretório local para o repositório remoto.
- `git pull` : Atualiza o repositório local com as alterações do remoto.
- `git fetch` : Busca alterações do repositório remoto, mas não as mescla com o branch atual.

## Restauração e Diferenças
- `git restore` : Restaura arquivos ou o projeto para um estado anterior.
- `git diff` : Mostra as diferenças entre arquivos ou commits.
- `git reset` : Desfaz commits ou altera o estado do repositório.

## Clonagem e Ramificação
- `git clone <url>` : Clona um repositório remoto para o ambiente local.
- `git branch` : Cria, lista ou exclui branches.
- `git checkout <branch>` : Alterna entre branches existentes ou restaura arquivos.
- `git checkout -b "nome_da_branch"` : Cria uma nova branch e muda para ela.
- `git switch "nome_da_branch"` : Troca de uma branch para outra sem alterar modificações (ainda experimental).

## Mesclagem e Gerenciamento Remoto
- `git merge <branch>` : Mescla alterações de um branch para outro.
- `git remote` : Gerencia repositórios remotos.
