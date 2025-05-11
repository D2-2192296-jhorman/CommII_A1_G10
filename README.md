# CommII_A1_G10
README – Laboratorio 5: Modulación Digital en GNU Radio
Descripción general
Este informe documenta el análisis práctico de cuatro técnicas de modulación digital: BPSK, QPSK, 8-PSK y 16-QAM, utilizando la plataforma GNU Radio. A través de simulaciones con un mismo vector de símbolos y un canal con ruido aditivo blanco gaussiano (AWGN), se estudia el comportamiento de cada esquema en términos de:

Forma de onda en el dominio del tiempo.

Espectro de frecuencia (incluyendo posiciones de nulos).

Diagramas de constelación.

Eficiencia espectral y tolerancia al ruido.

Objetivo
Comprender cómo el orden de modulación afecta el rendimiento del sistema en diferentes condiciones de canal, y visualizar de forma práctica los compromisos entre velocidad de transmisión y robustez ante interferencias.

Lo que encontrarás en el informe
Implementación de cada esquema de modulación en GNU Radio.

Comparaciones visuales en banda base y pasabanda.

Comportamiento frente al ruido: cómo afecta la dispersión de los puntos de la constelación.

Conclusiones sobre la viabilidad de cada técnica en función del entorno de transmisión.

Resultados clave
BPSK: Alta robustez al ruido, espectro estrecho, baja eficiencia.

QPSK: Doble tasa de bits por símbolo respecto a BPSK, con buena estabilidad.

8-PSK: Mejor eficiencia pero mayor sensibilidad al ruido, con constelaciones más solapadas.

16-QAM: Alta velocidad de transmisión y uso eficiente del espectro, pero vulnerable al ruido y requiere alta SNR.