# Exercicio055.py

maior = 0
menor = 0
for c in range(1,6):
    peso = float(input('Digite o peso da pessoa:'))
    if c == 1:
        maior = peso
        menor = peso
    else:
        if peso > maior:
            maior = peso
        if peso < menor:
            menor = peso
print('Maior peso foi:', maior)
print('Menor peso foi: ', menor)
