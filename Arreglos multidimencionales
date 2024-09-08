import numpy as np

# Definir las dimensiones de la matriz
num_ciudades = 3
num_dias = 7
num_semanas = 4

# Crear una matriz 3D aleatoria para simular los datos (puedes reemplazar estos valores con tus propios datos)
temperaturas = np.random.randint(15, 35, size=(num_ciudades, num_dias, num_semanas))

# Función para calcular el promedio semanal de una ciudad
def promedio_semanal_ciudad(ciudad):
  promedios = np.mean(temperaturas[ciudad], axis=0)
  return promedios

# Recorrer todas las ciudades y calcular los promedios semanales
for ciudad in range(num_ciudades):
  promedios_ciudad = promedio_semanal_ciudad(ciudad)
  print(f"Ciudad {ciudad+1}:")
  for semana in range(num_semanas):
    print(f"  Semana {semana+1}: {promedios_ciudad[semana]}°C")
