# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

## Microsoft Azure - Localizando Serviços por Categoria

- **Reforço na continuidade das aulas**, pedindo para que o aluno assista às aulas anteriores para não ter dificuldade.
- **Apresentadas funções da Azure** para personalização de temas, idioma e região.
- **Todas as categorias de produtos** e onde encontrá-los.
- **O que são e para que servem os Bastions**.
- **Reforço do compromisso mútuo** do desenvolvedor e do provedor de serviços da nuvem.
- **Apresentadas diferenças de ferramentas** que podem não estar disponíveis dependendo do plano gratuito ou da região do usuário.
- Significado do aviso de ferramenta "prévia" e que ela pode ser **tirada do ar sem aviso**.

## Criando máquinas Virtuais na Azure

- Apresentado o conceito de SLA e suas modalidades.
- O SLA garante que deteminada ferramenta pode ficar certo tempo indisponível, ultrapassado esse tempo, é possível o ressarcimento do valor desse serviço.
- Dicas para atendimento e respostas sobre como tratar com cliente quando um serviço é dado como indisponível.
- Apresentadas estratégias, arquitetura, de usodo sistema sobre como usar e planejar essas ferramentas.

LRS (armazenamento com redundância local)

GRS (armazenamento com redundância geográfica)

ZRS (armazenamento com redundância de zona)

GZRS (armazenamento com redundância de zona geongráfica)

## Configurando uma instância de Banco de Dados na Azure

- Apresentação da configuração de um banco de dados.
- Reforço sobre os limites de IaaS, PaaS e SaaS.
- Apresentação da calculadora ao final da configuração do banco de dados.

## Construindo Arquiteturas no Azure

* Apresentação dos data centers da Azure, com uma visita virtual para o data center do Brasil
* Criação de grupos de recursos
* Explicação do uso de marcações
* Configurações do grupo de recursos
* Criação da Vnet (rede virtual) associada ao grupo de recursos

## Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure

* Possibilidades de configurações de VMs "pré-configuradas"
* Configurações Gerais de Máquinas Virtuais:
  * Configurações de Escala e estratégia de escalonamento automático
  * Tamanhos de VMs para estratégias de máquinas
  * Opçõdes de exclusão na VM para que outras configurações não fiquem ativas quando a VM for deletada
  * Configuração de backup e comportamento
  * Regras de Monitoramento

## Dominando o armazenamento na Azure

* Configurações de armazenamento, migração e Data box
* Criação de uma conta de armazenamento -> files, queues, tables, blobs -> Contêineres, Compartilhamento de arquivos, Filas e Tabelas 
* Proteção de dados -> Configurações de backup
* O comando para teste utilizando a porta 445 pode não funcionar, pois é uma porta reservada para muitas operadoras.
* Azure Migrate: Discovery and Assessment
* Preços e simulação de Data box

## Entendendo sobre Segurança e Identidade na Azure

* Diretório no Azure, incluindo Microsoft Entra ID e o Microsoft Entra Domain Services
* Métodos de autenticação no Azure: SSO, MFA e sem senha
* Identidades externas e o acesso de convidado
* Acesso Condicional do Entra 

## Otimizando Custos no Azure

* Calculadora do TCO (Custo Total de Propriedade)
 * Construção da simulação com diversas opções de hardware, serviços e cobertura de seguro de software
* Calculadora de Preço
 * Construção de estimativa de preço de uma VM - demonstrando a abrangencia de preço das configurações
* Cost Management + Billing
 * Alerta de custos e orçamentos
 * Advisor recommendations

## Gerenciando Politicas em Acessos Azure

* Apresentação do Portal de Confiança do Serviço
 * Recursos para o Brasil - BACEN
 * Recursos para outros países
* Bloqueios a nível de Resource Group
* Apresentação do Microsoft Purview
 * Criação de conta
 * Apresentação do Novo Portal do Purview e algumas ferramentas
* Policies, onde acessar e como funcionam

## Ferramentas de Implantação na Azure

* Criação de recursos através do portal Azure
* Execução do Cloud Shell
* Apresentação de tópicos de automação - CLI/PS - Tasks - Export template
* Apresentação do Bicep Playground - azure.github.io/bicep/
* ARC - apresentação da adição de infraestrutura e serviços 

## Monitoramento Inteligente com o Azure

* Apontamento para os serviços Monitor, Advisor e Service Health para saber como estão as configurações da sua nuvem.
* Insights dentro do Monitor, que cobre diversos aspectos como: Applications, VMs, Storage Accounts, Containers, Networks, etc
* Trazer métricas e logs para entender o que esta acontecendo
* Apresentação do Service Health com o mapa-múndi
* Apresentação do Advisor - Recomendações de custo, segurança, performance, etc
