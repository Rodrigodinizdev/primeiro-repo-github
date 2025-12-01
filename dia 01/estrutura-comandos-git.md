## <comando> — ação principal que o Git vai executar, exemplo: status, commit, log, add, push; ##
## [opções] — modificadores do comando, podem alterar seu comportamento, exemplo: -a, -m, --all, --amend. ##
## [argumentos] — valores ou alvos sobre os quais o comando deve atuar, opcional mas depende do comando, exemplos: nome de arquivos, branch; ##

 ### Exemplos de comandos simples: ###
    git status
    git init

 ### Comandos com opções curtas (-a) ###   
     git commit -m
     git branch -d nome-da-branch

 ### comandos com opções longas ###    
      git config --global user.name "seu nome"
      git push --force

 ### comandos com argumentos ###
      git clone https://github.com/usuario/projeto.git
      git checkout minha-branch

 ### significado dos símbolos ###
      <> obrigatório / <mensagem> / usuário deve fornecer
      [] opcional / [--all] / pode ou não ser usado
       * / ou / --soft
       ... / múltiplos valores / permite vários argumentos    



