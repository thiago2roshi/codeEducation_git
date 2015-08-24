# Projeto inicial de github

curso ministrado pela code education/school of net, acessado em agosto de 2015.

## Release 0.1.1

### configurações do github
#### como setar o seu nome nos commits globalmente na maquina
git config --global user.name "SEU NOME"

#### como setar o seu email globalmente
git config --global user.email "SEUNOME@E.MAIL"

#### setar o editor de texto padrao para o git
git config --global core.editor atom

#### setar a ferramenta para o diff (resolução de conflito de merge)
git config --global merge.tool DIFF_TOOL

#### exibir as configurações usadas
git config --list


##Release 0.1.0

### comandos usados

#### git init
inicia um repositorio na pasta atual
bare
#### git status
exibe os arquivos com diferenças não comitadas

#### git add
seta os arquivos para o estagio de commit

#### git commit -m 'descrição do commit'
faz o commit dos arquivos setados no passo anterior

#### git checkout -b ___nomeDoBranch___
criar um branch do repositorio atual

#### git checkout ___nomeDoBranch___
alterna para o branch citado

#### git remote add origin __git@github.com:USER/REPOSITORY.git__

seta o repositorio remoto (github) para sincronização (via ssh neste exemplo)

#### git push
sincroniza o repositorio __local__ com o que ha no __remoto__

#### git pull
igual ao ___push___ so que este envia para o remoto o que ha no repositorio local

#### git tag 0.0.0
coloca uma tag no commit atual, para setar a versão atual do codigo/sistema

#### git init --bare
cria um repositorio apenas de armazanamento, como o proprio github, mas localmente

#### __hooks__
no repositorio criado com o parametro __--bare__, podesse fazer automação dos arquivos, como copia-los para um servidor, compilar ou qualquer outro tipo de automação que deseje.
