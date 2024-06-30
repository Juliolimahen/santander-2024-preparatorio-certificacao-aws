# santander-2024-preparatorio-certificacao-aws

## Introdução

Aws é um sistema de computação em nuvem que tem como um dos principais beneficios a economia de custos para quem a utiliza.

Diferença entre computação em nuvem e computação tradicional:

### Tradicional

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

É um conjunto de práticas recomendadas para projetar e operar sistemas na nuvem aws que ajuda aprender as melhores práticas de arquiteturas para sistemas confiáveis, seguros, eficientes, econômicos e sustentáveis na nuvem.

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

Beneficios do AWS CAF

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

### Estratégias de Migração para a Nuvem com AWS

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

## Aspectos Econômicos da Nuvem AWS

#### Custos fixos x Custos Variáveis

- Custos Fixos
  - Não mudam independetemente do uso ou demanda
  - Exemplo: servidor fisico na empresa (Manutenção, energia...)

- Custos Variáveis
  - Dependem do uso ou demanda
  - Exemplo: Serviço de streaming de video

#### Vantagens dos custos Variáveis

- Economia e eficiência
- Flexibilidade e escalabilidade

#### Pagamento por uso

- Transformar os seus custos fixo em custos variáveis
- Ter mais flexibilidade, escalabilidade e economia

#### Custos On-Premises x Custos na Nuvem

- Ambientes On-Premises: infraestrutura mantida internamente
  - Servidores
  - Redes
  - Sistemas operacionais
  - Softwares

- Nuvem: infraestrutura fornecida por provedor de serviços
  - serviços que vcs podem contratar e usar na internet

#### vantagens da nuvem

- Reduzir os custos
- Redução do TCO (Total cost of Ownership)
- Reduzir custos diretos
- Reduzir custos indiretos
- Focar no negócio, aplicação e solução
- Otimizar desempenho, segurança, disponibilidade, confiabilidade e inovação

#### Comparação de custos

- Ambientes On-premises
- Ambientes na Nuvem
  - Aws Princing Calculator

#### Estratégias de licenciamento

- Processo de obter o direito de usar um software
- Bring-Your-Own-License(BYOL)
  - Uso de licanças existentes na nuvem
  - Necessário gerenciar as suas licenças

- Licenças incluídas
  - Pagamento pelo uso do sofware junto com o uso do serviço de nuvem

Melhor estratégia de Licenciamento
    - Depende de fatores como tipo de software, o provedor, o custo, a flexibilidade, a compatibilidade
    - AWS License Manager

#### Dimesionamento correto

- Ajuste do tamanho e tipo de recursos conforme demanda
- Otimização de custos e desempenho

#### Vantagem de fazer o dimensionamento correto

- otimização de custos e desempenho

#### Dimensionamento na nuvem

- Ajuste do tamanho e tipo de recursos conforme demanda e desempenho

Farramentas e recursos

- AWS Compute Optimizer
- AWS Cost Explorer

#### Automação

- Processo de usar ferramentas e técnicas para executar tarefas de forma automática, sem intervenção humana
- AWS CloundFormation

#### Vantagens de usar Automação

- Redução de custos e aumento de eficiêcia
- Execução de tarefas sem intervenção humana

Serviços Gerenciados pela AWS

- AWS é responsável pela infraestrutura, configuração, atualização, backup e segurança

Exemplos de serviçõs gerenciados pela AWS

- Amazon Relational Database Service (Amazon RDS)
  - Oferece bancos de dados relacionais
  - MySQL, Oracle, PostgreSQL...

Amazon Elastic Container Service (Amazon ECS)

- serviço que oferece a execução de contêineres
  - Docker

Amazon Elastic Kubernetes Service (Amazon EKS)

- serviço que oferece a execução de clusters Kubernetes
- Kubernetes

Amazon DynamoDB

- Serviço que oferece um banci de dados NoSQL
  - NoSQL

Serviços Gerenciados pela AWS

- reduzir Custos e aumentar a eficiência
  - beneficios da nuvem

Ferramentsa para Automação

- AWS System Manager
- AWS Budgets

# Modelo de Responsabilidade Compartilhada da AWS

É uma forma de definir quais são as responsabilidades da Amazon (AWS) e do cliente na proteção de recusros e dados na nuvem.

