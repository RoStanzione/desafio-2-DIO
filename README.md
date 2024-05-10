# desafio-BI-DIO

- O primeiro passo do projeto foi criar as tabelas no banco de dados, decidi utilizar o MariaDB. 
- Após isso, conectei minha base de dados com o PowerBI.
- Com as tabelas carregadas, iniciei a transformação dos dados.
- O primeiro passo foi verificar se estava tudo certo, fazer um reconhecimento das informações e posteriormente o tratamento dos dados.
- 
- Tabela Employees:
  . renomeei algumas colunas
  . alterei o tipo de dado na coluna Salary para Moeda(Decimal Fixo)
  . separei a coluna Address, criando a coluna City e State
  . todos os colabores possuem gerente
  
  - Foi feita a mescla da tabela employee com a department, criando uma nova tabela, Employee/Department
    . Na nova tabela fiz a junção da coluna Fname(First name) com a Lname(Last name)

  - Realizei o agrupamento de Employees por Department pelo próprio Power BI

  - Após o processo de transformação dos dados criei um relatório que esta disponível no repositório
    
   
  
