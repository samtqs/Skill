# Skill
Este é um projeto simples de calculadora, desenvolvido em Python, que realiza operações matemáticas básicas:

Adição

Subtração

Multiplicação

Divisão


O objetivo deste projeto é praticar a lógica de programação, a utilização de funções e a interação com o usuário pelo terminal.

Tecnologias utilizadas:

Python 3



# Calculadora básica em Python

def adicao(a, b):
    return a + b

def subtracao(a, b):
    return a - b

def multiplicacao(a, b):
    return a * b

def divisao(a, b):
    if b != 0:
        return a / b
    else:
        return "Erro: divisão por zero!"

print("=== Calculadora Básica ===")
print("Escolha a operação:")
print("1 - Adição")
print("2 - Subtração")
print("3 - Multiplicação")
print("4 - Divisão")

opcao = input("Digite a opção (1/2/3/4): ")

num1 = float(input("Digite o primeiro número: "))
num2 = float(input("Digite o segundo número: "))

if opcao == "1":
    print("Resultado:", adicao(num1, num2))
elif opcao == "2":
    print("Resultado:", subtracao(num1, num2))
elif opcao == "3":
    print("Resultado:", multiplicacao(num1, num2))
elif opcao == "4":
    print("Resultado:", divisao(num1, num2))
else:
    print("Opção inválida!")



O que eu aprendido:

Como criar e organizar funções no Python.

Como receber dados do usuário pelo terminal usando input().

Como trabalhar com condicionais (if/elif/else).

Como exibir resultados no console.
    

Como executar:

1. Certifique-se de ter o Python 3 instalado em sua máquina.


2. Salve o código em um arquivo chamado calculadora.py.


3. Abra o terminal/prompt de comando e execute:

 python calculadora.py
