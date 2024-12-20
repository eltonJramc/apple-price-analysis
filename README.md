# **Análise de Dados com Python: Preços de Maçãs**

Este repositório contém um projeto desenvolvido em Python para a análise e tratamento de dados relacionados aos preços de maçãs em diferentes cidades da Rússia.
O projeto utiliza as bibliotecas **Numpy** e **Pandas** e foi inteiramente realizado no Google Colab.

---

## **Descrição do Projeto**

O objetivo principal do projeto foi realizar análises e visualizações sobre os preços das maçãs, utilizando dados armazenados em um arquivo CSV. A análise foi dividida nas seguintes etapas:

1. **Carregamento e Tratamento dos Dados:**
   - Importação do dataset `apples_ts.csv` com `numpy.loadtxt`.
   - Manipulação e limpeza dos dados, incluindo identificação e preenchimento de valores ausentes.

2. **Análise Estatística:**
   - Cálculo de médias e comparação de preços ao longo dos anos.
   - Verificação de similaridade entre séries temporais usando métodos como `np.linalg.norm`.

3. **Visualização de Dados:**
   - Criação de gráficos de linhas para visualizar as variações de preços ao longo dos anos.
   - Comparação entre cidades utilizando a biblioteca `Matplotlib`.

4. **Modelagem Linear Simples:**
   - Construção de um modelo linear para prever preços com base nos dados históricos.
   - Cálculo de coeficientes angulares e interceptos para análise de tendências.

5. **Geração e Exportação de Dados:**
   - Geração de novos datasets combinando informações como coeficientes e erros de norma.
   - Exportação do arquivo final para o formato CSV.

---

## **Bibliotecas Utilizadas**

- **Numpy**: Para manipulação de arrays, cálculos matemáticos e operações numéricas.
- **Pandas**: Para limpeza, transformação e organização dos dados.
- **Matplotlib**: Para visualização de dados em gráficos.

---

## **Principais Resultados**

- Comparação de preços em diferentes cidades ao longo de 4 anos.
- Identificação de padrões sazonais e tendências de preços.
- Modelos lineares simples para prever preços com base em dados históricos.

---

## **Contribuição**

Contribuições são bem-vindas! Se você encontrar problemas ou tiver sugestões para melhorar o projeto, sinta-se à vontade para abrir uma _issue_ ou enviar um _pull request_.


