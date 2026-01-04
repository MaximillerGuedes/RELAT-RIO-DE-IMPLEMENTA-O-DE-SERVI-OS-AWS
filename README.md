# RELATORIO-DE-IMPLEMENTACAO-DE-SERVICOS-AWS
RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 04/01/2026
Empresa: Abstergo Industries 
Responsável: Maximiller Guedes

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Maximiller Guedes. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- **AWS Compute Optimizer**
- Foco: Right-sizing de instâncias EC2 e recomendações de Savings Plans para otimizar o custo de computação.
- Descrição de caso de uso: O Compute Optimizer analisa o histórico de utilização das instâncias EC2 (CPU, memória, rede) e identifica instâncias superdimensionadas. Para a Abstergo Industries, essa ferramenta gera recomendações para downsizing de instâncias ociosas e sugestões de Savings Plans, resultando em redução de até 25-30% nos custos de computação mensal.

Etapa 2: 
- **AWS Cost Explorer com Cost Anomaly Detection**
- Foco: Monitoramento contínuo de gastos, detecção de anomalias e governança orçamentária para prevenir desperdícios.
- Descrição de caso de uso: O Cost Explorer fornece visibilidade granular dos custos por serviço, conta e tags. Com o Cost Anomaly Detection ativado, a Abstergo Industries recebe alertas automáticos sobre aumentos incomuns de gastos. Isso permite identificar rapidamente consumos anômalos (máquinas órfãs, vazamentos de dados), implementar orçamentos e reduzir gastos desnecessários em até 20-35%.

Etapa 3: 
- **Amazon S3 Intelligent-Tiering com Regras de Lifecycle**
- Foco: Otimização automática de custos de armazenamento através de classificação inteligente e transição de dados para classes de menor custo.
- Descrição de caso de uso: O S3 Intelligent-Tiering move automaticamente objetos entre diferentes classes de armazenamento conforme padrões de acesso. Combinado com Regras de Lifecycle, dados antigos são movidos para S3 Glacier ou Archive. Para a Abstergo Industries, essa implementação gera economia de 40-50% em custos de armazenamento, especialmente em dados históricos, logs e backups.



## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado uma redução de 30-50% nos custos operacionais de cloud, eliminação de recursos subutilizados, detecção proativa de anomalias de gastos e otimização contínua do armazenamento. Essas melhorias aumentarão significativamente a eficiência operacional e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas, o acompanhamento regular das recomendações geradas pelos serviços e a busca contínua por novas tecnologias que possam otimizar ainda mais os processos e custos na nuvem.

## Anexos

1. Relatório de recomendações do AWS Compute Optimizer (formato JSON/CSV)
2. Dashboard do Cost Explorer com histórico de 12 meses de gastos
3. Configuração de Alertas e Budgets no AWS Budgets
4. Plano de Implementação de Lifecycle Policies para buckets S3
5. Documentação de boas práticas de otimização de custos AWS

Assinatura do Responsável pelo Projeto:

Maximiller Guedes
