# Primeiros Passos na Nuvem com Azure
Bem-vindo(a) ao meu repositório de aprendizado! Este projeto foi desenvolvido durante o Bootcamp da DIO, com o objetivo de documentar e praticar a criação de recursos na plataforma Microsoft Azure. A ideia é consolidar os conhecimentos adquiridos sobre os principais serviços de nuvem e demonstrar a aplicação prática de conceitos como IaaS, PaaS e SaaS.

O foco principal foi a configuração de uma Máquina Virtual e a criação de uma instância de Banco de Dados SQL do Azure, que são serviços essenciais para qualquer arquiteto de nuvem.

## Conceitos Essenciais da Nuvem
Durante esta jornada, explorei e compreendi os seguintes conceitos-chave que guiaram a construção do projeto:

- **CapEx (Capital Expenditure) vs. OpEx (Operational Expenditure):** A principal diferença entre o modelo tradicional de data center e a nuvem. Entendi que a nuvem permite migrar os altos custos de investimento inicial (CapEx) para um modelo de pagamento sob demanda (OpEx), oferecendo mais flexibilidade e previsibilidade financeira.

- **Escalabilidade e Elasticidade:** A capacidade de adicionar recursos para acompanhar a demanda (Escalabilidade) e o ajuste automático e dinâmico desses recursos (Elasticidade) são vantagens cruciais da nuvem para garantir o bom desempenho de aplicações.

- **Alta Disponibilidade e SLA (Service Level Agreement):** O Azure garante um tempo mínimo de atividade de seus serviços através do SLA, o que é fundamental para a confiabilidade de aplicações essenciais.

- **Modelo de Responsabilidade Compartilhada:** A segurança na nuvem é uma responsabilidade conjunta entre o provedor (Microsoft) e o cliente. A divisão dessas responsabilidades varia de acordo com o modelo de serviço contratado (IaaS, PaaS ou SaaS).

- **Regiões e Grupos de Recursos:** Para organizar e gerenciar os recursos de forma eficiente, a Azure utiliza o conceito de Regiões (locais físicos de data centers) e Grupos de Recursos (contêineres lógicos para agrupar recursos de um projeto).

# Passo a Passo do Lab: Criando um Banco de Dados SQL
1. **Acesso ao Portal Azure:** Utilizei o portal da Microsoft Azure para iniciar a criação dos recursos.

2. **Criação de um Grupo de Recursos:** Como boa prática, criei um novo Grupo de Recursos para agrupar todos os componentes do projeto (o banco de dados e o servidor).

3. **Configuração da Instância:** Selecionei a opção de Banco de Dados SQL do Azure. Em seguida, configurei as principais opções, como o nome do banco, a região, o tipo de servidor e o modelo de preço.

4. **Definição do Servidor:** Criei um novo servidor lógico na Azure para hospedar o banco de dados. Configurei o nome, a localização e as credenciais de administrador.

5. **Ajustes Finais:** Revisei todas as configurações, inclusive a estimativa de custos exibida no portal, para garantir que tudo estivesse conforme o planejado.

O processo foi simples e me deu uma visão clara de como é fácil e rápido provisionar um banco de dados robusto na nuvem, sem me preocupar com a infraestrutura subjacente.

# Links Úteis
[Documentação oficial sobre o Azure SQL Managed Instance](https://learn.microsoft.com/pt-br/azure/azure-sql/managed-instance/instance-create-quickstart?view=azuresql&tabs=azure-portal)

[Well-Architected Framework da Microsoft](https://learn.microsoft.com/pt-br/azure/architecture/framework/)

[Modelos de preços da Azure](https://azure.microsoft.com/pt-br/pricing/)
