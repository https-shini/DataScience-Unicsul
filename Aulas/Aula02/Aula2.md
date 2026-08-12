# Aula 02 — Manipulação e Visualização de Dados

**Disciplina:** Ciência de Dados e Aprendizagem de Máquina
**Professor:** Alexandre M. Lucena
**Contato:** amlucena@cruzeirodosul.edu.br
**Ano:** 2026
**Instituição:** Universidade Cruzeiro do Sul
**Tema da aula:** Manipulação e Visualização de Dados

## Ciência de Dados

### O que é ciência de dados?

> A Ciência de Dados (*Data Science*) é uma área **interdisciplinar** voltada para o estudo e a análise de dados, que visa a extração de conhecimento, **detecção de padrões** e/ou obtenção de *insights* para possíveis **tomadas de decisão**.

**Áreas do Conhecimento:**
- Matemática e Estatística
- Ciência da Computação
- Especialização Científica

## Na última aula...

Revisão do conteúdo anterior: a relação entre **Inteligência Artificial**, **Machine Learning**, **Deep Learning** e **Data Science** (representada em círculos sobrepostos), além dos pilares:
- Coleta de Dados
- Limpeza e Transformação
- Análise e Exploração
- Criação de Modelos

## Coleta de Dados

- Quais dados coletar?
- Há uma quantidade relevante em relação ao problema estudado?

## Dados, Informação e Conhecimento

**Dados** são os componentes básicos a partir dos quais a informação é criada.

**Informação** são dados inseridos em um contexto. **Contexto** é a situação que está sendo analisada.

A partir da informação vem o **conhecimento**, que permite tomar decisões adequadas, trazendo vantagem competitiva.

### Exemplo — Dado, Contexto e Informação

| Dado | Contexto | Informação |
|---|---|---|
| 101221 | Hora (hh:mm:ss) | 10:12:21 |
| 101221 | Data (dd/mm/aa) | 10/Dez/2021 |
| 101221 | Data (mm/dd/aa) | 12/Out/2021 |
| 101221 | RA ou Identificação | 101221 |

Um **dado** pode ser considerado como um registro mais simples, sem processamento e equiparação com outros registros — é o dado bruto de certo evento, como o nome de uma pessoa ou os dados de uma venda em específico.

A **informação** já envolve a combinação de dados para prover alguma visão em um contexto um pouco maior, por exemplo, o valor de um produto de uma marca comparado com o de outra marca, ou a totalização de vendas de um caixa.

O **conhecimento** já contextualiza de forma ainda mais abrangente a informação, com o cruzamento de outros fatos internos ou externos à organização ou problema, como o aumento de vendas por conta das mais variadas causas: feriados, visita de turistas à cidade, ou outros.

> Em geral, há no conhecimento alguma análise crítica e cooperação com nossa habilidade humana de correlacionar fatos.

## Coleta de Dados — Exemplo Prático

**Cenário proposto:** Suponha que você foi contratado como analista na expectativa de aumentar as vendas de uma pizzaria.

**Pergunta:** Quais dados você coletaria?

### Como coletar dados

Pode ser tão simples quanto medir objetos, fazer questionários, contar pessoas que passam por uma avenida, **ou um pouco mais complexo**, envolvendo um fluxo estruturado:

- Fontes de dados: **CRM**, **ERP**, **PIM**, *Operational System*, *Server*, *Flat Files*
- Processo de **ETL** (*Extract, Transform, Load*)
- Armazenamento em **Data Warehouse**
- Aplicações finais: Business Intelligence, Data Mining, Business Analytics, Big Data, Predictive Analysis, Reporting, Planning, Data Visualisation

## Dados: Qualitativo vs Quantitativo

Dados são uma coleção de fatos, como números, palavras, medidas, observações ou apenas descrições de coisas.

### Classificação dos Dados

**Qualitativo:**
- **Nominal** — categorias sem ordem (ex.: "Azul", "Feminino")
- **Ordinal** — categorias com ordem (ex.: "pequeno", "médio", "grande")

**Quantitativo:**
- **Contínuo** — valores em uma faixa contínua (ex.: 3.265...)
- **Discreto** — valores contáveis (ex.: 5)

### Exemplos

**Qualitativo (Categórico):**
- O destino de férias favorito dos seus amigos
- Os nomes mais comuns na sua cidade
- Como descrever o cheiro de um novo perfume

**Quantitativo (Numérico):**
- Altura (contínuo)
- Peso (contínuo)
- Pétalas em uma flor (discreto)
- Clientes em uma loja (discreto)

## Análise Exploratória de Dados

