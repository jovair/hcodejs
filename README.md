# Developer JavaScript

## IA01 JD Introdução

### Principais assuntos

* Introdução ao curso falando de sua estrutura;
* Enfase na importância das anotações e repetição da escrita do código para fixação.

## LD01 JD Algoritmo

### Principais Assuntos

* Introdução à logica de programação;
  * Algoritmo - Conjunto de regras e procedimentos lógicos perfeitamente definidos que levam à solução de um problema em um número finito de etapas.
    * Algoritmo fósforo - decisão simples verificando se o fósforo acendeu ou não para tomar uma nova ação;
    * Algoritmo semáforo - decisão mais complexa que requer mais de uma verificação, dependendo da luz exibida pelo semáforo para saber qual ação tomar.

## LD02 JD Pseudo Código

O prefixo "pseudo" é usado para marcar alguma coisa como sendo superficial, ou seja, que parece ser uma coisa, mas na verdade é outra.

Pseudocódigo é uma forma genérica de escrever um algoritmo que parece ser um código de computador, mas que utiliza uma linguagem simples e nativa a quem o escreve.

Para nós, nativos em Português do Brasil utilizamos o Português Estruturado, também conhecido como Portugol.

## LD03 - JD Teste de Mesa

O Teste de Mesa é um processo manual que é utilizado para validar a lógica de um determinado algoritmo. Ele é utilizado principalmente em algoritmos quando a linguagem utilizada não possui nenhuma ferramenta automatizada de depuração. Como as linguagens de programação costumam possuir tais ferramentas, é mais comum utilizá-las a fazer o teste de mesa propriamente dito, embora para quem ainda é iniciante.

## LD04 - JD Hcode Challenge Fritando um Ovo e Trocando um Pneu de um Carro

* Tarefa para o futuro

## LD05 JD Tipos de Programas

* Compilado;
* Interpretado;
* Pseudo Compliado;
* JIT (Just in Time)

### Compilado

É uma linguagem de programação em que o código fonte é executado diretamente pelo sistema operacional ou pelo processador, após ser traduzido por meio de um processo chamado compilação, usando um programa de computador chamado compilador, para uma linguagem de baixo nível, como linguagem de montagem ou código de máquina.

### Interpretado

É uma linguagem de programação em que o código fonte nessa linguagem é executado por um programa de computador chamado interpretador, que em seguida é executado pelo sistema operacional ou processador.

### Pseudo Compilado

Quando um cóadigo passa pelo processo de compilação, mas mesmo assim o resultado precisa de um interpretador para resultar no código que será executado diretamente pelo sistema operacional ou processador.

### JIT

Just in Time, Também conhecida como tradução dinâmica é quando a compilação de um programa é feita em tempo de execução, ou seja, apenas na hora de usar o programa.

## LD06 JD Variáveis de Memória

É uma posição ou espaço localizado na memória do computador. Pode reter e representar um valor ou expressão. Esses valores são armazenados apenas em tempo de execução e possuem identificadores ou nomes para serem usados ou chamados durante o desenvolvimento do código.

### Tipos de variáveis

* Locais;
* Globais;
* Constantes.

## LD07 JD Tipos de dados

### Tipos de dados primitivos

* Número Inteiro;
* Número Decimal;
* Texto;
* Lógico.

#### Inteiro

É um número que pode ser escrito sem um componente fracional. Por exemplo, 0, 1, 2, 50, 100 e -2048 são numeros inteiros.

#### Decimal

São númerais que se usa uma vírgula, indicando que o algarismoa seguir pertence à ordem das décimas, ou casas decimais. Por exemplo 1,5 2,3 e assim por diante.

#### Texto

Texto são todos os caracteres possíveis como letras, números, pontuações, caracteres especiais e outros. Em algumas linguagens a variável pode ser identificada como string, ou ainda, char, que representa apenas um caracter do tipo texto.

#### Operador Lógico

Possui dois valores possíveis: verdadeiro e falso, sendo possível também usar os valores 0 para falso e 1 ou qualquer outro valor para verdadeiro. O caractere 0 indica que o valor lógico é falso, mas o valor verdadeiro pode ser representado por qualquer outro valor, não somente o 1.

## Operadores

Operadores são expressões que utilizamos para executar uma ação em nossos dados.

Essa ação pode ser: atribuir um valor a uma variável; realizar alguma conta matemática com este valor ou verificar se alguma condição é verdadeira.

### Tipos de operadores

* Atribuição;
* Aritmético;
* Comparação;
* Lógico;
* BIT A BIT;
* String.

#### Atribição

Este operador atribui um valor ao operando à sua esquerda, baseado no valor do operando à direita.

