  ##Contador-de-Personas-con-OpenCV

Este proyecto implementa un sistema básico de conteo de personas
utilizando visión por computador con OpenCV en Python.

El sistema detecta rostros mediante la cámara web y realiza el conteo
en tiempo real, utilizando clasificadores Haar Cascade para detección
frontal y de perfil (derecho e izquierdo).

Tecnologías utilizadas

Python 3.x

OpenCV

NumPy

Tkinter

Haar Cascades (detección facial frontal y perfil)

##Requisitos

Python 3.9 o superior

Cámara web funcional

Windows 10 o superior (para el ejecutable)

##Instalación

Clonar el repositorio:

git clone https://github.com/portadordelaluz/Contador-de-personas.git

Entrar a la carpeta del proyecto:

cd Contador-de-Personas-con-OpenCV

Crear entorno virtual (opcional pero recomendado):

python -m venv venv
venv\Scripts\activate

Instalar dependencias:

pip install -r requirements.txt

##Ejecución

Para ejecutar el programa:

python app.py

##Funcionamiento

Al ejecutar el programa, se abrirá una ventana con la cámara activa.

El sistema detecta:

Rostro frontal.

Perfil derecho.

Perfil izquierdo (mediante inversión horizontal).

Se eliminan detecciones duplicadas para evitar contar la misma persona más de una vez.

Se optimiza el rendimiento reduciendo la resolución del frame.

El conteo total de personas detectadas se muestra en tiempo real.

El botón "Salir" cierra completamente el programa.

##Limitaciones

La detección funciona mejor con buena iluminación.

Puede presentar fallos si el rostro está parcialmente cubierto.

No utiliza modelos de deep learning, sino clasificadores Haar.

La precisión puede variar según el ángulo del rostro.

##Autor

Keiler Ferrer Hurtado
20251020104
Ingeniería de Sistemas
Universidad Distrital
