# 📊 Análise de Campanhas de Marketing e Segmentação de Clientes

## 1. Resumo do Projeto 📝
Este projeto, que poderia muito bem ser uma missão para o Dumbledore's Army, tem como objetivo analisar o comportamento dos clientes de uma empresa de varejo. A ideia é descobrir quais perfis são mais trouxas, digo, mais prováveis de responder às campanhas de marketing. O plano é otimizar os galeões investidos em marketing, direcionando as campanhas de forma mais eficiente e garantindo um baita Retorno Sobre o Investimento (ROI). 💰

## 2. Fonte dos Dados 📚
Os dados foram garimpados diretamente do Kaggle, tipo a gente caçando promoções online! Usamos o dataset "Marketing Campaign", que é basicamente o Mapa do Maroto dos dados de clientes. Ele contém fofocas, quer dizer, informações demográficas, hábitos de consumo e as respostas a campanhas anteriores de 2.205 clientes.

## 3. Metodologia e Análise Exploratória de Dados (EDA) 🕵️‍♀️
A mágica toda aconteceu em Python, com a ajuda dos nossos elfos domésticos preferidos: as bibliotecas Pandas, Matplotlib e Seaborn. As etapas foram:

* **🧹 Limpeza e Preparação dos Dados:** Lançamos um feitiço *"Evanesco"* em colunas inúteis (`Z_CostContact`, `Z_Revenue`) que não agregavam em nada e demos um *check* geral pra ver se estava tudo nos trinques. Felizmente, não tinha nenhum bicho-papão (valor ausente) escondido no armário.
* **🧪 Engenharia de Features:** Qual a poção do dia? Criamos a feature `TotalKids`, somando `Kidhome` e `Teenhome`. Basicamente, juntamos todas as crianças num balaio só pra entender o impacto da prole no comportamento do consumidor.
* **🔍 Análise de Segmentos:** Usamos a função `groupby` para separar o joio do trigo e comparar métricas importantes (como renda e gastos) entre a galera que respondeu à campanha e a galera que deu uma de Patolino e disse "You're despicable!" pra nossa oferta.

## 4. Principais Descobertas (Key Findings) 👀
Eita, que a fofoca aqui é boa! Entramos no Mundo Invertido dos dados e descobrimos uns segredos de arrepiar!

A análise revelou três fatores que gritam mais alto que o Demogorgon sobre a chance de um cliente responder a uma campanha:

* **Perfil de Renda 💸:** Clientes que disseram "SIM!" para a campanha têm uma renda média beeem maior ($60.209) do que os que ignoraram ($50.094). Dinheiro chama dinheiro, né, meu bem?
* **Comportamento de Compra Prévio 🛍️:** Quem já era "gastão" continuou gastando! O gasto médio de quem respondeu ($924) é quase o DOBRO de quem não respondeu ($498). Ou seja, os melhores clientes são os mais abertos a novas ofertas. *Oh. My. God!*

    ![Gráfico de Gastos Totais](https://github.com/user-attachments/assets/ee02fc9a-58c5-45d3-832a-2ce4ec194ca7)

* **Estrutura Familiar 👨‍👩‍👧‍👦:** Ter filhos parece ser o repelente oficial de campanhas de marketing. Clientes sem crias não só respondem mais, como também são o filé mignon do consumo, gastando em média $1.041.

    ![Gráfico de Gastos por Número de Filhos](https://github.com/user-attachments/assets/02464e69-6fdb-4bb0-a981-8bbfd0917196)

## 5. Recomendações Estratégicas 🎯
Com base nessas fofocas quentíssimas, aqui vai o plano pra dominar o mundo... ou pelo menos o mercado:

1.  **Público-Alvo Prioritário:** Focar a grana e a energia no filão de ouro: a galera de alta renda e sem filhos (os famosos "DINKs" - *Dual Income, No Kids*). Eles são nosso bilhete premiado! 🎟️
2.  **Estratégia de Canais:** Investir em canais digitais onde a gente possa ser bem específico na mira (Instagram, Twitter, Threads) e dar uma espiada no universo gamer, que é onde esse povo gosta de torrar dinheiro.
3.  **Direcionamento Criativo:** Chega de comercial de margarina com família feliz! As campanhas precisam falar a língua dessa galera, com temas de lazer, hobbies, autocuidado e viagens. Pensa no Joey Tribbiani: "How you doin'?" pro seu novo videogame! 😉

## 6. Ferramentas Utilizadas 🛠️
* **Linguagem:** Python
*  **Bibliotecas:** Pandas, Matplotlib/Seaborn
