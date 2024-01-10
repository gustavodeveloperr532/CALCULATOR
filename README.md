# CALCULATOR
teste
# um projeto que comecei quando estava estudando python nao sei nem se to fazendo certo postando o codigo desa forma no github  

# Função para realizar uma operação de adição
def adicao(a, b):
    return a + b

# Função para realizar uma operação de subtração
def subtracao(a, b):
    return a - b

# Função para realizar uma operação de multiplicação
def multiplicacao(a, b):
    return a * b

# Função para realizar uma operação de divisão
def divisao(a, b):
    if b == 0:
        return "Erro! Divisão por zero não é permitida."
    return a / b

# Exemplo de uso
num1 = float(input("Digite o primeiro número: "))
num2 = float(input("Digite o segundo número: "))

print("Escolha a operação:")
print("1 - Adição")
print("2 - Subtração")
print("3 - Multiplicação")
print("4 - Divisão")

escolha = input("Digite o número da operação desejada: ")

if escolha == '1':
    resultado = adicao(num1, num2)
elif escolha == '2':
    resultado = subtracao(num1, num2)
elif escolha == '3':
    resultado = multiplicacao(num1, num2)
elif escolha == '4':
    resultado = divisao(num1, num2)
else:
    resultado = "Escolha inválida"

print(f"Resultado: {resultado}")
