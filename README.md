# JSExercicio1

O arquivo main.js contém um array com informações de 150 empresas de um conglomerado, cada empresa contém a seguinte estrutura de objeto:

{
  nome: "NOME DA EMPRESA",
  endereco: "RUA FULANO, 100",
  caixa: TOTAL QUE A EMPRESA POSSUI EM CAIXA (valor inteiro)
  lucro: TOTAL QUE A EMPRESA APRESENTOU DE LUCRO NESTE MÊS DE MARÇO (valor inteiro)
}

Utilizando o arquivo main.js deste repositório você deve alterá-lo para apresentar os seguintes resultados no terminal:

- Trazer um array com todos os elementos de um array de objetos que tenham lucro de vendas acima de 7000
- Criar um array apenas com os valores de lucro de todas as lojas
- Usar o array gerado no passo anterior para somar o total de vendas de todas as lojas
- Aplicar um bonus de 1000 reais ao caixa para cada loja que teve um lucro de vendas acima de 9000
- Apresentar um resumo com o nome da loja e total em caixa em um texto no seguinte formato:
    - "A loja [NOME_DA_LOJA] apresentou um lucro de vendas de [TOTAL_DE_VENDAS]"
- ATENÇÃO: EM TODAS AS MENSAGENS APRESENTADAS NÃO É PERMITIDO FAZER A APRESENTAÇÃO DESTA STRING USANDO CONCATENAÇÃO COM O SINAL DE +
