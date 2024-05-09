# santander-2024-preparatorio-certificacao-aws

## Introdução 
Aws é um sistema de computação em nuvem que tem como um dos principais beneficios a economia de custos para quem a utiliza. 

Diferença entre computação em nuvem e computação tradicional:

### Tradicional: 
- Comprar 
- Instalar 
- Configurar 
- Manter 
- Servidores 
- Redes 
- Softwares 
- Outros recursos 

É necessário um alto investimento para montar e manter toda infraestrutura. 

- Invetimento alto inicial  
- Arcar com custos de operação, manutenção, atualização, segurança e suporte. 
- Estimar demanda e provisionar recursos
- Desperdicio de recursos: demanda menor do o esperado 
- Falta de recursos: demanda maior do que o esperado
- Pagar por recursos q são seram utilizados por uma estimativa imprecisa 

### Nuvem 
Na compputação em nuvem você não tem a necessidade de comprar esses recursos e sim de aluga-los de um provedor como o aws da amazon. 

- Aluguel de recursos conforme necessidade
- Paga somente pelo que usa e pelo tempo que usa
- Escalável conforme demanda 

Na nuvem você não paga por recursos não utilizados ou q não comprem as demandas e esse modelo é chamado de dimensionamento sendo um dos aspectos ecônomicos mais importantes da aws.  
O Dimensionamento pode se dividir em dois tipos:
- Vertical 
- Horizontal

O vertical significa aumentar ou dimuir a capacidade de um único recurso.(Exemplo: 1 servidor )
Já o horizontal significa aumentar ou dimuir o numero de recusos. (Exemplo: varios servidores). 

- A nuvem aws conta com os dois tipos de forma manual ou automática. 

### Infraestrutura Global 

Organização dos recursos: 
- Regiões 
    - área geografica com um conjunto de data centers
    - servidores 
    - Redes 
    - Banco de dados
    - Outros recursos de TI

- Zonas de Disponibilidade
    - Parte isolada de uma região com um ou mais data centers 
    - Conectados por redes de alta velociadde e baixa latência 

Vantagens da infraestrutura Global:
- Velocidade de implantação 
    - lançamento rápido de recursos de TI em qualquer região/zona 
- Alcance Global 
    - Distribuição dos recursos conforme localização dos usuários/clientes 
    - Redução da latência, melhora de perfamance e satisfação 
    - Atendimento aos requisitos de conformidade

Vantagens da Alta Disponibilidade, Elasticidade e Agilidade

- Alta disponibilidade 
    - recursos sempre acessíveis e operacionais
    - Redundância 
    - balanceamento 
    - Backup 
    - Recuperação 

- Elasticidade 
    - Adaptação á demanda 
    - Manual ou automática 
    - Não compromete qualidade ou custo 

- Aglilidade 
    - Lançamento, modificação ou encerramento rápido 
    - Por uma inface web, linha decomando ou API

## AWS Well-Architected Framework

#### O que é AWS Well-Architected Framework? 

é um conjunto de práticas recomendadas para projetar e operar sistemas na nuvem aws que ajuda aprender as melhores práticas de arquiteturas para sistemas confiáveis, seguros, eficientes, econômicos e sustentáveis na nuvem.

#### Por que usar o AWS Well-architected Framework?

Usalo traz beneficios como 
- aumentar a confiança e a capacidade de tomar decisões arquiteturais informadas. 
- Melhorar a qualidade e a perfomance dos sistemas na nuvem. 
- acelerar a inovaçõs e a entrega de valor para s clientes   
- alinhar os sistemas com as melhores práticas e os padão da AWS
- preparar-se para o exame AWS Cloud Practitioner 

#### Como usar o AWS Well-ARchitected Framework?

Os pilares do AWS Well-Architected Framework (6 pilares) 
- Excelencia operacional 
    - Se concentra na execução e monitoramento de sistemas e na melhoria constante dos processos e procedimentos
        - Automatizar mudanças
        - Reagir a eventos 
        - Definir padrões 
        - Antecipar falhas 
        - aprender com a experiência 

- Segurança 
    - Se concentra na proteção de informações e sistemas, incluindo  confidencialidade, integridade, disponibilidade de dados, gerenciamentos de identidade e acessos e detecção e resposta a eventos de segurança.
    - proteção de informações e sistemas
        - Implemantar um forte controle de identidade 
        - Criptografia de dados 
        - Defesa em profundidade 
        - Automatização de segurança 
        - Preparação para incidentes

- Confiabilidade 
    - se concentra na capacidade dos sistemas de executar as funções pretendidas e de se recuperar rapidamente de falhas, atendendo as demandas de mudança e crescimento
    - capacidade de execução das funções pretendidas 
        - Testar a recuperação 
        - gerenciar alterações 
        - Lidar com a demanda 
        - Distribuir os recursos 
        - monitorar e alertar 

