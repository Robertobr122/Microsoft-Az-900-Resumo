# Guia de Estudo: Microsoft AZ-900 – Fundamentos do Azure


## Introdução
A certificação AZ-900 é a porta de entrada para compreender os fundamentos do Azure, a plataforma de nuvem da Microsoft. Este guia aborda desde a evolução dos data centers e a necessidade de virtualização até os modelos de nuvem e os conceitos de despesas de capital (CapEx) e operacionais (OpEx). Com uma abordagem clara e exemplos práticos, este material servirá tanto para revisão quanto para aprofundamento dos temas essenciais para a certificação.

---

## 1. Evolução dos Data Centers e a Computação em Nuvem

### 1.1 Da Infraestrutura Tradicional à Virtualização
Historicamente, toda empresa possuía seu próprio data center, onde eram armazenados servidores, equipamentos de rede e demais recursos de TI. Contudo, com o aumento das demandas e a evolução tecnológica, manter um data center físico tornou-se cada vez mais caro e complexo. Essa realidade impulsionou a migração para a computação em nuvem, onde grandes provedores como Microsoft e Oracle oferecem infraestrutura virtualizada.

### 1.2 Conceito de Computação em Nuvem
A computação em nuvem consiste no fornecimento de serviços de TI pela internet. Essa abordagem possibilita:

- **Inovação rápida**: Implementação ágil de novos recursos.
- **Flexibilidade**: Adaptação da infraestrutura conforme a demanda.
- **Economia de escala**: Redução de custos por meio do pagamento apenas pelo que é consumido.

**Exemplo Prático**: Uma empresa que precisa lançar um novo aplicativo pode provisionar rapidamente os recursos necessários na nuvem sem investir em hardware próprio, pagando apenas pelo uso efetivo durante o período de lançamento.

### 1.3 Quando a Computação em Nuvem Faz Sentido para a Empresa
Optar pela nuvem pode ser vantajoso quando:

- É necessário criar recursos rapidamente.
- Não há uma equipe especializada pronta para gerenciar uma infraestrutura tradicional.
- A empresa deseja evitar altos custos fixos com a manutenção de data centers próprios.
- A flexibilidade de pagar conforme o consumo é uma prioridade.

---

## 2. Modelos de Nuvem
A nuvem pode ser implementada em diferentes modelos, cada um com características específicas que atendem a diferentes necessidades organizacionais.

### 2.1 Nuvem Privada
**Definição**: Ambiente 100% on-premises, onde a empresa possui e gerencia seus próprios servidores, firewalls e demais equipamentos.

**Características**:
- Controle total dos recursos e da segurança.
- Responsabilidade exclusiva pela manutenção e atualizações de hardware.
- Ambiente restrito à organização, sem acesso externo.

**Exemplo**: Uma empresa altamente regulada pode optar por uma nuvem privada para garantir o controle absoluto sobre dados sensíveis.

### 2.2 Nuvem Pública
**Definição**: Recursos e serviços disponibilizados por um provedor único (como a Microsoft) através de data centers distribuídos globalmente.

**Características**:
- Nenhum investimento inicial em infraestrutura física.
- Pagamento conforme o uso, o que permite escalabilidade rápida.
- Acesso a recursos e serviços por várias organizações e usuários, por meio de conexões seguras (geralmente via internet).

**Exemplo**: Startups que necessitam de agilidade e escalabilidade sem grandes investimentos iniciais se beneficiam do modelo de nuvem pública.

### 2.3 Nuvem Híbrida
**Definição**: Combinação entre nuvem privada e nuvem pública, permitindo que as organizações escolham o ambiente mais adequado para cada aplicação.

**Características**:
- Flexibilidade para executar aplicativos tanto localmente quanto na nuvem.
- Permite o controle sobre segurança, conformidade e requisitos legais.
- Ideal para empresas que estão crescendo e precisam de mais flexibilidade sem abandonar totalmente a infraestrutura on-premises.

**Exemplo**: Uma grande organização pode utilizar uma nuvem privada para dados sensíveis e uma nuvem pública para hospedar aplicações com picos de acesso, garantindo o equilíbrio entre segurança e escalabilidade.

### 2.4 Comparação dos Modelos de Nuvem

