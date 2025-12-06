 # RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 06/12/2025  
**Empresa:** PharmaCloud Solutions  
**Responsável:** Guilherme Silva

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa **PharmaCloud Solutions**, realizado por **Guilherme Silva**. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar a diminuição de custos imediatos através da adoção de uma arquitetura *Serverless* (sem servidor).

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos focados na otimização de recursos e pagamento por uso. A seguir, serão descritas as etapas do projeto:

### Etapa 1:

* **Nome da ferramenta:** AWS Lambda
* **Foco da ferramenta:** Computação Serverless (Execução de código sob demanda).
* **Descrição de caso de uso:**
  Substituição dos servidores virtuais (EC2) que permaneciam ligados 24/7 para hospedar o *backend* da farmácia. O Lambda permite que o processamento de receitas e cálculos de frete ocorram apenas quando acionados pelo cliente, eliminando custos de ociosidade durante a noite ou períodos de baixo movimento.

### Etapa 2:

* **Nome da ferramenta:** Amazon S3 (com Intelligent-Tiering)
* **Foco da ferramenta:** Armazenamento de objetos com otimização automática de custos.
* **Descrição de caso de uso:**
  Armazenamento seguro de imagens de produtos, bulas e históricos de notas fiscais. A configuração do *Intelligent-Tiering* monitora os padrões de acesso e move automaticamente arquivos pouco acessados (ex: documentos fiscais antigos) para camadas de armazenamento mais baratas, reduzindo a fatura mensal sem intervenção manual.

### Etapa 3:

* **Nome da ferramenta:** Amazon DynamoDB (Modo On-Demand)
* **Foco da ferramenta:** Banco de dados NoSQL gerenciado de alta performance.
* **Descrição de caso de uso:**
  Gerenciamento do catálogo de medicamentos e carrinhos de compras. No modo *On-Demand*, o banco de dados ajusta automaticamente sua capacidade para suportar picos de acesso (como em promoções) e reduz o consumo a zero quando não há tráfego, eliminando o custo fixo de provisionamento de bancos de dados tradicionais.

## Conclusão

A implementação de ferramentas na empresa **PharmaCloud Solutions** tem como esperado a **redução dos custos operacionais (OpEx) em cerca de 40% e a flexibilidade para suportar picos de vendas sem falhas**, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias, como o monitoramento via *AWS Cost Explorer*, para manter a governança financeira do projeto.

 
---

**Assinatura do Responsável pelo Projeto:**

______________________________________________
**Guilherme Silva**