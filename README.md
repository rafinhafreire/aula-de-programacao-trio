# Tutorial MySQL

## Como criar um banco de dados

### Inicie o MySQL Workbench no seu computador

Clique em “+” ao lado de "MySQL Connections" para abrir uma nova conexão.
Preencha os detalhes da conexão (hostname, username, etc.) e clique em “OK”.
![primeira etapa.](https://github.com/rafinhafreire/aula-de-programacao-trio/blob/main/etapa1.png)
> Clique duas vezes na conexão para se conectar ao servidor.


No painel de navegação à esquerda, clique com o botão direito na opção "Schemas" (Esquemas).
Selecione “Create Schema…” (Criar Esquema).
![segunda etapa.](https://github.com/rafinhafreire/aula-de-programacao-trio/blob/main/etapa2.png)

Na janela que se abre, digite o nome do seu banco de dados no campo “Name”.
Verifique se o “Default Character Set” está configurado corretamente (geralmente, utf8mb4 é uma boa escolha).
![terceira etapa.](https://github.com/rafinhafreire/aula-de-programacao-trio/blob/main/etapa3.png)
> Clique em “Apply” (Aplicar).
> Uma nova janela mostrará o SQL que será executado. Clique em “Apply” novamente e após a execução, clique em “Finish” para concluir.

O novo banco de dados aparecerá na lista de Schemas (Esquemas) no painel à esquerda.
Você pode clicar nele para ver opções como criar tabelas, visualizar dados, etc.
![quarta etapa.](https://github.com/rafinhafreire/aula-de-programacao-trio/blob/main/etapa4.png)

## Como criar uma tabela

_Observações:
Essas são as estruturas de uma Tabela
Nome da Tabela: Identifica a tabela no banco de dados.
Colunas: Cada coluna tem um nome e um tipo de dado (ex.: INT, VARCHAR, DATE).
Chaves:
Chave Primária: Identifica de forma única cada linha na tabela.
Chave Estrangeira: Estabelece um relacionamento com outra tabela.
Criando uma Tabela no MySQL Workbench
Aqui está um passo a passo para criar uma tabela:_