- Segurança na nuvem é uma responsabilidade compartilhada
- Segurança da Nuvem (Responsabilidade da AWS) e segurança na Nuvem (Responsabilidade do cliente)

Analogia do aluguel de apartamento:

- Duas partes envolvidas (proprietario e você)
- proprietario: fornecer o apartamento em boas condições
- Inquilino: cuidar do apartamento

Responsabilidade Compartilhada da AWS

- Fornecer serviços de nuvem em boas condições
- Manter infraestrutura, sistemas operacionais e plataformas funcionando
- Garantir segurança fisica da infraestrutura

Responsabilidade Compartilhada cliente

- Cuidar dos recursos e dados na nuvem
- Manter proteção e organização dos dados
- Pagar as contas em dia e não causar danos aos serviços

Responsabilidade Compartilhadas

- Criptografia de dados
- Gestão de identidade e acesso
- Configuração de firewalls

Segurança da Nuvem (Responsabilidade da AWS)

- Proteção da infraestrutura da nuvem
- Hardware, software, redes e instalações
- Conformidade com padrões do setor

Segurança na Nuvem (Responsabilidade do cliente)

- Proteção de recursos e dados utilizados na nuvem
- Sistema operacional, sofwares, configuranção de rede, dados armazenados
- Garantia de conformidade com leis e regulamentos

# Categorias de Serviços em Nuvem

- Infraestrutura como serviço(IaaS)
  - Nivel mais baixo de abstração
  - Cliente tem acesso direto aos recursos de computação, armazenamento e rede na nuvem
  - Criação e execução de máquinas virtuais na nuvem
  - Amazon EC2

- Plataforma como Serviço (Paas)
  - Nivel intermediario de abstração
  - Cliente foca apenas na plataforma para desenvolver e executar aplicações
  - AWS Lambda

- Software como Serviço (Saas)
  - Nivel mais alto de abstração
  - Cliente foca apenas no software para realizar suas tarefas
  - Amazon S3

### Exemplos

#### IaaS

- Maior controle e resposabilidade para o cliente
- Cliente gerencia sistema operacional, softwares, cofiguração de rede, permissões de acesso, dados
- AWS protege infraestrutura fisica, redes, instalações
- Responsabilidade maior do cliente q da amazon

#### Paas

- Controle e responsabilidade intermediários
- Cliente gerencia código das aplicações, configurações de rede, permissões de acesso, dados
- AWS protege infraestrutura física, redes, instalações, sistemas operacionais, plataformas

#### SaaS

- Menor controle e responsabilidade para o cliente
- Cliente gerencia dados(incluindo criptografia) e permissões de acesso
- Aws protege infraestrutura fisca, redes, instalações, sistemas operacionais, plataformas, software
- Resposabilidade é menor para o cliente e maior para a amazon

### Variação de Responsabilidades

- Abstração do serviço influencia a distribuição das responsabilidades
- Serviços mais abstratos implicam em menor responsabilidade para o cliente
- Escolha do serviço deve considerar segurança, desempenho, custo e flexibilidade

### Garantia de segurança na nuvem

- AWS responsável pela segurança da infraestrutura
- cliente responsável pela segurança dos recursos e dados
- responsabilidade varia conforme o tipo de serviço:
Maior para IaaS, intermediaria para PaaS e menor para Saas.

### Sergurança, Governança e Conformidade

#### Iniciando com AWS Artifact

- Recurso indispensável para conformidade na nuvem AWS
- Oferece acesso a elatórios e acordos de associados
- Facilita entendimento e demonstração da conformidade

Se dastaca por relatórios de auditoria como:

- SOC 1
- SOC 2
- SOC 3
- PCI DSS nível 1

Acordos de Associados de negócios

- Especificam as responsabilidades e obrigações de cada parte na gestão de dados
- Exemplo: BAA da HIPPA
- Importantes para gestão de dados de saúde

Beneficios

- Facilita acesso à documentação importante de conformidade
- Simplifica o processo de auditória
- Permite foco em inovação ao reduzir burocracia

#### Analogia

Expedição em uma selva desconhecida

- Aws Artifact guia na jornada da Conformidade Regulatória
- Oferece orientação com detalhes e requisitos
- Garante uma exploração segura no mundo regulatório

### Navegando pela Conformidade Geográfica e Setorial

Estratégias de conformidade geográfica e Setorial

