## Alguns comandos úteis do Git

Repositório criado com o intuito de listar alguns dos comandos úteis do terminal Git, aprendidos no curso DevStart da BeAcademy.

## Linhas de comandos

- git init: inicia um repositório vazio naquele diretório.
- git status: mostra o estado atual do projeto, quantos as modificações de um ou mais arquivos, se foram ou não "commitados".
- git add: empacota um arquivo específico <nome do arquivo> ou todos os arquivos <.>, movendo-o(s) para a área de preparação (staging area) antes do commit.
- git rm --cached <nome do arquivo>: desfaz a ação de "empacotamento", retirando o arquivo da área de preparação (staging area)
- git commit: salva o estado daquele(s) arquivo(s) até o momento. Ideal que seja acrescido de -m "descrição das alterações", para identificação do que foi feito naquele "pacote".
- git log: mostra um histórico dos commits já efetuados.
- git branch: lista todas as branches locais que existem e, em qual branch você está, naquele momento.
- git branch <nome da branch>: cria uma branch nova e vazia.
- git checkout <nome da branch>: serve para tornar aquela branch, a branch ativa no momento. Navegação entre as branches.
- git checkout -b <nome da branch>: cria uma branch nova e automaticamente já a torna a branch ativa no momento.
- git branch -d <nome da branch>: remove/deleta aquela branch.
- git merge <nome da branch>: unifica as alterações entre duas branches. Imporante que o comando traz as alterações de uma segunda branch, portanto, é necessário estar na branch mais "desatualizada".