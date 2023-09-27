# RECAF - RED DE ESTACIONES CLIMATOLÓGICAS AUTOMÁTICAS FORMOSEÑAS

### Integrantes grupo:
- Brunelli, Juan José
- Cáceres, Ayrton Elian
- Castro, Elena
- Rivenson, Camila

## Problematica
Proporcionar información pública del estado del clima de toda la provincia en tiempo real brindada por la máquina SADA del equipo de investigación de Mecatrónica del Instituto Politécnico Formosa.

## Objetivo
Visualizar los datos del estado del clima, tales como Temperatura, Humedad,
Presión atmosférica, Altitud, Dirección, Velocidad y Fuerza del viento,
Precipitaciones y Precipitaciones totales; obtenidos por la máquina SADA del equipo de investigación de Mecatrónica del Instituto Politécnico Formosa.

## Objetivos especificos
- Crear una interfaz de usuario fácil de usar que permita a los usuarios acceder y comprender rápidamente la info-rmación climática y las funciones de la plataforma.

- Proporcionar información pública del estado del clima en tiempo real de toda la provincia.

- Mejorar los pronósticos del tiempo para el área provincial.

- Desarrollar modelos de humedad en suelo para uso agrícola.

- Generar estadísticas climáticas confiables para su utilización en diversos campos de la producción y el conocimiento.

- Mantener una vigilancia sobre eventuales variaciones del clima provincial.

- Diseñar perfiles de usuario específicos para distintos grupos, como agricultores, empresas, entre otros con características y funcionalidades adaptadas a sus necesidades.

### Seguimiento del proyecto
En cuanto a avances del proyecto, se estableció el primer sprint para la primer release del proyecto 
que estará vigente para el siguiente 9 de obtubre. El sprint tiene detalle en nuestro jira del proyecto,
el cual dejaremos el link vinculado.

Para llegar a la realizacion del primer sprint se tuvo que pasar por varias trabas que se venian arrastrando desde principio de año. Una de ellas era el tipo de archivo de los datos del SADA; otra contra era la forma de recibir los datos. Con ayuda de un profesor y gracias a que los integrantes del equipo del SADA investigaron una libreria para pasar sus datos a json, se pudo establecer un server intermedio que nos brinda los datos del SADA a un cluster en mongoDB Atlas.

Habiendo pasado esos inconvenientes, se pudo estableccer una version 0 del front y del back para ir modelando los datos. Esto tomaria mas forma y se refinaria en el transcurso de los primeros dos sprints, idealmente.

Tambien se planteó y se decidió el como vamos a dividirnos la carga de trabajo entre el grupo web y el mobile. Debido a que tenemos un solo integrante en el equipo mobile, se decidió que en primera instancia solo se contaria con pantallas de informacion en dicha version. Dejando las funcionalidades mas complejas solo para la version web.

Se estuvo trabajando con varias herramientas para ir tomando decisiones e ir documentando los avances del proyecto, tales como: Jira, Trello, Miro, Excalidraw, ChatGPT, entre otras.




