Arquivo de orientação para criação de stack REDMINE

Criar primeiramente o secret com a senha

echo "senha" | docker secret create rdm_dbpass -

Alterar apenas a senha onde tem a palavra senha

Fazer deploy primeiro do BANCO com o nome da stack redmine_db
Essa stack irá criar a network e a base que o REDMINE irá usar

Tendo feito sem erros, realizar o deploy do Redmine com o nome da stack redmine


