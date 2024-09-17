## Resumen de Comandos Básicos de Pandas
__Leer un archivo CSV:__

import pandas as pd
df = pd.read_csv('archivo.csv')

__Mostrar las primeras filas del DataFrame:__

print(df.head())

__Seleccionar una columna:__

columna = df['nombre_columna']

__Seleccionar múltiples columnas:__

columnas = df[['columna1', 'columna2']]

__Número de filas y columnas:__

num_filas, num_columnas = df.shape

__Filtrar datos:__

filtrado = df[df['columna'] > valor]

__Resumen estadístico de datos numéricos:__

print(df.describe())

__Información general del DataFrame:__

print(df.info())

__Agrupar datos y calcular estadísticas:__

agrupado = df.groupby('columna').agg({'otra_columna': 'mean'})