| Modelo  | Vantagens Principais | Desvantagens |
|---------|----------------------|--------------|
| **Pública** | Escalabilidade rápida, pagamento conforme o uso, menor investimento | Menor controle sobre a infraestrutura, dependência do provedor |
| **Privada** | Controle total dos recursos e segurança | Altos custos iniciais e responsabilidade integral pela manutenção |
| **Híbrida** | Flexibilidade, otimização de recursos conforme a demanda | Pode ser complexa de gerenciar e integrar os dois ambientes |

---

## 3. CapEx vs. OpEx: Despesas em TI

### 3.1 Despesas de Capital (CapEx)
**Conceito**: Investimentos iniciais em infraestrutura física.

**Características**:
- Custos elevados no início (ex.: aquisição de servidores e montagem de data centers).
- Redução de custos a longo prazo com despesas menores de manutenção e atualização.

**Exemplo**: Construir um data center é comparado à construção de uma casa – há um grande investimento inicial seguido de custos operacionais reduzidos.

### 3.2 Despesas Operacionais (OpEx)
**Conceito**: Gastos recorrentes com produtos e serviços conforme necessário.

**Características**:
- Pagamento imediato conforme o uso dos recursos.
- Permite flexibilidade e escalabilidade, pois só se paga pelo que é utilizado.
- Modelo típico na nuvem, onde a cobrança ocorre com base no consumo real.

**Exemplo**: No modelo de nuvem, se uma empresa provisiona 30 máquinas virtuais e, posteriormente, reduz para 15, ela paga apenas pelo uso das 15 máquinas ativas, permitindo melhor previsão e controle de custos.

---

## 4. Modelo Baseado em Consumo na Nuvem
Uma das grandes vantagens do Azure e de outros provedores de nuvem é o modelo baseado em consumo. Esse modelo permite:

- **Pagamento pelo uso real**: Apenas os recursos utilizados são cobrados.
- **Previsibilidade de custos**: Com preços pré-definidos para cada recurso, é possível planejar o orçamento de forma mais eficiente.
- **Agilidade na provisão**: Os aplicativos e serviços podem ser rapidamente provisionados e desprovisionados, otimizando o uso e evitando custos desnecessários.

---

# Benefícios e Recursos Fundamentais da Nuvem no Contexto do AZ-900

## 1. Introdução
A computação em nuvem continua sendo um dos principais pilares de transformação digital nas organizações, oferecendo ferramentas para criar, gerenciar e otimizar aplicações de forma ágil e segura. Dentro do Microsoft Azure, diversos conceitos e serviços permitem alcançar alta disponibilidade, escalabilidade, elasticidade, segurança e muito mais.

Nesta publicação, vamos nos aprofundar em benefícios essenciais da computação em nuvem e explorar conceitos avançados, como Acordos de Nível de Serviço (SLA), Availability Zones e mecanismos de redundância de armazenamento (LRS, GRS, ZRS, GZRS). Essas informações são fundamentais para quem está se preparando para a certificação **AZ-900 (Microsoft Azure Fundamentals)**.

---

## 2. Principais Benefícios da Nuvem

### 2.1. Alta Disponibilidade (High Availability)
A alta disponibilidade garante que os serviços permaneçam operacionais pelo maior tempo possível. O tempo de atividade é acordado entre o provedor de nuvem (no nosso caso, a Microsoft) e o cliente, por meio de um **Acordo de Nível de Serviço (SLA)**.

- **SLA**: Determina uma porcentagem de disponibilidade (ex.: 99,9%).
- Se o serviço ficar indisponível por mais tempo do que o acordado, o cliente poderá receber créditos em sua fatura, compensando o período de inatividade.
- Diferentes serviços no Azure podem ter SLAs diferentes. Portanto, entender cada SLA ajuda a planejar cenários de contingência e redundância.
- **Exemplo**: Um SLA de 99,9% pode significar até 10,1 minutos de inatividade por semana. Caso esse limite seja ultrapassado por responsabilidade do provedor, o cliente pode ser elegível a créditos.

---

### 2.2. Escalabilidade
A escalabilidade é a capacidade de aumentar (ou diminuir) os recursos de computação para atender às demandas de carga de trabalho.

- **Escala Vertical (Scale Up)**: Aumentar a capacidade de um recurso existente (ex.: adicionar CPU ou memória a uma Máquina Virtual).
- **Escala Horizontal (Scale Out)**: Adicionar mais instâncias de um recurso (ex.: adicionar mais servidores ou VMs ao pool de recursos).
- **Benefício de custo**: No modelo de nuvem, você paga pelo uso efetivo. Assim, não é preciso superdimensionar a infraestrutura para picos ocasionais; é possível escalá-la conforme a demanda cresce ou diminui.

