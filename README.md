# resumo-do-lab
# Computação em Nuvem

Essa jornada foi essencial para aprofundar meu entendimento sobre conceitos-chave, modelos de serviço e implantação em nuvem, além de explorar as vantagens estratégicas dessa tecnologia para impulsionar negócios.
Em um cenário onde a nuvem se tornou peça fundamental para inovação, resiliência e escalabilidade, acredito que esse conhecimento complementa minha atuação em estratégia e risco, trazendo novas perspectivas para apoiar organizações em suas jornadas digitais.
#ComputaçãoEmNuvem #Estratégia #TransformaçãoDigital #Tecnologia #Inovação #CloudComputing

# Beneficios e SLA 

A computação em nuvem transformou a forma como empresas e indivíduos utilizam tecnologia. Entre os principais benefícios, destaco:
Escalabilidade – Possibilidade de aumentar ou reduzir recursos conforme a demanda.
Redução de Custos – Pagamento apenas pelo que é utilizado, eliminando grandes investimentos iniciais.
Segurança – Provedores como a Microsoft oferecem proteção robusta contra ameaças.
Acessibilidade – Acesso remoto a dados e aplicativos, permitindo trabalho de qualquer lugar.
Um Acordo de Nível de Serviço (SLA) define os padrões de qualidade que um provedor de serviços deve garantir. Alguns pontos importantes:

Disponibilidade – Garantia de uptime do serviço (ex: 99,9%).
Desempenho – Tempo de resposta e latência aceitáveis.
Compensação – Definição de reembolsos caso o SLA não seja atendido.

# Modelos de Serviço na Nuvem (IaaS, PaaS, SaaS)

IaaS (Infrastructure as a Service) - Fornece infraestrutura virtualizada, como servidores, redes e armazenamento.
PaaS (Platform as a Service) - Oferece um ambiente gerenciado para desenvolvimento e implantação de aplicativos.
SaaS (Software as a Service) - Softwares hospedados na nuvem acessíveis via navegador, sem necessidade de instalação local.
Os recursos são as instâncias dos serviços do Azure, como máquinas virtuais, bancos de dados e armazenamento, que podem ser organizados dentro de um Grupo de Recursos. Esse agrupamento facilita o gerenciamento, controle de custos e aplicação de políticas de segurança, permitindo a administração centralizada de múltiplos recursos.

Para gerenciar eficientemente os serviços, o Azure oferece ferramentas como Azure Portal, uma interface gráfica para administração, Azure CLI e PowerShell.
Uma boa estruturação de regiões, recursos e grupos de recursos é essencial para otimizar desempenho, custos e segurança na nuvem Azure

# Computação e Maquinas Virtuais

É um serviço sob demanda que fornece recursos de computação como discos, processadores, memória, rede e sistemas operacionais 
Contêineres - fornece um ambiente leve e virtualizado que não exige o gerenciamento do sistema operacional e pode responder alterações sob demanda. É uma oferta PaaS 
Serviços de Kubnets (AKS) um serviço de orquestração para contêineres com arquitetura distribuídas e grandes volumes de contêineres
Azure Functions - oferta Paas que dá suporte a operações de computações sem serviço.
Área de Trabalho virtual - fornece uma experiência de área de trabalho do Windows em nuvem 
- o logon de vários clientes ao mesmo tempo 
- aplicativos dedicados para conexão e uso ou acessíveis de qualquer navegador moderno
Serviços de aplicativos - plataforma gerenciada para criar, implantar e dimensionar aplicativos Web e APIs. Trabalha com .NET, .NETCores, Node.js, Java, Phyton ou PHP. Oferta de PaaS com requisitos de nível corporativo de desempenho, segurança e conformidade
Rede Virtual (Vnet) permite que os recursos do azure se comuniquem uns com os outros, com a Internet e com as redes locais
Gateway de VPN - é usado para enviar tráfego criptografado entre uma rede virtual do azure e uma no local pela internet pública. VPN SITE-TO-SITE
ExpressRoute - estende as redes locais par Azure por meio de uma conexão privada facilitada por um provedor de conectividade

# Identidade, Acesso e Segurança

 Microsoft Entra ID (Active Directory) - é o serviço de gerenciamento de identidade e acesso baseado em nuvem do Microsoft Azure. 
 - autenticação
 - logon unico - sso
 - gerenciamento de aplicativos
 - negócios para negócios - B2B
 - gerenciamento de dispositivos

