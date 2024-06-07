range()

range(1,5)
def funcaoleitura():
    for num in [1,2,3,4,5]:
        print ("numero", num)

def funcaoleitura():
    for num in range(5):
        print("numero", num)

def addn (n1, n2):
    print ("o primeiro numero é:", n1)
    print ("o segundo numero é:", n2)
    print ("a soma numero é", n1+n2)

    varg = 10
def multiplicacao (n1,n2):
    varg = ((n1*n2))
    print("variavel da funcao multiplica", varg)
    multiplicacao(5,4)
    print(varg)

    varg = 10 
def multiplica(n1,n2):
    varloc = n1 * n2
    print ("variavel de funcao multiplica", varloc)
    print(varloc)

    def separartexto(text):
    return text.split()

    def variosparametros (*parametro):
    for n, item in enumerate (parametro):
        print ("parametro", n, item)
    return

    variosparametros("cibele", "suely", "giggio", "mada", "luquinha")

    variosparametros("pitomba", "jambo", "siriguela", "umbu")

    ("calculadora") 
def soma (n1, n2):
    return n1+n2
def subtrai (n1, n2):
    return n1-n2
def multiplica (n1, n2):
    return n1*n2
def divide (n1, n2):
    return n1/n2

    def soma(a, b):
    return a + b

def subtrai(a, b):
    return a - b

def multiplica(a, b):
    return a * b

def divide(a, b):
    if b == 0:
        return "Erro: divisão por zero!"
    else:
        return a / b
    
while True:
    print("+==================+")
    print("| menu de operacoes")
    print("| 1 - somar        ")
    print("| 2 - subtrair     ")
    print("| 3 - multiplicar  ")
    print("| 4 - dividir      ")
    print("| 0 - sair         ")
    print("+==================+")

    op = int(input("Escolha uma operação: "))

    if op == 0:
        break
    n1 = int(input("Primeiro número: "))
    n2 = int(input("Segundo número: "))

    if op == 1:
        print("O resultado da soma é", soma(n1, n2))
    elif op == 2:
        print("O resultado da subtração é", subtrai(n1, n2))
        elif op == 3:
        print("O resultado da multiplicação é", multiplica(n1, n2))
    elif op == 4:
        print("O resultado da divisão é", divide(n1, n2))
    else:
        print("Operação inválida!")