Nome                            | Operador  | Exemplo       | Resultado
:------------------------------ | :------:  |:------------: | :---------
Atribuição                      | =         | `idade = 1`     | A variável "idade" receberá o valor numérico um
Atribuição de adição            | +=        | `idade += 1`    | A variável "idade" somará 1 ao seu próprio valor já existente
Atribuição de subtração         | -=        | `idade -= 1`    | A variável "idade" subtrairá 1 ao seu próprio valor já existente
Atribuição de multiplicação     | *=        | `idade *= 1`    | A variável "idade" multiplicará 1 ao seu próprio valor já existente
Atribuição de divisão           | /-        | `idade /= 1`    | A variável "idade" dividirá 1 ao seu próprio valor já existente
Atribuição de resto             | %=         | `idade %= 1`    | A variável "idade" dividirá seu próprio valor já existente por 1 e selecionará o resto da equação
Atribuição exponencial          | **= 1     | `idade **- 1`   | A variável "idade" realizará a exponenciação de seu próprio valor já existente por 1

#### Aritmético

Este operador faz um cálculo aritmético de dois números e retorna um único valor numérico.

Nome          | Operador    | Exemplo   | Resultado
:----         | :--------:  | :-------: | :-------:
Adição        | +           | `2 + 2`     | 4
Subtração     | -           | `2 - 2`     | 0
Multiplicação | *           | `2 * 2`     | 4
Divisão       | /           | `2 / 2`     | 1
Módulo        | %           | `2 % 2`     | 0
Incremento    | ++          | `++2`       | 3
Decremento    | --          | `--2`       | 1
Exponenciação | **          | `2**`       | 4

#### Comparação

Este operador realiza uma comparação entre dois valores em uma condição lógica e retorna um resultado dizendo se essa dondição é verdadeira ou não.

Nome                  | Operador      | Exemplo   | Resultado
:----                 | :--------:    | :-------: | :-------:
Igualdade             | ==            | `2 == 2`       | sim
Desigualdade          | !=            | `2 != 2`       | não
Estrita Igualdade     | ===           | `2 === 2`      | não
Estrita Desigualdade  | !==           | `2 !== 2`      | sim
Maior que             | >             | `2 > 2`        | não
Menor que             | <             | `2 < 2`        | não
Maior ou igual que    | >=            | `2 >= 2`       | sim
Menor ou igual que    | <=            | `2 <= 2`       | sim

#### Lógico

Este operador geralmente é usado em conjunto com um operador de comparação e retorna um valor booleano.
Quando há mais de uma condição para ser comparada, ele define se todas elas são verdadeiras ou se apenas uma é.

Nome      | Operador      | Exemplo   | Resultado
:----:    | :--------:    | :-------: | :-------:
E         | AND ou &&     | `true && false`       | não
OU        | OR ou II      | `true || false`       | sim
Negação   | NOT ou !      | `!true && false`      | não

#### BIT a BIT

Operadores bit a bit tratam os valores como 32 bits, ou seja, de maneira binária. Ele é útil quando precisamos trabalhar com a representação binária de números.

Nome                               | Operador       | Exemplo    |  Convertido    | Resultado
:----                              | :--------:     | :-------:  | :--------      | :-------:
E                                  | &              | `1 & 2`    | 0001 & 0010    | 000 = 0
OU                                 | `|`              | `1 | 2`    | 0001 | 0010    | 0011 = 3
XOR                                | ^              | `1 ^ 2`    | 0001 ^ 0010    | 0011 = 3
NOT                                | ~              | `~2`       | (2 + 1)* -1    | -3
Deslocamento à esquerda            | <<             | `1 << 2`   | 0001 << 2      | 0100 = 4
Deslocamento à direira             | >>             | `1 >> 2`   | 0001 >> 2      | 0000 = 0
Deslocamento à direita com zero    | >>>            | `2 >>> 2`  | 0001 >>> 2     | 0000 = 0

#### String

Além dos operadores de comparação que podem ser utilizados em valores string, temos o operador de concatenação que faz a união de duas strings e retorna apenas uma.

Nome                 | Operador        | Exemplo                    | Resultado
:----:               | :--------:      | :-------:                  | :-------:
Concatenação         | + ou & ou .     | `"Hcode" + "Treinamentos"` | "HocodeTreinamentos"

**Nota** - O operador depende da linguagem que está sendo utilizada. A maioria das linguagens utilizam o operador +, mas não todas.

## LD09 JD Variável Indexada ou Vetor

É uma estrutura de dados que armazena uma coleção de elementos de tal forma que cada um dos elementos possa ser identificado por, pelo menos um índice.