---

### 2.3. Elasticidade
A elasticidade é um complemento à escalabilidade, focada em responder rapidamente às variações abruptas de demanda. É muito usada quando há picos imprevisíveis de uso, pois os recursos podem ser expandidos ou reduzidos de forma automática (ou manual).

- **Exemplo Prático**: Um e-commerce em datas promocionais (como Black Friday) pode precisar de mais VMs e, depois que o pico de tráfego passar, é possível reduzir a quantidade de máquinas para economizar custos.

---

### 2.4. Confiabilidade (Reliability)
A confiabilidade está ligada à resiliência dos serviços. O Azure, por ser distribuído mundialmente, permite que você:

- **Implante recursos em múltiplas regiões**: Caso uma região sofra um evento catastrófico (falha de energia, desastre natural etc.), outra região pode assumir as cargas de trabalho.
- **Mantenha backups e réplicas**: Facilita a recuperação e a continuidade dos negócios.

Quanto mais distribuído for o ambiente, maior é a confiabilidade do seu sistema.

---

### 2.5. Previsibilidade
A previsibilidade no contexto da nuvem abrange dois aspectos principais:

1. **Previsão de desempenho**: Você pode planejar o comportamento da aplicação graças aos recursos elásticos e escaláveis do Azure.
2. **Previsão de custos**: O modelo baseado em consumo (pay-as-you-go) permite acompanhar gastos em tempo real. Além disso, há ferramentas que ajudam a estimar custos futuros.

O **Well-Architected Framework**, da Microsoft, traz boas práticas para otimizar esses elementos de forma consistente.

---

### 2.6. Segurança
A nuvem oferece diversas ferramentas e serviços de segurança, mas existe um modelo de responsabilidade compartilhada:

- **Provedor (Microsoft)**: Responsável por proteger a infraestrutura física, atualizar o hardware e manter níveis de segurança no datacenter.
- **Cliente**: Responsável pela configuração segura dos serviços, aplicação de patches em sistemas operacionais (IaaS) e conformidade com políticas e normativas (LGPD, ISO, SOC, entre outras).

**Exemplos de ferramentas de segurança no Azure**:
- **Azure Security Center (Microsoft Defender for Cloud)**: Monitora e recomenda práticas de segurança.
- **Azure Key Vault**: Armazenamento seguro de chaves, segredos e certificados.

---

### 2.7. Governança
A governança envolve políticas, processos e controles que permitem gerenciar adequadamente seus recursos em nuvem:

- **Auditoria e Conformidade**: A nuvem facilita verificar se os recursos estão em conformidade com as políticas corporativas.
- **Automação de patches e atualizações**: Em modelos de PaaS ou SaaS, o provedor gerencia grande parte das atualizações, mas, no caso de IaaS, você também pode automatizá-las.
- **Padronização**: Definir modelos pré-configurados (templates) para implantação de VMs, redes e bancos de dados ajuda a evitar configurações manuais e propensas a erros.

Quanto mais cedo a governança for estabelecida, mais fácil é manter o ambiente seguro, bem gerenciado e escalável.

---

### 2.8. Gerenciabilidade
A gerenciabilidade está relacionada às ferramentas e abordagens disponíveis para administrar e automatizar recursos na nuvem. No Azure, é possível:

- **Gerenciar via Portal do Azure**: Interface gráfica web para criar, configurar e monitorar serviços.
- **Usar Interfaces de Linha de Comando (CLI)**: Automação e scripts, permitindo repetição de tarefas em vários recursos.
- **Infrastructure as Code (IaC)**: Utilizar modelos declarativos (ARM Templates, Bicep, Terraform) para padronizar e agilizar implantações.
- **Autoescalabilidade**: Configurar regras automáticas que criam ou removem recursos conforme a demanda (ex.: dimensionar um cluster de VMs de acordo com a CPU ou memória utilizadas).

---

## 3. SLA: Entendendo os Níveis de Disponibilidade
Os níveis de disponibilidade (SLA) são normalmente expressos em porcentagem. Cada pequena melhoria nesse número reflete em drástica redução do tempo de inatividade tolerado.

