# [Lab Project DIO - Santander Bootcamp 2023 - Ciência de Dados com Python](https://web.dio.me/track/71477949-f762-43c6-9bf2-9cf3d7f61d4a?tab=about)

## [Processando e Transformando Dados com Power BI](https://web.dio.me/lab/processando-e-transformando-dados-com-power-bi/learning/dc02898f-eee6-48b1-90b5-c0ef3f4f375a)

### Descrição do desafio: 
Processamento de dados simplificado com Power BI. Os arquivos de dados estão disponíveis no GitHub: 
[https://github.com/julianazanelatto/power_bi_analyst/tree/main/M%C3%B3dulo%203/Desafio%20de%20Projeto](https://github.com/julianazanelatto/power_bi_analyst/tree/main/M%C3%B3dulo%203/Desafio%20de%20Projeto) 

### Diretrizes: 

#### Preparação do ambiente:

- Criar uma instância na Azure para MySQL; `ok`
- Criar o Banco de Dados com base disponível no [GitHub](https://github.com/julianazanelatto/power_bi_analyst/tree/main/M%C3%B3dulo%203/Desafio%20de%20Projeto); `ok`
- Integrar o Power BI com o MySQL na Azure; `ok`
- Verificar problemas na base a fim de realizar a transformação dos dados. `ok`

<img src="/images/azure1.png">

<img src="/images/azure2.png">

#### Transformação dos dados:

- Verificar os cabeçalhos e tipos de dados; `ok (obs.: as datas foram colocadas no formato Short Date)`
- Modificar os valores monetários para o tipo double preciso; `Efetuada a modificação na coluna Salary da tabela employee`
- Verificar a existência de nulos e analisar a remoção; `ok`
- Os employees com nulos em Super_ssn podem ser os gerentes. Verificar se há algum colaborador sem gerente; `Sim, o de Ssn 888665555`
- Verificar se há algum departamento sem gerente; `Todos os departamentos têm gerente`
- Se houver departamento sem gerente, suponha que você possui os dados e preencha as lacunas; `ok`
- Verificar o número de horas dos projetos; `Efetuada modificação para número inteiro`
- Separar colunas complexas; `ok`
- Mesclar consultas employee e departament para criar uma tabela employee com o nome dos departamentos associados aos colaboradores. A mescla terá como base a tabela employee; `ok`
- Neste processo eliminar as colunas desnecessárias; `ok`
- Realizar a junção dos colaboradores e respectivos nomes dos gerentes. Isso pode ser feito com consulta SQL ou pela mescla de tabelas com Power BI; `ok`
- Mesclar as colunas de Nome e Sobrenome para ter apenas uma coluna definindo os nomes dos colaboradores; `ok`
- Mesclar os nomes de departamentos e localização. Isso fará que cada combinação departamento-local seja único; `ok`
- Agrupar os dados a fim de saber quantos colaboradores existem por gerente; `ok`
- Eliminar as colunas desnecessárias, que não serão usadas no relatório, de cada tabela. `ok`

<img src="/images/tabelaT.png">

<img src="/images/painel.png">

