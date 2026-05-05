# data-science-series-temporais

Este projeto teve como objetivo construir modelos de previsão de uma série temporal utilizando uma base de dados de uma empresa de aluguéis de bicicletas(**bicicletas.csv**). 
Durante a execução, foi feito tratamento dos dados para melhorar o modelo preditivo, bem como a separação dos mesmos em grupos de teste e treinamento. 
As informações contidas na base original dos dados foram:

- data_hora: dia, mês, ano e horário no formato 2015-08-15 23:00:00;
- contagem;
- temperatura: temperatura em °C;
- sensacao_termica: em °C;
- umidade: umidade do ar;
- velocidade_vento: em km;
- clima: Nublado, Parcialmente nubla, Céu limpo, Neve, Chuva leve, Chuva com trovoadas;
- feriado: Sim ou Não;
- fim_de_semana: Sim ou Não;
- estacao: Verão, Primavera, Outono, Inverno.

Para tal, foram usadas as seguintes bibliotecas, nas versões descritas abaixo:

- pandas 1.5.3
- seaborn 0.13.1
- matplotlib 3.7.1
- prophet 1.1.5
