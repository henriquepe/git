# GIT E GITHUB
  Guia Basico e Pratico


# Instalacao
  https://git-scm.com/dowload


# SCENES

Para iniciar um repositorio uso o comando

    git init

---------------------==----------------------------

Para subir para o repositorio a primeira versao de um projeto

    git add "nomedoprojeto/arquivo"

Apos o comando acima para finalizar o envio ao repositorio devemos

    git commit -m "mensagem da sua preferencia para o envio(added 'nomedoprojeto')"

---------------------==----------------------------

Para visualizar os registros feitos no git

    git log

pelo comando acima, sera exibido no terminal todas as alteracoes e tambem os numeros de commits registrados no log do git

---------------------==----------------------------

Caso queira verificar detalhadamente do que se trata aquele determinado commit copie o numero do commit e utilize:

    git show "numerodeidentificacaodocommit"

sera entao exibido tudo o que foi alterado ou o que foi adicionado por meio daquele commit(...)

---------------------==----------------------------

Caso tenha se esquecido de dar algum commit, o git possui o comando

    git status

para que voce possa verificar se existe algo pendente.

---------------------==----------------------------

Significado de Branch —>
  Branch significa **ramificacao,** enquanto estou na 
  ramificacao master posso criar ramificacoes alternativas.

---------------------==----------------------------

Meu cliente pediu para que no projeto eu incluisse um carrinho de compra, crio entao uma ramificao no meu projeto, pois o carrinho e algo novo nele. Seguinte codigo:

    git branch feature/cart
    
    //git branch eh o comando que cria a ramificacao
    //"feature/cart" eh o nome dessa nova ramificacao no projeto

---------------------==----------------------------

Para eu migrar de ramificacoes no git eu utilizo o seguinte codigo:
    //o comando para mudar e git checkout + o nome da ramificacao
    
      git checkout feature/cart
    
    //abaixo esta a mensagem de confirmacao no terminal quando foi mudado a ramificacao utilizada.
      Switched to branch 'feature/cart'

---------------------==----------------------------

Para voltar a branch Master basta:

    git checkou master

---------------------==----------------------------

Visualizar todas as branch's disponiveis:

    git branch
    
    //mensagem no terminal:
    	feature/cart
    	*master

---------------------==----------------------------

Desejo mesclar duas branch, para isso utilizo o codigo:

    git merge "nome-da-branch"

depois de mesclado, pode-se perceber que os arquivos adicionados na branch mesclada aparacem na branch master.

---------------------==----------------------------

Resumo:

- "git init"  —>  Inicia o repositorio
- "git add" —> Adiciona ou atualiza mudancas para o repositorio
- "git commit" —> adiciona um ponto (versionamento) de alteracao no repositorio
- "git log" —> Visualiza os versionamentos (commits) do repositorio
- "git status" —> Informa o estado de alteracoes do repositorio
- "git show" —> apresenta determinado versionamento no repositorio

---------------------==----------------------------

Como colocar o projeto na Nuvem??