- Especificações para o GDPR: Proteçãos e privacidade dos dados na Europa
- implementações ficadas no LGPD: Atendimento às exigências de proteção de dados no Brasil
- ADoção de abordagem global para garantir conformidade em diferentes regiãos e setores

Benefícios da Abordagem Global

- Permite que empresas globais operem com eficiência em diferentes cenãrios regulatórios
- Facilita navegação pela complexidades da conformidade
- Adoção de abordagem global para garantir conformidade em diferentes regiões e setores

#### Analogia

Quebra-Cabeça

- Conformidad como um quebra-cabeça que varia por localização e setor
- AWS como um conjunto de peças pré-montadas que se ajustam ás diferentes exigências regulatórias
- Peças ajustáveis ás diferentes exigências regulatórias globais, como
GDPR e LGPD, facilitando a conformidade empresarial

#### Protegendo Recursos com ferramentas AWS

Segurança multifacetada

- Proteção de dados
- Defesa contra ataques cibernéticos
- Conjunto de ferranmentas para salvaguradar seus recursos  

#### Ferramentas Chave de segurança na AWS

- Amazon Inspector: Avaliação automatizada de segurança e recomendações para remediação de vunerabilidades.
- AWS Security Hub: Consolidadção de alertas de segurança e gestão simplificada da postura de segurança.
- Amazon GuardDuty: Monitoramento de atividades suspeitas e maliciosas com detecção baseada em inteligência artificial
- AWS Shield: Proteção contra ataques DDoS com serviço gerenciado ativado automaticamente

Benefícios da implementação das ferramentas de segurança

- Fortalecimento da postura de segurança dos clientes AWS
- Alertas automatizados e proteção proativa contra diversas ameaças cibernáticas
- Foco em inovação e crescimento com a segurança garantida pela AWS

#### Analogia

Castelo Medieval

- Sgurança dos recursos na AWS como a construção e manutenção de um castelo medieval
- Ferramentas de segurança como diferentes camadas de defesa do castelo
- Amazon Inspector
- AWS Security Hub
- Amazon GuardDuty
- AWS Shield

#### Criptografia na AWS

- Protege dados em trânsito e em repouso
- Assegura confidencialidade e integridade dos dados
- Vital para a segurança das informações em ambientais digitais

#### Soluções para criptografia na AWS

- AWS Key management Service (KMS): Crie e controla chaves de criptografia
- AWS cloudHSM: Oferece ambiente dedicado para gerenciamento de chaves

Flexibilidade e Escalabilidade

- atende organizações de todos os tamanhos e tipos
- Proporciona soluções acessíveis e eficazes
- Adaptável às exigências especificas de cada empresa

#### Analogia

Cofre pessoal

- AWS key Management service (KMS)
- AWS CloudHSM
- Oferece diferentes niveis de segurança e chaves personalizadas
- Garante acesso a pessoas autorizadas

#### Governaça e Conformidade com Monitoramento e Auditoria

Ferramentas Essenciais para Governaça e Conformidade

- Amazon CloudWatch: Fornece metricas detalhadas e monitoramento em tempo real
- AWS CloudTrail: Registra eventos e ações, crucial para a auditoria e análise forense
- AWS Audit Manager: Simplifica a coleta de evidências de conformidade
- AWS Config: Avalia as configurações de recursos em realação aos padrões desejados

Visão continua da conformidade

- Permitem ajuste em tempo real
- Asseguram a aplicação rigorosa das politicas de governaça
- Otimizam os recusrsos e a detecção proativa de potenciais vulnerabilidades

#### Analogia

Capitão de um Navio

- Aws CloudWatch
- Aws CloudTrail
- Aws CloudWatch e CloudTrail são como o mapa estelar e o compasso, ajudando a navegar
- AWS Audit Manager
- AWS Config
- AWS Audit Manager e  AWS Config são como o diário de bordo e as verificações regulares do navio, garantindo conformidade e segurança.

#### Compreendendo a Variedade de Requisitos de Conformidade

Variação nos Requisitos de Conformidade

- Reconhecimento das diferença nos requisitos
- adaptaçõa das estratégias conforme necessário

Estratégias Especificas para cada serviços

- Adaptação do uso dos serviços AWS às necessudades de conformidade especificas
- Personalização das estrategias conforme o projeto ou a indústria

### Recursos de Gerenciamento de Acesso da AWS

#### Compreensão das Chaves de Acesso, das Políticas de Senha e do Armazenamento

