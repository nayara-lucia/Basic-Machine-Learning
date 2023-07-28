# Projeto Python IA: Inteligência Artificial e Previsões ![image](https://i.gifer.com/origin/c1/c1509216eff853bf8fb246b72bb07987_w200.gif)

### Case: Score de Crédito dos Clientes

Fui contratada por um banco para conseguir definir o score de crédito dos clientes. Preciso analisar todos os clientes do banco e, com base nessa análise, criar um modelo que consiga ler as informações do cliente e dizer automaticamente o score de crédito dele: Ruim, Ok, Bom

<hr>

### Tecnologias utilizadas: 
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) 
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

<em> O script desse projeto está disponível no arquivo "inicial.py"</em>

<hr>

### Etapas 🔛
🚨 <b> Entender o desafio da empresa </b> 🚨

1 - Importar a base de dados

2 - Preparar a base de dados para a Inteligência Artificial

- Criar um decodificador que vai permitir a transformação de objetos para números legíveis para a IA utilizando o LabelEncoder()
- Criar as bases X e Y e váriaveis de treino e teste
    
3 - Criar um modelo IA - Score de crédito ruim, médio, bom

- Escolher os modelos de IA
- Treinar os modelos
    
4 - Escolher o modelo

- Criação de previsão (realização do teste)
- Ánalise das acurácias e resultados
    
5 - Usar o modelo ideal

O modelo que melhor apresentou resultado entre o Árvore e KNN, foi o Árvore resultando em 82% de acertos

    from sklearn.metrics import accuracy_score

    previsao_arvore = modelo_arvore.predict(x_teste)
    previsao_vizinho = modelo_knn.predict(x_teste.to_numpy()) 

    print(accuracy_score(y_teste, previsao_arvore))

    print(accuracy_score(y_teste, previsao_vizinho))

    OUTPUT>
    0.82704
    0.7464



![image](https://github.com/nayara-lucia/python-IA/assets/126920974/7b5fc438-4b24-4eee-ba87-67c8c9629bd4)