Após a coleta, antes de pensarmos em aplicar modelos complexos, uma etapa importante é conhecer o conjunto de dados obtido. Fazer uma análise de forma a explorar suas características e como os dados se relacionam.

> A **Análise Exploratória de Dados** (*Exploratory Data Analysis* — EDA) é usada para analisar e investigar conjuntos de dados e resumir suas principais características, muitas vezes empregando métodos de **visualização de dados**.

Geralmente aplicada preliminarmente, esta etapa envolve analisar e visualizar dados para entender suas principais características, descobrir padrões e identificar relacionamentos entre variáveis.

Refere-se ao método de estudar e explorar conjuntos de registros para apreender suas características predominantes, descobrir padrões, localizar *outliers* e identificar relacionamentos entre variáveis.

### Etapas típicas da EDA (representadas em fluxo)

1. **Raw Data** (dados brutos)
2. Understand the Problem & the Data
3. Import & Inspect the Data
4. Handle Missing Data
5. Explore Data Characteristics
6. Perform Data Transformation
7. Visualize Data Relationships
8. Handling Outliers
9. Communicate Findings & Insights
10. **Conclusions** (conclusões)

### Aspectos principais da EDA

- **Distribuição de dados:** intervalo, tendências centrais (média, mediana) e dispersão.
- **Representações gráficas:** gráficos de dispersão, barras, linhas.
- **Detecção de Anomalias (*outliers*):** valores incomuns que se desviam de outros pontos de dados.
- **Análise de correlação:** relacionamentos entre variáveis, como afetam umas às outras.
- **Lidar com valores ausentes.**
- **Estatísticas resumidas.**

## Visualização de Dados

> Visualização de dados é a **representação gráfica** de informações e dados. Ao usar elementos visuais como tabelas, gráficos e mapas, as ferramentas de visualização de dados fornecem uma maneira acessível de ver e entender tendências, *outliers* e padrões em dados.

### Principais tipos de gráficos

- Linhas
- Barras
- Histogramas
- Dispersão
- Setores (pizza)
- Geográfico
- Árvores/Grafo

## Variáveis Qualitativas

### Exemplo — Pesquisa iMac (Apple)

A Apple Computer lançou o iMac em agosto de 1998 e queria saber se o novo produto estava conquistando novos clientes.

A principal dúvida era se o iMac atrairia apenas proprietários de Macs mais antigos ou se expandiria o mercado para a Apple.

Para investigar, a empresa realizou uma pesquisa com 500 clientes que compraram o iMac. Os entrevistados foram classificados em três grupos: antigos proprietários de Macintosh, antigos proprietários de Windows e novos compradores de computadores.

*Fonte: https://onlinestatbook.com/2/graphing_distributions/graphing_qualitative.html*

### Tabela de Frequência

| Computador anterior | Frequência | Frequência Relativa |
|---|---|---|
| Nenhum | 85 | 0,17 |
| Windows | 60 | 0,12 |
| Macintosh | 355 | 0,71 |
| **Total** | **500** | **1,00** |

### Gráfico de Setores (Pizza)

Em um gráfico de pizza, cada categoria é representada por uma fatia da pizza. A área da fatia é proporcional à porcentagem de respostas na categoria.

Gráficos de pizza são eficazes para exibir as frequências relativas de um pequeno número de categorias.

> Embora a maioria dos compradores de iMac fossem proprietários de Macintosh, a Apple foi encorajada pelos 12% de compradores que eram ex-usuários do Windows e pelos 17% de compradores que estavam comprando um computador pela primeira vez.

**Desvantagens do Gráfico de Pizza:**
- Não são recomendados quando se tem um grande número de categorias.
- Podem ser confusos quando usados para comparar os resultados de duas pesquisas ou experimentos diferentes.
- Se baseados em um pequeno número de observações, pode ser enganoso rotular as fatias da pizza com porcentagens.

### Gráfico de Barras

Gráficos de barras também podem ser usados para representar frequências de diferentes categorias.

No exemplo do iMac, as frequências são mostradas no eixo Y e o tipo de computador que o cliente já teve é mostrado no eixo X.

> Normalmente, o eixo Y mostra o número de observações em cada categoria, em vez da porcentagem de observações, como é típico em gráficos de pizza.

**Ponto de atenção:** Não exagere! Às vezes as pessoas adicionam recursos aos gráficos que não ajudam a transmitir as informações. Por exemplo, gráficos de barras tridimensionais geralmente não são tão eficazes quanto seus equivalentes bidimensionais.

## Variáveis Quantitativas

### Gráfico de Barras (aplicado a dados quantitativos)

Os gráficos de barras são particularmente eficazes para mostrar mudanças ao longo do tempo.

