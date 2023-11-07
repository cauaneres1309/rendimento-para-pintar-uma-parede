# rendimento-para-pintar-uma-parede
programa que calcula a quantidade de tinta necessária para pintar uma parede.O usuario devera fornecer as seguintes informaçoes:rendimento,altura e largura.o problema deve mostrar na tela a mensagem "voce necessita de x latas de tinta"

rendimento=int (input('qual é o rendimento da lata?'))
altura=int (input('qual é a altura da parede?'))
largura=int (input('qual é a largura da parede?'))
def calculo_tinta():
    area = altura * largura
    total = area/rendimento
    print(f'voce precisa de {total} latas de tintas')
  calculo_tinta()
