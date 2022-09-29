# Projeto - Casas para alugar

Neste projeto, foi analisado, um banco de dados que contém informações sobre imóveis disponíveis para alugar. Estes imóveis estão localizados em diferentes cidades e possuem diferentes características entre si, tais como, valor do aluguel, área, se é mobiliado, etc. No total, são 10693 registros, com 13 colunas.

## 1. Ferramentas utilizadas

- Planilha CSV com os dados
- Python
- Bibliotecas (Pandas, Matplot, Seaborn)

## 2. Perguntas que devem ser respondidas com esse relatório

1. Qual o número de imóveis por cidade? 

![Untitled](Projeto%20-%20Casas%20para%20alugar%20829ec7cd3ac84a0495f29f331ca4d33d/Untitled.png)

A figura apresenta o output de um countplot, mostrando o número de imóveis por cidade.

1. Qual é o valor médio do aluguel em cada cidade? Há diferenças entre cidades?

![Untitled](Projeto%20-%20Casas%20para%20alugar%20829ec7cd3ac84a0495f29f331ca4d33d/Untitled%201.png)

![Untitled](Projeto%20-%20Casas%20para%20alugar%20829ec7cd3ac84a0495f29f331ca4d33d/Untitled%202.png)

Como visto na figura e na tabela, as cidades de São Paulo e Belo Horizonte possuem os aluguéis mais caros, em seguida, o Rio de Janeiro, Campinas e Porto Alegre.

![Untitled](Projeto%20-%20Casas%20para%20alugar%20829ec7cd3ac84a0495f29f331ca4d33d/Untitled%203.png)

Porém, os valores médios dos aluguéis serão prejudicados devido à presença de outliers, valores muito discrepantes. Como no caso de São Paulo, onde existe um valor de R$ 17500, enquanto a mediana fica abaixo dos R$ 5000.

Mas de qualquer forma, considerando ou não estes outliers, os valores se mantêm coerentes.

1. Ser mobiliado altera o valor do aluguel?

![Untitled](Projeto%20-%20Casas%20para%20alugar%20829ec7cd3ac84a0495f29f331ca4d33d/Untitled%204.png)

Imóveis mobiliados, se apresentam com valores médios mais elevados em relação à imóveis não mobiliados. Valores coerentes em todas as cidades.

1. Permitir animais de estimação altera o valor do aluguel?
2. 

![Untitled](Projeto%20-%20Casas%20para%20alugar%20829ec7cd3ac84a0495f29f331ca4d33d/Untitled%205.png)

Imóveis que aceitam animais de estimação, se apresentam, em geral, com valores médios mais elevados em relação à imóveis que não aceitam. Valores coerentes em todas as cidades.

1. Existe diferença entre a área média dos imóveis em relação à localização?

![Untitled](Projeto%20-%20Casas%20para%20alugar%20829ec7cd3ac84a0495f29f331ca4d33d/Untitled%206.png)

Nesta tabela, a área é dada em m^2. 

Há grandes diferenças quando à área média dos imóveis, por região. 

Se comparar estes valores, com os valores de aluguel, nota-se que, em São Paulo, o valor do m^2 é mais caro do que Campinas, por exemplo. Enquanto em Campinas, em média se gasta R$ 3173,28 por um imóvel de 137 m^2, em São Paulo, se gasta o dobro por apenas 20 m^2 a mais.

1. O número de quartos, banheiros e vagas em estacionamento, alteram de que forma o valor do aluguel?

![Untitled](Projeto%20-%20Casas%20para%20alugar%20829ec7cd3ac84a0495f29f331ca4d33d/Untitled%207.png)

![Untitled](Projeto%20-%20Casas%20para%20alugar%20829ec7cd3ac84a0495f29f331ca4d33d/Untitled%208.png)

![Untitled](Projeto%20-%20Casas%20para%20alugar%20829ec7cd3ac84a0495f29f331ca4d33d/Untitled%209.png)

A diferença no valor do aluguel aumenta de acordo com o número de quartos, banheiros e é maior em imóveis que possuem vagas de estacionamento.
