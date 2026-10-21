[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=carolinagamez/MSFP2)
# Práctica 2: Modelado y control del sistema cardiovascular mediante el modelo Windkessel

## Información de la estudiante

Carolina Gamez Flores [23212193]; l23212193@tectijuana.edu.mx

Modelado de Sistemas Fisiológicos

Ingeniería Biomédica

## Docente

Dr. Paul Antonio Valle Trujillo; paul.valle@tectijuana.edu.mx

Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México/IT Tijuana, Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México.

## Descripción de la asignatura

El modelizado de sistemas fisiológicos es una herramienta importante en Ingeniería Biomédica, permite comprender el funcionamiento del cuerpo humano, así como diseñar y evaluar terapias y dispositivos médicos; se define como el proceso de formular modelos matemáticos o computacionales que representan el comportamiento y la interacción de los sistemas biológicos y fisiológicos. Esta asignatura pretende aportar al perfil del Ingeniero Biomédico la capacidad de realizar investigación científica en el área de Biología de Sistemas con la finalidad de dirigir y participar en equipos de trabajo interdisciplinarios en contextos nacionales e internacionales, así como de proporcionar soluciones informáticas para resolver problemas en el campo de la Ingeniería Biomédica con ética profesional; lo anterior al proporcionar al estudiante bases sólidas para modelizar sistemas y diseñar controladores para la solución de problemas en las áreas de atención médica y del sector industrial médico. La construcción de analogías entre circuitos eléctricos y sistemas fisiológicos para la formulación de modelos matemáticos y el diseño de controladores mediante la experimentación in silico brindan herramientas de gran aplicación en el quehacer profesional del Ingeniero Biomédico.

La asignatura de Modelado de Sistemas Fisiológicos forma parte del plan de estudios de la carrera en Ingeniería Biomédica con la siguiente competencia general del curso: Utiliza las propiedades de los circuitos RLC para describir la dinámica de sistemas fisiológicos, obtener modelos matemáticos y aplicar el control clásico, esto con el objetivo de integrar los principios de la Ingeniería de Control, la Electrónica Analógica y las Ciencias de la Computación con la Anatomía y Fisiología del cuerpo humano para proporcionar descripciones cuantitativas y cualitativas de sistemas fisiológicos complejos con el objetivo de modelizar, analizar, controlar, ilustrar y predecir su dinámica tanto en el corto como en el largo plazo.

## Objetivos

1. Calcular la función de transferencia del modelo Windkessel para las condiciones hipotensa, normotensa e hipertensa.
2. Determinar el modelo de ecuaciones integro-diferenciales del sistema cardiovascular.
3. Establecer el modelo de ecuaciones diferenciales ordinarias de primer orden.
4. Analizar la estabilidad del sistema para las tres condiciones y determinar el error en estado estacionario.
5. Simular la respuesta del modelo Windkessel en Simulink/MATLAB para los individuos hipotenso, normotenso e hipertenso.
6. Sintonizar las ganancias de los controladores PID para las condiciones hipotensa e hipertensa mediante la herramienta Tune de Simulink.
7. Obtener las respuestas de los tres individuos y de los sistemas controlados mediante las simulaciones en MATLAB/Simulink.
8. Corroborar las respuestas obtenidas en MATLAB/Simulink mediante simulaciones numéricas en Python.

## Descripción detallada del sistema

En esta práctica se presenta el modelo Windkessel del sistema cardiovascular mediante un circuito eléctrico de segundo orden, en el cual la impedancia Z, la inertancia L, la resistencia R y la capacitancia C representan las propiedades del sistema circulatorio. El modelo relaciona la presión de entrada Pa(t) con la presión de salida Pp(t) y permite estudiar tres condiciones: hipotensión, normotensión e hipertensión. Las respuestas se obtienen modificando la capacitancia C para cada individuo, manteniendo constantes los demás parámetros del circuito. El análisis matemático permite determinar la función de transferencia, la estabilidad y el error en estado estacionario; posteriormente se simulan las señales en Simulink/MATLAB y se sintonizan los controladores PID para aproximar las respuestas hipotensa e hipertensa a la respuesta normotensa. Las simulaciones se corroboran mediante Python.

Palabras clave: Modelo Windkessel; Sistema cardiovascular; Circuito RLC; Controlador PID; Modelo matemático; Simulaciones numéricas.

## Lista de archivos incluidos en el repositorio

1. Cuaderno computacional de MATLAB [.mlx y .pdf].
2. Modelo de Simulink [.slx]: Simulación de los tres individuos, modelo de ecuaciones y sintonización de los controladores.
3. Archivo de Python [.py] para corroborar las respuestas obtenidas en MATLAB/Simulink.
4. Figuras de las simulaciones en MATLAB [.pdf]: Respuesta de los tres individuos y respuestas con controlador para las condiciones hipotensa e hipertensa.
5. Figuras de las simulaciones en Python [.pdf].
6. Análisis matemático realizado a mano [.pdf]: Función de transferencia, estabilidad, error en estado estacionario y modelo de ecuaciones integro-diferenciales.
7. Ilustración del sistema fisiológico realizada en BioRender.

## Referencias

[1] P. A. Valle, Syllabus para Modelado de Sistemas Fisiológicos, Tecnológico Nacional de México / Instituto Tecnológico de Tijuana, Tijuana, B.C., México, 2025. Permalink: https://biomath.xyz/course/

[2] M. C. Khoo, Physiological Control Systems Analysis Simulation, and Estimation, 2nd ed. Piscataway, New Jersey, USA: IEEE Press, 2018, Section 4, Page 93.

[3] N. S. Nise, Control Systems Engineering, 8th ed. Hoboken, New Jersey, USA: John Wiley & Sons, 2020.
