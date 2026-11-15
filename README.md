# Mocus Inspectio
NASA Space Challenges. Health Monitoring System

Mocus Inspectio es un detector portátil de Staphylococcus aureus para misiones espaciales. Una cámara con inteligencia artificial integrada (OpenMV Cam H7 Plus) observa un cultivo en placa de Petri, localiza cada colonia y la clasifica en segundos con una red neuronal que corre dentro de la propia camara: sin internet, sin laboratorio y sin enviar muestras a la Tierra. El resultado (número de colonias y cuántas son sospechosas de S. aureus) viaja por cable serie a una camara que lo muestra en pantalla y dispara una alerta. El modelo se entrenó con más de 240 colonias reales del dataset público AGAR y alcanzó 98 % de acierto en placas nunca vistas. El proyecto responde a un hallazgo de la NASA: en la Estación Espacial, S. aureus activa su sistema de comunicación bacteriana (quorum sensing) 88 veces más que en la Tierra y aumenta sus factores de virulencia, justo cuando el sistema inmune del astronauta está debilitado. Mocus Inspectio le da a la tripulación detección temprana, a bordo y en tiempo real.

Materiales

* Placas de Petri de 90 mm con agar sal-manitol (medio selectivo para Staphylococcus; S. aureus lo vuelve amarillo).
Alternativa segura para presentar sin bacterias vivas: fotos del dataset AGAR mostradas en tablet o impresas.

Software (gratuito)

* OpenMV IDE
* Dataset AGAR (licencia CC BY-NC) vía HuggingFace.

Codigo

* ei-model.tflite
* ei-model.txt
* ei_image_classification.py
