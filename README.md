# exercise_14

#calculating the price to pay for a rented car, Kms and days

dias = float (input ('quantos dias o carro foi usado? '))
km = float (input ('quantos kilometros foram percorridos com o carro? '))
total = (dias * 60) + (km * 0.15)

print ('o total a pagar é R${}' .format (total))
