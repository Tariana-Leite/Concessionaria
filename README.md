# Projeto Concessionária
Este repositório é um projeto desenvolvido em parceria com @summonsumo em um curso de Engenharia de Dados utilizando a plataforma Databricks.


## Arquitetura
A figura abaixo ilustra de forma bastante simplificada como ocorreu a comunicação entre os componentes.
Os arquivos utilizados vieram de um servidor SFTP onde o cliente hipotético postou conforme sua necessidade.
Depois de carregado no Datalake, a plataforma Databricks foi usada para limpeza e preparação para consumo.

![projeto_concessionaria drawio (1)](https://user-images.githubusercontent.com/121232292/210135812-afd2fd40-1fda-4a43-bacd-6853a093d026.png)

## Setup
Como já comentado acima, o projeto fez parte de um curso destinado a ensinar Engenharia de Dados de forma prática fazendo uso da plataforma Databricks.
Para a reprodução deste material, há a necessidade de um acesso. 
Dentro do site da Azure mesmo você pode criar uma [conta de teste gratuita](https://azure.microsoft.com/pt-br/free/databricks/?&ef_id=Cj0KCQiAw8OeBhCeARIsAGxWtUzyuJDgdon5Z3mJQY5kR4J6Wbn6fdLU5JqgKA5D_Ewm85h7dOYbGVYaAsj6EALw_wcB:G:s&OCID=AIDcmmzmnb0182_SEM_Cj0KCQiAw8OeBhCeARIsAGxWtUzyuJDgdon5Z3mJQY5kR4J6Wbn6fdLU5JqgKA5D_Ewm85h7dOYbGVYaAsj6EALw_wcB:G:s&gclid=Cj0KCQiAw8OeBhCeARIsAGxWtUzyuJDgdon5Z3mJQY5kR4J6Wbn6fdLU5JqgKA5D_Ewm85h7dOYbGVYaAsj6EALw_wcB) e seguir os passos simples descritos no próprio site:
- Logar com sua conta microsoft;
- Aceitar os termos de contrato de uso; e 
- Colocar os dados de um cartão de crádito válido. 

Ou ainda há a possibilidade de utilização da plataforma [Datatabricks Community](https://community.cloud.databricks.com):
- Clicar no botão [sign up](https://community.cloud.databricks.com/login.html);
- Fazer cadastro e escolher get started with Community Edition;
- Confirmar seu email; e
- Esta pronto para uso =D

