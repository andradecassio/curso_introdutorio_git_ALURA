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
* git log -p (visualiza as alterações realizadas --- após o comando aperte a tecla Q para voltar à tela de comando)
* outras personalizações: https://devhints.io/git-log

Ignorar arquivos:
* criar arquivo chamado gitignore
* git irá ignorar todos os arquivos que estivem listados nesse arquivo
* lembrar de adicionar o arquivo: git add gitignore
* comitar alterações

Criando um servidor:

Suponha que uma pasta local será o servidor C:\git\servidor_local\

* cd servidor_local
* git init --bare 
* repositorio puro: so contem alterações dos arquivos, e nao a copis fisica deles
* (repositorio do git que so vai controlar alteracoes, nao entra pra editar arquivos)

Voltando para uma outra pasta que seja o repositorio do git C:\git\aplicacao\ e fazer com que ele conheça servidor_local como  servidor
* git remote (lista todos os repositorios remotos que o repositorio em questao conhece)
* git remote add qq_nome_para_servidor caminho_do_servidor
* caminho_do_servidor pode ser um endereço url, uma pasta, de um PC, de uma rede
* git remote -v (mostra os endereços)

Enviando o repositorio para o servidor recem criado:
* git push servidor_local main (vai enviar dados do branch main para servidor local)

Outra pessoa conectada ao servidor remoto que queira pegar os dados que estão lá:
* git pull nome_repositorio_remoto branch_destino
