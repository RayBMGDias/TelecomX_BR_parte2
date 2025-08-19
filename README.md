#  Análise de Evasão de Clientes – TelecomX parte 2

<h2> Análise e Modelagem de Churn </h2>

Este projeto foi desenvolvido como parte da formação em Data Science, uma parceria entre o programa ONE - Oracle Next Education e a Alura.

### Objetivo Principal
Analisar os dados de uma empresa fictícia de telecomunicações para identificar os fatores que mais influenciam a evasão de clientes (Churn) e, com base nesses insights, propor estratégias de retenção eficazes.

### Metodologia
A análise utiliza o ecossistema Python para Ciência de Dados, com foco nas seguintes ferramentas e técnicas:

- Pandas: Para a manipulação e pré-processamento dos dados.

- Matplotlib e Seaborn: Para a criação de visualizações que facilitam a compreensão dos padrões de evasão.

- Modelagem Preditiva: Treinamento e avaliação de modelos de Machine Learning, como K-Vizinhos Mais Próximos (KNN) e Árvore de Decisão, para prever a probabilidade de um cliente cancelar.


## Ferramentas Utilizadas 

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab


## Estrutura do Conjunto de Dados

O dataset contém dados completos sobre clientes, organizados nas seguintes categorias:

Dados Demográficos: Gênero, idade e informações sobre dependentes.

Serviços e Contrato: Detalhes dos serviços de telefone e internet, tipo de contrato e método de pagamento.

Cobranças: Informações sobre os valores mensais e totais faturados.

Variável Alvo: Uma coluna indicando se o cliente cancelou ou não o serviço (Churn).


## Etapa de Pré-processamento

Para preparar os dados para a modelagem, as seguintes etapas foram realizadas:

Codificação de Variáveis: Conversão de variáveis categóricas em um formato numérico para que os modelos de Machine Learning possam interpretá-las.

Balanceamento de Classes: Aplicação de uma técnica para resolver o desequilíbrio entre as classes de clientes que evadiram e os que não evadiram.

Divisão de Dados: Separação dos dados em variáveis preditoras (X) e a variável alvo (y), seguida da divisão em conjuntos de treino e teste.

## Análise Exploratória de Dados
A análise buscou entender como diferentes variáveis influenciam a evasão, com destaque para:

- Tipo de contrato
- Tempo de permanência
- Valor mensal de pagamento
- Quantidade de serviços contratados
- Método de pagamento

---
## Insights-Chave da Análise de Evasão <h2>
  
- Com base na análise preditiva e na importância das variáveis, os principais fatores que levam ao cancelamento de clientes são:
- Tipo de Contrato: Contratos mensais (mês a mês) apresentam o maior risco, indicando uma baixa fidelidade.
- Tempo de Permanência: Clientes com menor tempo de serviço são mais propensos a evadir.
- Valor da Mensalidade: Custos elevados estão diretamente associados a uma maior probabilidade de cancelamento.
- Método de Pagamento: Certos métodos de pagamento, como o "cheque eletrônico", se correlacionam com uma alta taxa de evasão.
- Serviços Adicionais: A ausência de serviços de valor agregado, como segurança online e suporte técnico, aumenta o risco de churn.

-----
## Recomendações Estratégicas
  
- Com o objetivo de reduzir a taxa de evasão, sugerimos as seguintes ações:
- Incentivar Contratos de Longo Prazo: Oferecer benefícios e descontos exclusivos para que clientes migrem de planos mensais para anuais.
- Otimizar a Experiência de Pagamento: Simplificar os processos de pagamento e promover opções de débito automático para reduzir o atrito.
- Personalizar a Oferta: Criar pacotes de serviços personalizados com base nas necessidades e no uso do cliente.
- Ação Proativa: Utilizar o modelo preditivo para identificar clientes em alto risco e lançar campanhas de reengajamento ou suporte direcionado antes que o cancelamento ocorra.
  
---
## Conclusão Final
  
O projeto demonstra que a evasão de clientes é um problema multifacetado, mas que pode ser antecipado. A aplicação de modelos preditivos é fundamental para identificar, de forma estratégica, os clientes com maior probabilidade de cancelamento. Essa abordagem permite que a empresa adote uma postura proativa, otimizando recursos e direcionando esforços de retenção para onde eles trarão o maior retorno.


#👤 Autor
Rayra Bandeira
