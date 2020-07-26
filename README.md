# Python
 Exercícios de Python 🐍

  
print('\033[1;30m-_-'*17)
print('\033[1;36mEscolha um número de 0 a 10 para ver a sua tabuada\033[m')
print('\033[1;30m-_-'*17)
num = int(input('Digite um número: '))
print('\033[1;36mTabuada do {}'.format(num))
for c in range(1, 11, 1):
    res = num * c
    print('{} X {} = {}'.format(num, c, res))
