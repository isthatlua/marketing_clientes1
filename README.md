# Análise de Marketing 360°: Do Comportamento do Cliente à Estratégia de Mídia Digital

*Data de Criação: 04 de Julho de 2025*

## 📜 Resumo Executivo

Este projeto apresenta uma análise de ponta a ponta com o objetivo de otimizar os investimentos em marketing de uma empresa de varejo. A análise foi dividida em duas fases:
1.  **Análise Interna (Python):** Utilizando dados de campanhas anteriores, identificamos o perfil dos clientes com maior propensão à conversão e maior Retorno Sobre o Investimento (ROI).
2.  **Análise Externa (Power BI):** Com base em dados de mercado (Sprout Social), validamos nossa hipótese e identificamos os canais de mídia digital mais eficazes para alcançar nosso público-alvo de alto valor.

A conclusão principal aponta para uma estratégia focada em **YouTube e Facebook** para campanhas de conversão de alto ROI, devido à sua dominância nos segmentos de público de alta renda, que foram previamente identificados como os mais lucrativos para a empresa.

## 🎯 O Problema de Negócio

A questão central que guiou este projeto foi: **"Como podemos direcionar nossos investimentos em campanhas de marketing de forma mais inteligente para aumentar a taxa de resposta e maximizar o retorno financeiro?"**

## 🛠️ Ferramentas e Metodologia

* **Análise Exploratória e Limpeza de Dados:** Python, com as bibliotecas Pandas, Matplotlib e Seaborn.
* **Dashboard Interativo e Storytelling com Dados:** Microsoft Power BI, com fórmulas DAX para criação de KPIs.
* **Fontes de Dados:**
    * Dataset "Marketing Campaign" (Kaggle) - Dados internos de clientes.
    * Dados Demográficos de Mídias Sociais (Sprout Social, 2021) - Dados externos de mercado.
* **Versionamento:** GitHub.

---

## 🔬 Parte I: Análise do Comportamento do Cliente (Dados Internos)

Nesta primeira fase, o objetivo foi olhar para dentro de casa e entender: **Quem são nossos melhores clientes?**

### Principais Descobertas:

1.  **Renda é um Fator Decisivo:** Clientes que responderam positivamente às campanhas possuem uma renda média significativamente superior **($60,209)** em comparação aos não respondentes **($50,094)**.

2.  **Histórico de Compra Importa:** O gasto total médio dos respondentes **($924)** é quase o dobro do gasto dos não respondentes **($498)**, indicando que clientes de alto valor já engajados são mais receptivos.

    ![image](https://github.com/user-attachments/assets/de1b7e05-037a-4209-881e-acaa50f39a36)


3.  **Estrutura Familiar Influencia o Consumo:** Clientes sem filhos não apenas respondem com mais frequência, como também representam o segmento de maior consumo **($1,041 em média)**.

    ![image](https://github.com/user-attachments/assets/95856b04-d447-47cf-bc81-ea3b680d5014)


### Conclusão da Parte I:

A análise interna gerou uma hipótese clara: nosso público-alvo de maior potencial de ROI é composto por **indivíduos ou casais de alta renda e sem filhos (perfil "DINKs")**.

---

## 📊 Parte II: Validação de Mercado e Análise de Canais (Dashboard em Power BI)

Com a hipótese em mãos, a próxima pergunta foi: **Onde encontramos esse público na internet?** Para responder a isso, construímos um dashboard interativo no Power BI.

### O Dashboard de Decisão Estratégica

Este dashboard cruza dados de uso de plataformas com demografia de idade e renda, permitindo uma visualização clara das oportunidades de mercado.


**Visão Geral do Dashboard**

![Captura de tela 2025-07-04 172720](https://github.com/user-attachments/assets/8b9d5570-fb82-4ad1-b169-07a23c2b4afa)


![Captura de tela 2025-07-04 172738](https://github.com/user-attachments/assets/d2b22730-a5b7-4e9d-910c-61c181df8ad2)




---

## 🏆 A Grande Síntese: Conclusões Finais e Recomendação Estratégica

A mágica acontece quando conectamos os pontos entre as duas análises:

* A **Análise Interna** nos disse **QUEM** procurar: o público de alta renda.
* A **Análise Externa** (via Power BI) nos disse **ONDE** encontrá-los.

O cruzamento dos dados revelou que as plataformas **YouTube (com 83% de penetração)** e **Facebook (74%)** são os canais com o maior alcance dentro do segmento de renda superior a US$ 75.000, validando e refinando nossa estratégia.

### Recomendação Final:

Com base na análise 360°, a seguinte estratégia de alocação de investimentos em marketing é recomendada:

1.  **Para Campanhas de Máximo ROI e Conversão:**
    * **Foco Primário:** **YouTube** e **Facebook**. Esses canais oferecem a maior concentração do nosso público-alvo mais lucrativo.

2.  **Para Campanhas de Alcance e Reconhecimento de Marca (Público Jovem):**
    * **Foco Secundário:** **Instagram** e **X**. São essenciais para construir presença com a próxima geração de consumidores, embora possuam menor penetração no segmento de alta renda.

## 🚀 Como Explorar este Projeto

* **Para ver a análise de dados inicial:** Abra o notebook `marketing_segmentacao.ipynb`.
* **Para explorar o dashboard interativo:** Baixe o arquivo `relatorio_final.pbix` e abra-o com o Power BI Desktop.

