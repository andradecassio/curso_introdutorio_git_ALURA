# Outro curso de git da ALURA

* disponivel em: https://cursos.alura.com.br/course/git-github-controle-de-versao

Informar que uma pasta é um repositório do git:
*  git init  

Tudo que estiver nessa pasta será monitarado pelo git

Para passar a monitorar um arquivo que nunca foi editado ou salvo pelo git:
 * git add nome_do_arquivo
 * git add .   (para todos os arquivos) 

Configurando usuário apenas para o repositório atual, apenas para esse projeto:
 * git config --local user.name "Nome do Usuário"
 * git config user.email   (verifica o email do usuario logado) 

Histórico:
* git log
*  git log --oneline (forma resumida)
* git log -p (visualiza as alterações realizadas)
* outras personalizações: https://devhints.io/git-log

Ignorar arquivos:
* criar arquivo chamado gitignore
* git irá ignorar todos os arquivos que estivem listados nesse arquivo
* lembrar de adicionar o arquivo: git add gitignore
* comitar alterações

