# SHA1
A sigla SHA significa Secure Hash Algorithm
(algoritmo de Hash Seguro), é um conjunto
de funções hash criptográficas projetadas pela 
NSA.

A encripatação gera conjunto de characteres 
identificador de 40 digitos.

Objetos do GIT

BLOBS

TREES

COMMITS

echo 'conteudo' | git hash-object --stdin

gerando a chave SSH
ssh-keygen -t ed25519 -C seuemail@algo.com

vai até a pasta onde gerou o ssh
cd /root/.ssh
cat nomedoarquivo.pub

ativando o sshagent
eval $(ssh-agent -s)

ssh-add id_chaveprivada

pega a saida desse arquivo e cola lá no github

criando um repo
mkdir livros-receitas
cd livros-receitas
git init
ls -a
git config --global user.email "douglas.littig@gmail.com"
git config --global user.name gittil

git add *
git commit -m "commit inicial"

_______________________________________

git status

mkdir receitas

mv batata-frita.md ./receitas/

git status

git add batata-frita.md receitas/

git commit -m "cria pasta receitas e move arquivos"

echo > README.md

git status

________________________________________

git --config


alterando a configuração de email e nome
git config --global --unset user.email
git config --global --unset user.name

indicando o repositorio remoto
git remote add origin endereçodorepo

git remote -v
git status

git push origin main










