<h1> Curso introdutório de Git e Github </h1>

# Outra forma de cabeçalho

> Disponível em: https://cursos.alura.com.br/course/git-github-repositorio-commit-versoes

Exemplo de texto no formato de código

```
node app_em_javascript.js
```

# Commit

* é um rótulo das alterações que estão sendo realizadas
* modo como estava o projeto em determinado momento

* segurando a tecla '.' no site do github, ele abre uma versão dev utilizando o VSCODE
* apertando a tecla '.' o VSCode sugere um texto pra html

* para dar o commit (enviar alterações): aba Source Control (ctrl+sfht+g), dá o nome e aperta na setinha OK

* clicando na mensagem do commit vc consegue ver todas as alterações que foram feitas nesse estado

* para copiar o projeto na maquina de forma local (clonar o repositório):
* vai no repositório --- <>code --- e copia o link
* abre o terminal/powershell
* para ver os arquivos do diretorio atual
  * ls
* para mudar de diretorio
  * cd 
  * git clone link

* comando para ver historico de alterações:
  * git log
* para ver apenas títulos dos commits: 
  * git log --oneline

* comando para limpar a tela:
  * ctrl+L

* se você clonar (git clone) você apaga tudo o que tem localmente e copia o que está no github

* agora para atualizar conforme o estado que está no github, usa-se:
  * git pull link

# Usando VSCode localmente

* pode ser usado o terminal internamente no VSCode
  * ctrl+J

* para visualizar a situação do momento:
  * git status

OBS: salvar o arquivo antes no VSCode para dar o commit!

* da pra criar o commit via comando (similar no github) ou via código
  * git commit (nome do arquivo) -m "titulo do commit"
  * git commit . -m "titulo do commit" (para todos os arquivos)

* empurrar todos os commits para o repositório
  * git push (local desejado: origin main)
  
 
