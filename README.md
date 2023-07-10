Desenvolva um programa que recebe do usuário nome completo e ano de nascimento que seja entre 1922 e 2021.
A partir dessas informações, o sistema mostrará o nome do usuário e a idade que completou, ou completará, no ano atual (2022).

Caso o usuário não digite um número ou apareça um inválido no campo do ano, o sistema informará o erro e continuará perguntando até que um valor correto seja preenchido.

Trabalhe esse código em seu IDE, suba ele para sua conta no GitHub e compartilhe o link desse projeto no campo ao lado para que outros desenvolvedores possam analisá-lo.

Resposta: 

print("Informe seu nome:")
nome = input()

executar = True

while(executar == True):
print("Informe seu ano de nascimento")
try: 
ano = int(input())
if(ano < 1922) or (ano > 2021):
print("O ano precisa ser entre 1922 e 2021")
else: 
idade = 2022 - ano
print("O usuário", nome, "completou ou completará", idade, "anos de idade no ano de 2022")
executar = False
except:
print("Os anos precisam ser escritos apenas com números")