Chaves de Acesso

- Identificação para comunicação programática
- Compostas por ID de acesso e chave secreta
- Gestão cuidadosa para evitar exposição e abuso

Políticas de Senha

- Configuráveis para reforçar a segurança
- Critérios de complexidade (comprimento mínimo, caracteres especiais)
- Gestão cuidadosa para evitar exposição e abuso

AWS Secrets Manager

- Armazenamento e rotação segura de segredos
- Simplifica o gerenciamento de acesso
- Permite aos desenvolvedores recuperar segredos sem codificar diretamente

AWS Systems Manager Parameter Store

- Local centralizado para dados e segredos
- Integração com IAM para controle de acesso
- Permite o controle fino sobre quem pode acessar esses segredos

#### Analogia

Chaves de Casa

- Chaves de acesso como Chaves de casa
- Políticas de senha como Regras para obter cópias das chaves
- AWS Secrets Manager e Parameter Store como Cofres seguros para armazenar chaves, com controle de acesso

#### Compreensão das Chaves de Acesso, das Políticas de Senha e do Armazenamento de Credenciais

Autenticação Multifator (MFA)

- Adiciona uma camada de segurança
- Requer um segundo fator além da senha
- Pode ser um token físico ou SMS

IAM Identity Center (SSO)

- Gestão simplificada de acesso
- Login único para acessar todos os recursos autorizado
- Melhora a experiência do usuário e a segurança

Perfis do IAM

- Usuários de uma conta assumem funções temporárias em outras
- Facilita acesso seguro a recursos compartilhados
- Essencial para empresas com múltiplas contas

Analogia

Sistema de Segurança em um Banco

- MFA é como o sistema de segurança em um banco
- IAM Identity Center é como uma chave mestra digital
- Perfis do IAM entre contas são como dar permissões temporárias

#### Definição de Grupos, Usuários, Políticas Personalizadas e Políticas Gerenciadas

AWS Identity and Access Management (IAM)

- Controle de acesso aos recursos da AWS
- Usuários: entidades individuais para interação com a AWS
- Grupos: facilitam atribuição de permissões em massa, simplificando administração

Políticas Personalizadas

- Permitem definição granular de permissões específicas

Políticas Gerenciadas

- Templates da AWS para aplicação de práticas recomendadas de segurança

AWS Identity and Access Management (IAM)

Princípio do menor privilégio:

- Entidades recebem permissões necessárias
- Fundamental a revisão periódica de permissões
- Uso do AWS Access Analyzer para identificar permissões excessivas

#### Analogia

Sistema de Bilhetagem para Evento

- Usuários como convidados com bilhetes
- Grupos como categorias de bilhetes
- Políticas definem áreas e atividades permitidas

#### Identificação das Tarefas que Somente o Usuário-Raiz da Conta Pode Realizar

Usuário raiz (root)

- Possui acesso irrestrito a todos os
- recursos e configurações da conta AWS

Tarefas sensíveis do Usuário raiz

- Alterar configurações de faturamento
- Adicionar novas formas de pagamento
- Acessar relatórios de uso e custos e modificar configurações avançadas de segurança

Recomendações para o Usuário raiz

- Limitar a tarefas que não podem ser realizadas por um usuário IAM.
- Restringir seu uso devido ao seu potencial de risco.
- Criar um contato de segurança na conta AWS para receber notificações de atividades suspeitas.

#### Analogia
Dono de uma Loja

- Usuário-raiz é comparável ao dono de uma loja com a chave mestra
- Acesso total as partes da loja e capacidade de fazer mudanças fundamentais na operação
- Uso da chave requer sabedoria e parcimônia devido ao seu poder e implicações de segurança

#### Compreensão de Quais Métodos Podem Proteger o Usuário-Raiz

Importância da Proteção do Acesso do Usuário-raiz

- Proteger o acesso do usuário-raiz (root) é crucial para a segurança da conta.
- O uso do usuário-raiz deve ser restringido.
- Recomenda-se a ativação da autenticação multifator (MFA) para o usuário-raiz.

Autenticação Multifator (MFA)
- Evita acesso não autorizado mesmo se credenciais de login forem comprometidas.
- Requer segundo fator de autenticação para acessar a conta
- Recomenda-se o uso de dispositivo MFA físico para segurança adicional

#### Analogia 

