Pos e Neg
a = int(input())

if a >= 0:
    print("positivo")
else:
    print("negativo")


Dobro 

a = int(input())

print(a * 2)


mostrar

a = input()

print("Valor:", a)
print("Tipo:", type(a))


par ou impar

a = int(input())

if a % 2 == 0:
    print("par")
else:
    print("impar")


texto

a = input()
a = int(a)

print(a * 3)

maior 2 número 

a = int(input())
b = int(input())

if a > b:
    print(a)
else:
    print(b)


maior que 10 n

a = int(input())

if a > 10:
    print("Maior que 10")
else:
    print("Menor ou igual a 10")


raiz

a = int(input())

if a >= 0:
    print(a ** 0.5)
else:
    print("Número inválido")


metade

a = float(input())

print(a / 2)


10 - dentro interv

a = int(input())

if a >= 0 and a <= 10:
    print("Dentro do intervalo")
else:
    print("Fora do intervalo")
    
    
11 - par posi neg

a = int(input())

if a % 2 == 0:
    if a > 0:
        print("Par positivo")
    else:
        print("Par negativo")
else:
    print("Impar")


12 - soma

a = int(input())
b = int(input())

soma = a + b
print("Soma:", soma)

if a > b:
    print("A é maior")
elif b > a:
    print("B é maior")
else:
    print("São iguais")

    
13 - a = int(input())

if a > 100:
    print(a / 2)
else:
    print(a * 2)


14 - a = input()
a = int(a)

if a % 3 == 0:
    print("Múltiplo de 3")
else:
    print("Não é múltiplo")


 15-    intervalo 

 a = int(input())

if a >= 10 and a <= 20:
    print("Dentro")
else:
    print("Fora")

    
16- a = input()

print("Tipo:", type(a))

# tentativa de conversão
if a.isnumeric():
    a = int(a)
    print(a ** 2)


17 - classi idade

idade = int(input())

if idade < 18:
    print("Menor de idade")
elif idade <= 59:
    print("Adulto")
else:
    print("Idoso")


19- igual diferença

a = int(input())
b = int(input())

if a == b:
    print("Iguais")
else:
    print("Diferença:", abs(a - b))


18- compl classificação 

a = int(input())

if a == 0:
    print("Neutro")
elif a % 2 == 0:
    if a > 0:
        print("Par positivo")
    else:
        print("Par negativo")
else:
    if a > 0:
        print("Impar positivo")
    else:
        print("Impar negativo")



20- fora do inter

a = int(input())

if a < 0 or a > 100:
    print(a)


21- 

a = int(input())

if a > 0:
    if a % 2 == 0 and a % 3 == 0:
        print("Múltiplo de 2 e 3")
    else:
        print("Não atende")
else:
    print("Número inválido")


    
22 -

a = input()

if a.isnumeric():
    a = int(a)
    if a > 10:
        print("Alto")
    else:
        print("Baixo")
else:
    print("Entrada inválida")


23 -

a = int(input())
b = int(input())
c = int(input())

# ordenando
lista = [a, b, c]
lista.sort(reverse=True)

print(lista)
print("Resto da divisão do 3º por 3:", lista[2] % 3)


24 -
a = int(input())

if a >= 1 and a <= 100:
    if a % 2 == 0:
        print("Par no intervalo")
    else:
        print("Ímpar no intervalo")
else:
    print("Fora do intervalo")


    
25
a = input()

try:
    a = float(a)
    print(a / 2)
except:
    print("Não numérico")


26
a = int(input())

if a < 0:
    print("Negativo ou zero")
elif a <= 10:
    print("Pequeno")
elif a <= 100:
    print("Médio")
else:
    print("Grande")


27-
 a = int(input())
b = int(input())
c = int(input())

soma = 0

if a > 0:
    soma += a
if b > 0:
    soma += b
if c > 0:
    soma += c

print("Soma:", soma)


28- 
a = input()

try:
    if "." in a:
        num = float(a)
        print(num / 2)
    else:
        num = int(a)
        print(num * 2)
except:
    print("Tipo inválido")


29-
a = int(input())

if a % 5 == 0:
    if a > 50:
        print("Múltiplo alto")
    else:
        print("Múltiplo baixo")
else:
    print("Não é múltiplo")

 
 30 -
 a = input()

try:
    a = int(a)
    
    if a % 2 == 0:
        if a > 100:
            print("Par alto")
        else:
            print("Par baixo")
    else:
        print("Ímpar")
        
except:
    print("Entrada inválida")

































