Comandos Git
============

_Lista dos meus comandos do Git usados no dia a dia_

--

### Obtendo & Criando Projetos

| Comando | Descrição |
| ------- | --------- |
| `git init` | Inicializa um repositório Git localmente |
| `git clone ssh://git@github.com/[username]/[repository-name].git` | Crie uma cópia local de um repositório remoto |

### Comandos básicos

| Comando | Descrição |
| ------- | --------- |
| `git status` | Checa o status |
| `git add [file-name.txt]` | Adiciona um arquivo |
| `git add -A ou git add *` | Adicione todos os arquivos novos e alterados |
| `git commit -m "[Mensagem do commit]"` | Confirmar alterações |
| `git rm -r [file-name.txt]` | Remove um arquivo ou um diretório |

### Branching & Merging

| Comando | Descrição |
| ------- | --------- |
| `git branch` | Lista os branches (o asterisco (*) indica o branch atual) |
| `git branch -a` | Lista todos os branches (local e remoto) |
| `git branch [nome do branch]` | Cria um novo branch |
| `git branch -d [nome do branch]` | Apaga um branch |
| `git push origin --delete [nome do branch]` | Apaga um branch remoto |
| `git checkout -b [nome do branch]` | Cria um novo branch e swita para ele |
| `git checkout -b [nome do branch] origin/[branch nome]` | Cria um novo branch remotamente e swita para ele |
| `git checkout [nome do branch]` | Swita para branch |
| `git checkout -` | Switch para o último branch utilizado |
| `git checkout -- [file-nome.txt]` | Discarta todas as mudanças de um arquivo |
| `git merge [nome do branch]` | Mescla um branch com o branch ativo |
| `git merge [branch 1] [branch 2]` | Mescla um branch com o branch de destino |
| `git stash` | NÃO SEI BEM O QUE FAZ |
| `git stash clear` | Apaga todas as entradas ocultas |

### Compartilhando & Atualizando o projeto

| Comando | Descrição |
| ------- | --------- |
| `git push origin [nome do branch]` | Envia um branch para um repositório remoto |
| `git push -u origin [nome do branch]` | Envia as mudanças para um repositório remoto e já fica nele |
| `git push` | Envia as mudanças para um repositório remoto) |
| `git push origin --delete [branch nome]` | Apaga e remove o branch |
| `git pull` | Atualize o repositório local com o commit mais recente |
| `git pull origin [nome do branch]` | Atualiza as mudanças com o repositório remoto |
| `git remote add origin ssh://git@github.com/[username]/[repository-name].git` | Adiciona um repositório remoto |
| `git remote set-url origin ssh://git@github.com/[username]/[repository-name].git` | Definir um branch de origem do repositório para SSH |

### Inspeção & Comparação

| Comando | Descrição |
| ------- | --------- |
| `git log` | Vizualiza as mudanças |
| `git log --summary` | Vizualiza as mudanças com detalhes |
| `git diff [branch 1] [branch 2]` | Visualizar alterações antes do merge |
