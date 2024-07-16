
**Análise do Comportamento dos Clientes de uma Fintech para Lançamento de nova Funcionalidade**

CONTEXTO DO PROJETO:
Uma fintech especializada em transferências bancárias que opera dos EUA, será responsável por lançar um serviço de transferência instantânea nos Estados Unidos da América (PS: eles não têm PIX por lá…). Mas para garantir o sucesso do lançamento, gostariam de levantar algumas informações para definir a melhor data de lançamento dessa nova funcionalidade.
Ele quer atingir o maior número de usuários possível e para isso, gostaria de lançar o produto no dia e horário com maior engajamento. Além disso, gostaria de saber qual sistema operacional deve ser priorizado no desenvolvimento, para garantir que na data esteja disponível para o maior número de usuários possíveis.

Analisando a base de dados disponibilizada pela empresa, segui as seguintes etapas para entregar a solução desejada:

- Análise das tabelas do banco de dados e as relações entre elas
- Construção de gráfico de faturamento do período. Considerando que a fintech tinha uma meta de $400.000,00 e fatura a partir de uma taxa em cada transação realizada
- Construção de gráfico de faturamento por dia na semana analisada
- Construção de gráfico de análise de interações, mostrando quantos usuários estavam ativos em cada horario, quantas avaliações positivas foram feitas e quantas vezes a funcionalidade premium foi utilizada
- Criação de gráfico de proporção de usuários Android x IOS
- Criação de um Dashboard para apresentação das análises
- Definição da proposta de lançamento

Os gráficos, análises e dashboard foram feitos utilizando SQL no Metabase

![image](https://github.com/user-attachments/assets/403557b5-10a8-435b-abdc-9c3aff59dbc9)


CONCLUSÃO:
  Observando o gráfico de faturamento é possível perceber que o dia com maior faturamento é terça-feira. Já analisando o gráfico de análise das interações por hora, percebemos um maior número de usuários ativos e utilização de funcionalidade Premium a partir das 15h. Por isso a recomendação de lançamento foi para a próxima terça-feira (02/05) ás 15:00, priorizando o sistema operacional Android.
