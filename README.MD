# GIT E GITHUB

Guia prático para iniciantes.

### Instalação

https://git-scm.com/download

## SCENES

- [x] Você deseja criar pontos na história da produção do seu projeto.
- [x] Você deseja verificar mudanças feitas no seu projeto.

- [x] Você começa uma nova funcionalidade no seu projeto, sem estragar o que já foi feito.
- [x] Você adiciona as novas funcionalidades ao seu projeto em produção.
- [x] Você quer deletar a branch da nova funcionalidade, depois de aplicar em seu projeto.

- [x] Você quer colocar seu projeto na nuvem.

- [x] Você vai pegar um projeto já iniciado, para trabalhar com o time.
- [x] Você precisa resolver um conflito.
- [x] Antes de enviar a solução, precisamos atualizar o projeto local.

- [x] Você precisa voltar um arquivo para um determinado momento na linha do tempo.
- [x] Você precisa recuperar algo deletado.

## COMMANDS

- 'git init' // Inicia a linha do tempo
- 'git add .' // Adiciona ou atualiza mudanças de todos os arquivos da branch para irem para a linha do tempo
- 'git add {{$archive}}' // Adiciona ou atualiza mudanças para irem para a linha do tempo
- 'git commit {{$archive}} -m "{{$comment_commit}}"' // Adiciona um ponto na linha do tempo
- 'git log' // Visualiza os ponto na linha do tempo / commit
- 'git status' // Informa o estado das alterações do nosso projeto
- 'git show' //  Apresenta determinado ponto na história

- 'git branch {{feature/$nome}}' // Cria uma branch no projeto que não interfere na branch 'master'
- 'git checkout {{$branch}}' // Navega pelas branchs
- 'git checkout -b {{feature/$nome}}' // Cria uma nova branch e vai pra essa nova branch
- 'git branch' // Visualiza as branchs do projeto
- 'git merge {{$branch}}' // Uni a branch
- 'git branch -d {{$branch}}' // Deleta a branch
- 'git branch -D {{$branch}}' // Deleta a branch e todas as sub-branchs de modo forçado

- 'git remote add origin {{$url_repository_github}}' // Adiciona um repositório remoto
- 'git remote -v' // Exibi os repositórios remotos disponíveis
- 'git push -u origin master' // Envia os commities para o repositório remoto
- 'git pull' // Atualiza o repositório local de acordo com o repositório remoto

- 'git clone {{$repository_remote}}' // Cria um clone de um determinado repositório remoto

- 'git checkout -- {{$archive}} // Restaura um arquivo antes do último commit
- 'git checkout {{$id_commit}} -- {{$archive}}' // Restaura um arquivo antes do commit em questão

### Extras
- 'git credencial.helper store' // Utiliza a última credencial informada