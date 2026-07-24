# everpeack_analisis
analisis de una empresa de telecomunicacion
El objetivo de este estudio es identificar patrones de uso, detectar comportamientos atipicos y comprender que segmentos de clientes muestran nececidades diferenciadas, con el fin de optimizar la oferta comercial y mejorar la experiencia del usuarioo

se trabaja con 3 fuentes 
- plans.csv: los planes acutales (precio, minutos incluidos, GB incluidos, costo por extra)
- users_latam.csv: información de clientes: edad, ciudad, fecha de registro, plan contratado.
- usage.csv: el detalle de uso real: llamadas (duración) y mensajes (longitud).

las etapas del analisis son:

- cargamos los datasets
- Contar nulos, detectar sentinels, revisar fechas fuera de rango.
- Reemplazar sentinels, convertir fechas, imputar o marcar NA según reglas.
- Revisar las medidas clave en variables categóricas y numéricas.
- Creación de histogramas y boxplots.
- Crear segmentaciones basadas en reglas claras; visualizar proporciones con countplots.
- Redactar conclusiones y recomendaciones comerciales basadas en los pasos anteriores.

Podemos ejecutar el archivo desde Google Colab
- Seleccionamos el repositirio y la carpeta correcta
- abrimos el proyecto atraves del link
  
