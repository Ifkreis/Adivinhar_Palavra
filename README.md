import random as rd

Palavra = ['arco-iris', 'computador', 'ciencia', 'programação', 
         'python', 'matematica', 'player', 'condição', 
         'reverter', 'agua', 'board', 'nerds'] 

cont = 1

print(Palavra)


Palavra_escolhida = rd.choice(Palavra)

print (Palavra_escolhida)

Descobrir_palavra = input('Digite uma das palavra: ')


while Descobrir_palavra.lower() != Palavra_escolhida:
    
    if Descobrir_palavra.lower() != Palavra_escolhida:
        print("Tente novamente")
    Descobrir_palavra = input('Digite uma das palavra: ')
    cont = cont + 1
    

print (f'Você acertou, a palavra escolhida foi: {Palavra_escolhida}')
print(f'Você tentou {cont} vezes')
