# project-dio-aws
Projeto de arquitetura Cloud focado na redução de custos para o setor farmacêutico. A solução utiliza AWS Lambda e S3 Intelligent-Tiering para otimizar o fluxo de caixa, convertendo CAPEX em OPEX e reduzindo o custo marginal. Inclui governança via AWS Budgets para controle rigoroso de EBITDA e viabilidade econômica. Relatório no GitHub.

# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 12 de Março de 2026  
**Empresa:** Abstergo Industries (Pharma Division)  
**Responsável:** Alice Ramos Saar

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Pharma, realizado por Alice Ramos Saar. O objetivo do projeto foi elencar 3 serviços AWS com a finalidade de realizar a diminuição de custos imediatos e otimização do fluxo de caixa operacional.

## Descrição do Projeto
O projeto de implementação foi dividido em 3 etapas estratégicas:

### Etapa 1: 
- **Ferramenta:** Amazon S3 (Intelligent-Tiering)
- **Foco:** Otimização de armazenamento de dados frios.
- **Caso de Uso:** Armazenamento de receitas médicas digitalizadas. A ferramenta move automaticamente dados pouco acessados para camadas de custo reduzido, gerando economia imediata sem necessidade de gestão manual.

### Etapa 2: 
- **Ferramenta:** AWS Lambda (Serverless)
- **Foco:** Eliminação de custos fixos com servidores ociosos.
- **Caso de Uso:** Processamento de transações e fechamento de caixa. Ao contrário de um servidor ligado 24/7, a cobrança ocorre apenas nos milissegundos de execução das vendas, otimizando o EBITDA da operação.

### Etapa 3: 
- **Ferramenta:** AWS Budgets
- **Foco:** Governança e controle financeiro (FinOps).
- **Caso de Uso:** Monitoramento de gastos em tempo real com alertas automáticos ao atingir 80% do orçamento planejado, garantindo previsibilidade e evitando surpresas na fatura mensal.

## Conclusão
A implementação das ferramentas na Abstergo Pharma tem como esperado a redução significativa de despesas operacionais (OPEX) e a eliminação da necessidade de novos investimentos em hardware (CAPEX). Isso aumentará a eficiência, a escalabilidade marginal da rede e a segurança dos dados sensíveis da empresa.

## Anexos
- Tabela de Viabilidade Econômica (On-Premise vs Cloud)
- Arquitetura lógica do projeto (Serverless & Storage)

**Assinatura do Responsável pelo Projeto:** Alice Ramos Saar
