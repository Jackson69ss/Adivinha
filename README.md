Estrutura condicional composta:
import random as r

resposta = r.randint(1,10)

chute = int(input("Estou pensando 
em um numero de 1 a 10. Em qual  número estou pensando? "))

if chute == resposta:
  print("Parabéns! Você acertou :)")
elif chute < 7 or chute > 10:
  print("Ops! 0 número digitado não é válido.In")
else:
  print("Poxa, não foi dessa vez :( \nA resposta era
resposta)
