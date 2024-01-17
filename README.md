# analise dataset iris.

O projeto em questão trata-se de uma análise de dados voltada para a classificação de espécies de flores Iris. A motivação principal é criar um modelo capaz de prever a espécie de uma flor com base em suas características específicas, como o comprimento e largura da sépala e da pétala.

Para realizar essa análise, utilizei o conjunto de dados Iris, uma base de dados que contém informações sobre três espécies distintas de flores: Setosa, Versicolor e Virginica. Inicialmente, conduzi uma análise exploratória para compreender a distribuição dessas características e as relações entre elas.

No processo de treinamento do modelo, optei por implementar o algoritmo KNN (K-Nearest Neighbors), dividindo o conjunto de dados em conjuntos de treino e teste. A avaliação da performance do modelo foi realizada por meio de métricas, sendo a acurácia uma das principais consideradas.

Quanto à visualização dos resultados, criei representações gráficas interativas para demonstrar como o modelo classifica diferentes regiões com base nas características das pétalas. Além disso, utilizei boxplots e scatter plots para explorar a distribuição das medidas de sépalas e pétalas em relação a cada espécie.

Durante a análise, identifiquei padrões interessantes, como a capacidade do modelo em separar eficientemente as espécies, especialmente no caso da "Iris-setosa". No entanto, também observei áreas de sobreposição entre as espécies, sugerindo oportunidades para aprimorar o modelo ou explorar outras características.

Como extensão da análise, realizei visualizações adicionais, como a matriz de correlação e pair plots, buscando compreender ainda mais as relações e padrões presentes nos dados.

Em resumo, o projeto proporcionou insights valiosos sobre a relação entre as características das flores Iris e suas respectivas espécies. As conclusões obtidas e as sugestões para aprimoramento do modelo são elementos essenciais a serem considerados para futuras aplicações práticas e refinamentos na análise de dados.




![Screenshot 2024-01-17 13 19 29](https://github.com/Josue185/analise-iris/assets/92592495/e895790e-5282-4238-b865-5f86e38a6e73)


![Screenshot 2024-01-17 13 19 36](https://github.com/Josue185/analise-iris/assets/92592495/e84390b9-5c81-4d22-aa23-49433bf3511a)

![Screenshot 2024-01-17 13 19 58](https://github.com/Josue185/analise-iris/assets/92592495/84a9246f-f7bb-4e65-821d-ef53c742485b)

![Screenshot 2024-01-17 13 20 09](https://github.com/Josue185/analise-iris/assets/92592495/36b9217f-f03e-4249-989e-6cfe69e2f17c)


Mas Afinal o que o Metodo KNN
Em resumo, o KNN tenta classificar cada amostra de um conjunto de dados avaliando sua distância em relação aos vizinhos mais próximos. Se os vizinhos mais próximos forem majoritariamente de uma classe, a amostra em questão será classificada nesta categoria.

Após a análise e compreensão dos padrões das Flores criei mais uma etapa:

1 - Cenário da aplicação
O usuario do sistema precisa verificar uma possivel planta que não esta rotulada em sua estufa, coleta as suas medidas e realiza uma pesquisa no sistema.

![Screenshot 2024-01-17 13 29 45](https://github.com/Josue185/analise-iris/assets/92592495/9de641a9-774e-42f0-bcb3-75064ed7732d)

2 - Recebe o retorno com o nome da especie já processado pelo KNN.

![Screenshot 2024-01-17 13 30 00](https://github.com/Josue185/analise-iris/assets/92592495/1832dc83-7497-4bb5-9022-15037a041f2a)

