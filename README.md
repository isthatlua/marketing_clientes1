# 📊 Análise de Campanhas de Marketing e Segmentação de Clientes

## 1. Resumo do Projeto 📝
O presente projeto tem como objetivo analisar o comportamento dos clientes de uma empresa de varejo para identificar os perfis com maior probabilidade de responder a campanhas de marketing. A análise visa otimizar futuros investimentos na área por meio de uma segmentação de clientes baseada em dados, permitindo um direcionamento de campanha mais eficiente e com maior Retorno Sobre o Investimento (ROI).

## 2. Fonte dos Dados 📚
Os dados utilizados foram obtidos do dataset "Marketing Campaign", disponibilizado na plataforma Kaggle. O conjunto de dados contém informações demográficas, hábitos de consumo e respostas a campanhas anteriores de 2.205 clientes.

## 3. Metodologia e Análise Exploratória de Dados (EDA) 🔬
A análise foi desenvolvida em ambiente Python, utilizando principalmente as bibliotecas Pandas para manipulação de dados e Matplotlib/Seaborn para visualização. As etapas principais incluíram:

* **🧹 Limpeza e Preparação dos Dados:** Verificação da integridade dos dados, tratamento de valores ausentes (o dataset estava completo) e remoção de colunas consideradas irrelevantes para a análise (`Z_CostContact`, `Z_Revenue`), por não apresentarem variabilidade.
* **🛠️ Engenharia de Atributos (Feature Engineering):** Criação de novas variáveis para aprofundar a análise. Foi criada a variável `TotalKids`, a partir da soma das colunas `Kidhome` e `Teenhome`, para consolidar o impacto da estrutura familiar no comportamento do consumidor.
* **🔍 Análise de Segmentos:** Utilização da função `groupby` para agregar dados e comparar métricas-chave (como renda e gastos totais) entre diferentes segmentos de clientes, com foco naqueles que responderam e os que não responderam à última campanha.

## 4. Principais Resultados (Key Findings) 💡
A análise exploratória revelou três fatores principais que se correlacionam fortemente com a propensão de um cliente a responder a uma campanha de marketing:

* **💰 Perfil de Renda:** Clientes que responderam positivamente à campanha possuem uma renda média significativamente superior ($60.209) em comparação aos não respondentes ($50.094).
* **🛒 Comportamento de Compra Prévio:** O gasto total médio dos respondentes ($924) é aproximadamente o dobro do gasto dos não respondentes ($498). Isso indica que os clientes já engajados e de alto valor são os mais receptivos a novas ofertas.
    ![Gráfico de Gasto Total por Resposta à Campanha](https://github.com/user-attachments/assets/ee02fc9a-58c5-45d3-832a-2ce4ec194ca7)
* **👨‍👩‍👧‍👦 Estrutura Familiar:** Observa-se uma forte correlação negativa entre o número de filhos na residência e a resposta à campanha. Clientes sem filhos não apenas respondem com maior frequência, como também representam o segmento de maior consumo ($1.041 em média).
    ![Gráfico de Gasto Total por Número de Filhos](https://github.com/user-attachments/assets/02464e69-6fdb-4bb0-a981-8bbfd0917196)

## 5. Recomendações Estratégicas 🎯
Com base nos resultados obtidos, as seguintes ações são recomendadas para otimizar futuras campanhas de marketing:

1.  **🏆 Público-Alvo Prioritário:** Direcionar os investimentos de marketing para o segmento de clientes com maior potencial de ROI: indivíduos e casais de alta renda e sem filhos (perfil "DINKs" - Dual Income, No Kids).
2.  **📡 Estratégia de Canais:** Alocar o orçamento de mídia em canais digitais que permitam segmentação demográfica e de interesses avançada (ex: Instagram, Twitter, Threads) e explorar plataformas de nicho com alto engajamento do público-alvo, como o ecossistema de jogos eletrônicos.
3.  **🎨 Direcionamento Criativo:** Desenvolver campanhas com mensagens e elementos visuais que ressoem com o estilo de vida do público-alvo, focando em temas de lazer, hobbies e consumo pessoal, em detrimento de narrativas familiares tradicionais.

## 6. Ferramentas Utilizadas 🛠️
* **Linguagem:** Python
* **Bibliotecas:** Pandas, Matplotlib/Seaborn
