#Projeto feito em 1 dia e meio então não está 100% contém alguns erros, mais continua sendo funcional!
##Processo para que o projeto funcione corretamente quando você for testar!

1. Instale o banco de dados.
-   Estou deixando um arquivo sql que e o backup do banco de dados
-  você faz o export dele no seu serviço de banco de dados e faz
-   as devidas alterações no arquivo (DAO>Conexao.java em static final private String caminho =
                                                                      "jdbc:mysql://localhost/cinemamanager";
                                                              static final private String usuario = "root";
                                                              static final private String senha = "password";
    Coloque as configurações do seu sistema de banco de dados!
    Caso sejam diferentes.

2. Para iniciar o programa, vá na raiz do package e compile o arquivo "Main.java"
se todas as conexões estiverem corretas, aparecerar um pequeno painel na tela dizendo "Conexao Realizada"
e é so voce da Ok que ele continuará

Atenção nem todas os paneis são via JOptionPane
alguns comandos são pelo console então deixe o seu console aberto!

Esquema de usuarios.
1 usuario pode ter 3 niveis
```
no nivel 1 ele apenas visualiza os filmes, salas e sessões
o nivel 2 faz o mesmo do 1 so que ele consegue adicionar filmes
o nivel 3 faz tudo, como:
Visualizar filmes, salas e sessões
Criar filmes, salas e sessões
Modificar filmes, salas e sessões
Excluir filmes, salas e sessões
e tambem criar usuarios.
e todos os usuarios tem a opção de deletar sua conta!
```
> User e Password para cada nivel:

nivel 1 =>
User = user1
Password = user1

nivel 2 =>
User = user2
Password = user2

nivel 3 =>
User = user3
Password = user3

Vlw!
https://github.com/WilliamRodri
https://www.instagram.com/will_tnc/
