# Projeto Aplicado I - Tendência de compras em shoppings de Istambul
## Sumário
[Apresentação](https://github.com/OtavioBer/ProjetoAplicadoI#apresenta%C3%A7%C3%A3o)
- [Integrantes](https://github.com/OtavioBer/ProjetoAplicadoI#integrantes)
- [Introdução](https://github.com/OtavioBer/ProjetoAplicadoI#introdu%C3%A7%C3%A3o)

[Link dos Datasets analisado](https://github.com/OtavioBer/ProjetoAplicadoI#link-dos-datasets-analisado)
- [Dataset público Kaggle](https://github.com/OtavioBer/ProjetoAplicadoI#dataset-p%C3%BAblico-kaggle)
- [Dataset criado a partir de busca no Google](https://github.com/OtavioBer/ProjetoAplicadoI#dataset-criado-a-partir-de-busca-no-google)

[Perguntas a serem respondidas](https://github.com/OtavioBer/ProjetoAplicadoI#perguntas-a-serem-respondidas)
- [O público feminino consome mais roupas que o masculino?](https://github.com/OtavioBer/ProjetoAplicadoI#1-o-p%C3%BAblico-feminino-consome-mais-roupas-que-o-masculino)
- [Quais produtos são mais consumidos por gênero?](https://github.com/OtavioBer/ProjetoAplicadoI#2-quais-produtos-s%C3%A3o-mais-consumidos-por-g%C3%AAnero)
- [Qual o ranking de produtos mais consumidos pelo público em geral?](https://github.com/OtavioBer/ProjetoAplicadoI#3-qual-o-ranking-de-produtos-mais-consumidos-pelo-p%C3%BAblico-em-geral)
- [Qual a forma de pagamento mais utilizada por faixa etária e por gênero?](https://github.com/OtavioBer/ProjetoAplicadoI#4-qual-a-forma-de-pagamento-mais-utilizada-por-faixa-et%C3%A1ria-e-por-g%C3%AAnero)
- [Qual a sazonalidade (dia da semana) de consumo com maior volume de compras?](https://github.com/OtavioBer/ProjetoAplicadoI#5-qual-a-sazonalidade-dia-da-semana-de-consumo-com-maior-volume-de-compras)
- [Qual a média de consumo anual por gênero e faixa etária?](https://github.com/OtavioBer/ProjetoAplicadoI#6-qual-a-m%C3%A9dia-de-consumo-anual-por-g%C3%AAnero-e-faixa-et%C3%A1ria)
- [Qual shopping possui o maior ticket médio de compras?](https://github.com/OtavioBer/ProjetoAplicadoI#7-qual-shopping-possui-o-maior-ticket-m%C3%A9dio-de-compras)
- [Como se dá a comparação de gastos totais por gênero e por faixa etária? E dos gastos médios?](https://github.com/OtavioBer/ProjetoAplicadoI#8-como-se-d%C3%A1-a-compara%C3%A7%C3%A3o-de-gastos-totais-por-g%C3%AAnero-e-por-faixa-et%C3%A1ria-e-dos-gastos-m%C3%A9dios)
- [Qual faixa etária mais consome artigos de leitura?](https://github.com/OtavioBer/ProjetoAplicadoI#9-qual-faixa-et%C3%A1ria-mais-consome-artigos-de-leitura)
- [Qual a localidade de shopping tem o maior consumo por categoria?](https://github.com/OtavioBer/ProjetoAplicadoI#10-qual-a-localidade-de-shopping-tem-o-maior-consumo-por-categoria)
- [Qual produto tem o maior e menor ticket médio por região?](https://github.com/OtavioBer/ProjetoAplicadoI#11-qual-produto-tem-o-maior-e-menor-ticket-m%C3%A9dio-por-regi%C3%A3o)

## Apresentação
### Integrantes
	Adrieli Machado Zaluski
	Caroline Ribeiro Ferreira 
	Lais César Fonseca 
	Liliane Gonçalves de Brito Ferraz 
	Mucio Emanuel Feitosa Ferraz Filho
	Otavio Bernardo Scandiuzzi


### Introdução

	O propósito deste projeto é realizar um estudo de caso prático em uma base de dados pública, disponibilizada no site Kaggle¹. 
	Os dados escolhidos para este estudo referem-se a compras em shoppings na cidade de Istambul, na Turquia.Esses dados serão utilizados
	para identificar padrões no comportamento de compras e prever tendências futuras de consumo. 
	Para este estudo de ciências de dados será utilizado técnicas adquiridas nos componentes curriculares de introdução a ciência de dados,
	pensamento computacional e análise exploratória de dados, com o objetivo principal de analisar e interpretar o que esses dados podem 
	mostrar através de aplicação de medidas estatísticas, no qual discutiremos e responderemos algumas perguntas ao longo do projeto, 
	permitindo uma compreensão mais profunda do comportamento dos consumidores em Istambul.
	Neste projeto apresentaremos os principais comandos utilizados para realizar as análises dos dados através da aplicação da linguagem Python,
	com o uso do Colab. Como acessar o metadado, consultar quantidade de atributos, linhas, resumo do dataset, verificar os tipos dos atributos
	e como importar as bibliotecas necessárias para realizar a exploração de dados de forma mais simplificada.


## Link dos Datasets analisado
### Dataset público Kaggle 
	https://www.kaggle.com/datasets/mehmettahiraslan/customer-shopping-dataset
  
### Dataset criado a partir de busca no Google
	https://github.com/OtavioBer/ProjetoAplicadoI/blob/main/Dados/Backup/Base_Google_Endere%C3%A7o_Shoppings_Istambul.xlsx


## Perguntas a serem respondidas
### 1. O público feminino consome mais roupas que o masculino?
### 2. Quais produtos são mais consumidos por gênero?
### 3. Qual o ranking de produtos mais consumidos pelo público em geral?
### 4. Qual a forma de pagamento mais utilizada por faixa etária e por gênero?
### 5. Qual a sazonalidade (dia da semana) de consumo com maior volume de compras?
### 6. Qual a média de consumo anual por gênero e faixa etária?
### 7. Qual shopping possui o maior ticket médio de compras?
### 8. Como se dá a comparação de gastos totais por gênero e por faixa etária? E dos gastos médios?
### 9. Qual faixa etária mais consome artigos de leitura?
### 10. Qual a localidade de shopping tem o maior consumo por categoria?
### 11. Qual produto tem o maior e menor ticket médio por região?


### [Assista aqui o video de apresentação](https://youtu.be/zn3LurrLf2k)
