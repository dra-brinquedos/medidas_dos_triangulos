# medidas_dos_triangulos
#Dados 3 numeros, verifique se eles podem ser medidas de um triangulo com: 
#equilátero, isóscele ou escaleno.
lado1 = int(input("Digite:"))
lado2 = int(input("Digite:"))
lado3 = int(input("Digite:"))
if lado1 == lado2 and lado3 < lado1:
    print("É um triangulo Isósceles")
    print("Existe dois lados iguais e um menor.")
elif lado2 == lado3 and lado1 < lado2:
    print("É um triangulo isosceles.")
    print("Existe dois lados iguais e um menor.")
elif lado3 == lado1 and lado2 < lado1:
   print("É um triangulo isosceles.")
   print("Existe dois lados iguais e um menor.") 
elif lado1 == lado2 and lado3:
    print("É um triangulo equilatero:")
    print("Todos os lados são iguais.")
else:
    print("É um triangulo escaleno:")
    print("Todos os lados são diferentes.")