| Disponibilidade (SLA) | Tempo de Inatividade/Semana | Tempo de Inatividade/Mês | Tempo de Inatividade/Ano |
|-----------------------|----------------------------|--------------------------|--------------------------|
| 99%                   | ~1,68 horas               | ~7,2 horas              | ~3,65 dias              |
| 99,9%                 | ~10,1 minutos             | ~43,2 minutos           | ~8,76 horas             |
| 99,95%                | ~5 minutos                | ~21,6 minutos           | ~4,38 horas             |
| 99,999%               | ~6 segundos               | ~25,9 segundos          | ~5,26 minutos           |

> **Observação**: Estes valores são aproximados. Cada SLA oficial da Microsoft detalha exatamente os cálculos e métricas aplicáveis a cada serviço.

---

## 4. Availability Zones (Zonas de Disponibilidade)
As **Availability Zones** são localizações fisicamente separadas dentro de uma mesma região do Azure. Cada zona tem sua própria fonte de energia, refrigeração e rede, oferecendo maior proteção contra falhas locais.

- **Vantagem**: Se uma zona tiver problemas, as outras ainda ficam operacionais, possibilitando alta disponibilidade.
- **Aplicação prática**: Ao criar uma Máquina Virtual, você pode selecionar a zona onde ela será implantada. Para alta disponibilidade, normalmente distribui-se réplicas das VMs em zonas diferentes dentro da mesma região.

---

## 5. Redundância de Armazenamento (LRS, GRS, ZRS, GZRS)
Ao armazenar dados no Azure, você pode escolher diferentes estratégias de redundância, cada uma atendendo a necessidades específicas de conformidade, custo e disponibilidade.

### LRS (Locally Redundant Storage)
- Armazena três cópias dos dados em um único datacenter na região primária.
- Protege contra falhas de hardware local dentro do datacenter.
- **Limitação**: Se houver falha completa do datacenter (ex.: desastre natural), os dados podem ficar indisponíveis.

### GRS (Geo-Redundant Storage)
- Armazena dados de maneira redundante em duas regiões: três cópias na região primária e mais três na região secundária, geograficamente distante.
- Em caso de falha catastrófica na região primária, os dados podem ser recuperados da região secundária.
- A replicação para a região secundária é assíncrona.

### ZRS (Zone-Redundant Storage)
- Distribui dados entre diferentes zonas dentro da mesma região.
- Protege contra a perda de um datacenter completo dentro de uma região com Availability Zones.
- Caso uma zona fique indisponível, os dados ainda estão acessíveis a partir das zonas restantes.

### GZRS (Geo Zone-Redundant Storage)
- Combina ZRS e GRS, armazenando dados de forma redundante em zonas diferentes na região primária e em outra região secundária.
- É o nível máximo de resiliência, ideal para workloads críticos que precisam de alta disponibilidade e proteção contra falhas regionais.

# Artigo: Tipos de Serviço em Nuvem (IaaS, PaaS e SaaS) e o Modelo de Responsabilidade Compartilhada

## 1. Introdução
Os serviços de nuvem revolucionaram a maneira como as organizações adquirem e gerenciam recursos de TI. Em vez de comprar e manter toda a infraestrutura localmente (on-premises), muitas empresas optam pelo uso de serviços em nuvem, pagando apenas pelos recursos que realmente utilizam.

Dentro desse contexto, surgem três modelos principais de serviço em nuvem: **Infrastructure as a Service (IaaS)**, **Platform as a Service (PaaS)** e **Software as a Service (SaaS)**. Eles não são exclusivos da Microsoft; provedores como AWS, Google Cloud e Oracle também oferecem serviços que se enquadram nesses modelos. Cada um traz diferentes níveis de gerenciamento e responsabilidade, tanto para o provedor quanto para o cliente.

Neste artigo, abordaremos:
- O **Modelo de Responsabilidade Compartilhada**.
- As definições de **IaaS**, **PaaS** e **SaaS**, com seus casos de uso mais apropriados.
- Alguns exemplos práticos para esclarecer cada modelo.
- Orientações de estudo e dicas para quem está iniciando no Azure ou se preparando para o exame **AZ-900**.

---

## 2. Modelo de Responsabilidade Compartilhada
Independentemente do modelo (IaaS, PaaS ou SaaS), existem responsabilidades que são divididas entre o fornecedor da nuvem (por exemplo, Microsoft) e o cliente (usuário/empresa).

### Fornecedor de Nuvem (Microsoft)
- Gerencia a infraestrutura física (datacenters, máquinas, rede, energia etc.).
- Fornece segurança em nível físico e mantém a camada básica de virtualização e serviços subjacentes.

