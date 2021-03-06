# InformeLaboratorio8

Integrantes: Jonathan Insuasti - Melany  Villa - César Garnica 

# 1. Objetivos 

     Objetivo General
     
     Analizar las características de las ondas sinusoidales mediante la simulación y utilizacion 
     del laboratorio virtual.
    
    Objetivos Específicos
     - Analizar la documentación bibliográfica acerca de los tipos de configuraciones y las
     técnicas de control del inversor de DC a AC, para el cálculo de la relación de conversión y
     eficiencia.
     - Definir el circuito más adecuado de modulación basado en: modulación de ancho de pulsos
     Sinusoidal.
     - Definir la frecuencia más adecuada de trabajo en base al tipo de Transformador que se
     utilizará.

# 2. Marco Teórico

![](https://github.com/mjvilla1/ImagenesLab8/blob/main/Marco%20teorico%20Onda%20Senoidal.JPG)

![](https://github.com/mjvilla1/ImagenesLab8/blob/main/Marco%20Teorico.PNG)

# 3. Explicación  del procedimiento

![](https://github.com/mjvilla1/ImagenesLab8/blob/main/Diagram%20lab%208.jpeg)


Plasmamos el diagrama en el simulador con los valores dados previamente y conectamos los elementos de medición para poder medir los valores pedidos de la misma manera observamos como se produce la onda sinusoidal para ser analizada.

![](https://github.com/mjvilla1/ImagenesLab8/blob/main/circuito%20lab%208.jpeg)

 

#  4. Respuestas 

## ¿Cuántas divisiones por cuadro abarca la amplitud pico de la señal de salida?

Tiene aproximadamente 2.3 divisiones por cuadro

## ¿En qué valor está posicionada la perilla VOLTS/DIV?

Está posicionada en el valor de 3

## ¿Cuántas divisiones por cuadro abarca un ciclo completo de la señal de salida?

El ciclo completo abarca 4.6 cuadros aproximadamente

## ¿En qué valor está posicionada la perilla TIME/DIV?

Está posicionada en el valor de 0.1ms

- ¿Cuál es la amplitud de voltaje y el periodo de la señal que aparece en la pantalla del osciloscopio?

Amplitud de voltaje: 6.86 (V) 

Periodo: 0.00046 (s)

- Determine la frecuencia natural (Hz) y la frecuencia angular (rad/s) de la señal de salida.

f:  2173.91 (Hz)

ω:  346 (rad/s)

-Con el multimetro digital mida el voltaje de salida de Rl: 4.84V

- ¿COINCIDEN? No coinciden ¿Por qué? Los valores del osciloscopio y el multímetro no seran los mismos ya que el valor que nos da el multimetro es el valor eficaz el cual es siempre menor que el valor entregado por el osciloscopio, matematicamente se podria expesar el valor eficaz es igual al valor pico mostrado en el osciloscopio dvidido para raiz de 2 o multiplicado o 0.707.

# 5. Video

https://youtu.be/f-9GaqRmcnk

# 6. Conclusiones

- A mayor frecuencia en el oscilador PWM de onda cuadrada, el voltaje en el transformador
toroidal aumenta, lo cual valida la ecuación de la relación del número de vueltas.
- La utilización de circuitos integrados desarrollados específicamente para inversores,
cuenta con características necesarias para la implementación y control de fuentes.
- Las realimentaciones nos ayudan a detectar inconvenientes apagan el circuito para salvaguardar
la integridad de los componentes, mismas que fueron probadas con diferentes cargas para validar
su funcionamiento.


# 7. Bibliografía 

Floyd Thomas L, “Principios de Circuitos Eléctricos”, 8 ed. 2007 .Pearson Educación de México, S.A. de C.V. México, pp. 431.
