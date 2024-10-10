# pr10-Sepulveda-Gonzalez-Angel-Alejandro-3W-1215

# 10. Función que verifica si un carácter es una vocal

def es_vocal(caracter):

  # Verificamos si el carácter está en el conjunto de vocales (a, e, i, o, u)
    
  return caracter.lower() in 'aeiou'

# Pedimos al usuario que introduzca un carácter

caracter_usuario = input("Introduce un carácter: ")

# Verificamos que solo se haya ingresado un carácter

if len(caracter_usuario) == 1:

  # Llamamos a la función y mostramos el resultado
   
  if es_vocal(caracter_usuario):
    
  print(f"'{caracter_usuario}' es una vocal.")
    
  else:
    
  print(f"'{caracter_usuario}' no es una vocal.")

else:

  print("Por favor, introduce solo un carácter.")
  
![image](https://github.com/user-attachments/assets/a43629f7-99d1-4510-99b5-8e006ce878fe)
![image](https://github.com/user-attachments/assets/7715f00f-313b-4315-bc56-8ee62a371ce5)