### Cliente (Usuário/Empresa)
- Configura e gerencia o que está dentro do escopo de seu controle: sistemas operacionais, aplicativos e dados (no caso de IaaS), configurações de plataforma (no caso de PaaS) ou apenas a forma como o software é usado (no caso de SaaS).
  
Assim, a responsabilidade do usuário **aumenta** conforme se aproxima do modelo IaaS e **diminui** conforme vai em direção ao modelo SaaS.

---

## 3. Modelos de Serviço em Nuvem

### 3.1. Infrastructure as a Service (IaaS)
No modelo **IaaS**, o provedor de nuvem oferece toda a infraestrutura virtual: servidores, máquinas virtuais, redes e armazenamento. O cliente, por sua vez:

- Tem mais controle sobre o sistema operacional, configurações de rede, aplicações instaladas etc.
- É responsável por instalar e manter sistemas operacionais, aplicar patches de segurança e gerenciar a configuração do servidor.
- Paga de acordo com o uso (**pay-as-you-go**).

**Exemplo:**
- **Azure Virtual Machines**: você escolhe o sistema operacional, tamanho da VM, configurações de rede e é o responsável pelo gerenciamento do SO e das aplicações.

**Caso de uso**:
- Migração de uma aplicação legada para a nuvem, onde você precisa de acesso profundo ao servidor, customizações específicas ou compatibilidade com sistemas operacionais diferenciados.

**Vantagens do IaaS**:
- Flexibilidade total para instalar e gerenciar qualquer tipo de aplicação.
- Maior controle de segurança, se a empresa precisar de configurações específicas.
- Ótimo para quem ainda não está pronto para reescrever todo o aplicativo e precisa apenas levar seu ambiente on-premises para a nuvem.

---

### 3.2. Platform as a Service (PaaS)
No modelo **PaaS**, o provedor de nuvem oferece uma plataforma gerenciada para que você possa desenvolver, testar, implantar e gerenciar aplicações sem se preocupar com detalhes de infraestrutura, servidores ou sistemas operacionais.

- O cliente se foca apenas em desenvolver e manter o código do aplicativo.
- A configuração e manutenção de servidores, sistemas operacionais e estruturas básicas de software ficam a cargo do provedor.
- Geralmente, inclui ferramentas de análise, banco de dados e suporte para linguagens de programação modernas.

**Exemplo:**
- **Azure App Service**: permite implantar aplicativos web ou APIs sem gerenciar servidores diretamente.
- **Azure SQL Database**: oferece banco de dados SQL totalmente gerenciado, dispensando a preocupação com patches, upgrades de SO ou instalação de SQL Server.

**Caso de uso**:
- Criação de aplicações novas (ou modernização de antigas) que podem se beneficiar de um ambiente gerenciado, escalável e de alta disponibilidade, sem exigir a gerência minuciosa de infraestrutura.

**Vantagens do PaaS**:
- **Desenvolvimento acelerado**: Foco no código e não na infraestrutura.
- **Custos otimizados**: Tempo de entrega reduzido, pois não é preciso gerenciar máquinas virtuais, patches e atualizações de SO.
- **Escalabilidade simplificada**: As plataformas muitas vezes oferecem escalonamento automático de recursos.

---

### 3.3. Software as a Service (SaaS)
No modelo **SaaS**, o provedor entrega o software completo, pronto para uso, pela Internet. É o modelo em que o usuário final tem menos responsabilidade quanto à infraestrutura e aplicação.

- O cliente utiliza o software pagando por assinatura ou conforme o uso.
- Não há preocupação alguma com servidores, configurações ou instalação local.
- As atualizações e manutenções são totalmente gerenciadas pelo fornecedor.

**Exemplo:**
- **Microsoft 365 (Office 365)**: inclui e-mail (Exchange Online), armazenamento (OneDrive), colaboração (Teams) e outras ferramentas, tudo gerenciado pela Microsoft.

**Caso de uso**:
- Empresas que querem focar totalmente em sua atividade principal, sem se preocupar em instalar ou manter aplicativos de produtividade internamente.

**Vantagens do SaaS**:
- **Implantação imediata**: Basta assinar o serviço e começar a usar.
- **Custos previsíveis**: Modelo de assinatura mensal/anual conforme o número de usuários.
- **Atualizações e patches**: Realizados automaticamente pelo provedor.

---

## 4. Comparando IaaS, PaaS e SaaS