Microsoft Entra Domain Services - é um serviço gerenciado da Microsoft que fornece funcionalidades do Active Directory (AD) na nuvem. Ele permite que aplicativos e serviços que dependem do AD tradicional operem no Azure sem a necessidade de configurar e gerenciar um controlador de domínio físico
- obtenha os benefícios dos serviços de domínio baseados em nuvem sem gerenciar os controladores de domínio
- execute aplicativos herdados (que não podem utilizar os padrões de autenticação modernos) na nuvem
- Sincronizar automaticamente a partir do Microsoft Entra ID

Autenticação
- identifica a pessoa ou serviço buscando acesso a um recurso
- solicita credenciais de acesso legítimo
- base para criar princípios de identidade e controle de acesso seguros

Autorização
- deterrmina o nível de acesso de uma pessoa ou serviço autenticado
- define quais dados eles podem acessar e o que podem fazer com eles
  
Autenticaação Multifator MFA
- fornece segurança adicional para identidades exigindo dois ou mais elementos para autenticação completa
- estratégia - algo que você sabe, algo que você possui, algo que você é
  
Acesso Condicional - monitoramento detalhado
- associação de usuário ou grupo
- local do ip
- dispositivo
- aplicativo
- detecção de risco
  
Controle de acesso baseado em função - RBAC

- gerenciamento de acesso de granularidade fina
- divida as tarefas dentro da equipe e conceda somente a quantidade de acesso de que os usuários precisam para trabalhar
- habilite o acesso ao portal do azure e o controle de acesso aos recursos
  
Confiança Zero
- restringe tudo a uma rede 'segura'
- protege os ativos em qualquer lugar com uma política central
  
Proteção completa
- Camadas/níveis de proteção: segurança física > identidade de acesso > perímetro > rede > computação > aplicativo > dados
- uma abordagem em camadas para proteger sistema de computador
- fornece vários níveis de proteção
- ataques contra uma camada são isolados das camadas subsequentes
  
Microsoft Defender para Nuvem - é um serviço de monitoramento que fornece proteção contra ameaças nos datacentets do Azure e locais

Recursos do Azure Proteção
- Fornece recomendações de segurança
- Detectar e bloquear malware
- Analisar e identificar ataques potenciais
- Controle de acessos just-in-time para portas

# Análise de Sentimentos com Language Studio no Azure AI

Análise de texto Resposta a perguntas
Defina uma base de conhecimento de pares de perguntas e respostas
- ao inserir perguntas e respostas
- de um documento de perguntas frequentes existentes
- usando bate-papo integrado

Serviço de bot do Azure
- plataforma baseada em nuvem para desenvolvimento e gerenciamento
- integração com AI Languade e outros serviços
- Conectividade através de vários canais

# Azure Cognitive Search: Utilizando AI Search para indexação e consulta de Dados

é um serviço da Microsoft que permite criar buscas inteligentes em grandes volumes de dados. Ele vai muito além de uma simples pesquisa por palavras-chave — com a integração de inteligência artificial, ele consegue entender o conteúdo, extrair informações relevantes e até interpretar linguagem natural
- Ao usar o AI Search, você pode indexar dados de diferentes fontes (como documentos, bancos de dados ou até imagens) e enriquecer esses dados automaticamente com recursos como reconhecimento de texto em imagens (OCR), tradução, extração de entidades (como nomes, datas, locais) e mais. Isso transforma conteúdo bruto em algo pesquisável e útil.
- pode ser integrado em aplicativos, portais, sistemas internos ou sites, permitindo que os usuários encontrem rapidamente o que precisam — mesmo em coleções enormes e desorganizadas de documentos.

# O que é o OpenAI do Azure

é a solução de nuvem da microsoft para implantar, personalizar e hospedar modelos de linguagem grandes
Azure OpenAI combina o poder dos modelos avançados da OpenAI com os recursos empresariais do Azure — como segurança, compliance, controle de acesso e integração com outros serviços Microsoft.
permite usar a IA de ponta da OpenAI de forma segura, escalável e adaptada para empresas e desenvolvedores no ecossistema Microsoft.

# Explorando os Recursos de IA Generativa com Copilot e OpenAI

Fases do processo par adesenvolver e implemntar um plano de IA responsável: identificar, medida, mitigar e operar
- Identificar: possiveis danos relevantes para a solução desejada
- Medida: a presença de danos nas saidas geradas pela solução
- Mitigar: os danos em varias camadas em sua solução para minimizar a presença e impacto deles
- Operar: a solução com responsabilidade definindo e seguindo um plano de implantação e de preparação operacional


