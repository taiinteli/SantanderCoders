# Git e Versionamento

## Gravando Mudanças no Repositório

<br>

 ![Estatdos Git](https://raw.githubusercontent.com/taiinteli/SantanderCoders/master/midea/estados_git.png) 

- `git status `: com ele é possível verificar o status dos arquivos antes de realizar uma confirmação. Ele sintetiza os seguintes tipos de informações:

Arquivos modificados -> São arquivos que foram alterados, mas ainda não foram adicionados para a próxima confirmação (commit).

Arquivos a serem confirmados -> São arquivos que foram modificados e adicionados à área de preparação (staging area) para a próxima confirmação (commit).

Arquivos não rastreados -> São arquivos novos que foram adicionados ao diretório de trabalho, mas ainda não foram adicionados à área de preparação.

- `git add .\readme.md`: adicionar à área de preparação (staging area) do repositório Git. Assim, as alterações feitas no arquivo "readme.md" são incluídas no próximo commit.

- `git diff`: ele serve para mostrar as diferenças entre o estado atual do repositório Git e o último commit. Em vermelho é o que foi alterado ou removidas e o verde é aquelas linhas que foram adicionadas. 

- `git commit -m "Mensagem do commit"`: é usado para criar um novo commit no repositório Git com uma mensagem de commit associada. Com ele é possível fornecer uma mensagem de commit diretamente na linha de comando, em vez de abrir um editor de texto para escrever a mensagem. A mensagem de commit é uma descrição breve e concisa das alterações feitas no commit.

- `git log`: serve para exibir o histório de todos os commits que foram feitos.  