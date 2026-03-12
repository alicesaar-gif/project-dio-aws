# Redução de Custos com AWS – Abstergo Pharma

Projeto de implementação de serviços AWS com foco em **redução de custos operacionais imediatos**.

**Empresa:** Abstergo Industries (Pharma Division)  
**Responsável:** Alice Ramos Saar  
**Data:** 12 de Março de 2026

---

## Serviços Implementados

| Serviço | Objetivo |
|---------|----------|
| Amazon S3 (Intelligent-Tiering) | Armazenamento inteligente de documentos clínicos |
| AWS Lambda | Processamento serverless de eventos transacionais |
| AWS Budgets | Governança financeira e alertas de gastos |

---

## Arquitetura da Solução

```
Sistema de vendas / usuário
        ↓
     AWS Lambda
 (processamento serverless)
        ↓
   Amazon S3
 (armazenamento escalável)
        ↓
   AWS Budgets
 (controle de custos)
```

- **AWS Lambda** — processa eventos sem necessidade de servidores permanentes
- **Amazon S3** — armazena documentos com camadas automáticas de custo
- **AWS Budgets** — monitora gastos e emite alertas ao atingir 80% do orçamento

---

## Impacto Esperado

- Redução de até **40% nos custos de armazenamento**
- **Eliminação de servidores ociosos** com arquitetura serverless
- **Previsibilidade financeira** com monitoramento contínuo de gastos

---

## Estrutura do Repositório

```
aws-cost-reduction-project/
│
├── README.md
├── relatorio-implementacao-aws.md
│
└── docs/
    ├── viabilidade.md
    ├── arquitetura.md
    └── referencias.md
```

---

## Documentação

- [Relatório Completo](./relatorio-implementacao-aws.md)
- [Viabilidade Econômica](./docs/viabilidade.md)
- [Arquitetura do Projeto](./docs/arquitetura.md)
- [Referências AWS](./docs/referencias.md)
