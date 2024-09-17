# Componentes de Arquitetura do Azure

## Componentes de Arquitetura do Azure
## Principais componentes arquitetônicos do Azure

### Regiões
- O Azure oferece mais regiões globais do que qualquer outro provedor de nuvem, com mais de 60 regiões representando mais de 140 países
- As regiões são compostas de um ou mais datacenters muito próximos
- Eles fornecem flexibilidade e escala para reduzir a latência do cliente
- As regiões preservam a residência dos dados com uma oferta abrangente de conformidade

### Zonas de disponibilidade
- Fornece proteção contra tempo de inatividade devido a falha do datacenter
- Separa fisicamente os datacenters dentro da mesma região
- Cada datacenter é equipado com alimentação, resfriamento e rede independentes
- Conectadas por meio de redes privadas de fibra óptica

## Entendendo Pares de Região e Grupos de Recursos
## Pares de Regiões
[https://aka.ms/PairedRegions-ptb](https://aka.ms/PairedRegions-ptb)

- No mínimo 300 milhas de separação entre pares de regiões
- Replicação automática para alguns serviços
- Recupera de região priorizada em caso de interrupção
- As atualizações são distribuídas seqüencialmente para minimizar o tempo de inatividade

## Regiões soberanas do Azure

### Serviços Governamentais dos EUA
- Atende às necessidades de segurança e conformidade das agências federais, governos estaduais e locais dos EUA e seus provedores de soluções

### Azure Governamental
- Instância separada do Azure
- Fisicamente isolada de implantações que não sejam do governo dos EUA
- Acessível somente a pessoal verificado e autorizado

### Azure China
A Microsoft é o primeiro provedor estrangeiro de serviços de nuvem pública na China, em conformidade com as regulamentações governamentais

### Recursos do Azure China
Instância fisicamente separada dos serviços de nuvem do Azure operados pela 21Vianet.
Todos os dados permanecem dentro da China para garantir a conformidade

## Recursos do Azure
Os recursos do Azure são componentes como armazenamento, máquinas virtuais e redes que estão disponível para criar soluções de nuvem

### Grupo de recursos
Um grupo de recursos é um contêiner que você usa para gerenciar e agregar recursos em uma única unidade
- Os recursos podem existir em apenas um grupo de recursos
- Os recursos podem existir em diferentes regiões
- Os recursos podem ser movidos para diferentes grupos de recursos
- Os aplicativos podem utilizar vários grupos de recursos

## Assinatura da Azure e Grupos de Gerenciamentos

## Assinaturas do Azure
- Uma assinatura do Azure fornece a você acesso autenticado e autorizado às contas do Azure

### Limite de cobrança
gere relatórios de cobrança e faturas separados para cada assinatura

### Limite do controle de acesso
Gerenciar e controlar o acesso aos recursos que os usuários podem provisionar com assinaturas específicas 

## Grupos de gerenciamento
- Os grupos de gerenciamento podem incluir várias assinaturas do Azure
- As assinaturas herdam as condições aplicadas ao grupo de gerenciamento
