## Objetos

1. Crie um objeto `lunch` para representar o seguinte item do menu:

    ```
    Feijoada - R$12,99
    arroz, feijão, couve refogada, linguiça, farofa
    ```

    O objeto deve conter propriedades para `name`, `price` e `ingredients`.

1. Conta no banco
    ```javascript
    let contaCorrente = {
      saldo: 1000,
      taxaDeJuros: 1,
      depositar: function adicionarDinheiros(qtde) {
        if (qtde > 0) {
          contaCorrente.saldo += qtde;
        }
      },
      sacar: function retirarDinheiro(qtde) {
        var saldoDisponivel = contaCorrente.saldo - qtde;
        if (qtde > 0 && saldoDisponivel >= 0) {
          contaCorrente.saldo -= qtde;
        }
      },
    };
    ```

    adicione um método `imprimirExtrato()` que retorne a seguinte mensagem de conta:

    ```
    Olar!
    Seu saldo atual é de R$1000 e sua taxa de juros é de 1%.
    ```

1. Usando o objeto do quiz anterior, responda à seguinte pergunta: Quais são as maneiras válidas para acessar propriedades e chamar métodos de um objeto chamado contaCorrente?

1. Crie um objeto chamado `facebookProfile`. O objeto deve ter três propriedades:
    - seu nome (`name`)
    - o número de amigos (`friends`) que você tem e
    - um array de mensagens (`messages`) que você postou (como strings)

    O objeto deve também possuir quatro métodos:
    - postMessage(`message`) - adiciona uma nova mensagem em formato de string na array
    - deleteMessage(`index`) - remove a mensagem correspondente ao índice fornecido
    - addFriend() - aumenta a contagem de amigos em 1
    - removeFriend() - diminui a contagem de amigos em 1

1. Crie uma função que receba 3 parâmetros: o nome de um livro, a quantidade de páginas e a autoria. Retorne um objeto no formato: {titulo: "nome do livro", paginas: "número de páginas", autoria: "nome da pessoa"}``. Exemplo: 

    ```
    objLivro('Antes do Baile Verde', 234, 'Lygia Fagundes Telles') 

    // retorna o objeto:

    {
      titulo: 'Antes do Baile Verde', 
      paginas: 234,
      autoria: 'Lygia Fagundes Telles'
    }
    ```

1. Aproveite a função acima em outra função, que deve retornar a seguinte frase: "O livro XXXX foi escrito por XXX e tem XXX páginas". Você deve utilizar a função que já está pronta, e não reescrever a lógica dela dentro dessa nova função.

1. Crie uma função que receba um objeto como o abaixo:
    ```
    const pessoa = {
      nome: 'Nazaré',
      sobrenome: 'Tedesco',
    }
    ```
    Dado um objeto que tem uma propriedade 'nome' e uma propriedade 'sobrenome', a função deve retornar um novo objeto com as mesmas propriedades que o objeto recebido e mais uma propriedade, chamada 'nomeCompleto', cujo valor é uma string com o nome e sobrenome separados por um espaço. Exemplo de retorno:
    ```
    {
      nome: 'Nazaré',
      sobrenome: 'Tedesco',
      nomeCompleto: 'Nazaré Tedesco'
    }
    ```

1. Crie uma função que receba o objeto abaixo e o nome de uma das chaves, e retorne a soma de todos os elementos do array que for selecionado através da chave.
    ```
    const objArrays = {
      array1: [1, 2, 3],
      array2: [5, 6, 7, 8],
      array3: [9, 9, 9],
    }
    ```

1. (Alerta de questão grande) Declare uma constante `pessoa`, que receba suas informações pessoais. As propriedades e tipos de valores para cada propriedade desse objeto devem ser: `nome - String; sobrenome - String; idade - Number; altura - Number; peso - Number; andando - Boolean; caminhouQuantosMetros - Number`
    - Adicione uma função ao objeto `pessoa` chamada `fazerAniversario`. A função deve alterar o valor da propriedade `idade` dessa pessoa, somando `1` a cada vez que for chamado.
    - Adicione um método ao objeto `pessoa` chamado `andar`, que terá as seguintes características: (1) Esse método deve receber por parâmetro um valor que representará a quantidade de metros caminhados; (2) Ele deve alterar o valor da propriedade `caminhouQuantosMetros`, somando ao valor dessa propriedade a quantidade passada por parâmetro; (3) Ele deverá modificar o valor da propriedade `andando` para o valor booleano que representa "verdadeiro";
    - Adicione um método ao objeto `pessoa` chamado `parar`, que irá modificar o valor da propriedade `andando` para o valor booleano que representa "falso".
    - Crie um método chamado `nomeCompleto`, que retorne a frase: "Olá! Meu nome é [NOME] [SOBRENOME]!"
    - Crie um método chamado `mostrarIdade`, que retorne a frase: "Olá, eu tenho [IDADE] anos!"
    - Crie um método chamado `mostrarPeso`, que retorne a frase: "Eu peso [PESO]Kg."
    - Crie um método chamado `mostrarAltura` que retorne a frase: "Minha altura é [ALTURA]m."
    - Faça a `pessoa` fazer 3 aniversários.
    - Quantos anos a `pessoa` tem agora? Mostre no console.
    - Faça a `pessoa` caminhar alguns metros, invocando o método `andar` 3x, com metragens diferentes passadas por parâmetro.
    - Mostre quantos metros a pessoa andou. Verifique se ele ainda está andando e se estiver, pare a pessoa!
    - Crie um método chamado `mostrarDistancia` que retorne a frase: "[NOME] caminhou [caminhouQuantosMetros]m"
    - Crie um método para o objeto `pessoa` chamado `apresentacao`. Esse método deve retornar a string: "Olá, eu sou [NOME COMPLETO], tenho [IDADE] anos, [ALTURA], meu peso é [PESO] e, só hoje, eu já caminhei [CAMINHOU QUANTOS METROS] metros!". Certifique de usar singular ou plural para anos e metros.
