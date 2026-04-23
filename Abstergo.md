# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 24 de abril de 2026
Empresa: Abstergo Industries
Responsável: Daniel Dias Fontes

## Introdução

Este relatório apresenta o processo dde implementação de ferramentas na empresa Abstergo Industries, realizado por Daniel Dias Fontes. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos e otimização do processamento de memórias genéticas.

## Descrição do \projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

**Etapa 1**:

* **Amazon SageMaker**
* **Foco**: Inteligência Artificial e Machine Learning.
* **Descrição de caso de uso**: Utilizado para automatizar a reconstrução de ambientes históricos a partir de DNA degradado. Em vez de contratar milhares de historiadores e programadores para modelagem manual, o SageMaker treina modelos que preenchem as lacunas das memórias genéticas automaticamente, reduzindo drasticamente o tempo e o custo de produçãp do Projeto Animus.

**Etapa 2**:

* **Amazon Forecast**
* **Foco**: Redução de custos operacionais e desperdício de estoque.
* **Descrição de caso de uso**: Utilização de Inteligência Artificial para prever com precisão a demanda de medicamentos em cada unidade da Abstergo Pharmaceuticals. Ao analisar o histórico de vendas e tendências sazonais, o serviço evita o excesso de estoque (capital parado) e a perda de produtos por validade vencida. Isso permite uma logística just-in-time, reduzindo gastos com armazenamento físico e descartes em até 30% logo nos primeiros meses.
> **Impacto Financeiro:** A migração para previsões baseadas em ML (Machine Learning) elimina a necessidade de softwares de ERP legados e caros, centralizando tudo na AWS.


**Etapa 3**:

* **AWS Batch**
* **Foco**: Computação em lote eficiente.
* **Descrição de caso de uso**: Gerenciamento de cargas de trabalho pesadas de processamento de dados genômicos. O AWS Batch executa os jobs de análise apenas quando necessário, utilizando Instâncias Spot(recursos ociosos da AWS com até 90% de desconto), eliminando a necessidade de manter supercomputadores ligados 24/7 na sede da empresa.

## Conclusão

A implementação de ferramentas na empresa Abstergo Industries tem como esperado a redução de gastos com hardware local, aceleração no lançamento de novos produtos da Abstergo Entertainment e maior segurança no processamento de informações confidencias, o que aumentará a eficiência a e produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.


### Anexo A: Tabela de Redução de Custos (Setor Farmacêutico e P&D)

| Categoria de Gasto | Sistema Tradicional (Antigo) | Solução AWS (Nova) | Economia Gerada |
| :--- | :--- | :--- | :--- |
| **Perda por Validade (Medicamentos)** | R$ 950.000,00 | R$ 190.000,00 | 80% |
| **Manutenção de Servidores (Animus)** | R$ 1.500.000,00 | R$ 450.000,00 | 70% |
| **Licenciamento de Software ERP** | R$ 500.000,00 | R$ 50.000,00 | 90% |
| **TOTAL** | **R$ 2.950.000,00** | **R$ 690.000,00** | **~76% de ROI** |

### Anexo B: Detalhamento Técnico da Etapa 2
Para garantir a redução de custos nas farmácias da Abstergo Pharmaceuticals, o fluxo de implementação seguirá os protocolos:
*   **Coleta de Dados:** Integração dos PDVs com o **Amazon S3** para centralizar dados de vendas.
*   **Processamento:** O **Amazon Forecast** utilizará algoritmos de IA para prever picos de demanda e quedas, otimizando o estoque *just-in-time*.
*   **Conformidade:** Uso do **AWS Artifact** para garantir que todos os dados de saúde sigam as normas da LGPD.

---

**Assinatura do Responsável pelo Projeto:**

**Daniel Dias Fontes**

