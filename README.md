# Desafio1-zetta-lab-2025
Repositório do Desafio 1 - Zetta Lab 2025

Análise Socioeconômica do Município de Melgaço (PA)
Autora: Klistanaonny Amábille Diniz Lucchesi

📘 Descrição Geral
Este projeto faz parte do Desafio 1 da Zetta Lab 2025 e tem como objetivo avaliar e visualizar os fenômenos que mais impactam o desenvolvimento socioeconômico no Brasil, utilizando como estudo de caso o município de Melgaço (PA) — cidade com o menor Índice de Desenvolvimento Humano (IDH) do país segundo o Atlas Brasil (2010).
A escolha de Melgaço permite compreender, de forma concreta, como fatores educacionais, demográficos, raciais e de infraestrutura influenciam diretamente o desenvolvimento humano. A análise busca, portanto, relacionar os dados locais com o contexto nacional e refletir sobre como a desigualdade social se manifesta de maneira estrutural no Brasil.

🎯 Escolha dos Dados
Os dados foram obtidos manualmente a partir do Atlas Brasil (2010), uma base que consolida indicadores do IBGE, PNUD e Ipea.
A escolha do Atlas se deve ao fato de ele oferecer informações integradas, padronizadas e comparáveis entre municípios brasileiros, o que facilita a visualização e a análise exploratória.
Além disso, foram incluídas referências pontuais do IBGE e de fontes jornalísticas (como BBC News e O Globo) para complementar a contextualização social e comparar os resultados de Melgaço com cidades de maior IDH, como São Caetano do Sul (SP).

🧹 Metodologia e Tratamento dos Dados
A etapa de aquisição e curadoria dos dados foi realizada manualmente por meio da plataforma do Atlas Brasil.
Em seguida, os indicadores foram organizados e tratados em planilha eletrônica (base_de_dados.ods).
O processo de tratamento envolveu:
    • seleção apenas das variáveis relevantes à análise (educação, saúde, infraestrutura, demografia e desigualdade racial);
    • remoção de colunas com dados incompletos ou inconsistentes entre cidades;
    • padronização dos nomes e formatos numéricos;
    • e organização em um formato limpo para posterior visualização no Python.
A planilha final representa um conjunto consistente e comparável de dados socioeconômicos e foi incluída no repositório.

💻 Estrutura e Principais Passos do Notebook
O notebook (notebook_zetta.ipynb) foi desenvolvido em Python 3, utilizando as bibliotecas pandas, matplotlib e seaborn para visualização de dados.
Ele foi estruturado em seções temáticas, cada uma representando uma dimensão socioeconômica do município:
    1. Distribuição racial — gráfico de barras mostrando que 84,37% da população é preta, destacando a relação entre desigualdade racial, acesso à educação e renda.
    2. Razão de dependência e proporção de idosos — análise temporal entre 2000 e 2010, indicando envelhecimento reduzido e baixa expectativa de vida.
    3. Pirâmide etária — representação gráfica da estrutura populacional, com base larga e topo estreito, evidenciando alta natalidade e gravidez precoce.
    4. Mortalidade infantil — comparação da queda do índice entre 2000 e 2010 e a meta da ONU para 2030.
    5. Fluxo e evasão escolar — linhas e barras que mostram a queda na permanência escolar conforme a idade aumenta.
    6. Expectativa de anos de estudo — comparação entre Melgaço e o estado do Pará.
    7. Escolarização da população adulta — análise da baixa escolaridade e sua relação com desinformação e exclusão social.
    8. Infraestrutura e saneamento — comparação entre Melgaço (PA) e São Caetano do Sul (SP), mostrando o impacto direto da falta de água e esgoto tratados.
Cada seção contém explicações textuais que conectam os gráficos aos fenômenos sociais descritos.

📈 Principais Insights
A análise permitiu identificar padrões de vulnerabilidade que se repetem em municípios de baixo IDH, destacando que:
    • O baixo acesso à educação é o principal fator que perpetua a pobreza e a desigualdade;
    • A estrutura demográfica jovem de Melgaço reflete altas taxas de natalidade e gravidez precoce;
    • Apesar de avanços em saúde, a mortalidade infantil ainda está acima da meta da ONU;
    • A ausência de saneamento básico está diretamente ligada à piora dos indicadores de saúde e renda;
    • A baixa escolarização adulta limita o pensamento crítico e a participação política;
    • E os problemas estruturais de Melgaço representam, em escala menor, os mesmos desafios enfrentados pelo Brasil.
Esses insights reforçam que o desenvolvimento humano depende de educação, políticas públicas sustentáveis e infraestrutura básica.

🧩 Conclusão
Analisar Melgaço é observar um microcosmo do Brasil: um país em que o progresso convive com a exclusão social, e onde a educação continua sendo o eixo central do desenvolvimento humano e econômico.
A compreensão desses dados permite visualizar como cada variável socioeconômica se conecta em um ciclo contínuo que define as condições de vida da população  (e como políticas públicas eficazes podem ser o ponto de virada nesse processo).
