# Tutorial MySQL

## Como criar um banco de dados

### Inicie o MySQL Workbench no seu computador

Clique em “+” ao lado de "MySQL Connections" para abrir uma nova conexão.
Preencha os detalhes da conexão (hostname, username, etc.) e clique em “OK”.
![primeira etapa.](https://github.com/rafinhafreire/aula-de-programacao-trio/blob/main/etapa1.png)





No painel de navegação à esquerda, clique com o botão direito na opção "Schemas" (Esquemas).
Selecione “Create Schema…” (Criar Esquema).
![segunda etapa.](https://github.com/rafinhafreire/aula-de-programacao-trio/blob/main/etapa2.png)

Na janela que se abre, digite o nome do seu banco de dados no campo “Name”.
Verifique se o “Default Character Set” está configurado corretamente (geralmente, utf8mb4 é uma boa escolha).
![terceira etapa.](https://github.com/rafinhafreire/aula-de-programacao-trio/blob/main/etapa3.png)
> Clique em “Apply” (Aplicar).
> Uma nova janela mostrará o SQL que será executado. Clique em “Apply” novamente e após a execução, clique em “Finish” para concluir.

![quarta etapa.](https://github.com/rafinhafreire/aula-de-programacao-trio/blob/main/etapa4.png)
O novo banco de dados aparecerá na lista de Schemas (Esquemas) no painel à esquerda.
Você pode clicar nele para ver opções como criar tabelas, visualizar dados, etc.
![quinta etapa.](https://github.com/rafinhafreire/aula-de-programacao-trio/blob/main/etapa5.png)


## Como criar uma tabela

_Observações:
Essas são as estruturas de uma Tabela_

_Nome da Tabela: Identifica a tabela no banco de dados.
Colunas: Cada coluna tem um nome e um tipo de dado (ex.: INT, VARCHAR, DATE).
Chaves:
Chave Primária: Identifica de forma única cada linha na tabela.
Chave Estrangeira: Estabelece um relacionamento com outra tabela._

Clique com o botão direito no nome do seu banco de dados no painel de navegação à esquerda.
Selecione “Create Table…”.
![sexta etapa.](https://github.com/rafinhafreire/aula-de-programacao-trio/blob/main/etapa6.png)

Nome da Tabela: Digite o nome da sua nova tabela.
Definir Colunas: Na aba “Columns”, você pode adicionar colunas:
Clique em “Add” para adicionar uma nova coluna.
Defina o Nome, Tipo (ex.: INT, VARCHAR, etc.), e outras propriedades (como se pode ser nulo ou não).
Marque uma coluna como “Primary Key” se for a chave primária.
![setima etapa.](https://github.com/rafinhafreire/aula-de-programacao-trio/blob/main/etapa7.png)
> Se você tiver chaves estrangeiras, vá até a aba “Foreign Keys” e adicione os relacionamentos necessários com outras tabelas.

![oitava etapa.](https://github.com/rafinhafreire/aula-de-programacao-trio/blob/main/etapa8.png)



Após criar a tabela, você pode visualizá-la no painel de navegação.
Para inserir dados, clique com o botão direito na tabela e selecione “Select Rows” para abrir um editor onde pode adicionar novos registros.
![nona etapa.](https://github.com/rafinhafreire/aula-de-programacao-trio/blob/main/etapa9.png)
> Para alterar a estrutura da tabela, clique com o botão direito e escolha “Alter Table…”.

![decima etapa.](https://github.com/rafinhafreire/aula-de-programacao-trio/blob/main/etapa10.png)



