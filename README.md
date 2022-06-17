<h1 align="center">
    Introdução ao Github
</h1>

<hr>

# Dowload GIT <a href="https://git-scm.com/download/win">Access</a>
    - verificar a versão pelo terminal
        - git --version
            - retorno: 2.36.1

# Conta no github <a href="https://github.com/">Criar conta</a>
    - Inserir o email / senha e login desejado
    - Selecionar todas as opções que vier e confirmar registro


# Iniciando um novo repositório
    - git init

# Inserindo as credênciais 
    - git config --global user.name "Fulano de Tal"
    - git config --global user.email fulanodetal@exemplo.br
    - (opcional) IDE ou editor sendo utilizado 
        - git config --global core.editor emacs 

# Subindo um repositório existente para o remoto
    - git add .
    - git commit -m "seu commit"
    - git push -u origin (nome da brancha) - master / main


# Inserindo modificações
    - git add . 
    - git commit -m ""
    - git push origin master
        - OBS.: sem o -u

# Para mais informações sobre o Github <a href="https://docs.github.com/pt/get-started">Access</a>
