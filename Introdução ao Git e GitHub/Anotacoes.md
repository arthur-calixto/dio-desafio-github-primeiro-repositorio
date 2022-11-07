# Git e Github

PROMPT DE COMANDO

dir - Listar no Windows || ls - listar no linux
cd - Navegar
cls - Limpar tela no Windows || clear - limpar no linux ou ctrl + l
tab - autopreenchimento
mkdir + nome da pasta - para criar pasta no Windows e no linux também
echo - para criar arquivos
del + nome da pasta ou nome do arquivo - para deletar arquivos que estejam dentro desta pasta
rmdir + nome da pasta - para deletar a pasta
Ls -a - mostrar arquivos ocultos no git bash

Tópicos fundamentais do Git (Usando Git Bash)

SHA1 -  é um algorítmo de criptografia, ele é um algpritmo pega determminada informação e faz a encriptação.
> Gera um conjunto de carctere identificador de 40 dígitos.
> Cada vez que o arquivo é alterado ele gera um novo código identificador.
> Se a alteração for revertida ele volta a ter o código de indentificação anterior.

Objetos internos do GIT

Blobs -  Sha1 dos arquivos.

Trees - Árvores que apontam para os blobs e o nome dos arquivos.

Commits - Da significancia para o conjunto de alterações realizadas, que por sua vez aponta para as árvores e consequentemente para os Blobs.

Chave SSH - Forma de estabelecer uma conexão segura entre duas máquinas.
comandos para gerar chave SSH
ssh-keygen -t ed25519 -C + e-mail
Exemplo: ssh-keygen -t ed25519 -C arthur-calixto@hotmail.com

para inicializar o SSH: eval $(ssh-agent -s)

Comandos no Git

Git init - Iniciar um repositório.
Git status - para ver o status do repositório
Git Add - usamos o git add * || git add. || git add + nome do arquivo
Git Commit - git commit -m "msg"
Para subir o commit para o GitHub - git push origin master
