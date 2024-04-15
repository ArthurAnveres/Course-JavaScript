## Aprendendo JavaScript



# Tipos de dados e variáveis em JavaScript

Como guardar dados para usar mais para frente

Focar em uso de comentarios no código:
tipos de comentarios em javascript: // e /* */

# Como criar alerta em JavaScript

window.alert para criar um alerta de mensagem
window.confirm para criar um alerta de confirmação
window.prompt para criar um alerta que exige um texto do usuario

# Regras dos Identificadores em JavaScript

Podem começar com letra, $ ou _
Não podem começar com números
É possível usar letras ou números
É possível usar acentos e símbolos
Não podem conter espaços
Não podem ser palavras reservadas

# Dicas para identificadores

Maiúscula e minúscula fazem diferença
Tente escolher nomes coerentes para as variáveis.
Evite se tornar um 'programador alfabeto' ou um 'programador contador'

# Tipos de variaveis

Number para números tanto inteiros como flutuantes
Number possui Infinity e NaN

String usado para palavras ou números como cpf, telefone, rg.
Boolean usado como falso ou verdadeiro
Null
Undefined
Object
Array
Function

Comando para usar os tipos de variaveis é typeof

# Soma e contatenação

o + pode servir para contatenação quanto para soma
para o + ser de soma tem de ser number + number
para contatenação tem de ser string + string

# Converter valores String para int e float

Number.parseInt(n) para converter para inteiro
Number.parseFloat(n) para converter para número em ponto flutuante
Ou somente Number para deixar o JavaScript decidir

# Converter de number para String

String()

# Formatando Strings
var s = 'JavaScript'
'Eu estou aprendendo s' // não faz interpolação
'Eu estou aprendendo' + s // faz concatenação
`Eu estou aprendendo ${s}` // usa template string

s.lenght  // quantos caracteres a string tem
s.toUpperCase() // tudo para 'MAIÚSCULAS'
s.toLowerCase() // tudo para 'minúsculas'

# Formatando números

n1.ToFixed(2) para fixar a casa decimal
n1.toFixed(2).replace('.', ',') para alterar a casa decimal de '.' para ','
n1.toLocaleString('pt-BR', {style: 'currency', currency: 'BRL'}) serve para localizar para real ou qualquer moeda do país de escolha.

# Tipos de operadores

aritméticos (+, -, *, /, %, **) segue as regras de precedência da matemática. a ordem é:
()
**
* / %
+ -

incremento // soma 1 ao valor da variavel
i++ pos incremento
i-- pos decremento
++i pre incremento
--i pre decremento

relacionais // darão resultados booleanos:
5 > 2 = true
7 < 4 = false
8 >= 8 = true
9 <= 7 = false
5 == 5 = true
5 === '5' = false
4 != 4 = false
4 !== '4' = true

lógicos
! negação é true ou false

&& conjunção
true + true = true
true + false = false
false + true = false
false + false = false

|| Disjunção
true + true = true
true + false = true
false + true = true
false + false = false

# Ordem de precedência:

operadores aritmêdicos:
()
**
/
ordem dos operadores relacionais:
>
<
>=
operadores lógicos:
!
&&
||

operador ternário

teste ? true : false

média>=7.0 ? "aprovado" : "reprovado"

# Document Object Model
Modelo de objetos dentro do navegador que dara acesso a documentos internos do navegador



# Árvore DOM
dentro da window tem o location, document, history
dentro de document possui o html que possui o head e o body

posso acessar por:
Marca = getElementsByTagName() para escolher um em especifico abrir [] e colocar o vetor
ID = getElementById()
Nome = getElementsByName()
Classe = getElementsByClassName()
Seletor = querySelector() e querySelectorAll()

[Exemplos práticos de uso](aula2\ex005.html)

# Eventos DOM
Eventos que podem ocontecer com mouse:
mouseenter
mousemove
mousedown
mouseup
click
mouseout

# Funções
as funções são feitas da seguinte maneira:
function ação(param){

}

# Condições

Sequências deve seguir em sequência os comandos Ex de condição:
comando 1
comando 2
comando 3

