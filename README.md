# Análise de Dados dos Jogos da Nintendo 🎮

## Sobre o projeto 

Este trabalho foi desenvolvido como parte da disciplina de **Big Data em Python** e tem como objetivo analisar o desempenho histórico dos jogos publicados pela Nintendo por meio de técnicas de análise e visualização de dados.

A partir de uma base de dados organizada em uma planilha Excel, são investigados aspectos como vendas, avaliações da crítica, avaliações do público, gêneros, franquias, plataformas e ano de lançamento.

O projeto utiliza Python para importar, organizar, tratar e explorar os dados, buscando identificar padrões, tendências e diferenças de desempenho entre os jogos.

## Objetivos 🎯

- Organizar e tratar a base de dados dos jogos da Nintendo.
- Identificar valores ausentes, registros duplicados e possíveis inconsistências.
- Analisar as vendas e as avaliações de publico e critica dos jogos.
- Comparar o desempenho de diferentes franquias e gêneros.
- Investigar a evolução das vendas do historico da nintendo de acordo com o ano de lançamento.
- Desenvolver gráficos e indicadores para apresentar os principais resultados.

## Tecnologias e bibliotecas 🛠️

- **Python** — linguagem utilizada no desenvolvimento.
- **Pandas** — importação, organização, limpeza e análise dos dados.
- **NumPy** — operações numéricas e manipulação de dados.
- **Matplotlib** — criação de gráficos.
- **Plotly** - criação de gráficos interativos.
- **Google Colab** — ambiente utilizado para executar o código e desenvolver as análises.
- **Excel** — armazenamento e organização da base de dados.

## Análises realizadas 📊

O projeto contempla análises exploratórias como:

- Ranking de jogos mais vendidos e jogos mais bem avaliados.
- Ranking das franquias com maiores vendas acumuladas e com maiores médias de notas acumuladas.
- Comparação de vendas e avaliações entre consoles.
- Evolução das vendas dos jogos por ano de lançamento.
- Comparação do desempenho dos gêneros em vendas e avaliações.
- Comparação entre as notas da crítica e do público em categorias específicas de jogos.
- Contagem de jogos lançados por ano.

## Dashboard 📈 

O dashboard reúne gráficos e indicadores para facilitar a interpretação dos dados, incluindo:

- Quantidade de jogos na base.
- Vendas acumuladas dos jogos registrados na base.
- Franquias com maiores vendas.
- Desempenho dos consoles.
- Evolução das vendas por ano.
- Comparação de quantidade de jogos por ano
- Médias das avaliações da crítica e do público.

Os resultados são calculados a partir dos dados disponíveis na planilha e podem ser atualizados quando a base é modificada.

## Metodologia dos Dados 📚

Os dados utilizados neste projeto foram obtidos a partir de fontes especializadas em videogames e de informações oficiais disponibilizadas pela Nintendo. O Metacritic foi utilizado como referência para as avaliações da crítica especializada e do público, enquanto o VGChartz foi consultado como fonte complementar de informações históricas de vendas, considerando as limitações metodológicas das estimativas publicadas.

Após a coleta, os dados são tratados com Python e Pandas, com conversão de tipos, identificação de valores ausentes, verificação de inconsistências e padronização das categorias. As análises e visualizações são produzidas com bibliotecas como NumPy, Matplotlib e Plotly.

As fontes, os critérios de seleção e as limitações dos dados são documentados para favorecer a transparência e a reprodução das análises.
A base de dados reúne informações sobre jogos publicados pela Nintendo, incluindo ano de lançamento, gênero, plataforma original, franquia, desenvolvedora, vendas e avaliações.

Os dados são organizados em uma planilha e passam por procedimentos de verificação, limpeza e padronização antes das análises.

As vendas e avaliações devem ser interpretadas de acordo com as fontes utilizadas e a disponibilidade de informações para cada jogo. Valores ausentes não devem ser tratados automaticamente como zero.

**Fontes específicas dos dados:** 
VGchartz
[https://www.vgchartz.com/games/games.php?name=&keyword=&console=&region=All&developer=&publisher=Nintendo&goty_year=&genre=&boxart=Both&banner=Both&ownership=Both&showmultiplat=No&results=50&order=Sales&showtotalsales=0&showtotalsales=1&showpublisher=0&showpublisher=1&showvgchartzscore=0&showvgchartzscore=1&shownasales=0&showdeveloper=0&showcriticscore=0&showcriticscore=1&showpalsales=0&showreleasedate=0&showreleasedate=1&showuserscore=0&showuserscore=1&showjapansales=0&showlastupdate=0&showlastupdate=1&showothersales=0&showshipped=0&showshipped=1].

Metacritic
[https://www.metacritic.com/browse/game/?platform=3ds&platform=game-boy-advance&platform=gamecube&platform=mobile&platform=nintendo-64&platform=nintendo-ds&platform=nintendo-switch&platform=nintendo-switch-2&platform=wii&platform=wii-u].

## Limitações ⚠️

- Alguns jogos ficaram sem vendas atualizadas, por isso alguns jogos podem ficar com vendas datadas.
- Foram evitados jogos como remakes, remasters , relançamentos, versões alterativas ou exclusivas de determinados lugares.
- Foi apenas incluido a plataforma em que o jogo lançou e não todas as plataformas em que ele foi disponibilizado para jogar.
- Alguns jogos podem não possuir dados de vendas ou avaliações oficiais disponíveis, por isso foi deixado algumas linhas em branco.
- As estimativas de vendas podem variar conforme a fonte consultada.
- As notas podem utilizar critérios e escalas diferentes dependendo da origem.
- As conclusões representam os dados registrados na base, não necessariamente todo o mercado de jogos.

## Informações do Aluno 🎓

**Disciplina:** Tópicos de Big Data em Python

**Tema:** Análise do desempenho histórico dos jogos da Nintendo.

**Aluno:** Guilherme Pupo Nunes

**Curso:** Análise e Desenvolvimento de Sistemas

