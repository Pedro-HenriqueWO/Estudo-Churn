## Predição de Churn
Este modelo preditivo foi desenvolvido para calcular a taxa de churn, utilizando uma base de dados com informações sobre contratos de clientes, como tempo de contratação, número de renovações, datas de início e término do contrato e outras variáveis.

## Objetivo
O modelo visa prever a probabilidade de um cliente cancelar seu contrato em um certo período de tempo, ajudando a empresa a identificar clientes com alto risco de churn e a implementar estratégias de retenção.

## Etapas do processo

- **Passo 1:** Pré-processamento de Dados 
- **Passo 2:** Criação da Variável-Alvo  
- **Passo 3:** Modelo Preditivo  
   - **3.1** Verificação de performance e eficiência do modelo
- **Passo 4:** Retenção dos dados

## Ferramentas utilizadas

 • [Python 3.13](https://www.python.org/)

 • [Visual Studio Code](https://code.visualstudio.com/download)

 • [Jupyter Notebook](https://jupyter.org/)

 ## Bibliotecas utilizadas
 
• [Pandas](https://pandas.pydata.org/)  - Manipulação de arquivos.

• [NumPy](https://numpy.org/)  - Operações numéricas e científicas.

• [Scikit-learn](https://scikit-learn.org/)  - Criação de modelos de machine learning.

## Atividade

Ao inserir os dados em uma base Excel, foi realizado o processo de ETL utilizando Python. Após isso, um modelo de machine learning foi treinado para prever o churn nos próximos 3 meses (tempo determinado pelo desafio).

Ao analisar os gráficos, foi observada que a taxa de churn prevista para os próximos 3 meses é de 75,46%. Ou seja, caso não haja mudanças em certos aspectos e fatores que impactam essa taxa de churn, ela aumentaria drasticamente, comprometendo a saúde da empresa e trazendo-a para um nível mais crítico.

![Imagem 1](https://github.com/Pedro-HenriqueWO/Estudo-Churn/blob/master/output%201.png?raw=true)

Visto isso, uma estratégia eficaz seria melhorar o engajamento da empresa com seus clientes, uma vez que o alto número de clientes que provavelmente não utilizarão mais nossos serviços e deixarão o aplicativo nos próximos 3 meses indica a necessidade de ações proativas para reverter esse quadro.

![Imagem 2](https://github.com/Pedro-HenriqueWO/Estudo-Churn/blob/master/output.png)

Ao analisar os gráficos, é possível identificar dois motivos de cancelamento que se destacam em relação aos outros.

Será necessário revisar os meios de comunicação da empresa com os clientes, como mensagens via aplicativo, e-mail, ou implementar ações inovadoras que estejam alinhadas com os interesses do público-alvo.

O motivo "Não aceita proposta" sugere que a proposta não atende às necessidades ou expectativas dos clientes, possivelmente devido a preços, serviços ou condições de contrato pouco atraentes. Se torna necessário
personalizar as propostas conforme o perfil de cada cliente e avaliar a flexibilidade nas condições de renovação e personalização dos contratos para aumentar a aceitação.

## Conclusão

Em resumo, os gráficos mostram que a empresa está enfrentando uma alta taxa de churn e tem poucos clientes fiéis, o que pode afetar sua saúde financeira no futuro. Focar em ações preventivas, melhorar o atendimento e a experiência do cliente, além de investir em estratégias de fidelização, são passos importantes para mudar esse cenário.
