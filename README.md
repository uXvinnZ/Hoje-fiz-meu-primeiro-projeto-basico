#Entrada das notas  e  Transformar str em int ou float (transformar letra em numero)
nota1 = float(input("Nota 1: "))
nota2 = float(input("Nota 2: "))
nota3 = float(input("Nota 3: "))
nota4 = float(input("Nota 4: "))

# Soma 
resultado = (nota1 + nota2 + nota3 + nota4) / 4

#Mensagem de AP ou RP
if resultado >= 7 and resultado<20:
    print('voce foi aprovado, com a media de', (resultado))
else:
    print('voce foi reprovado, sua media foi de', (resultado))    
