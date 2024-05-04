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