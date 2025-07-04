Análise de Campanhas de Marketing e Segmentação de Clientes
1. Resumo do Projeto
Este projeto tem como objetivo analisar o comportamento dos clientes de uma empresa de varejo para identificar os perfis com maior probabilidade de responder a campanhas de marketing. A análise visa otimizar futuros investimentos em marketing através de uma segmentação de clientes baseada em dados, permitindo um direcionamento de campanha mais eficiente e com maior retorno sobre o investimento (ROI).

2. Fonte dos Dados
Os dados utilizados foram obtidos do dataset "Marketing Campaign" disponível na plataforma Kaggle. O conjunto de dados contém informações demográficas, hábitos de consumo e respostas a campanhas anteriores de 2.205 clientes.

3. Metodologia e Análise Exploratória de Dados (EDA)
A análise foi desenvolvida em um ambiente Python, utilizando principalmente as bibliotecas Pandas para manipulação de dados e Matplotlib/Seaborn para visualização. As etapas principais incluíram:

Limpeza e Preparação dos Dados: Verificação da integridade dos dados, tratamento de valores ausentes (neste caso, o dataset estava completo) e remoção de colunas irrelevantes (Z_CostContact, Z_Revenue) que não apresentavam variabilidade e não contribuíam para a análise.

Engenharia de Features: Criação de novas variáveis para aprofundar a análise. Foi criada a feature TotalKids, somando as colunas Kidhome e Teenhome, para consolidar o impacto da estrutura familiar no comportamento do consumidor.

Análise de Segmentos: Utilização da função groupby para agregar dados e comparar métricas-chave (como renda e gastos totais) entre diferentes segmentos de clientes, principalmente entre aqueles que responderam e os que não responderam à última campanha de marketing.

4. Principais Descobertas (Key Findings)
A análise exploratória revelou três fatores principais que se correlacionam fortemente com a propensão de um cliente a responder a uma campanha de marketing:

Perfil de Renda: Clientes que responderam positivamente à campanha possuem uma renda média significativamente superior ($60,209) em comparação aos não respondentes ($50,094).

Comportamento de Compra Prévio: O gasto total médio dos respondentes ($924) é quase o dobro do gasto dos não respondentes ($498). Isso indica que os clientes já engajados e de alto valor são os mais receptivos a novas ofertas.

Estrutura Familiar: Existe uma forte correlação negativa entre o número de filhos na residência e a resposta à campanha. Clientes sem filhos não apenas respondem com mais frequência, como também representam o segmento de maior consumo ($1,041 em média).

5. Recomendações Estratégicas
Com base nas descobertas, as seguintes ações são recomendadas para otimizar futuras campanhas de marketing:

Público-Alvo Prioritário: Direcionar os investimentos de marketing para o segmento de clientes com maior potencial de ROI: indivíduos e casais de alta renda e sem filhos (perfil conhecido como "DINKs" - Dual Income, No Kids).

Estratégia de Canais: Alocar o orçamento de mídia em canais digitais que permitam segmentação demográfica e de interesses avançada (ex: Instagram, Twitter, Threads) e explorar plataformas de nicho com alto engajamento do público-alvo, como o ecossistema gamer.

Direcionamento Criativo: Desenvolver campanhas com mensagens e visuais que ressoem com o estilo de vida do público-alvo, focando em temas de lazer, hobbies e consumo pessoal, em detrimento de narrativas familiares tradicionais.

6. Ferramentas Utilizadas
Linguagem: Python

Bibliotecas: Pandas, Matplotlib, Seaborn

Ambiente: Jupyter Notebook (via VS Code
