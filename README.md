# Jogo-da-adivinha-o-
#Jogo consiste em o computador pensar em um número entre 1 e 10 onde o usuário irá tentar acertar e no final o programa dirá quantas vezes foi necessário ate o acerto

import random 
computador = random.randint(1,11)
jogador = int(input('qual número eu pensei?: '))


while not jogador == computador: 
    jogador = int(input('tente denovo: '))
    jogador += 0

print(f'você venceu eu pensei no número {computador} foram necessarias {jogador} vezes')
