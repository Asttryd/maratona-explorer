RESUMO DAS LINGUAGENS DE FRONT END


# HTML
- Hypertext Markup Language

- Hiper Texto: 
- Marcação
  - tags
    - atributos
- Linguagem
  - maneira de escrever

# CSS
  #Declaração
  - Seletor
  - Propriedade e valor

  #Conceitos
  - Cascata
  - Especificidade
  - Box Model:
    > Tudo são caixas
    > Caixas possuem determinadas propriedades
  - Display block vs inline
    > Display block: os elementos serão apresentados em colunas
    > Display inline: os elementos serão apresentados um do lado do outro (automático)

  Especificidade > Cascata

# JavaScript

  1. Variáveis
    atribuir um valor em um espaço na memória
    > let: o valor pode ser alterado em qualquer momento posterior
    (true/false)
    > const: o valor não pode ser alterado uma vez que foi definido
    (const meuNome = 'Pacheco')
    (Uma vez que a const meuNome está definida como 'Pacheco', não poderá ser alterada para qualquer outra coisa além de 'Pacheco')

  2. Tipos de Dados

    > String: todo texto que precisa ser adicionado entre "" ou ''

    > Number:
      números inteiros (12) = Integer (+ -)
      números decimais (3.2) = Float (+ -)

    > Boolean:
      true | false
      undefined - indefinido

      ex: const maiorDeDezoito = false

  3. Operadores:
    -Atribuição (ex: =)
      atribui valor
      let n1 = 12
      let n2 = 3

    -Aritméticos (ex: * / + - )
      *cálculos aritméticos simples
        console.log (x * y)

      *Concatenação de String (+)
        console.log("23" + 4 + "abc")

      *comparação: (ex: > < ==)
        transforma a expressão em true ou false
          const maiorQue = 1 > 2 (false)
          const igualA = 1 == 1 (true)

  4. Condicional (if/else)
      const idade = 17
      const maiorDeDezoito = idade >= 18

      if(maiorDeDezoito) {
        alert("Pode tirar carteira de motorista")
      } else {
        alert("Não pode tirar")
      }

  5. Estrutura de Dados
    > Array - Vetor - Lista
    > Array --------       0     1    2  3
    const temperaturas = [23.3, 32.2, 1, 5]
    console.log(temperatura[1,2,3...])

    const pessoa = {
      nome: "Mayk",
      idade: 38,
      filhos: ["K", "E", "J", "L", "G"]
    }
    console.log(pessoa.filhos[3])
  
  6. Function
    1. Criação
    function nomeDaFuncao() {
      console.log('código dentro da função')
    }
  
  7. Extensões da Linguagem (ex: Math, Date ...)

    Math.random()
    Math.floor(1.2)
    Math.ceil(1.2)
    Math.PI

  8. DOM - Document Object Model

    window
    window.alert("alerta")
    document
    document.write("texto")
    manipular elementos
    document.documentElement.style.background = "black"

    2. Execução
      nomeDaFuncao()

    Parâmetros
      function soma(a, b) {
        return a + b
      }
      console.log(soma(2, 2))
  
bola de cristal:

  https://gist.githubusercontent.com/maykbrito/0acdf4ce919838ffed50915a31fc5b23/raw/6f4dd01ec3116428ec4c99255944cb9ac7927590/cristal-ball.svg