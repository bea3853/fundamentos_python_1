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


<img width="511" alt="PEMDAS" src="https://github.com/user-attachments/assets/bc011fe6-2b14-4e88-9aad-cc202687864d">


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

REPOLICAÇÃO  * 

























