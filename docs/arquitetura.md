# Arquitetura Lógica do Projeto

## Fluxo da Solução

```
Sistema de vendas / usuário
        ↓
     AWS Lambda
 (processamento de eventos)
        ↓
   Amazon S3
 (armazenamento de documentos)
        ↓
   AWS Budgets
 (controle e monitoramento de custos)
```

## Descrição dos Componentes

### AWS Lambda
- Executa funções apenas quando acionado por eventos (registro de vendas, logs, faturamento)
- Cobrado por milissegundo de execução — sem custo em idle
- Elimina a necessidade de servidores permanentes

### Amazon S3 (Intelligent-Tiering)
- Armazena documentos clínicos, receitas digitalizadas e dados históricos
- Move automaticamente dados pouco acessados para camadas de menor custo
- Suporte a políticas de lifecycle para arquivamento em Glacier

### AWS Budgets
- Monitora os gastos da infraestrutura cloud em tempo real
- Emite alertas automáticos ao atingir 80% do orçamento planejado
- Facilita a adoção de práticas de FinOps

## Benefícios da Arquitetura

- Sem servidores permanentes → sem custos fixos de infraestrutura
- Escalabilidade automática conforme demanda
- Visibilidade financeira contínua dos recursos em nuvem
