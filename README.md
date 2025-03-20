# Projeto de Aprendizado de Máquina

Este projeto foi desenvolvido como parte da disciplina de Inteligência Artificial e tem como objetivo a aplicação de algoritmos de classificação em diversos datasets.

## Alunos

* João Paulo Garcia Nusp: 11816056
* Igor Mateus Queiroz Gato Nusp: 10261481
* Anderson Araujo de Oliveira Nusp: 11371311

## Objetivo

O objetivo principal deste projeto é proporcionar a experiência de elaborar um projeto de aprendizado de máquina, utilizando alguns dos algoritmos de classificação mais tradicionais. 

## Etapas do Projeto

O projeto foi desenvolvido seguindo as seguintes etapas:

1.  **Seleção de Datasets:**
    
    * Dez datasets foram selecionados de repositórios como Kaggle e UCI. 
2.  **Pré-processamento dos Dados:**
    
    * Para cada dataset, foram aplicadas técnicas de pré-processamento, incluindo tratamento de dados faltantes, seleção de atributos e padronização. 
    * Dados faltantes foram tratados com a remoção de linhas. 
    * Dados não numéricos (strings) foram tratados com LabelEncoder (para saída) e OneHotEncoder (para entrada). 
    * Dados de tempo foram convertidos para segundos.
    * Dados numéricos foram padronizados utilizando MinMaxEncoder ou MaxAbsEncoder.
3.  **Medidas de Avaliação:**
    
    * Medidas de avaliação adequadas foram selecionadas para cada dataset.
4.  **Validação Cruzada:**
    
    * Validação cruzada (10-fold cross validation) foi utilizada nos experimentos. 
5.  **Aplicação de Algoritmos de Classificação:**
    
    * Os seguintes algoritmos de classificação foram aplicados com diferentes configurações (hiperparâmetros):
        * K-Nearest Neighbors (KNN) 
        * Naive Bayes (GaussianNB) 
        * Árvores de Decisão
        * Multilayer Perceptron (MLP) 
6.  **Análise de Resultados:**
    
    * Os dois melhores algoritmos de cada dataset foram selecionados e comparados utilizando o erro absoluto médio.

## Datasets Utilizados

Os seguintes datasets foram utilizados no projeto:

* Dados de Zoológico ([https://www.kaggle.com/datasets/agajorte/zoo-animals-extended-dataset](https://www.kaggle.com/datasets/agajorte/zoo-animals-extended-dataset)) 
* Preço de Abacates ([https://www.kaggle.com/datasets/neuromusic/avocado-prices](https://www.kaggle.com/datasets/neuromusic/avocado-prices)) 
* Análise de Vinhos ([https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)) 
* Análise de GPU Kernel Performance ([https://archive.ics.uci.edu/ml/datasets/SGEMM+GPU+kernel+performance](https://archive.ics.uci.edu/ml/datasets/SGEMM+GPU+kernel+performance)) 
* Análise de Flores Iris ([https://www.kaggle.com/uciml/iris](https://www.kaggle.com/uciml/iris)) 
* Dados de Doenças do Coração ([https://www.kaggle.com/datasets/zgeakyldz/heart-desease-data](https://www.kaggle.com/datasets/zgeakyldz/heart-desease-data)) 
* Análise de Dados para Predição de Diabetes ([https://www.kaggle.com/datasets/mathchi/diabetes-data-set](https://www.kaggle.com/datasets/mathchi/diabetes-data-set)) 
* Análise de DnD ([https://www.kaggle.com/datasets/andrewabeles/dnd-stats](https://www.kaggle.com/datasets/andrewabeles/dnd-stats)) 
* Resultados de Jogos ([https://www.kaggle.com/datasets/depmountaineer/arcade-game-stats](https://www.kaggle.com/datasets/depmountaineer/arcade-game-stats)) 
* Dados Google Play ([https://www.kaggle.com/datasets/gauthamp10/google-playstore-apps](https://www.kaggle.com/datasets/gauthamp10/google-playstore-apps)) 

## Ferramentas e Bibliotecas

O projeto foi implementado em Python, utilizando as seguintes bibliotecas:

* Pandas: para manipulação e análise de dados. 
* Seaborn: para geração de gráficos. 
* Scikit-learn: algoritmos de classificação, medidas de avaliação, pré-processamento, validação cruzada, etc.
* Numpy: para tratamento eficiente de dados numéricos. 
* Datetime: para trabalhar com datas. 
* Matplotlib: para plotar gráficos. 

O projeto foi desenvolvido em formato de notebook (Jupyter Notebook ou Google Colab).

## Execução

Para executar o projeto:

1.  Clone este repositório.
2.  Instale as dependências: `pip install pandas scikit-learn seaborn matplotlib numpy`
3.  Execute os notebooks no Jupyter Notebook ou Google Colab.

