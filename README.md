# repo_reto_4

1. Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.

```python
esNumeroASCII = input("Ingrese un numero ASCII: ")
if esNumeroASCII >= "97" and esNumeroASCII <= "122":
    print("Es un numero ASCII, es la letra: ", esNumeroASCII)
else:
    print("No es un numero ASCII")
```

2. Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.

```python
cadenaDeLongitud1 = input("Ingrese un solo caracter: ")
if ord(cadenaDeLongitud1) % 2 == 0:
    print("El codigo ASCII del caracter es par")
else:
    print("El codigo ASCII del caracter es impar")
```
3. Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.
```python
caracter = input("Ingrese un caracter: ")
if caracter.isdigit():
    print("Es un digito")
else:
    print("No es un digito")
```
4. Dado un número real x, construya un programa que permita determinar si el número es positivo,
negativo o cero. Para cada caso de debe imprimir el texto que se especifica a continuación:
Positivo: "El número x es positivo"
Negativo: "El número x es negativo"
Cero (0): "El número x es el neutro para la suma"

```python

numeroReal= input("Ingrese un numero real: ")
if numeroReal > 0:
    print("El numero es positivo")
elif numeroReal == 0: 
    print("El número x es el neutro para la suma")
else:
    print("El numero es negativo")
```
5. Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo.
```python
centroX = float(input("Ingrese el centro en X: "))
centroY = float(input("Ingrese el centro en Y: "))
radio = float(input("Ingrese el radio: "))
PI = 3.14159

circulo= PI * radio**2
puntoCualquieraEnX = float(input("Ingrese un punto cualquiera para x: "))
puntoCualquieraEnY = float(input("Ingrese un punto cualquiera para y: "))
distancia = (puntoCualquieraEnX - centroX)**2 + (puntoCualquieraEnY - centroY)**2
if  distancia < circulo:
    print("esta dentro del circulo")
else:
    print("no esta dentro del circulo")
```
6. Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.
```python
cateto1= int(input("(cateto1)ingrese un numero positivo: "))
cateto2 = int(input("(cateto2)ingrese un numero positivo: "))
hipotenusa = int(input("(hipotenusa)ingrese un numero positivo: "))

if cateto1**2 + cateto2**2 == hipotenusa**2:
    print("Con las 3 longitudes puedes formar un triangulo rectangulo.")
elif cateto1 + cateto2 = hipotenusa and cateto + hipotenusa > cateto1 and hipotenusa + cateto1 > cateto2:
    print("Con las 3 longitudes puedes formar un triangulo.")
else:
    print("Con las 3 longitudes no puedes formar un triangulo.")
```
