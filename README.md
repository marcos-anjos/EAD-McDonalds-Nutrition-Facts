<div align="center">
    <h1>Exploração Nutricional do Menu do McDonald's</h1>
    
  <img src="https://github.com/marcos-anjos/Data-Analytics-Portifolio---EAD-McDonald-s-Nutrition-Facts/assets/160321440/591915ec-6d86-4dfe-b38a-88927f0b83c6" />

  <div align="center">
        <img alt="Kaggle" src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white" />
        <a href="#"><img alt="Python" src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue"></a>
        <a href="#"><img alt="JUPYTER" src="https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white"></a>
    </div>

<h3>Análise Exploratória De Dados</h3>

  <p>O projeto consiste em uma análise exploratória dos dados nutricionais do menu do McDonald's, utilizando técnicas de limpeza, visualização e análise de dados.</p>
  
</div>

## <a name="table">Súmario</a>

1. [Introdução](#introdução)
2. [Objetivo do Projeto](#Objetivo)
3. [Sobre o Dataset](#Dataset)
4. [Limpeza dos Dados](#Limpeza)
5. [Análise Exploratória de Dados](#Análise)
6. [Conclusões](#Conclusões)

## <a name="introdução">Introdução</a>

<body>
    <p style="text-align: justify;">
        Este repositório contém um notebook Jupyter detalhando uma análise exploratória de dados do conjunto de dados "Menu Nutrition Dataset" obtido do Kaggle. O objetivo deste notebook é explorar e visualizar os dados relacionados à nutrição de itens de menu de uma determinada empresa de fast food.
    </p>
</body>

## <a name="Objetivo">Objetivo do Projeto</a>

<body>
    <p style="text-align: justify;">
       O objetivo deste projeto é realizar uma análise exploratória dos dados do Menu Nutrition Dataset, disponível no Kaggle, a fim de entender a composição nutricional dos itens de menu de uma cadeia de fast food específica. Por meio dessa análise, buscamos identificar padrões, tendências e insights relevantes relacionados às características nutricionais dos alimentos oferecidos, como calorias, proteínas, gorduras, carboidratos, açúcares e sódio. O objetivo final é fornecer uma visão abrangente que possa auxiliar na tomada de decisões informadas pelos consumidores e na conscientização sobre escolhas alimentares saudáveis.
    </p>
</body>


## <a name="Dataset">Sobre o Dataset</a>

Este conjunto de dados fornece os factos nutricionais de cada item do menu do McDonald's indiano. Eles possuem 141 entradas e 13 colunas, sendo 10 do tipo numérico e 3 do tipo categórico. Algumas das colunas incluem:

Fonte: [Kaggle | Menu Nutrition Dataset](https://www.kaggle.com/datasets/deepcontractor/mcdonalds-india-menu-nutrition-facts)

- `Categoria do menu`: A categoria a que pertence o item de menu específico.
- **`Itens do menu`**: A lista de todos os itens servidos
- **`Tamanho por dose`**: A quantidade (em g ou ml) de um determinado item de menu servido.
- **`Energia (kCal)`**: A quantidade de energia (kCal) por porção
- **`Proteína (g)`**: A quantidade de proteína (g) por porção
- **`Gordura total (g)`**: A quantidade de gordura total (g) por porção
- **`Gordura saturada (g)`**: A quantidade de gordura saturada (g) por porção
- **`Gorduras trans (g)`**: A quantidade de gordura trans (g) por porção
- **`Colesteróis (mg)`**: A quantidade de colestrol (mg) por porção
- **`Carboidratos (g)`**: A quantidade de hidratos de carbono (g) por porção
- **`Açúcares totais (g)`**: A quantidade de Açúcares totais (g) por porção
- **`Açúcares adicionados (g)`**: A quantidade de Açúcares adicionados (g) por porção
- **`Sódio (mg)`**: A quantidade de Sódio (mg) por porção

## <a name="Limpeza">Limpeza dos Dados</a>
- Verificação de valores nulos e sua correção.
- Verificação de valores duplicados.
- Preenchimento de valores nulos com a média

## <a name="Análise">Análise Exploratória de Dados</a>
- Contagem de itens por categoria de menu, visualizando essas contagens em um gráfico de barras para identificar as categorias mais comuns.
- Identificação dos cinco principais itens em várias métricas nutricionais, como calorias, proteínas, gorduras, carboidratos, açúcares e sódio. Visualizamos esses resultados em gráficos de barras para uma compreensão clara. Destacando áreas de foco para os consumidores preocupados com a saúde e fornecendo insights valiosos para tomada de decisão informada sobre escolhas alimentares.

## <a name="Conclusões">Conclusões</a>
- Identificamos as categorias de menu mais comuns e a distribuição de itens em cada uma delas. Isso nos permitiu entender melhor a variedade de opções disponíveis para os clientes.
- Ao analisar os itens com maiores quantidades de calorias, proteínas, gorduras, carboidratos, açúcares e sódio, pudemos destacar os itens que podem ter impacto significativo na ingestão diária desses nutrientes.
- Os gráficos de barras nos permitiram visualizar facilmente os principais itens em cada categoria, facilitando a compreensão das tendências nutricionais.

É importante notar que, embora esses dados forneçam informações valiosas, devemos interpretá-los com cautela. A análise nutricional de itens de fast food é apenas uma parte da equação quando se trata de fazer escolhas alimentares saudáveis. Outros fatores, como tamanho das porções, ingredientes e preparação dos alimentos, também desempenham um papel importante na saúde geral.
