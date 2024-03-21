# EDA dos salários dos jogadores da MLS

Esse trabalho tem como objetivo conduzir uma Análise Exploratória de Dados (EDA) em um conjunto de dados disponível no Kaggle, que abrange os salários dos jogadores da Major League Soccer (MLS) ao longo de um período de dez anos, de 2007 a 2017.

A Major League Soccer (MLS) é a principal liga de futebol profissional dos Estados Unidos e Canadá, e esta análise busca proporcionar uma compreensão mais profunda da estrutura de remuneração dos jogadores nesta liga. Ao explorar os dados salariais, buscamos identificar padrões, tendências e características que possam fornecer insights valiosos sobre a distribuição de salários, variações ao longo do tempo e fatores que influenciam a compensação dos jogadores.

Por meio desta EDA, esperamos fornecer informações acionáveis que possam ser úteis para gestores de clubes, agentes de jogadores, analistas esportivos e outros interessados ​​no mercado de futebol da MLS. Ao compreender melhor como os salários dos jogadores estão distribuídos e quais fatores podem influenciar essas remunerações, podemos tomar decisões mais informadas relacionadas a contratações, negociações salariais e estratégias de equipe na liga americana de futebol.

# Dicionário de dados

_club_: Abreviação do nome do time </br>
_last_name_: Último nome do jogador </br>
_last_name_: Último nome do jogador </br>
_first_name_: Primeiro nome do jogador </br> 
_last_name_: Último nome do jogador </br>
_position_: Posição abreviada do jogador</br>
_last_name_: Último nome do jogador </br>
_base_salary_: Base salarial</br>
_last_name_: Último nome do jogador </br>
_guaranteed_compensation_: Compensação salarial</br>

# Fonte dos dados

Os dados estão disponíveis no Kaggle no link: https://www.kaggle.com/datasets/crawford/us-major-league-soccer-salaries

# Análise da distribuição salarial
Iniciamos nossa análise com uma representação gráfica da distribuição dos salários. O gráfico permite uma visão clara da distribuição, destacando faixas salariais predominantes e fornecendo insights valiosos sobre a estrutura salarial da base de estudo.

![1](https://github.com/luanrossini/eda_mls_salaries/assets/119509335/3c341771-9f3c-4de2-8d81-7a748e629179)

O gráfico acima representa a distribuição dos salários, com uma distribuição assimétrica para a direita devido aos outliers (valores discrepantes), que podem ser observados especialmente no gráfico boxplot. Isso faz com que a média seja "aumentada". A existência dos outliers pode ser explicada pela existência de jogadores que recem mais do que outros, devido ao seu histórico de conquistas, experiência, nível de habilidade e talento, posição desempenhada e até pela sua popularidade.

A maioria dos salários se concentra no intervalo de 50k a 200k, com uma média de 186k dolares e mediana 79k. Essa faixa sugere uma tendência central nos salários, enquanto as caudas do histograma podem indicar a presença de alguns valores atípicos ou extremos.

# Top 10 jogadores com maior salário
![image](https://github.com/luanrossini/eda_mls_salaries/assets/119509335/b303d5ae-6159-451f-bb7d-136af744652c)

Observado a lista dos 10 principais salários da base, observa-se uma real tendência dos jogadores já consagrados por conquistas e fama, como Kaka, Gerard e Lampard, terem as maiores bases salariais. Esse comportamento é muito explicado devido ao movimento da MLS em atrair investimentos e se posicionar como uma liga madura e atrativa financeiramente para investidores. Esses nomes já consagrados no cenário mundial de futebol profissional atraem não só torcedores e admiradores do esporte quanto potenciais investidores e empresas parceiras da MLS. 

# Média salarial por clube da MLS
![image](https://github.com/luanrossini/eda_mls_salaries/assets/119509335/9611b710-4b80-4776-a7a2-1623d17a399b)

A análise da média salarial segmentada por clubes da MLS emerge como um indicador fundamental para compreender se os times da MLS tem uma disparidade média entre os valores praticados pelos atletas. Notavelmente, observamos uma grande diferente entre a média salarial dos clubes. New York City, Los Angeles Galaxy, Orlando CIty, Toronto e New York Reb Bulls são os clubes que tem as maiores bases salariais da liga americana de futebol. Esses cinco times tem em comum estarem localizados geograficamente em cidades com grande mercados meltropolitanos e com uma base de fãs considerável e uma mídia significativa, possibilitando atrair investimentos e patrocinadores locais e internacionais, resultando em maiores receitas e possibilitando esses clubes investir em salários mais altos à seus atletas. 

Além disso, é importante destacar também que os clubes com maiores médias salariais contam em seus elencos com jogadores já consagrados como Kaka (Orlando City), Lampard (New York City), Henry (New York Reed Bulls) e Beckham (LA Galaxy). Esses jogadores e outros contam com salários mais robustos, impactando na média salarial do time mais alta em comparação com os outros times.

# Média salarial por posição
![image](https://github.com/luanrossini/eda_mls_salaries/assets/119509335/d47e017b-c17e-4747-b44e-18ca73005ee9)

Conforme esperado, a análise salarial média revela que os jogadores que estão nas posições de ataque ou meio-campo tendem a ter maiores salários. Os jogadores classificados como "atacantes" na base da MLS ostentam o maior salário médio, atingindo a marca de 167.7K USD. Na sequência, os jogadores "meio-campo" apresentam um salário médio de 141.8K USD, já os defensores e goleiros são os que contemplam os menores salários médios. Essa análise reforça a teoria que os jogadores que mais participam de gols, seja pela alteração de fato do placar quanto por assistências, são os mais recompensados financeiramente.



