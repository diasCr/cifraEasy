# Como abrir

Acessar o link [draw.io](https://app.diagrams.net/) e importar o diagrama desejado.

# Business model

business_model.drawio

Modelo de negócio envolvendo todos objetos relevantes para o funcionamento do programa. Apresenta os limites do negócio e quais objetos não pertecem ao programa mais devem ser considerados para melhor entendimento do funcionamento da aplicação. Representa o núcleo e só pode ser alterado se o negócio for alterado.

## Detalhes

Uma música tem a referência (lista) de todas as suas versões que por sua vez tem uma lista de suas respectivas partes. Uma música também tem somente o nome de quem canta a música.

Um(a) cantor(a) por sua vez tem uma lista simplificada de suas músicas, contendo somente nome e o ID da música. Assim evitamos a dependência cíclica entre músicas e cantores.

Os objetos "VERSION" e "PART" jamais serão utilizados de forma separadas de seu objeto de origem que no caso é "MUSIC".