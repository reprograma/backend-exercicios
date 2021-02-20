## Estruturas de Repetição

1. Calcule a potência de 2 elevado a um número específico. Deve usar um loop (não usar `Math.pow()`).

1. Crie uma função que determina se um número é primo e retorne true ou false conforme o caso. Em matemática, um número primo é um número natural maior que 1 que é divisível somente por ele mesmo e 1. Utilize o operador módulo (`%`) para determinar se um número é divisível por outro.

1. Faça um programa que peça uma nota, entre zero e dez. Mostre uma mensagem caso o valor seja inválido e continue pedindo até que o usuário informe um valor válido.

1. Faça um programa que leia um nome de usuário e a sua senha e não aceite a senha igual ao nome do usuário, mostrando uma mensagem de erro e voltando a pedir as informações.

1. Crie um programa que pergunta seu nome. Depois que digitar o nome, o programa deverá responder 'Olá [nome]'. Enquanto digitar qualquer palavra, imprima na tela o que foi digitado mas avise que, para sair, é só dizer 'Tchau'. O programa vai dizer 'Tchau [nome]' e finalizar.

1. Imprima na tela os números pares existentes entre 0 e 100.

1. Crie uma função que receba dois números e exiba no console uma contagem regressiva entre eles, contando de dois em dois números. Por exemplo: recebendo o número inicial 20 e o final 0, a função deverá imprimir em sequência 20 18 16 14 12 10 8 6 4 2 0. Extra: Verifique se o primeiro número é maior do que o primeiro antes de tentar mostrar a sequência.

1. crie uma função que receba um número qualquer devolva o seguinte padrão como resultado (inclusive com os espaços). Por exemplo, caso receba o número 6 como parâmetro:

```
*
**
***
****
*****
******
```

1. Refaça o exercício acima, porém agora com o seguinte padrão:

```
     *
    **
   ***
  ****
 *****
```

1. Seu Miguel da vendinha da esquina, não sabe multiplicar. Faça para ele um programa que dado um número, print (console.log) a tabuada do mesmo de 1 a 10.

1. Dados dois números calcule o MDC deles.

1. Faça um algoritmo que imprima a soma dos números múltiplos de 3 e 5, menores que 1000.

1. Faça um programa que leia 5 números e informe o maior número.

1. Para calcular o fatorial de um número, você multiplica todos os números menores que ele até 1. Por exemplo, 10! = 10 * 9 * 8 * 7 * 6 * 5 * 4 * 3 * 2 * 1. Faça um algoritmo que dado um número calcule o fatorial do mesmo.

1. Escreva um algoritmo que printe o seguinte padrão no console:

```
1
22
333
4444
55555
```

1. Crie um algoritmo que dados dois números calcule o MMC (Mínimo Múltiplo Comum)

1. Escreva um loop em Javascript que printa o seguinte padrão no console:

```
1******
12*****
123****
1234***
12345**
123456*
1234567
```

## Arrays

1. Faça um programa que leia 5 números e informe o maior número, utilizando um array.

1. Faça um Programa que leia um array de 5 números inteiros e mostre-os.

1. O Departamento Estadual de Meteorologia lhe contratou para desenvolver um programa que leia as um conjunto indeterminado de temperaturas, e informe ao final a menor e a maior temperaturas informadas, bem como a média das temperaturas.

1. Em uma competição de ginástica, cada atleta recebe votos de sete jurados. A melhor e a pior nota são eliminadas. A sua nota fica sendo a média dos votos restantes. Você deve fazer um programa que receba o nome do ginasta e as notas dos sete jurados (um array) alcançadas pelo atleta em sua apresentação e depois informe a sua média, conforme a descrição acima informada. As notas não são informados ordenadas. Um exemplo de saída do programa deve ser conforme o exemplo abaixo:

>Resultado final:
>
>Atleta: Aparecido Parente
>
>Melhor nota: 9.9
>
>Pior nota: 7.5
>
>Média: 9.04

1. Faça uma função que receba uma quantidade x e retorne um array com x números randomicos.

1. Faça um algoritmo que sortei cara (0) ou coroa (1) n vezes. E no fim mostre quantas vezes deu cara e quantas coroa.

1. Pangrama é uma frase que possui todas as letras do alfabeto. Faça um algoritmo que verifique se uma frase é um pangrama ou não. (Sem Regex)

1. Escreva um programa que faça o seguinte:
     - pergunte para a usuária o sabor a ser cadastrado
     - se a usuaria digitar 0, imprima a lista de sabores que ela cadastrou e saia do programa.

1. Baseado no código do exercício anterior, 2screva uma função que recebe 2 parametros: array e número.   Você deverá usar um laço de repetição para remover do array a quantidade exata passada como parametro da função.

Por fim, imprima no console o array modificado pela sua função
Exemplo:

```javascript
let sorvetes = ["Chocolate", "Creme", "Iogurte"];

removeSabor(sorvetes, 2);

console.log(sorvetes);
// retorna ["Chocolate]
```

1. Crie um array de preços com as seguintes informações:

- 1.23,
- 48.11,
- 90.11,
- 8.50,
- 9.99,
- 1.00,
- 1.10,
- 67.00

Altere o preço do 1°, 3°, 7° elemento.

1. Decidimos renovar o sabor de alguns sorvetes.

```javascript
let sorvetes = [
  "Coco",
  "Maracujá",
  "Abacaxi",
  "Baunilha",
  "Tangerina",
  "Doce de Leite",
  "Iogurte de frutas vermelhas",
  "Melancia",
  "Chocolate",
  "Chocolate Belga",
  "Torta de limão",
];
```

Precisamos que você retire do cardápio o sabor `Iogurte de frutas vermelhas` e acrescente os sabores `Paçoquita` e `Passas ao rum`.

1. Utilize o array do exercício anterior para fazer este exercício. Faremos um evento corporativo e por isso reduziremos nosso cardápio, levando apenas os 3 primeiros sabores da nossa lista. Remova todos os outros sabores.

1. Considere o seguinte array:

```javascript
let sabores = ["Limão", "Milho", "Napolitano", "Maracujá"];
```

Escreva uma funcão chamada `topissimos()` que recebe um array como parâmetro.

Retorne `true` ou `false` dependendo de o array ter pelo menos 5 sabores.

> dica: Modifique o array para validar se sua função está retornando o valor correto.

Imprima no console o resultado.

1. Use estruturas de controle para inverter uma array de inteiros. A função deverá receber uma array de números e retornar uma array com a ordem dos elementos invertida. Não é válido utilizar `arr.reverse()`.

1. Usando um loop, crie uma matriz 4 x 4, com valores de 1 a 16.