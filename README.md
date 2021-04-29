# JavaScript - Exercício 1

O arquivo main.js contém um array com informações de 150 empresas de um conglomerado, cada empresa contém a seguinte estrutura de objeto:

```javascript
{
  nome: "NOME DA EMPRESA",
  endereco: "RUA FULANO, 100",
  caixa: 12405 (valor inteiro),
  lucro: 4500 (valor inteiro)
}
```

Utilizando o arquivo main.js deste repositório você deve alterá-lo para apresentar os seguintes resultados no terminal:

- Trazer um array com todos os elementos de um array de objetos que tenham lucro de vendas acima de 7000, com o seguinte texto:
  - "Este mês tivemos [TOTAL_DE_EMPRESAS_COM_LUCRO_ACIMA_DE_7000] acima de R$ 7000,00"
- Criar um array apenas com os valores de lucro de todas as lojas
- Usar o array gerado no passo anterior para somar o total de vendas de todas as lojas, com o seguinte texto:
  -  "Apresentamos um resultado de R$ [TOTAL_DE_VENDAS] este mês"
- Aplicar um bonus de 1000 reais ao caixa para cada loja que teve um lucro de vendas acima de 9000
- Apresentar um resumo com o nome da loja e total em caixa em um texto no seguinte formato:
    - "A loja [NOME_DA_LOJA] apresentou um lucro de vendas de [TOTAL_DE_VENDAS] e um caixa de [VALOR_EM_CAIXA_ATUALIZADO]"
- ATENÇÃO: EM TODAS AS MENSAGENS APRESENTADAS NÃO É PERMITIDO FAZER A APRESENTAÇÃO DESTA STRING USANDO CONCATENAÇÃO COM O SINAL DE +
