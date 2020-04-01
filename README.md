# GIT E GITHUB
  guia pratico para iniciantes

# Instalacao
  https://git-scm.com/dowload

# SCENES

- [x] Voce deseja criar pontos na historia da producao do seu projeto
- [x] Voce deseja verificar mudancas feitas no seu projeto


Para iniciar um repositorio uso o comando
  git init

para subir para o repositorio a primeira versao de um projeto
  git add "nomedoprojeto/arquivo"

apos o comando acima para finalizar o envio ao repositorio devemos
  git commit -m "mensagem da sua preferencia para o envio (added 'nomedoprojeto')"


para visualizar os registros feitos no git
  git log


pelo comando acima, sera exibido no terminal todas as alteracoes
e tambem os numeros de commits registrados no log do git
caso queira verificar detalhadamente do que se trata aquele determinado commit
copie o numero do commit e utilize
  git show "numerodeidentificacaodocommit"

sera entao exibido tudo o que foi alterado ou o que foi adicionado por meio daquele
commit(...)


caso tenha se esquecido de dar algum commit, o git possui o comando
  git status

para que voce possa verificar se existe algo pendente de commits.

