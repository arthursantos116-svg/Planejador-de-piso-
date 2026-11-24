print('questao 18')
import  math
comp = float(input('digite o comprimento da sala '))
largura = float(input('digite a largura da sala '))
lado = float(input('digite o lado da placa')) 

areaSala = comp+largura
areaPlaca = lado + lado 
qntPlacas = areaSala/areaPlaca

print(f'antes de arredondar {qntPlacas}')
qntPlacas = math.ceil (qntPlacas)
print(f'depois do arredondamento {qntPlacas}')

areaReserva = qntPlacas+qntPlacas*(10/100) 
print(f'quantidade apos os 10%: {qntPlacas}')
areaReserva = math.ceil(areaReserva)
print(f'depois do arredondamento: {areaReserva}