| Característica  | IaaS                                           | PaaS                                                | SaaS                                        |
|-----------------|-----------------------------------------------|-----------------------------------------------------|---------------------------------------------|
| **Controle**        | Alto (usuário gerencia SO, rede, etc.)        | Médio (usuário gerencia apps e dados)               | Baixo (usuário só usa o software)           |
| **Responsabilidade** | Compartilhada, com maior carga no cliente    | Compartilhada, mas maior parte no provedor          | Maior parte no provedor                     |
| **Casos de Uso**     | Migração de VMs, sistemas legados, customização total | Desenvolvimento de apps sem gerenciar infra         | Soluções de produtividade (e-mail, ERP, CRM)|
| **Exemplo no Azure** | Azure Virtual Machines                        | Azure App Service, Azure SQL Database               | Microsoft 365, Dynamics 365                 |

---

## 5. Laboratório e Observações Práticas (Módulo 1)
Nos laboratórios do Módulo 1 (referentes ao treinamento **AZ-900**), é possível explorar:

### Máquinas Virtuais no Portal Azure (IaaS)
- Ao criar uma VM, você define imagem do SO, tamanho da máquina, opções de disponibilidade (Availability Sets ou Zones), rede virtual e outras configurações.  
- No final, o portal mostra uma previsão de custo com base nas suas escolhas.

### Banco de Dados SQL (PaaS)
- Ao provisionar um **Azure SQL Database**, você não precisa se preocupar com a instalação do SQL Server ou do sistema operacional.
- É necessário apenas configurar parâmetros como tamanho do banco, nível de desempenho e segurança.
- O portal estima o custo mensal com base no tipo de SQL escolhido (Basic, Standard, Premium etc.).

Essas experiências no Portal do Azure ajudam a entender como cada modelo de serviço delega responsabilidades diferentes ao usuário e ao provedor.

## 6. Gerenciamento e Monitoramento de Recursos no Portal do Azure
### 6.1 Exploração do Site DataCenter.microsoft.com
No site datacenter.microsoft.com, é possível:

Acompanhar as notícias sobre os data centers da Microsoft.

Visualizar um mapa interativo que mostra a localização de todos os data centers do mundo, permitindo uma visão global da infraestrutura da Microsoft.

### 6.2 Criação de um Grupo de Recursos no Portal do Azure
O grupo de recursos é um contêiner lógico no Azure que agrupa recursos relacionados para facilitar o gerenciamento. Veja o passo a passo para criá-lo:

Acesso e Pesquisa:
No portal do Microsoft Azure, utilize a barra de pesquisa para localizar “grupo de recursos” e clique na opção correspondente.

Configuração Inicial:

Assinatura: Selecione a assinatura ativa.

Grupo de Recursos: Defina um nome para o grupo, que servirá como identificador.

Região: Escolha a região onde os recursos serão alocados, considerando fatores como latência e conformidade.

Marcações (Tags): Utilize tags para adicionar informações descritivas (por exemplo, subtítulos que expliquem funcionalidades e obrigações). Essa prática facilita a identificação dos recursos na fatura e melhora a organização.

Revisão e Criação:
Após preencher as informações, clique em “Revisar + criar”. Revise os detalhes e, se tudo estiver correto, confirme clicando em “Criar”.

O grupo de recursos será criado vazio e você poderá adicionar, posteriormente, as diversas soluções e serviços que compõem sua infraestrutura.

### 6.3 Ferramentas de Monitoramento e Gerenciamento
Log de Atividade:
Exibe registros de criação, alteração ou exclusão de recursos, funcionando como um sistema de auditoria que ajuda a monitorar as operações realizadas.

IAM (Identity and Access Management):
Permite gerenciar o acesso aos recursos, atribuindo ou revogando permissões para usuários e grupos. Essa ferramenta é fundamental para garantir que apenas pessoas autorizadas possam modificar ou acessar determinados recursos.

Eventos:
Oferece uma visualização das automações e alertas configurados, ajudando a identificar atividades importantes ou problemas potenciais.

Implantações:
Lista os recursos e serviços que foram implantados, permitindo acompanhar o histórico de configurações e alterações realizadas na infraestrutura.

Exemplo Prático:
Após criar um grupo de recursos para um novo projeto, você pode usar o Log de Atividade para monitorar a criação de VMs e o IAM para garantir que apenas a equipe de TI tenha acesso administrativo, garantindo transparência e segurança.


