# Calculo-de-ano-e-Python

nome = input ("Digite seu nome: ")
percentual = int(input("Digite o percentual: "))
idade = int (input ("Digite sua idade: "))
saldo = float (input ("Digite seu saldo: "))
ano = 2023 - idade
saldop = (saldo/100*percentual)+saldo
print (nome, "o ano que você nasceu é: ", (2023 - idade))
print (nome, "o seu saldo bancário é: ", saldo)
print ("Seu saldo com", percentual, "% é de: " , saldop)
print (f"Você {nome} que nasceu em {ano} terá um saldo de {percentual} %, que será de R$: {saldop}")