Instalação de Sistema de Alarme em Cofre
- Habilitar MFA é como instalar um sistema de alarme com reconhecimento de impressão digital em um cofre valioso.
- Mesmo com a combinação do cofre descoberta, a impressão digital correta é necessária para acesso

#### Compreensão dos Tipos de Gerenciamento de Identidade

Gerenciamento de Identidade Federado
- Permite uso de sistemas de identidade próprios
- Simplifica processo de login, eliminando múltiplas credenciais
- Centraliza controle de acesso, facilitando governança e conformidade

#### Analogia

- Passe Universal para Parques Temáticos
- Gerenciamento de identidade federado é como ter um passe universal para parques temáticos.
- Ao invés de comprar um ingresso para cada parque, usa-se um passe existente.
- Simplificação do acesso, melhorando a experiência do usuário, mantendo segurança e controle centralizado


### Componentes e Recursos de Segurança na AWS

#### Recursos e Serviços de Segurança da AWS

Grupos de Segurança
- Controlam tráfego de entrada e saída para instâncias EC2
- Protegem suas aplicações contra acessos não autorizados ou mal-intencionados
- Exemplo: permitindo apenas tráfego nas portas 80 (HTTP) e 443 (HTTPS)

ACLs de Rede (Access Control Lists)
- Definem permissões de entrada e saída para as sub-redes na Virtual Private Cloud (VPC)
- Oferecem um nível adicional de segurança 
- Complementam os Grupos de Segurança 

AWS WAF (Web Application Firewall)
- Serviço dedicado à proteção de aplicações web
contra ataques comuns
- Inspeção do tráfego para criar regras personalizadas de bloqueio
- Defende contra injeções SQL, cross-site scripting (XSS)
e outras vulnerabilidades

Controle Detalhado de Tráfego
- Garante processamento apenas de solicitações legitimas
- Funciona como um sistema de defesa avançado
para suas aplicações web
- Filtra mensagens suspeitas, evitando acessos não autorizados

#### Explorando Produtos de Segurança de Terceiros no AWS Marketplace

AWS Marketplace
- Vitrine de soluções de segurança de terceiros para complementar as capacidades nativas da AWS
- Oferece uma variedade de produtos avançados, como firewalls e sistemas de detecção de intrusão
- Escolha meticulosa de soluções para atender às necessidades específicas de segurança

Facilita a Implementação de Soluções
- Integra-se perfeitamente ao seu ecossistema AWS existente
- Permite uma configuração ágil
- Possibilita um gerenciamento eficiente

#### Localizando Informações de Segurança Essenciais da AWS

AWS Knowledge Center
- Biblioteca extensa de tutoriais e soluções
para problemas comuns na AWS
- Ideal tanto para quem está começando quanto para
aqueles que buscam resolver problemas específicos
- Oferece guias detalhados, como configuração de políticas
de segurança IAM e otimização do Amazon VPC

Blog de Segurança da AWS
- Últimas tendências e melhores práticas
no mundo da segurança na nuvem
- Estudos de caso, análises de recursos de segurança, e whitepapers
- Acesso a insights valiosos

AWS Security Hub
- Visão centralizada e gerenciamento de alertas de segurança e conformidade
- Integra dados de segurança de várias fontes
- Facilita a identificação e gerenciamento de potenciais riscos e vulnerabilidades

Documentação Oficial e Whitepapers
- Detalhes sobre melhores práticas de segurança
- Configurações recomendadas
- Análises de segurança

Comunidade AWS
- Interação através de fóruns, grupos de usuários e conferências
- Compartilhamento de conhecimento
- Aprendizado com a experiência de outros profissionais

#### Utilizando o AWS Trusted Advisor para Identificar Problemas de Segurança

AWS Trusted Advisor
- Analisa seu ambiente AWS em busca de potencials problemas de segurança
- Oferece recomendações para melhorar a eficiência, performance e segurança
- Identifica práticas recomendadas que você pode não estar seguindo

AWS Trusted Advisor
- Verifica sua configuração para identificar pontos fracos
- Crucial para prevenir problemas








### Modelos de Preços da AWS

#### Opções de Compra de Computação na AWS
Opções de Compra de Computação na AWS
- Oferece diversas opções para atender diferentes necessidades
de negócios e técnicas
- Exemplos: instâncias sob demanda, instâncias reservadas, Spot Instances, Savings Plans, hosts dedicados, instâncias
dedicadas e reserva de capacidade