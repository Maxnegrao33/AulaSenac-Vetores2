# AulaSenac-Vetores2
Segundo código de Vetores em Python
#Aula de Vetores - Código 02

#tupla é criada com () e não pode ter seus dados alterados
#lista é criada com [] e pode não ter dados obrigatórios

numeros = ('zero', 'um', 'dois', 'três', 'quatro', 'cinco', 'seis', 'sete', 'oito', 'nove')
dez = ('dez', 'onze', 'doze', 'treze', 'quatorze', 'quinze', 'dezesseis', 'dezessete', 'dezoito', 'dezenove')
dezenas = ('', '', 'vinte', 'trinta', 'quarenta', 'cinquenta', 'sessenta', 'setenta', 'oitenta', 'noventa')

print(numeros[7])
print(dez[3])
print(dezenas[5])

pos = int(input('Digite um número entre 0 e 99: '))

if pos < 10;
    extenso = numeros[pos]
elif pos < 20;
    extenso = dez[pos - 10]
elif pos <= 99;
    dezena = int(pos / 10)
        print(dezena)
    numeral = (pos % 10)
        print (numeral)
        numero = ''
    if (numeral !=0)
        numero = 'e' + numeros[numeral]
        extenso = dezenas[dezena] + número
        else:
            extenso = 'Número maior que 100...'
            print(extenso)
