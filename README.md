# Fundamentos_python_1
### Função - print()

PARÂMETROS DO PYTHON:

SEP - END  -  ARGUMENTOS 

<img width="606" alt="PRINT" src="https://github.com/user-attachments/assets/36029c7f-cafc-4803-aa5a-182afc30f74c">

ou 

print(objeto(s), argumentos_de_palavra-chave)

Parâmetros

<img width="606" alt="parametros" src="https://github.com/user-attachments/assets/87cbf4cf-0aa0-473c-8f27-52d3972a6ce5">

separador para milhar, melhorar a leitura 

n = 1_0_0_0_0_0
print(n)



# NÚMEROS COMPLEXOS

Incorpora todas as possibilidades numeração, mais utilizado em física quântica, matemática esttistica.

c = 10j+25

type(c)



# CARACTERES DE SCAPE 



\n  NOVA LINHA - pular linha 
\t  TABULAÇÃO - espaço
\u  UNICODE - 


(Tabela unicode  -  16 bits)

print('Eu \u2764 Python')

tabela unicode:

2 ** 16 -  Tabela unicode 

https://symbl.cc/pt/unicode-table/#box-drawing

CÓDIGOS ESPECIAIS UTILIZADOS DENTRO DE STRINGS

print("\n\tTeste\n123)


# *************************
                Teste
123
# *************************


# DOCUMENT STRINGS

'''   cria uma memória temporária   '''


# CADEIA DE CARACTERES 

print('\')

\ - Especifico para fazer algo, é uma palavra reservada.  


# SISTEMA DE NUMERAÇÃO

10 - DECIMAL

É como representar um valor em outras notações.

0b10 - BINÁRIO

0o10 - OCTAL

ox10 - HEXADECIMAL

PARA RECEBER UM VALOR EM QUALQUE OUTRA NOTAÇÃO E CONVERTER

bin()

oct()

hex()

exemplo:

descobrir o binário de 10

bin(10)

# SOBRE O BIN

A = 6
print(bin(A))  # Isso funcionará, já que A é um inteiro.

A = A / 6     # A agora é um float.

B = A         # B também será um float.

C = bin(int(B))  # Converte B para int antes de usar bin().

print(C)  # Isso imprimirá o resultado da conversão.






# NOTAÇÃO CIENTIFICA

x = .00006

print(x)

6e-05


## PEMDAS 

https://science.howstuffworks.com/math-concepts/PEMDAS.htm 



![PEMDAS - Página 1](https://github.com/user-attachments/assets/4e30ded9-757c-41b8-bfe8-68f8071a1a2c)


# LIGAÇÃO  À DIREITA 

PARA POTENCIA PREVALECE A LIGAÇÃO  DA DIREITAPARA ESQUERDA 
 -  \*   /     //     %

  

# LIGAÇÃO A ESQUERDA 

OPERADORES IGUAIS 
 - (+)

# EXEMPLO:

N =  (5 * ((25%13)+100)/(2*13)//2)

print(N)


# CONCATENAÇÃO 

 -  FORMAT
 -  F-STRING
 -  %
 -  ,
 -  +

# DIR()

b = 10
A  = TYPE(b)
dir(A)

# CURIOSIDADE

print = 10

print() para de funcionar - GERA UM ERRO

# FUNÇÃO ID

VERIFICA O ENDEREÇO DA VARIÁVEL NA MEMÓRIA.

A LOCAÇÃO DE MEMÓRIA É DINÂMICA E A TIPAGEM TAMBÉM.  

n = 10
id(n)
##### saida 10869672

# OPERADORES DE ATALHO

+=  | -= | *= | /= | //= | %= | **=

INCREMENTO, DESCREMENTO ... 

> Todo dado digitado no teclado é uma string

> A int() vai tentar converter uma String para um número inteiro

> float() vai tentar converter para um número real

b = 'text'

c = float(b)

print(c) 

##### saída ValueError: could not convert string to float: c

# FUNÇÃO INPUT()

peso   =  float(input('>>'))

altura =  float(input('>>'))

imc    =  peso/altura ** 2

print(f'IMC: {imc:.2f}')

print(f'IMC: {round(imc, 1)}')


# LIMPAR O TERMINAL (automatização)

from click import *

clear()

# SINAL DE MULTIPLICAÇÃO  (*) 

Ele replica a string o mesmo número de vezes especificado pelo número.

Por exemplo:

"James" * 3 gera "JamesJamesJames"

3 * "an" gera "ananan"

5 * "2" (or "2" * 5) gera "22222" (não10!)

# OPERAÇÕES COM STRING

CONCATENAÇÃO  + , F-STRING , %, FORMAT, (,) 

# CONDICIONAIS 

Condicionais simples 

Condicionais Compostas

If -  Else -  Elif


# MATCH CASE

idade  =  int(input('>>'))

match idade:

    case 18:

        print('maior de idade')

    case 65:

        print('idoso')

    case 'x' | 'z':

        print('geraçoes')

    case _:

        print('adulto')


O operador | é um operador bit a bit em Python, usado para realizar operações em nível de bits. Quando você usa |, o Python tenta realizar uma operação bit a bit entre dois valores booleanos, o que pode não produzir o resultado esperado em uma condição de teste lógico.

Por outro lado, o or é o operador lógico apropriado para combinar condições booleanas. Aqui está um resumo:

- |: Operador bit a bit. Usa-se para operações entre bits (ex: 1 | 0 resulta em 1).
- or: Operador lógico. Avalia se pelo menos uma das condições é verdadeira.

Portanto, para verificar se a idade é 10 ou 15, você deve usar or. Se usar |, o código pode não funcionar como esperado.

Quando usar cada um?

- Use 'if' quando:

Você está lidando com condições simples ou complexas.

Não precisa verificar muitos casos diferentes.

- Use 'match' case quando:

Você precisa comparar um valor contra múltiplos casos.

Está lidando com padrões complexos e deseja uma sintaxe mais clara.


# FOR

- Para frequências finitas


for i in range(1,5):

    print(i)

A variável i recebe todos os valores menos o valor que etsá sendo expressado. 

for n in range(0,19,3):
   
    print(n)

saída

0
3
6
9
12
15
18

for n in range(6):

    print(n)





    


# WHILE

- Para frequências inifinitas 

c  =  0

while c <=10:

    print(c)
    
    c += 1

    

# OPERADORES BIT A BIT (BITWISE)

&               and
|               or
^               xor
~               not

# AND

Como estarão as operações bit a bit com and

4   &    10

# divisão binária

o resto até subir

10%2 = 0

5%2 =  1 ...


#### bit a bit

x = 4 | 10

print(x)

z  = 12 & 8

print(z)

linguagem binária

https://teleeducacao.weebly.com/bitbyte.html 

![image](https://github.com/user-attachments/assets/986c6ff4-2162-4b8b-941a-80e6c8e7a7db)

JOGO BINÁRIO:

https://www.ime.unicamp.br/sites/default/files/lem/material/clubinho_de_matematica_-_jogo_dos_cartoes_binarios.pdf


# ~ NOT

NOT -  SOMA 1 E COLOCA NEGATIVO
~ 5

### saída: - 6

~ - 5

### saída:  4

# OPERADORES DE DESLOCAMENTO

>> A ESQUERDA
<< A DIREITA

10 << 2  = 40

1  -  TRANSFORMA O PRIMEIRO VALOR EM BINÁRIO  -  1010

2  -  DESLOCA UMA CASA A FRENTE - 101000

3  -  CONVERTER PARA DECIMAL -  32 16 8 4 2 1  = 40
      
                                   .    . . .

Se desloca para a esquerda vai aumentar
testando:x = 2<<3

1 0**2 0**2 0**2 0**2

ou

2 * 2 ** 3 = 16 

# AO CONTRARIO

15>>3

1111

# LISTAS 

Estrutura composta, que pode ser do tipo, homogenea, heterogenea ou mista...

Possui indexação, pode ser acessada da esquerda p/ direita e da direita p/ esquerda.

Não se comportam como as arrays do Java, por exemplo. 

Devido ser mutável, flexivel ... 


# DIR -  PARA MOSTRAR TODAS AS POSSIBILIDADES DE UTILIZAÇÃO DO OBJETO

lista = [1, 2, 3]

print(dir(lista))

Documentação lista:

https://docs.python.org/pt-br/3/tutorial/datastructures.html#list-comprehensions



# LEN

função de comprimento ...

l = ['maçã', 'banana','pera']

x = l.__len__()

print(x)
........................................

frutas.__len__()

frutas.len()

### Curiosidade:

terminal interativo não precisa de print()***

# LIST COMPREHESION

l = [i for i in range(1,6)]

l = [i for i in range(0,21,2) ]
print(l)

# RANDOM 

import ramdom



# ALIAS 

as 

#







                                   

        

























