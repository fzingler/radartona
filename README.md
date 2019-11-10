Radartona 2019 - InterSCity team 
===================================================

Desafio Radares x Acidentes

Para relacionar radares com acidentes, o grupo desenvolveu um sistema Web para visualizar as posições de todos os radares da cidade de São Paulo e os acidentes de Fevereiro de 2016, 2017, 2018 e 2019. Esse sistema permite a filtragem dos acidentes por ano ou a exibição de todos os acidentes.

Os radares são exibidos com um buffer de 100 metros para mostrar os acidentes que aconteceram próximo a um radar específico. Outra funcionalidade é ao usuário clicar em um radar, dados sobre esse radar são exibidos como o número de autuações e a contagem de veículos. (Atualmente só está funcionando o número de autuações)

A imagem a seguir mostra a interface da aplicação.

![Interface da Aplicação](images/interface.png)

Foram analisados também a quantidade de acidentes que ocorrem dependendo da distância dos radares.

![Interface da Aplicação](images/numero-acidentes.png)

![Interface da Aplicação](images/grafico-porcentagem.png)

Também foi feita a correlação entre as contagens dos radares dos tipos de veículos nos distritos da cidade e a quantidade de acidentes.

![Interface da Aplicação](https://raw.githubusercontent.com/ezambomsantana/radartona/master/images/correlacao.png)





---------------------------------------------------
Python modules and dependencies
---------------------------------------------------
- psycopg2
- flask
- flask_restful
- unidecode
- utm

- postgresql DB



---------------------------------------------------
Dados Utilizados
---------------------------------------------------

- Posição dos radares
- Contagem de veículos
- Acidentes
- Distritos