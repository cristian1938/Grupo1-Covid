
# **<center> 💻 G1 2022-I (ANÁLISIS DE DATOS EMPRESARIALES) 💻 </center>**

---

### Datos Academicos 📖

- **Institucion:** Universidad Nacional de San Antonio Abad del Cusco
- **Facultad:** Facultad de ingenieria electrica, electronica, informatica y mecanica
- **Escuela Prof:** Ingenieria Informatica y de Sistemas

#### Docente:
- **Garcia zanabria Germain** - _Docente_ 

#### Trabajo:

- Analizar y entender datos estadísticos sobre COVID 19- [presentacion](https://docs.google.com/presentation/d/15J2aJxqnLcrGnATdavOG_ogp7IxHmdyej7eULPLHw9c/edit?usp=sharing) 


#### Autores:✒️

- **Achahuanco Achahui Euridice Ingrid** - _GitHub Account_ - [Euridice](https://github.com/Euridice-I)
- **Guevara Ferro Cristian Luis** - _GitHub Account_ - [Cristian](https://github.com/cristian1938)
- **Mamani Quinta Michael Antonni** - _GitHub Account_ - [Michael](https://github.com/Michael-Antonni)

## Colaboratory 📖

# PROBLEMA

Ya habiendo pasado 3 años desde el primer contagio por coronavirus COVID-19 en Perú, realizaremos un análisis de la evolución de la enfermedad por su distribución por departamentos en el país.

Donde compararemos si hay diferencias en los promedios de personas con contagio positivo y fallecidos entre los diferentes departamentos. 
Utilizando los datos abiertos del Minsa, con la información acumulada de los años 2020-2021 donde las cifras del covid fueron más elevadas.
Buscaremos compartir algunas reflexiones en torno a la pandemia de COVID-19 en el Perú. La idea central refiere a que tanto el Estado como la sociedad peruana hicieron lo que pudieron en la medida de sus posibilidades y, a pesar de las cerca de 70 000 muertes, es posible que se haya evitado la mayor catástrofe humanitaria de nuestra historia conocida. En primer lugar, si comparamos la epidemia de COVID-19 con otros eventos de nuestra historia. Por otro lado, hablando de las fortalezas y debilidades al momento de manejar la crisis. Y por último, una estimación de qué hubiera pasado de no haberse tomado ninguna medida.


# DATOS
Realizamos un pequeño dataset de los departamentos y provincias del Perú para su posterior ayuda, donde contiene los 25 departamentos.
## ¿Qué datos tenemos actualmente?
- Datos a nivel **MINSA**:
	- [Casos positivos por COVID-19](https://www.datosabiertos.gob.pe/dataset/casos-positivos-por-covid-19-ministerio-de-salud-minsa) - Es el registro diario de casos positivos de covid-19 confirmados con cualquier tipo de prueba y que presentan síntomas
	- [Fallecidos por COVID-19]([https://www.datosabiertos.gob.pe/dataset/casos-positivos-por-covid-19-ministerio-de-salud-minsa](https://www.datosabiertos.gob.pe/dataset/fallecidos-por-covid-19-ministerio-de-salud-minsa#:~:text=Esta%20nueva%20clasificaci%C3%B3n%20est%C3%A1%20definida,para%20SARS%2DCoV%2D2.)) - Es el registro diario de muertes por Covid-19


Contamos con el registro diario de casos positivos de covid-19 confirmados con cualquier tipo de prueba y que presentan síntomas. Cada registro es igual a una persona, la cual puede caracterizarse por sexo, edad y ubicación geográfica hasta nivel de distrito.
Obtenido de la Directiva Sanitaria para la vigilancia epidemiológica de la enfermedad de Coronavirus en el Perú

![image](https://user-images.githubusercontent.com/59376790/188521335-4a4e50e3-f59b-4370-9e3e-ed3acad71a23.png)

## Diccionario de datos positivos
![image](https://user-images.githubusercontent.com/59376790/188521379-1d1cf1d0-88f8-4eb9-be5f-646c09979cac.png)

## Datos positivos
![image](https://user-images.githubusercontent.com/59376790/188521401-6c69ea3a-c8c4-4ffd-bb67-7077b67e66a7.png)

Obtuvimos el registro diario de muertes por Covid-19. Cada registro es igual a una persona, la cual puede caracterizarse por sexo, edad y ubicación geográfica hasta nivel de distrito.
Desde que se publicó este dataset, cada registro representaba un fallecido confirmado por covid-19, quienes cumplen con criterios clínicos y de laboratorio (prueba molecular, antigénica o pruebas serológicas).  A partir del 31.enero.2021 se cambió el criterio de “Fallecidos por Covid-19” por “Muertes por Covid-19” y como resultado el dataset creció casi al triple en el número de registros.

## Diccionario de Datos de Fallecidos
![image](https://user-images.githubusercontent.com/59376790/188521750-fb6e308a-0ae9-4b63-80d0-acc1ba2d36bd.png)

## Datos de Fallecidos
![image](https://user-images.githubusercontent.com/59376790/188521783-0fbc440b-e12d-4aa6-a438-7743685b0d6e.png)



# ANALISIS 

Teniendo en cuenta del cómo nos afectó esta pandemia nos propusimos:
## Tarea principal:
Analizar la enfermedad por su distribución por departamentos en el país donde se compara las diferencias en los promedios de personas con contagio positivo, fallecidos.
## Tarea secundaria

Analizar la tasa de personas fallecidas por edad en departamentos del país según la fecha de prueba de resultado.


# TAREAS

## 1) La enfermedad por su distribución por departamentos
![image](https://user-images.githubusercontent.com/59376790/188521848-56bfc146-6e8d-4a86-aa59-8593c4c60d31.png)

Fallecidos Enero del 2021

![image](https://user-images.githubusercontent.com/59376790/188521902-1473661d-133f-4bbe-a149-7addb0ce7b1f.png)

Contagiados

![image](https://user-images.githubusercontent.com/59376790/188521922-1dc1cadc-f07f-42c8-a129-72e983dbc7fe.png)

### Factores
1. Deficiencias en el sistema de salud
2. Enfoque en cuidados intensivos en vez de en prevención
3. Escasez de oxígeno
4. Reacción del gobierno
5. Cumplimiento de restricciones


## 2) Personas fallecidas por edad en departamentos

![image](https://user-images.githubusercontent.com/59376790/188521985-3c66657d-41df-4f6d-b582-f31392b34331.png)

![image](https://user-images.githubusercontent.com/59376790/188522000-d36d322d-383c-43cd-9ca3-74c4ff979dd6.png)


# CONCLUSIONES

1.- Podemos concluir que dados los de los dos casos de análisis, observamos que hubo un momento de déficit en el control de la enfermedad por ello se puede observar en la curva de casos de muerte una cifra muy elevada

2.-Se observó que en las gráficas de casos positivos y fallecidos por departamento, Lima fue el departamento más afectado debido a que tiene más habitantes.

3.-De acuerdo a las gráficas vemos que las personas de tercera edad (50-90 años) fueron las más afectadas






## Expresiones de Gratitud 🎁

- Comenta a otros sobre este proyecto 📢.
- Agradecemos a todas las personas involucradas (nosotros) 🤓.
- Esperamos les sea util, gracias por descargar.

---

⌨️ con ❤️ por [Grupo1] 😊
