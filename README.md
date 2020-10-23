# pegueama-
Bem , o computador te da o numero que passos que esta a maçã e te da o numero de passos que o avatar deu , então ee fala se você consegiu pegar a maçã ou não , lembrando o programa esta empython e não tem interface grafica

import random
gato = 1
for i in range (1):
    x = random.choice([1,2,3,4,5,6,7,8,9])
    print('A maçã esta a ',x,'passos')
    maçã = x
for a in range(1):
    b = random.choice([1,2,3,4,5,6,7,8,9])
    print('voce deu ',b,' passos para pegar a maçã')
    if b == x:
        print('Você pegou a maçã')
    elif b != x or b > x:
        print('Voce esta no bloco ', b ,'mas a maçã esta no bloco ',x)
    else:
        print('')
