# Bootcamp_Monitoramento_Inteligente_Azure
Este repositório fala um pouco sobre o que aprendi durante o modulo Monitoramento inteligente na Azure do Bootcamp Microsoft Azure Essentials da Dio.

# Assistente do Azure e Integridade do Serviço do Azure

O **Assistente do Azure** (Azure Advisor) é um serviço personalizado que oferece recomendações práticas para ajudar a otimizar seus recursos no Azure. Ele analisa suas configurações e uso de recursos e oferece sugestões para melhorar desempenho, alta disponibilidade, segurança e gerenciamento de custos.

### Finalidade:
- **Otimização de Desempenho**: Sugestões para melhorar a eficiência dos recursos.
- **Alta Disponibilidade**: Recomendações para aumentar a confiabilidade dos serviços.
- **Segurança**: Melhorias de segurança para proteger os recursos e dados.
- **Redução de Custos**: Indicações para reduzir custos, como otimizar o uso de VMs.

### Casos de Uso:
- Receber recomendações automáticas sobre o uso de recursos.
- Identificar áreas onde pode haver economia de custos.
- Garantir que sua infraestrutura esteja configurada para alta disponibilidade.

---

## Integridade do Serviço do Azure

A **Integridade do Serviço do Azure** é um recurso que fornece informações sobre o status dos serviços do Azure, incidentes em andamento e manutenções planejadas. Ele ajuda os usuários a acompanhar a saúde de seus serviços no Azure e a reagir rapidamente a problemas.

### Finalidade:
- **Monitoramento da Integridade**: Permite acompanhar incidentes que podem afetar seus serviços.
- **Notificações Personalizadas**: Você pode receber alertas sobre interrupções e manutenções que podem impactar seus recursos.
- **Planejamento**: Acompanhar manutenções programadas para garantir a continuidade das operações.

### Casos de Uso:
- Ser notificado sobre interrupções de serviço que possam afetar o funcionamento de suas aplicações.
- Planejar com antecedência quando houver manutenções planejadas que possam causar impacto.

---

# Azure Monitor

O **Azure Monitor** é um serviço abrangente que permite monitorar e coletar métricas, logs e dados de desempenho de seus recursos no Azure. Ele é projetado para fornecer visibilidade sobre a integridade, o desempenho e a utilização de seus aplicativos e infraestrutura.

### Finalidade:
- **Coleta de Dados**: Captura logs e métricas de diferentes serviços do Azure.
- **Monitoramento de Aplicações**: Acompanhar o desempenho e a saúde de aplicativos hospedados na nuvem.
- **Análise de Dados**: Permite a análise avançada de dados com base em logs e métricas, oferecendo insights práticos.

### Principais Funcionalidades:
- **Dashboards Personalizados**: Criação de dashboards para visualizar métricas e insights.
- **Alertas**: Configuração de alertas para identificar e reagir a eventos específicos.
- **Automação de Respostas**: Integrar com scripts de automação para responder automaticamente a incidentes.

---

##  Azure Log Analytics

O **Azure Log Analytics** é uma ferramenta integrada ao **Azure Monitor** que permite coletar, analisar e visualizar dados de logs em toda a sua infraestrutura e aplicativos. Ele utiliza a **Linguagem de Consulta Kusto (KQL)** para analisar os logs.

### Finalidade:
- **Coleta Centralizada**: Agrega logs de diferentes fontes, como máquinas virtuais, bancos de dados, e serviços.
- **Análise Avançada**: Permite consultar e analisar grandes volumes de dados em tempo real.
- **Visibilidade e Diagnóstico**: Ajuda a identificar problemas de desempenho e falhas em sua infraestrutura.

### Casos de Uso:
- Consultar logs de servidores e redes para depuração.
- Gerar relatórios de uso de recursos e tendências de desempenho.
- Criar visualizações para monitoramento contínuo de serviços.

---

##  Alertas do Azure Monitor

Os **Alertas do Azure Monitor** permitem configurar notificações automáticas quando determinados eventos ou condições são detectados em seus recursos. Isso ajuda a reagir rapidamente a problemas que podem surgir.

### Finalidade:
- **Monitoramento Proativo**: Receber alertas em tempo real sobre incidentes como falhas de VMs ou violações de desempenho.
- **Notificações Customizadas**: Definir condições específicas para disparar alertas (como uso de CPU acima de certo nível).
- **Automação de Respostas**: Integrar alertas com ferramentas de automação para tomar ações corretivas automaticamente.

### Casos de Uso:
- Ser notificado quando o uso de recursos ultrapassa um limite estabelecido.
- Configurar alertas para falhas em serviços críticos, como bancos de dados ou VMs.
- Integrar alertas com ferramentas de automação, como o **Logic Apps**, para respostas automáticas.

---



