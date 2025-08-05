RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 05/08/2025
Empresa: Abstergo Industries
Responsável: Ivan Monteiro

Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Ivan Monteiro. O objetivo do projeto foi elencar 3 serviços AWS com a finalidade de realizar diminuição de custos imediatos.

Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos.A seguir, serão descritas as etapas do projeto:

Etapa 1: Amazon S3 (com Intelligent-Tiering)
Foco: Armazenamento de dados de pesquisa e documentação regulatória.
Descrição de caso de uso:
A Abstergo Industries enfrentava altos custos operacionais com o armazenamento local de grandes volumes de documentos de pesquisa científica e registros regulatórios exigidos por órgãos fiscalizadores. Esses arquivos, embora importantes, eram acessados com pouca frequência, o que tornava o investimento em servidores locais pouco eficiente.

Com a adoção do Amazon S3 utilizando o recurso Intelligent-Tiering, a empresa passou a armazenar esses dados na nuvem com gestão automática de camadas de armazenamento. Isso significa que os documentos acessados com menor frequência são automaticamente movidos para camadas de custo reduzido, sem impacto na performance quando forem necessários.

Esse modelo resultou em redução imediata de custos com armazenamento, eliminação de gastos com manutenção de hardware e maior segurança e disponibilidade dos arquivos críticos para a operação da empresa.

Etapa 2: Amazon RDS (PostgreSQL)
Foco: Banco de dados relacional para sistemas internos de controle de qualidade e estoque.
Descrição de caso de uso:
A Abstergo Industries utilizava um banco de dados local para gerenciar os sistemas internos de controle de qualidade e estoque. Essa infraestrutura apresentava limitações como falta de alta disponibilidade, necessidade de manutenção manual e risco elevado de perda de dados em caso de falhas.

Com a migração para o Amazon RDS (PostgreSQL), a empresa passou a contar com uma solução gerenciada, que oferece backups automáticos, aplicação de patches de segurança, escalabilidade e failover automático. Isso garantiu a continuidade das operações críticas, mesmo em situações imprevistas, e reduziu o tempo e os recursos gastos com administração de servidores.

O resultado foi um sistema mais confiável, seguro e eficiente, com custos operacionais controlados e maior capacidade de resposta às demandas internas da empresa.

Etapa 3: AWS Lambda + API Gateway
Foco: Automatização de relatórios laboratoriais e geração de alertas de estoque.
Descrição de caso de uso:
Na rotina da Abstergo Industries, tarefas como geração de relatórios laboratoriais e emissão de alertas de estoque eram realizadas manualmente ou por sistemas que dependiam de servidores em tempo integral, gerando custos com infraestrutura ociosa e baixa escalabilidade.

Com a adoção do AWS Lambda em conjunto com o API Gateway, essas tarefas foram automatizadas e passaram a ser executadas por funções serverless, que só consomem recursos quando são acionadas. Isso permitiu à empresa eliminar servidores dedicados para tarefas simples, além de ganhar agilidade no processamento de dados, reduzir custos operacionais e aumentar a capacidade de resposta do sistema.

Essa mudança resultou em uma operação mais enxuta, moderna e adaptável à demanda real, com foco na eficiência e no uso inteligente dos recursos da nuvem.

Conclusão
A implementação das ferramentas AWS na Abstergo Industries proporcionou benefícios significativos, especialmente na redução de custos e aumento da eficiência operacional. O uso do Amazon S3 com Intelligent-Tiering otimizou o armazenamento de dados, o Amazon RDS garantiu alta disponibilidade e segurança para os sistemas internos, e o AWS Lambda com API Gateway eliminou a necessidade de infraestrutura ociosa. Com essas soluções, a empresa alcançou maior escalabilidade, automação e controle, consolidando um ambiente mais moderno e econômico.
