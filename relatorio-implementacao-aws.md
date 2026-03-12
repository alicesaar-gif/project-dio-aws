# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 12 de Março de 2026
**Empresa:** Abstergo Industries (Pharma Division)
**Responsável:** Alice Ramos Saar

---

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa **Abstergo Pharma**, realizado por **Alice Ramos Saar**. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

A estratégia adotada priorizou soluções **cloud-native e serverless**, permitindo maior escalabilidade, redução de custos com infraestrutura física e melhor governança financeira dos recursos computacionais.

---

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

---

### Etapa 1

- **Nome da ferramenta:** Amazon S3 (Intelligent-Tiering)
- **Foco da ferramenta:** Otimização de armazenamento de dados de acesso pouco frequente.
- **Descrição de caso de uso:** Armazenamento de receitas médicas digitalizadas e documentos clínicos arquivados. O Amazon S3 Intelligent-Tiering move automaticamente dados pouco acessados para camadas de armazenamento de menor custo, sem impacto no desempenho. Políticas de lifecycle podem ser aplicadas para arquivamento em camadas Glacier, reduzindo ainda mais os custos de dados históricos e regulatórios.

---

### Etapa 2

- **Nome da ferramenta:** AWS Lambda (Arquitetura Serverless)
- **Foco da ferramenta:** Eliminação de custos fixos associados a servidores ociosos.
- **Descrição de caso de uso:** Automação de eventos transacionais, como registro de vendas, geração de logs operacionais e integração com sistemas de faturamento. O AWS Lambda executa funções apenas quando acionado por eventos específicos, sendo cobrado somente pelo tempo efetivo de execução em milissegundos — eliminando custos com recursos computacionais subutilizados.

---

### Etapa 3

- **Nome da ferramenta:** AWS Budgets
- **Foco da ferramenta:** Governança financeira e práticas de FinOps.
- **Descrição de caso de uso:** Monitoramento contínuo dos gastos em nuvem com alertas automáticos ao atingir 80% do orçamento planejado. Essa abordagem permite maior previsibilidade financeira, facilita o controle de custos entre equipes e reduz o risco de surpresas na fatura mensal da infraestrutura cloud.

---

## Conclusão

A implementação das ferramentas na empresa **Abstergo Pharma** tem como esperado a **redução de despesas operacionais (OPEX)**, a eliminação de investimentos adicionais em infraestrutura física (CAPEX) e o aumento da eficiência da operação tecnológica — o que aumentará a eficiência e a produtividade da empresa.

A adoção de práticas de **FinOps**, combinada com arquitetura **serverless** e armazenamento inteligente, cria uma infraestrutura mais escalável, resiliente e financeiramente previsível, fortalecendo a capacidade da empresa de expandir suas operações digitais com controle rigoroso sobre custos e segurança de dados sensíveis.

Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

---

## Anexos

- [Tabela de Viabilidade Econômica](./docs/viabilidade.md)
- [Arquitetura Lógica do Projeto](./docs/arquitetura.md)
- [Documentação de Referência AWS](./docs/referencias.md)

---

**Assinatura do Responsável pelo Projeto:**

Alice Ramos Saar
