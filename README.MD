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
- 'git branch' // Visualiza as branchs do projeto
- 'git merge {{$branch}}' // Uni a branch
- 'git branch -d {{$branch}}' // Deleta a branch
- 'git branch -D {{$branch}}' // Deleta a branch e todas as sub-branchs de modo forçado

- 'git remote add origin {{$url_repository_github}}' // Adiciona um repositório remoto
- 'git remote -v' // Exibi os repositórios remotos disponíveis
- 'git push -u origin master' // Envia os commities para o repositório remoto