**Exemplo:** Aumento percentual do Índice de Preços ao Consumidor (IPC) em quatro períodos de três meses (julho/2000, outubro/2000, janeiro/2001, abril/2001). A flutuação da inflação é evidente no gráfico.

### Histograma

Um **histograma** é um método gráfico para exibir o formato de uma distribuição. É particularmente útil quando há um grande número de observações.

**Exemplo:** notas de 642 alunos em um teste de psicologia, composto por 197 itens classificados como "correto" ou "incorreto". As notas variaram de 46 a 167.

**Tabela de Frequência de Classes:**

| Limite inferior | Limite superior | Frequência |
|---|---|---|
| 39,5 | 49,5 | 3 |
| 49,5 | 59,5 | 10 |
| 59,5 | 69,5 | 53 |
| 69,5 | 79,5 | 107 |
| 79,5 | 89,5 | 147 |
| 89,5 | 99,5 | 130 |
| 99,5 | 109,5 | 78 |
| 109,5 | 119,5 | 59 |
| 119,5 | 129,5 | 36 |
| 129,5 | 139,5 | 11 |
| 139,5 | 149,5 | 6 |
| 149,5 | 159,5 | 1 |
| 159,5 | 169,5 | 1 |

Em um histograma, as frequências de classe são representadas por barras. A altura de cada barra corresponde à sua frequência de classe.

> O histograma deixa claro que a maioria das pontuações está no meio da distribuição, com menos pontuações nos extremos. A distribuição não é simétrica: as pontuações se estendem mais para a direita do que para a esquerda.

### Gráfico de Linha

Um **gráfico de linhas** é um gráfico de barras com os topos das barras representados por pontos unidos por linhas (o restante da barra é suprimido).

**Exemplo:** o mesmo dado do IPC (Figura 1 — gráfico de barras) é representado como Figura 2 — gráfico de linhas.

### Polígonos de Frequência

Gráficos de linhas são apropriados apenas quando os eixos X e Y exibem variáveis ordenadas (em vez de qualitativas).

Embora gráficos de barras também possam ser usados nessa situação, gráficos de linhas geralmente são melhores para comparar mudanças ao longo do tempo.

> **Atenção:** É enganoso usar um gráfico de linhas quando o eixo X contém apenas variáveis qualitativas.

**Exemplo de uso incorreto:** número de jogadores de diferentes jogos de cartas (Poker, Blackjack, Bridge, Gin, Cribbage, Hearts, Canasta, Pinochle, Euchre, Spades) comparando quarta-feira e domingo — como o eixo X é qualitativo (nomes de jogos), o uso do gráfico de linhas foi marcado como **"ERRADO!"** no material.

**Polígonos de frequência** são um recurso gráfico para compreender as formas das distribuições. Têm a mesma finalidade dos histogramas, mas são especialmente úteis para comparar conjuntos de dados.

**Exemplo:** polígono de frequência para as 642 pontuações de testes de psicologia (mesmos dados do histograma anterior), construído a partir da tabela de frequência.

### Gráfico de Pontos ou Dispersão (Scatter)

Diagramas de pontos podem ser usados para exibir vários tipos de informações.

**Exemplo 1:** gráfico de pontos mostrando o número de pessoas jogando vários jogos de cartas no site do Yahoo em uma quarta-feira.

> Este gráfico facilita a comparação da popularidade dos jogos separadamente nos dois dias, mas não facilita a comparação da popularidade de um determinado jogo nos dois dias.

**Exemplo 2 (alternativa):** gráfico de pontos combinando domingo e quarta-feira no mesmo eixo (usando marcadores diferentes: ponto preenchido para domingo, círculo vazio para quarta-feira).

> O gráfico de pontos facilita a comparação dos dias da semana para jogos específicos, ao mesmo tempo em que retrata as diferenças entre os jogos.

## Escolhendo Gráficos e Cores

A escolha adequada do gráfico mais aderente à natureza dos dados e ao propósito de visualização requer um bom conhecimento das estratégias possíveis de visualização, bem como entender a organização dos dados existentes em um *dataset*.

**Perguntas-guia:**
- O que você está tentando comunicar com seus dados? Qual é a história que você quer contar?
- Variação de uma medida ao longo do tempo? → **Linhas**
- Comparar magnitudes ou grandezas? → **Barras**
- Mostrar as partes de um todo? → **Setores**
- Correlações? → **Dispersão**

**Material de referência:** https://raw.githubusercontent.com/ft-interactive/chart-doctor/master/visual-vocabulary/poster.png

### A importância da cor

