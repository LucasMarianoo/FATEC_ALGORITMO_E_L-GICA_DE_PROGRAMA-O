# VERIFICADOR DE FORMA GEOMÉTRICA

import os
os.system('cls||clear')

# número de lados
numLados = int(input('Digite o número de lados do polígono:'))
# medida dos lados
medLado = input('Digite a medida dos lados separado por vírgulas: ')
# armazenamento das medidas dos lados
vetor_medLados = medLado.split(",")
# converte itens da lista em int
vetor_medLados = [int(item) for item in vetor_medLados]
# print(type(vetor_medLados[0])) # verificação do tipo de dados de vetor_medLados

if numLados == 3:
    numLados = 'Triângulo'
elif numLados == 4:
    numLados = 'Quadrado'
elif numLados == 5:
    numLados = 'Pentágono'
elif numLados > 5:
    numLados = 'Polígono não reconhecido'
    print(numLados)

match numLados:
    case 'Triângulo':
        semi_per = (vetor_medLados[0]+vetor_medLados[1]+vetor_medLados[2])/2
        area_tri = semi_per*(semi_per-vetor_medLados[0])*(semi_per-vetor_medLados[1])*(semi_per-vetor_medLados[2])**(1/2)
        print(area_tri)
        
    case 'Quadrado'
        area_quad = vetor_medLados[0]*vetor_medLados[1]
        print(area_quad)
        
    case 'Pentágono'

    case 'Polígono não reconhecido'
