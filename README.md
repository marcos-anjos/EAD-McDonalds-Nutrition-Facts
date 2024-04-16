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
2. [Objetivo do Projeto](#tech-stack)
3. [Sobre o Dataset](#features)
4. [Limpeza dos Dados](#contato)
5. [Análise Exploratória de Dados](#contato)
6. [Conclusões](#contato)

## <a name="introdução">Introdução</a>

<body>
    <p style="text-align: justify;">
        Este repositório contém um notebook Jupyter detalhando uma análise exploratória de dados do conjunto de dados "Menu Nutrition Dataset" obtido do Kaggle. O objetivo deste notebook é explorar e visualizar os dados relacionados à nutrição de itens de menu de uma determinada empresa de fast food.
    </p>
</body>

## <a name="tech-stack">Objetivo do Projeto</a>

<body>
    <p style="text-align: justify;">
        O objetivo deste projeto de análise exploratória de dados é examinar o conjunto de dados do Menu de Nutrição e identificar padrões, tendências e insights relevantes sobre a composição nutricional dos itens do menu de uma empresa de fast food. A análise visa proporcionar uma compreensão mais profunda das características dos produtos oferecidos, como calorias, proteínas, gorduras, carboidratos e sódio, além de fornecer insights sobre a distribuição dessas variáveis em diferentes categorias de menu. Essas informações podem ser úteis para a empresa em termos de tomada de decisões estratégicas relacionadas ao desenvolvimento de novos produtos, otimização do menu existente, comunicação nutricional e atendimento às demandas dos consumidores por opções alimentares mais saudáveis.
    </p>
</body>


## <a name="features">Sobre o Dataset</a>

Este conjunto de dados fornece os factos nutricionais de cada item do menu do McDonald's indiano. Eles possuem 141 entradas e 13 colunas, sendo 10 do tipo numérico e 3 do tipo categórico. Algumas das colunas incluem:

Fonte: [Kaggle | Menu Nutrition Dataset](https://www.kaggle.com/datasets/deepcontractor/mcdonalds-india-menu-nutrition-facts)

- `Categoria do menu`
- **`Itens do menu`**
- **`Tamanho por dose`**
- **`Energia (kCal)`**
- **`Proteína (g)`**
- **`Gordura total (g)`**
- **`Gordura saturada (g)`**
- **`Gorduras trans (g)`**
- **`Colesteróis (mg)`**
- **`Carboidratos (g)`**
- **`Açúcares totais (g)`**
- **`Açúcares adicionados (g)`**
- **`Sódio (mg)`**

## <a name="contato">Limpeza dos Dados</a>
- Verificação de valores nulos e sua correção.
- Verificação de valores duplicados.
- Preenchimento de valores nulos com a média

## <a name="contato">Análise Exploratória de Dados</a>
- Contagem de itens por categoria de menu.
- Cálculo da média nutricional por categoria de menu.
- Visualização da distribuição de energia (kCal) por categoria de menu.
- Identificação de colunas com outliers e distribuição das variáveis nutricionais.
- Cálculo da correlação entre as variáveis nutricionais e visualização em um mapa de calor.

## <a name="contato">Conclusões</a>
- "McCafe Menu" possui o maior número de itens, enquanto "Desserts Menu" possui o menor.
- A categoria "Gourmet Menu" tem os maiores valores médios nutricionais.
- A categoria "Breakfast Menu" também apresenta valores médios consideráveis.
- A categoria "Beverages Menu" possui valores médios relativamente baixos.
- As variáveis com maior correlação são "Energy (kCal)" e "Protein (g)".
