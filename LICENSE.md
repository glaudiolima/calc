numero = (1, 2, 3, 4, 5, 6, 7, 8, 9, 10,11,12)
soma_pares = 0
soma_impares = 0
for n in numero:
    if n % 2 == 0:
        soma_pares += n
    else:
        soma_impares += n
print(f'Soma dos pares: {soma_pares}')
print(f'Soma dos impares: {soma_impares}')