A cor é um fator importante na criação dos gráficos. Um bom conjunto de cores destacará a história que os dados contam, enquanto um conjunto ruim esconderá ou distrairá do propósito de uma visualização.

**É importante conhecer:**
- Diferentes padrões, como **RGB** e **HSL**
- Conceito de **paleta**
- Conceitos de **matiz** (*hue*) e **luminosidade**

## Tipos de Paleta de Cores

*Fonte: https://www.atlassian.com/data/charts/how-to-choose-colors-data-visualization*

### Paleta Qualitativa

Usada quando a variável é categórica por natureza. Variáveis categóricas são aquelas que assumem rótulos distintos sem ordenação inerente (ex.: país ou estado, raça, gênero). Cada valor possível da variável recebe uma cor de uma paleta qualitativa.

### Paleta Sequencial

Quando a variável atribuída é numérica ou tem valores ordenados, ela pode ser representada com uma paleta sequencial. As cores são atribuídas a valores de dados de forma contínua, geralmente com base na luminosidade, matiz ou ambos.

### Paleta Divergente

Se a variável numérica tiver um valor central significativo, como zero, então podemos aplicar uma paleta divergente. Uma paleta divergente é uma combinação de duas paletas sequenciais com um ponto compartilhado no valor central. Valores maiores que o centro são atribuídos a cores em um lado, enquanto valores menores são atribuídos a cores no lado oposto.

## Contínuo vs Discreto

Paletas sequenciais e divergentes podem ser associadas a valores de dados de duas maneiras diferentes:
- Como um **conjunto discreto de cores**, cada uma associada a um intervalo numérico;
- Como uma **função contínua** entre valor numérico e cor.

**Exemplo:** mapas dos EUA com dados de população de 2010, representados de forma contínua e de forma discreta (por faixas).

## Algumas Sugestões

1. Evite o uso desnecessário de cores.
2. Seja consistente com as cores em todos os gráficos.
3. Aproveite o significado da cor.
4. Acessibilidade e atenção ao daltonismo (foram mostrados exemplos de visão normal vs. visão simulada com deuteranomalia e protanopia).

### Ferramentas recomendadas

- **ColorBrewer** — https://colorbrewer2.org/#type=sequential&scheme=BuGn&n=3
- **Data Color Picker** — https://www.learnui.design/tools/data-color-picker.html

*Fonte: https://www.atlassian.com/data/charts/how-to-choose-colors-data-visualization*

## Resumo da aula

- A aula retomou os conceitos de Ciência de Dados e revisou a relação entre IA, Machine Learning, Deep Learning e Data Science apresentada na aula anterior.
- Foram definidos os conceitos de **Dado**, **Informação** e **Conhecimento**, com exemplo prático de um mesmo dado numérico interpretado sob diferentes contextos.
- Foi discutido o processo de **Coleta de Dados**, incluindo um exemplo prático (pizzaria) e um fluxo mais complexo envolvendo CRM, ERP, PIM, ETL e Data Warehouse.
- Os dados foram classificados em **Qualitativos** (Nominal e Ordinal) e **Quantitativos** (Contínuo e Discreto), com exemplos de cada tipo.
- Foi apresentado o conceito de **Análise Exploratória de Dados (EDA)**, com suas etapas e principais aspectos: distribuição, representações gráficas, detecção de outliers, correlação, valores ausentes e estatísticas resumidas.
- Foi introduzido o conceito de **Visualização de Dados** e os principais tipos de gráficos: linhas, barras, histogramas, dispersão, setores, geográfico e árvores/grafo.
- Para **Variáveis Qualitativas**, foram detalhados o gráfico de setores (pizza) — com suas vantagens e desvantagens — e o gráfico de barras, usando como exemplo a pesquisa de compradores do iMac da Apple (1998).
- Para **Variáveis Quantitativas**, foram detalhados o gráfico de barras (mudanças ao longo do tempo), o histograma (distribuição de notas de teste de psicologia), o gráfico de linhas, os polígonos de frequência e o gráfico de pontos/dispersão (scatter), incluindo um alerta sobre o uso incorreto de gráficos de linha com eixo X qualitativo.
- Foi discutida a importância da escolha adequada do tipo de gráfico conforme o objetivo de comunicação (linhas para variação temporal, barras para magnitudes, setores para partes de um todo, dispersão para correlações).
- Foram apresentados os conceitos de cor em visualização de dados: padrões RGB e HSL, paletas (qualitativa, sequencial e divergente), e a diferença entre representação contínua e discreta de dados.
- A aula encerrou com boas práticas no uso de cores (evitar excesso, manter consistência, considerar significado e acessibilidade para daltonismo) e a indicação de ferramentas práticas: ColorBrewer e Data Color Picker.