- Eficiência de performance 
    - se concentra na alocação eficaz e otimizada de recursos de TI e Computação, incluindo seleção, provisionamento, monitoramento e ajuste de recursos.   
    - Alocação eficaz de recursos de TI 
        - Seleção e provisionamento otimizados 
        - Monitoramento e avalição continua 
        - Ajuste dinâmico de recursos  

- Otimização de custos 
    - se concentra na obtenção do melhor retorno sobre o investimento em recursos de TI e computação incluindo analise, medição, previsão e contraole de custos. 
    - Analise e atribuição de custos 
        - Medição e relatório de custos 
        - Previsão e planejamento de custos 
        - Controle e otimização de custos 

- Sustentabilidade
    - Se consentra na redução do impacto ambiental dos sistemas na nuvem incluindo o consumo de energia, emissão de carbono, uso de materias e descarte de residuos.
    - Redução do impacto ambiental 
        - medir o impacto 
        - Reportar o impacto
        - Reduzir o impacto 
        - Compensar o impacto 


#### Reflexão sobre os pilares do AWS WAF

Exemplo 1 - Escalabilidade x Elasticidade 

- Escalabilidade 
    - Lidar com o aumento ou diminuição da demanda 
        - Performance 
        - Disponibilidade 
    
    - esta relacionado ao pilar de confiabilidade  

- Elasticidade 
    - ajusta a capacdade dos recursos 
        - Dinãmica 
        - Automática 

    - Esta relacionada ao pilar de Eficiência de performance 

Exemplo 2 - Segurança x Confiabilidade

- Segurança 
    - Proteção de informações e Sistemas 
        - Confidenciabilidade, integridade e Disponibilidade de Dados
        - Gerenciamento de identidades e Acessos 
        - Detecção e resposta a eventos de segurança

- Confiabilidade 
    - Capaciadade de executar as funçãos pretendidas 
    - Recuperar de falhas 
        - Demandas de mudanças e crescimento     

- elas estão intimamente ligadas, pois a segurança afeta a confiabilidade e vice e versa 

Exemplo 3 - Otimização de custos x Sustentabilidade 

- Otimização de custos 
    - Melhor retorno sobre ivestimento
        - Análise 
        - Medição
        - Previsão 
        - Controle  

- Sustentabilidade 
    - Redução do impacto ambiental dos sistemas na nuvem 
        - Consumo de energia 
        - Emissão de carbono
        - Uso de materiais 
        - Descarte de residuos 

- elas estão alinhadas, pois a otimazação de custos reduz o consumo de recusros de TI que implica na redução do impacto ambiental (sutentabilidade). 

    - Sinergia entre os pilares de otimização de custos e sustentabilidade
        - Uso de serviços gerenciados 
        - Reduzir custos de operação e manutenção dos recusros 
        - Reduzir o consumo de energia e emissão de carbono 
        - uso de regiões verdes 
        - Reduzir o impacto ambiental
        - Aproveitar descontos e incetivos oferecidos pela AWS 

## Estratégias de Migração para a Nuvem com AWS CAF

#### AWS CAF 

    - Identificar e priorizar opurtunidades de transformação digital
    - Avaliar e aumentar a prontidão para a nuvem 
    - Desenvolver um roteiro para guiar a transição dos negócios para a nuvem

