# BI-projeto-Dio

## Desafio de Projeto – Processamento de Dados Simplificado com Power BI

### Instruções de Entrega do Desafio
1.	Criação de uma instância na Azure para MySQL
2.	Criar o Banco de dados com base disponível no github
3.	Integração do Power BI com MySQL no Azure 
4.	Verificar problemas na base a fim de realizar a transformação dos dados Diretrizes para transformação dos dados
1.	Verifique os cabeçalhos e tipos de dados
2.	Modifique os valores monetários para o tipo double preciso
3.	Verifique a existência dos nulos e analise a remoção
4.	Os employees com nulos em Super_ssn podem ser os gerentes. Verifique se há algum colaborador sem gerente
5.	Verifique se há algum departamento sem gerente
6.	Se houver departamento sem gerente, suponha que você possui os dados e preencha as lacunas
7.	Verifique o número de horas dos projetos
8.	Separar colunas complexas
9.	Mesclar consultas employee e departament para criar uma tabela employee com o nome dos departamentos associados aos colaboradores. A mescla terá como base a tabela employee. Fique atento, essa informação influencia no tipo de junção
10.	Neste processo elimine as colunas desnecessárias. 
11.	Realize a junção dos colaboradores e respectivos nomes dos gerentes . Isso pode ser feito com consulta SQL ou pela mescla de tabelas com Power BI. Caso utilize SQL, especifique no README a query utilizada no processo.
12.	Mescle as colunas de Nome e Sobrenome para ter apenas uma coluna definindo os nomes dos colaboradores
13.	Mescle os nomes de departamentos e localização. Isso fará que cada combinação departamento-local seja único. Isso irá auxiliar na criação do modelo estrela em um módulo futuro.
14.	Explique por que, neste caso supracitado, podemos apenas utilizar o mesclar e não o atribuir. 
15.	Agrupe os dados a fim de saber quantos colaboradores existem por gerente
16.	Elimine as colunas desnecessárias, que não serão usadas no relatório, de cada tabela

<div>

# Imagens Referente ao Projeto

**Criação de Banco de Dados MySql no Azure**
![azure_project](https://github.com/Naldo85/BI-projeto-Dio/assets/82780957/56ab3a4c-69fa-4222-8b3d-414d67a08220)

**Conexão com Banco de Dados no Azure Usando o Workbench**
![conection_MySql](https://github.com/Naldo85/BI-projeto-Dio/assets/82780957/4b2f2c9b-7afa-414f-a37d-0cd35de97e67)

## Componentes do relatório:
**Relatório Proposto no Projeto**
![project_BI_dio](https://github.com/Naldo85/BI-projeto-Dio/assets/82780957/02d41f78-ceb8-45d5-a08f-9266d485a6e2)
  - Três cartões na parte superior nos quais descrevem respectivame nte: Contagem de Colaboradores, Contagem de Gerentes e Soma de Horas Executadas;

  - Na parte mais a direita do relatório, um gráfico de Colunas Clusterizado, no qual descreve no eixo Y a soma de horas, enquanto no eixo X o Nome;

  - As visões na parte inferior esquerdo do relatório, encontra-se disposto dois gráficos no qual são eles: Um Gráfico de Rosca descrevendo Quantidade de Dependente por Colaborador e  Um Gráfico de Cascata refletindo a contagem de Colaboradores por Departamento.

  - Ainda na parte inferior, mas disposto na parte central, um gráfico de Barras de contagem de Horas por Projetos;

  - Por fim, a última visão da parte inferior do relatório, um gráfico de Pizza. Neste foram agrupados a contagem de Colaboradores por Cidade.

</div>


## 📚 Referências
- **[Projeto Power_BI_Analyst](https://github.com/julianazanelatto/power_bi_analyst)**
