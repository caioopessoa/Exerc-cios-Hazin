# Exercios-Hazin
expressao = input('insira a expressao para encontrar o numero: ').lower()
numero = ''
for letra in expressao:
    if letra == 'a' or letra == 'b' or letra == 'c':
        numero = numero + '2'
    elif letra == 'd' or letra == 'e' or letra == 'f':
        numero = numero + '3'
    elif letra == 'g' or letra == 'h' or letra == 'i':
        numero = numero + '4'
    elif letra == 'j' or letra == 'k' or letra == 'l':
        numero = numero + '5'
    elif letra == 'm' or letra == 'n' or letra == 'o':
        numero = numero + '6'
    elif letra == 'p' or letra == 'q' or letra == 'r' or letra == 's':
        numero = numero + '7'
    elif letra == 't' or letra == 'u' or letra == 'v':
        numero = numero + '8'
    elif letra == 'w' or letra == 'x' or letra == 'y' or letra == 'z':
        numero = numero + '9'
    elif letra == ' ':
        numero = numero + ' '

print(numero)