#### Beneficios do AWS CAF

    - Redução do risco comercial
        - Orquestrar as iniciativas de nuvem 
        - maximiza os beneficos organizacionais e minimiza os riscos relacionads à transformação 
        - confidencialidade, integridade e disponibilidade de dados e workloads na nuvem 
    
    - Melhoria do desempenho em ESG
        - Aspectos: ambiental, social e de governança 
        - AWS CAF ajuda a alinhar os objetivos de negócios com os princípios de ESG 
        - Reduzir a pegada de carbono, promover a inclusão e a diversidade e melhoar a transparência e a responsabilidade
    
    - Aumento da receita 
        - acelerar ambições de transformação digital e resultados de negócios 
        - aumentar a agilidade, inovação e competividade no mercado 
        - expandir o alcance globa e a base de clientes 

    Aumento da eficiência Operacional 
        - Construir uma plataforma de nuvem híbrida, escalável e de nível empresarial
        - Modernizar workloads existentes e implementar novas soluções nativas da nuvem 
        - Otimizar custos, recursos e processos 
        - Melhorar a qualidade, performance e disponibilidade de seus workloads 

    Resultados de negócio 
        - Consequência da cadeia de vaor de transformação da nuvem 
    
    Domínios de transformação da nuvem 

        - Transformação tecnológica 
            - Migração e modernização de infraestrura, aplicações e plataformas de dados e análises 
            - Clound Value Benchmarking 

        - Transformação de processos 
            - Digitalização, automação das operações de negócios 
            - Aproveitamento de nova plataformas de dados e análises
            para criar insights factíveis ou uso Machine Learning 
            - Melhorar a experiência de atendimento ao cliente, produtividade e tomada de decisões dos funcionários, previsão de negócios, detecção e prevenção de fraudes, operações industriais 

        - Transfomação Organizacional 
            - Reimaginaçao do modelo operacional e organização de equipes em torno de produtos e valor

        - Transformação de produtos 
            - Reimaginação do modelo de negócios, criação de novas propostas de valor e modelos de receita 
            - Clound value benchmarking 
        
    Domínios de transformação da nuvem 
        - Tranformação tecnológica 
        - Tranformação de processos 
        - Transformação Organizacional 
        - Transformação de Produtos 

    Conjunto de capacidades fundamentais 
        - habilidade Organizacional de usar processos para implamtar recursos 
    para alcançar um resultado especifico 
        - Orientação de práticas recomendadas para melhorar a prontidão para nuvem 

    Perpectivas do AWS CAF 
        - Negócios
        - Pessoas 
        - Governança
        - Plataforma 
        - Segurança 
        - Operações  

    Perspectiva de negócios 
        - Alinhamento dos investimentos em nuvem com as ambições de tranformações digital
        - Cargos de CEO, CFO, COO, CIO e CTO 
        - Evolução para uma culatura de crescimento e aprovetamento contínuos 

    Perspectiva de Pessoas 
        - Evolução para uma cultura de crescimento e apendizado contínuos
        - Cargos de CIO, COO, CTO, diretor de nuvem, além de líderes multifuncionais e de toda a empresa

    Perspectiva de governança 
        - Orquestração de iniciativas de nuvem, maximizando os beneficios organizacionais de riscos
        - Cargos de diretor de transformação, CIO, CTO, CFO, CDO e CRO 

    Perspectiva de plataformas 
        - Criação de uma plataforma de nuvem hibrida escalável  
        - Cargos CTO, lideres de tecnologis, arquitetos e engenheiros 

    Perspectiva de segurança 
        - Garantia de confidecialidade, integridade e disponilidade dos dados
        - Cargos de Ciso, CCO, lideres de auditoria interna e arquitetos e engenheiros de segurança  

    Perspectiva de Operações 
        - Garantia da entrega de serviços de nuvem atendendo ás necessidades da empresa 
        - Cargos de lideres de infraesrutura e opreações, engenheiros de confiabilidade do local e gerentes de serviços de tecnologia da informação 

#### Estratégias de Migração para a Nuvem com AWS 

Estratégias de Migração
    - Métodos ou Abordagens 
        - Planejar 
        - Executar 
        - Validar 

    - Tipo, complexidade e criticidade 
    - objetivos, requisitos e restrições de negocios 
    - Tempo, custo, risco e beneficio 

As sete estratégias de migração para a Nuvem 
(7 Rs)

    - Retire(retirada)
        - Manter aplicativos no ambiente de origem ou adiar a migração

    - Retain (reter)
        - Mater aplicativos no ambiente de origem ou adiar sua migração para a nuvem 

    Rehost (Rehospedar)
        - Mover aplicativos para a nuvem sem modificalos (lift and shift)

    Relocade(Realocar)
        - tranferir servidores ou instancias para outra plataforma na nuvem 

    Repurchase(Recompra)
        - Substituir o aplicativo por uma versão ou produto diferente 

    Replatform(Realocação de plataformas)
    - Mover aplicativos para a nuvem e otimizá-los para reduzir custos ou melhorar o desempenho 

    Refactor or Re-architect(Refatorar ou Rearquitetar)
        - Modificar a arquitetura do aplicativo ao movê-lo para a nuvem, aproveitando os recursos nativos para melhoar  agilidade, desempenho e escalabilidade 

    Fatores na Escolha da estratégia de migração 
        - Tipo, complexidade e criticidade dos workloads
        - Objetivos, requisitos e restrições de negócios 
        - Tempo, custo e risco da migração 
        - Nível de maturidade e prontidão para a nuvem 


    Exemplos de estratégias de migração para a nuvem aws
    Rehosting 
        - Replicação de banco de dados 
            - copiar dados de um banco local para uma na nuvem AWS, mantendo a estrutura 
            - utilização do AWS Database Migration Service (AWS DMS)
            - Migração rápida, segura e confiável 

    Replatform
        - Uso do AWS Snowball Edge 
            - Dispositivo fisico para transferir grandes volumes de dados pra a nuvem AWS
            - Evita limitações de largura de banda, tempo ou segurança da internet

    Refactor or Re-architect
        - Uso do Amazon lambda 
            - redesenhar workloads para se adaptarem aos recursos nativos da nuvem AWS
            - Serviço para executar código sem provisionar ou gerenciar servidores 
            - Escalabilidade, performance e custo otimizado 