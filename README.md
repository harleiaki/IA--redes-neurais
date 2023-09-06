# RFV


https://github.com/harleiaki/Streamlit-V/assets/96266332/6e786ad9-78d4-422b-b921-c66847babcf9


## RFV significa recência, frequência, valor e é utilizado para segmentação de clientes baseado no comportamento de compras dos clientes e agrupa eles em clusters parecidos. Utilizando esse tipo de agrupamento podemos realizar ações de marketing e CRM melhores direcionadas, ajudando assim na personalização do conteúdo e até na retenção de clientes.

Para cada cliente é preciso calcular cada uma das componentes abaixo:

- Recência (R): Quantidade de dias desde a última compra.
- Frequência (F): Quantidade total de compras no período.
- Valor (V): Total de dinheiro gasto nas compras do período.

## Segmentação utilizando o RFV
Um jeito de segmentar os clientes é criando quartis para cada componente do RFV, sendo que o melhor quartil é chamado de 'A', o segundo melhor quartil de 'B', o terceiro melhor de 'C' e o pior de 'D'. O melhor e o pior depende da componente. Po exemplo, quanto menor a recência melhor é o cliente (pois ele comprou com a gente tem pouco tempo) logo o menor quartil seria classificado como 'A', já pra componente frêquencia a lógica se inverte, ou seja, quanto maior a frêquencia do cliente comprar com a gente, melhor ele/a é, logo, o maior quartil recebe a letra 'A'.

Se a gente tiver interessado em mais ou menos classes, basta a gente aumentar ou diminuir o número de quantils pra cada componente.

### Instalação
Faça o download do arquivo csv "dados" [dados](https://github.com/harleiaki/Streamlit-V/blob/main/dados.csv)

![image](https://github.com/harleiaki/Streamlit-V/assets/96266332/f8701bd7-b5ac-4db8-84a5-d43b87f1d6df)

### Executando o projeto

![image](https://github.com/harleiaki/Streamlit-V/assets/96266332/783162fd-615d-4e69-8232-c65a1a8c4194)
![image](https://github.com/harleiaki/Streamlit-V/assets/96266332/c32c8163-fa22-476c-9a1a-4d4b13e83dfd)


