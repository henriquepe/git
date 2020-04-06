
![gitandgithub](https://user-images.githubusercontent.com/62850277/78594941-88a42700-781f-11ea-889f-1570328106e9.jpeg)



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

"git init"  —>  Inicia o repositorio

"git add" —> Adiciona ou atualiza mudancas para o repositorio

"git commit" —> adiciona um ponto (versionamento) de alteracao no repositorio

"git log" —> Visualiza os versionamentos (commits) do repositorio

"git status" —> Informa o estado de alteracoes do repositorio

"git show" —> apresenta determinado versionamento no repositorio

"git branch" —> Gerenciar novas branch's

"git checkout" —> Move tua administracao entre as branch's e recupera alteracoes de um arquivo.

"git merge" —> Mesclador de branch's

"git push" —> Realiza o upload do repositorio atualizado ao GitHub

"git clone" —> Clonar um repositorio

"git pull" —> Puxar alteracoes feitas no repositorio remoto

---------------------==----------------------------

Como colocar o projeto na Nuvem??

  Primeiro de tudo, criar um repositorio no github, depois
  —>
  —>
  —>
  Para dar um upload do repositorio local para o repositorio remoto, em nuvem:

    git remote add origin "link-do-repositorio-no-github"
    git push -u origin master

  e pronto, o repositorio local ja foi enviado para um repositorio remoto criado no GitHub.

---------------------==----------------------------

Clonando repositorios

Para clonar um repositorio encontre-o no GitHub, abra sua tela principal.

Na tela principal tera um botao verde com uma mensagem "Clone or Download", ao clicar sobre ele um item podera ser copiado, copie!!

Voltando para o terminal local da sua maquina, digite o seguinte codigo para clonar o repositorio selecionado para o repositorio local:

    git clone "https://github.com/diego3g/novoprojeto.git"
    //exemplo

Quando se trabalha em equipe pode-se,

por commits de um mesmo arquivo em branch's diferentes, ocasionar conflitos. Para evita-los pode-se utilizar o:

    git pull

o git pull ira fazer a atualizacao do repositorio local de acordo com o repositorio remoto, pois em equipe, aquele repositorio pode ter sido atualizado e voce sem esse comando nao tera ele dessa nova forma.

