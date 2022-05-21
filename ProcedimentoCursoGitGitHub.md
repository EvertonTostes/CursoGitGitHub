### Passo-a-passo para Inserir Pasta no GitHub

- Terminal Git Bash:

  1) Abra o Git Bash dentro do Este Computador > OS (C);

  2) Crie a Pasta através do comando $ mkdir CursoGitGitHub;

  3) Dê um comando $ ls para verificar se realmente a pasta CursoGitGithub foi criada;

  4) Iniciar o repositorio Git $ git init;

  5) Configurar os dados pela primeira vez no Git:

     $ git config --global user.email "evertontostes@gmail.com"

     $ git config --global user.name "EvertonTostes";

- Criar Arquivo dentro da Pasta CursoGitGitHub com as descrições dos comandos;

- Voltar para o Terminal Git Bash;

  1. Adicionar o arquivo para realizar o commit;

     $ git add *;

     $ git commit -m "commit inicial";

- Entrar no GitHub e criar um novo Repositório;

- Copiar o Link do Repositório criado e dentro do Terminal do Git Bash novamente:

  $ git remote add origin https://github.com/EvertonTostes/CursoGitGitHub.git

  $ git push origin master

- Entrar novamente do GitHub e recarregar;

Finished.



