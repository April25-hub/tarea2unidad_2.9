print(" ")
print("Arzaba Diaz April 3W 1173")
def sum(numeros):
    """
    esta funcion recibe una lista de numeros y devuelve la suma de todos ellos
    
    args:
    numeros (list): Lista de numeros a sumar

    returns:
    float: La suma de todos los numeros en la lista
    """
    total = 0
    for num in numeros:
        total += num
    return total

def multip(numeros):
    """
    esta funcion recibe una lista de numeros y devuelve el producto de todos ellos.
    
    args:
    numeros (list): lista de numeros a multiplicar.

    returns:
    float: el producto de todos los numeros en la lista.
    """
    total = 1
    for num in numeros:
        total *= num
    return total

#esta linea dara un ejemplo de uso
suma_resultado = sum([1, 2, 3, 4])
multip_resultado = multip([1, 2, 3, 4])
print(suma_resultado)  #salida: 10
print(multip_resultado)  #salida: 24
![image](https://github.com/user-attachments/assets/be0b810b-8df9-47bd-8ff8-32973f051029)

