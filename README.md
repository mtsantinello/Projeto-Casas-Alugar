# Projeto - Casas para alugar

Neste projeto, foi analisado, um banco de dados que contém informações sobre imóveis disponíveis para alugar. Estes imóveis estão localizados em diferentes cidades e possuem diferentes características entre si, tais como, valor do aluguel, área, se é mobiliado, etc. No total, são 10693 registros, com 13 colunas.

## 1. Ferramentas utilizadas

- Planilha CSV com os dados
- Python
- Bibliotecas (Pandas, Matplot, Seaborn)

## 2. Perguntas que devem ser respondidas com esse relatório

1. Qual o número de imóveis por cidade? 

<div align="center">
<img src="https://user-images.githubusercontent.com/110427400/194962084-28622ae9-9762-46bd-92fd-d6b5cead238c.png" width="450px" />
</div>

A figura apresenta o output de um countplot, mostrando o número de imóveis por cidade.

2. Qual é o valor médio do aluguel em cada cidade? Há diferenças entre cidades?

<div align="center">
<img src="https://user-images.githubusercontent.com/110427400/194965306-cc883164-014b-4a94-bc34-583a2f1f7261.png" width="450px" />
</div>

<div align="center">
<img src="https://user-images.githubusercontent.com/110427400/194965458-ecf893b2-cc59-4fa2-96e1-c0cf730b3a24.png" width="180px" />
</div>

Como visto na figura e na tabela, as cidades de São Paulo e Belo Horizonte possuem os aluguéis mais caros, em seguida, o Rio de Janeiro, Campinas e Porto Alegre.

<div align="center">
<img src="https://user-images.githubusercontent.com/110427400/194965511-fde59c8d-56db-4399-8f72-777b45a7e840.png" width="450px" />
</div>

Porém, os valores médios dos aluguéis serão prejudicados devido à presença de outliers, valores muito discrepantes. Como no caso de São Paulo, onde existe um valor de R$ 17500, enquanto a mediana fica abaixo dos R$ 5000.

Mas de qualquer forma, considerando ou não estes outliers, os valores se mantêm coerentes.

3. Ser mobiliado altera o valor do aluguel?

<div align="center">
<img src="https://user-images.githubusercontent.com/110427400/194965576-dcc99047-557d-4180-8332-f8130b349324.png" width="700px" />
</div>

Imóveis mobiliados, se apresentam com valores médios mais elevados em relação à imóveis não mobiliados. Valores coerentes em todas as cidades.

4. Permitir animais de estimação altera o valor do aluguel?
 

<div align="center">
<img src="https://user-images.githubusercontent.com/110427400/194965620-be4cb594-d233-4546-ac84-bcca21c7f410.png" width="700px" />
</div>

Imóveis que aceitam animais de estimação, se apresentam, em geral, com valores médios mais elevados em relação à imóveis que não aceitam. Valores coerentes em todas as cidades.

5. Existe diferença entre a área média dos imóveis em relação à localização?

<div align="center">
<img src="https://user-images.githubusercontent.com/110427400/194965658-a0cf6cf6-5f98-4721-9c4f-dbdf8a306c2b.png" width="180px" />
</div>

Nesta tabela, a área é dada em m^2. 

Há grandes diferenças quando à área média dos imóveis, por região. 

Se comparar estes valores, com os valores de aluguel, nota-se que, em São Paulo, o valor do m^2 é mais caro do que Campinas, por exemplo. Enquanto em Campinas, em média se gasta R$ 3173,28 por um imóvel de 137 m^2, em São Paulo, se gasta o dobro por apenas 20 m^2 a mais.

6. O número de quartos, banheiros e vagas em estacionamento, alteram de que forma o valor do aluguel?

<div align="center">
<img src="https://user-images.githubusercontent.com/110427400/194965726-431bbd51-1a05-4e7e-a54e-3c1eb79619d9.png" width="350px" />
</div>

<div align="center">
<img src="https://user-images.githubusercontent.com/110427400/194965763-eb260efd-9b5f-4d2c-83b4-e86a8c7ecf24.png" width="350px" />
</div>

<div align="center">
<img src="https://user-images.githubusercontent.com/110427400/194965793-aeb31921-6930-415b-91c2-80862009dfba.png" width="700px" />
</div>

A diferença no valor do aluguel aumenta de acordo com o número de quartos, banheiros e é maior em imóveis que possuem vagas de estacionamento.
