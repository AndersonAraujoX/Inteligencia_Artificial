# Projeto de Aprendizado de Máquina

Este projeto foi desenvolvido como parte da disciplina de Inteligência Artificial e tem como objetivo a aplicação de algoritmos de classificação em diversos datasets.

## Alunos

* João Paulo Garcia Nusp: 11816056
* Igor Mateus Queiroz Gato Nusp: 10261481
* Anderson Araujo de Oliveira Nusp: 11371311

## Objetivo

O objetivo principal deste projeto é proporcionar a experiência de elaborar um projeto de aprendizado de máquina, utilizando alguns dos algoritmos de classificação mais tradicionais. [cite: 1, 2, 3, 4, 5, 6, 7, 8]

## Etapas do Projeto

O projeto foi desenvolvido seguindo as seguintes etapas:

1.  **Seleção de Datasets:**
    
    * Dez datasets foram selecionados de repositórios como Kaggle e UCI. [cite: 2, 3, 4, 5, 6, 15, 16, 22, 23, 24]
2.  **Pré-processamento dos Dados:**
    
    * Para cada dataset, foram aplicadas técnicas de pré-processamento, incluindo tratamento de dados faltantes, seleção de atributos e padronização. [cite: 2, 3, 4, 5, 6, 72, 73, 74]
    * Dados faltantes foram tratados com a remoção de linhas. [cite: 71]
    * Dados não numéricos (strings) foram tratados com LabelEncoder (para saída) e OneHotEncoder (para entrada). [cite: 72, 73]
    * Dados de tempo foram convertidos para segundos. [cite: 73]
    * Dados numéricos foram padronizados utilizando MinMaxEncoder ou MaxAbsEncoder. [cite: 74]
3.  **Medidas de Avaliação:**
    
    * Medidas de avaliação adequadas foram selecionadas para cada dataset. [cite: 4]
4.  **Validação Cruzada:**
    
    * Validação cruzada (10-fold cross validation) foi utilizada nos experimentos. [cite: 4, 5]
5.  **Aplicação de Algoritmos de Classificação:**
    
    * Os seguintes algoritmos de classificação foram aplicados com diferentes configurações (hiperparâmetros):
        * K-Nearest Neighbors (KNN) [cite: 5, 86, 89, 92, 94, 100, 103, 106, 109, 112]
        * Naive Bayes (GaussianNB) [cite: 5, 88, 91, 93, 96, 98, 102, 105, 108, 111, 114]
        * Árvores de Decisão [cite: 5, 86, 90, 93, 96, 97, 101, 104, 107, 110, 113]
        * Multilayer Perceptron (MLP) [cite: 5, 86, 87, 90, 94, 97, 99, 102, 106, 109, 112, 87]
6.  **Análise de Resultados:**
    
    * Os dois melhores algoritmos de cada dataset foram selecionados e comparados utilizando o erro absoluto médio. [cite: 6, 115]

## Datasets Utilizados

Os seguintes datasets foram utilizados no projeto:

* Dados de Zoológico ([https://www.kaggle.com/datasets/agajorte/zoo-animals-extended-dataset](https://www.kaggle.com/datasets/agajorte/zoo-animals-extended-dataset)) [cite: 23]
* Preço de Abacates ([https://www.kaggle.com/datasets/neuromusic/avocado-prices](https://www.kaggle.com/datasets/neuromusic/avocado-prices)) [cite: 23]
* Análise de Vinhos ([https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)) [cite: 23]
* Análise de GPU Kernel Performance ([https://archive.ics.uci.edu/ml/datasets/SGEMM+GPU+kernel+performance](https://archive.ics.uci.edu/ml/datasets/SGEMM+GPU+kernel+performance)) [cite: 23]
* Análise de Flores Iris ([https://www.kaggle.com/uciml/iris](https://www.kaggle.com/uciml/iris)) [cite: 23]
* Dados de Doenças do Coração ([https://www.kaggle.com/datasets/zgeakyldz/heart-desease-data](https://www.kaggle.com/datasets/zgeakyldz/heart-desease-data)) [cite: 23]
* Análise de Dados para Predição de Diabetes ([https://www.kaggle.com/datasets/mathchi/diabetes-data-set](https://www.kaggle.com/datasets/mathchi/diabetes-data-set)) [cite: 23]
* Análise de DnD ([https://www.kaggle.com/datasets/andrewabeles/dnd-stats](https://www.kaggle.com/datasets/andrewabeles/dnd-stats)) [cite: 23]
* Resultados de Jogos ([https://www.kaggle.com/datasets/depmountaineer/arcade-game-stats](https://www.kaggle.com/datasets/depmountaineer/arcade-game-stats)) [cite: 23]
* Dados Google Play ([https://www.kaggle.com/datasets/gauthamp10/google-playstore-apps](https://www.kaggle.com/datasets/gauthamp10/google-playstore-apps)) [cite: 23]

## Ferramentas e Bibliotecas

O projeto foi implementado em Python, utilizando as seguintes bibliotecas:

* Pandas: para manipulação e análise de dados. [cite: 16, 17]
* Seaborn: para geração de gráficos. [cite: 16, 17, 23]
* Scikit-learn: algoritmos de classificação, medidas de avaliação, pré-processamento, validação cruzada, etc. [cite: 16, 17, 74, 75, 76, 77, 78, 79, 80, 82, 83, 84, 85, 86, 87, 89, 90, 91, 92, 93, 94, 95, 96, 97, 98, 99, 100, 101, 102, 103, 104, 105, 106, 107, 108, 109, 110, 111, 112, 113, 114, 23, 74, 75, 76, 77, 78, 79, 80, 82, 83, 84, 85, 86, 87, 89, 90, 91, 92, 93, 94, 95, 96, 97, 98, 99, 100, 101, 102, 103, 104, 105, 106, 107, 108, 109, 110, 111, 112, 113, 114]
* Numpy: para tratamento eficiente de dados numéricos. [cite: 23]
* Datetime: para trabalhar com datas. [cite: 23, 73]
* Matplotlib: para plotar gráficos. [cite: 23]

O projeto foi desenvolvido em formato de notebook (Jupyter Notebook ou Google Colab). [cite: 17]

## Execução

Para executar o projeto:

1.  Clone este repositório.
2.  Instale as dependências: `pip install pandas scikit-learn seaborn matplotlib numpy`
3.  Execute os notebooks no Jupyter Notebook ou Google Colab.

## Arquivos Entregues

Os seguintes arquivos foram entregues:

* `.ipynb` (notebook executável) [cite: 17]
* `.html` (relatório em HTML) [cite: 17]
* Slide da apresentação [cite: 17]

## Datas Importantes

* Depósito do projeto: 21/06 [cite: 20, 21]
* Apresentações: 21/06, 24/06, 28/06 e 01/07 [cite: 21]

## Contato

Em caso de dúvidas, entre em contato com os alunos responsáveis.
