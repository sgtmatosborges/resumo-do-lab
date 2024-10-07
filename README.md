# resumo-do-lab
# Resumos Aulas GIT e GITHUB
Repositorio de resumo de aulas GIT e GITHUB da
[DIO](https://web.dio.me/home).
Aprendizado das aulas:
_Introdução ao curso e ferramentas_, _instalação_, _configuração e autenticação_, _primeiros passos com git e github_.
## 📚 Documentação
- [Documentação Git](https://git-scm.com/docs/git/pt_BR)
- [Documentação GitHub](https://docs.github.com/pt)

# 📚 ☁️ Resumo criando Maquinas virtuais na Azure Microsoft.

Aprendidzado nas aulas Benefícios da nuvem: **escalabilidade** e **elasticidade**
Benefícios da nuvem: **confiabilidade**, **previsibilidade** e **segurança** Benefícios da nuvem: **Governança** e **gerenciabilidade**, tambem realizado o entendimento sobre 

##🔍 Referência

 - [Portal Azure](https://portal.azure.com/#home)
 - [Documentação AZURE](https://learn.microsoft.com/pt-br/azure/?product=popular&WT.mc_id=Portal-Microsoft_Azure_Support)

## 📷Screenshots_ Azure Menu

![Azure menu principal](https://learn.microsoft.com/pt-br/purview/media/create-service-principal-azure/create-service-principal-azure-aad.png)

# 🛅 ☁️ Resumo Serviços de Nuvem:

 **Iaas** Infraestrutura como serviço:É uma infraestrutura de TI de pagamento conforme o uso alugando servidores, máquinas virtuais, armazenamento, redes e sistemas operacionais de um provedor de nuvem.
**PaaS** Plataforma como serviço: Fornece um ambiente para a criação, o teste e a implantação de aplicativos de software, sem focar no gerenciamento da infraestrutura subjacente. **SaaS** Software como serviço: Os usuários se conectam e usam aplicativos com base em nuvem pela Internet: por exemplo, Microsoft Office 365, email e calendários.
- IaaS O serviço de nuvem mais flexível, você configura e gerencia o hardware para seu aplicativo.
* PaaS Focado no desenvolvimento de aplicativos, gerenciamento de plataforma é realizado pelo provedor de nuvem.
+ SaaS Modelo de preço de pagamento conforme o uso, usuários pagam pelo software que utilizam em um modelo de assinatura.
## 📷 Imagem SaaS, PaaS, IaaS:

![Azure menu principal](https://media.licdn.com/dms/image/C4E12AQFJ5HpWNPU6TA/article-cover_image-shrink_720_1280/0/1614239296629?e=2147483647&v=beta&t=kZng28PBfBLFP1bCr753f5e7pU0S54cqbPaVeND60pg)

# Dominando o Armazenamento no azure

O armazenamento do Azure é um serviço da Microsoft que permite armazenar e gerenciar dados em nuvem. Ele oferece vários tipos de armazenamento, como: 
Armazenamento de Blobs
Ideal para armazenar grandes quantidades de dados não estruturados, como imagens, vídeos, arquivos de áudio e arquivos de texto. 
Armazenamento de Arquivos do Azure
Oferece armazenamento em nuvem seguro, durável e altamente disponível para dados raramente acessados. 
Azure Files
Permite compartilhar arquivos entre a nuvem e sistemas on-premise (locais). 
Azure Queue Storage
Um recurso de armazenamento de filas que pode ser acessado pelos serviços HTTP ou HTTPS. 
Data Lake Storage Gen2
Oferece um sistema de arquivos hierárquico, com armazenamento em camadas de baixo custo, alta disponibilidade, forte consistência e recursos de recuperação de desastres. 
Uma conta de armazenamento do Azure contém todos os objetos de dados do Armazenamento do Azure, como blobs, arquivos, filas e tabelas. Os limites de capacidade de armazenamento do Azure são definidos no nível da conta. 
O Gerenciador de Armazenamento do Microsoft Azure é um aplicativo que facilita o trabalho com dados do Armazenamento do Azure no Windows, macOS e Linux. 

# Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure

Configurar recursos e dimensionar máquinas virtuais na Azure é um processo essencial para garantir que suas aplicações sejam eficientes e escaláveis. Aqui estão alguns passos básicos para te ajudar a começar:

Acessar o Portal do Azure: Primeiro, acesse o portal do Azure e selecione "Grupos de Recursos" no menu à esquerda
. Escolha o grupo de recursos que contém o conjunto de escalas e, em seguida, selecione o conjunto de escalas na lista de recursos
Configurar Recursos: Dentro do conjunto de escalas, você pode ajustar os recursos, como o número de instâncias, o tamanho das instâncias (tamanho da VM), e a rede associada
Dimensionamento Automático: Para dimensionar automaticamente, vá para a seção "Dimensionamento" no menu à esquerda da janela do conjunto de escalas
. Aqui, você pode configurar regras de dimensionamento automático com base em métricas como CPU, memória ou tráfego de rede
Monitoramento e Ajustes: Após configurar, é importante monitorar o desempenho e fazer ajustes conforme necessário. O Azure fornece ferramentas de monitoramento que ajudam a entender o uso de recursos e a identificar quando ajustes são necessários.


# Visão geral da segurança de gerenciamento de identidade do Azure

Gerenciamento de identidade é o processo de autenticação e autorização das entidades de segurança. Também envolve controlar informações sobre as entidades (identidades). As entidades de segurança (identidades) podem incluir serviços, aplicativos, usuários, grupos etc. As soluções de gerenciamento de acesso e identidade da Microsoft ajudam a TI a proteger o acesso a aplicativos e recursos no datacenter corporativo e na nuvem. Esse tipo de proteção permite níveis adicionais de validação, tais como autenticação multifator e políticas de acesso condicional. O monitoramento de atividade suspeita por meio de alertas, auditoria e relatórios de segurança avançados ajuda a reduzir potenciais problemas de segurança. O Microsoft Entra ID P1 ou P2 fornece SSO (logon único) para milhares de aplicativos SaaS (software como serviço) de nuvem e acesso a aplicativos Web executados localmente.

Aproveitando os benefícios de segurança do Microsoft Entra ID, você pode:

Crie e gerencie uma identidade única para cada usuário em sua empresa híbrida, mantendo usuários, grupos e dispositivos em sincronia.
Fornecer acesso de SSO para seus aplicativos, incluindo milhares de aplicativos de SaaS pré-integrados.
Habilitar segurança de acesso do aplicativo por meio da aplicação da autenticação multifator com base em regras para aplicativos locais e na nuvem.
Provisionar o acesso remoto seguro a aplicativos Web locais por meio do proxy de aplicativo do Microsoft Entra.
O objetivo deste artigo é fornecer uma visão geral dos recursos de segurança centrais do Azure que ajudam com o gerenciamento de identidades. Também fornecemos links para artigos que dão os detalhes de cada recurso para que você possa saber mais.

O artigo se concentra nas seguintes funcionalidades de gerenciamento de identidade centrais do Azure:

Logon único
Proxy reverso
Autenticação multifator
RBAC do Azure (controle de acesso baseado em função do Azure)
Relatórios baseados em aprendizado de máquina, alertas e monitoramento de segurança
Gerenciamento de acesso e identidade do consumidor
Registro de dispositivos
Privileged Identity Management
Proteção de identidade
Gerenciamento de identidade híbrida/conectar Azure Active Directory
Revisões de acesso do Microsoft Entra

# Logon Único
SSO (logon único) significa poder acessar todos os aplicativos e recursos de que você precisa para fazer negócios, conectando-se apenas uma vez usando uma única conta de usuário. Depois de conectado, você pode acessar todos os aplicativos necessários sem a exigência de autenticação (por exemplo, digitar uma senha) uma segunda vez.

Muitas organizações contam com aplicativos de SaaS como o Microsoft 365, o Box e o Salesforce, para aumentar a produtividade do usuário. Historicamente, a equipe de TI precisava criar e atualizar individualmente as contas de usuário em cada aplicativo SaaS e os usuários precisavam lembrar uma senha para cada aplicativo SaaS.

O Microsoft Entra ID estende os ambientes do Active Directory local para a nuvem, permitindo que os usuários usem suas contas organizacionais primárias para se conectar não apenas a recursos corporativos e dispositivos ingressados no domínio, mas também a todos os aplicativos Web e de SaaS necessários para seus trabalhos.

Os usuários não precisam apenas gerenciar vários conjuntos de nomes de usuário e senhas, mas também podem provisionar ou desprovisionar o acesso automaticamente com base nos grupos organizacionais e no status de funcionário deles. O Microsoft Entra ID introduz controles de governança de acesso e segurança com os quais você pode gerenciar centralmente o acesso dos usuários a aplicativos de SaaS.

# Autenticação multifator

A autenticação multifator do Microsoft Entra é um método de autenticação que exige o uso de mais de um método de verificação e adiciona uma segunda camada de segurança crítica às entradas e transações dos usuários. A autenticação multifator ajuda a proteger o acesso a dados e aplicativos enquanto atende à demanda dos usuários para um processo de logon simples. Ela fornece autenticação forte por meio de uma variedade de opções de verificação: chamada telefônica, mensagem de texto, notificações de aplicativo móvel ou códigos de verificação e tokens OAuth de terceiros.

# RBAC do Azure
O RBAC do Azure é um sistema de autorização baseado no Azure Resource Manager que fornece gerenciamento de acesso refinado aos recursos no Azure. O RBAC do Azure permite controlar de modo granular o nível de acesso que os usuários têm. Por exemplo, você pode limitar um usuário para somente gerenciar redes virtuais e outro usuário para gerenciar todos os recursos em um grupo de recursos. O Azure inclui várias funções internas que você pode usar.

# Relatórios baseados em aprendizado de máquina, alertas e monitoramento de segurança

Monitoramento de segurança, alertas e relatórios baseados no aprendizado de máquina que identificam padrões de acesso inconsistentes podem ajudá-lo a proteger seus negócios. Você pode usar os relatórios de uso e de acesso do Microsoft Entra ID para obter visibilidade quanto à integridade e segurança do diretório da sua organização. Com essas informações, um administrador de diretório pode determinar melhor onde possíveis riscos de segurança podem estar, de modo que pode fazer planos adequados para mitigar esses riscos.

No portal do Azure, os relatórios se enquadram nas categorias a seguir:

Relatórios de anomalias: contêm eventos de entrada que nós identificamos como anômalos. Nossa meta é que você fique ciente dessas atividades e possa determinar se um evento é suspeito ou não.
Relatórios de aplicativos integrados: fornecem um panorama de como os aplicativos em nuvem estão sendo usados na sua organização. O Microsoft Entra ID oferece integração com milhares de aplicativos em nuvem.
Relatórios de erros: indicam erros que podem ocorrer ao provisionar contas para aplicativos externos.
Relatórios específicos do usuário: exibem dados de atividade de entrada/dispositivo de um usuário específico.
Logs de atividades: contêm um registro de todos os eventos auditados nas últimas 24 horas, nos últimos 7 dias ou 30 dias, bem como alterações de atividades do grupo e atividades de registro e redefinição de senha.

# Otimizando Custos no Azure

Otimizar custos no Azure é essencial para garantir que você esteja utilizando seus recursos de forma eficiente e economizando dinheiro. Aqui estão algumas dicas para te ajudar:

Monitoramento e Análise de Custos: Utilize o Azure Cost Management para monitorar e analisar seus gastos. 
Ele oferece ferramentas como análise de custos, previsão de custos e orçamentos para ajudar a controlar os gastos

Uso de Tags: Utilize tags para organizar e categorizar seus recursos. 
Isso facilita a identificação de quais recursos estão sendo usados por quais departamentos ou projetos, ajudando a entender melhor onde os custos estão sendo gerados

Desligar Recursos Não Utilizados: Desligue ou desative recursos que não estão sendo utilizados. Muitas vezes, recursos como VMs e armazenamento são deixados ligados mesmo quando não são necessários, resultando em custos desnecessários.

Dimensionamento Automático: Utilize o dimensionamento automático para ajustar a quantidade de recursos conforme a demanda. Isso garante que você esteja utilizando apenas o necessário, evitando desperdícios.

Aproveitar Ofertas e Descontos: O Azure oferece várias ofertas e descontos, como a Azure Reserved Instances, que podem reduzir significativamente os custos se você planejar usar recursos por um período prolongado.

Revisão Regular de Custos: Faça revisões regulares dos seus custos e compare-os com seus orçamentos. Isso ajuda a identificar áreas onde você pode fazer ajustes para economizar.

# Gerenciando Politicas em Acessos Azure


Gerenciar quem pode acessar seus recursos e assinaturas do Azure constitui uma parte importante de sua estratégia de governança do Azure. Atribuir direitos e privilégios de acesso baseados em grupo é uma boa prática. Lidar com grupos em vez de usuários individuais simplifica a manutenção das políticas de acesso, fornece gerenciamento de acesso consistente entre as equipes e reduz os erros de configuração. O Azure RBAC (controle de acesso baseado em função do Azure) é o principal método de gerenciamento de acesso no Azure.

O RBAC do Azure permite gerenciar o acesso de seus recursos no Azure. Ele ajuda você a gerenciar quem tem acesso aos recursos do Azure, o que eles podem fazer com esses recursos e que escopo eles podem acessar.

Ao planejar sua estratégia de controle de acesso, conceda a usuários o menor privilégio necessário para realizarem seus trabalhos. A imagem a seguir mostra um padrão sugerido para a atribuição do Azure RBAC.

Ao planejar sua metodologia de controle de acesso, tente trabalhar com as pessoas de sua organização. Recomendamos trabalhar com pessoas nas áreas de segurança e conformidade, administração de TI e arquitetura empresarial.

# Ferramentas de Implantação na Azure

As ferramentas de implantação no Azure são essenciais para automatizar e gerenciar a entrega de aplicativos e serviços. Aqui estão algumas das principais ferramentas e práticas recomendadas:

Azure DevOps: Oferece pipelines de CI/CD (Integração Contínua e Entrega Contínua) que permitem automatizar a construção, teste e implantação de aplicativos.

Azure Resource Manager (ARM) Templates: Usado para definir a infraestrutura como código, permitindo a implantação consistente de recursos do Azure

GitHub Actions: Integrado ao GitHub, permite configurar fluxos de trabalho de CI/CD diretamente nos repositórios de código1.
Azure Resource Manager (ARM) Templates: Usado para definir a infraestrutura como código, permitindo a implantação consistente de recursos do Azure.

Terraform: Uma ferramenta de código aberto que permite definir e provisionar infraestrutura através de arquivos de configuração.

Azure Kubernetes Service (AKS): Facilita a implantação, gerenciamento e operação de clusters Kubernetes no Azure

# Monitoramento Inteligente com o Azure

O Monitoramento Inteligente com o Azure envolve o uso de várias ferramentas para garantir a observabilidade e o desempenho ideal dos seus aplicativos e infraestrutura. Aqui estão algumas das principais ferramentas e recursos:

Azure Monitor: Coleta e analisa dados telemétricos de seus aplicativos e infraestrutura, ajudando a identificar e resolver problemas rapidamente.

Azure Log Analytics: Permite coletar e analisar dados de logs de diferentes fontes, facilitando a detecção de anomalias e a geração de insights.

Azure Application Insights: Fornece monitoramento de desempenho de aplicativos em tempo real, ajudando a identificar gargalos e melhorar a experiência do usuário.

Intelligent Insights: Usa inteligência artificial para monitorar e otimizar o desempenho de bancos de dados SQL no Azure

## Referência

 - [Azure Monitor](https://azure.microsoft.com/pt-br/products/monitor/)

## 🚀 Sobre mim
Sou Rafael Matos Borges, 41 anos Graduação em Analise de Sistemas e Redes de Computadores com atuação na area de Infra-estrutura migrando para cloud aprendendo LINUX, DOCKER, KUBERNETES.
## 🔗🛜 Minhas Redes e Link.
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/sgtmatosborges)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rafael-matos-borges-86918b294/)
