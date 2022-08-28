# Apache Airflow - Docker Compose - PostgresSQL

Este repositório foi criado com base no uso das ferramentas: 
- **Apache Airflow** </br>
Uma orquestradora e automatizadora de fluxos de tarefas e trabalhos muito incrível, com diversos recursos e exemplos existentes para buscar adaptar cada situação da melhor maneira

- __PostgresSQL__ </br>
Banco de dados relacional open source, combinando o Apache Airflow junto com ele, podemos criar fluxos de tarefas de maneira paralela, otimizando recursos e tempo de execução.

- __Docker Compose__ </br>
Ferramenta que facilita a gestão de containers e seus serviços / microsserviços através do arquivo yml posso replicar todo meu ambiente montado localmente em outras máquinas, facilitando o processo de uso e instalação das ferramentas anteriores


##### Observação
Pode haver um erro de permissionamento nas pastas que serão criadas ou habilitadas pelo uso do Docker Compose, procure por mudanças de permissão, por exemplo chmod ou algum similar em powershell.
Realize a mudança permitindo que o Airflow faça a escrita dos logs e eventuais arquivos que suas DAGS criem