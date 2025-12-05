# SPORTPRO

¿Qué es SportPro? SportPro es un aplicativo que cuenta con el fin de ayudar a la gente a prepararse y entrenar para cuatro diferentes deportes (Futbol, Natación, Baloncesto, Tenis) dependiendo de su nivel como deportista o incluso algunas discapacidades (Por favor tenga en cuenta que a la hora de manejar discapacidades debe de también asistir con un médico y comprobar sus capacidades), hicimos esta aplicación no solo como un proyecto final sino también con la idea de ayudar a las personas ya que a la hora de jugar o entrenar un mal estiramiento o calentamiento puede terminar con problemas de salud, nuestra aplicación busca ayudar a las personas que practican deportes y cuidarlas.

# 📋 Características de SportPro!

SportPro trae cuatro funciones principales que le ayudaran con sus entrenamientos.

1. Rutinas personalizadas para el usuario!
Dependiendo de los datos que usted como usuario le otorgue al aplicativo se le dará una rutina especializada para su beneficio y pensada para su eficiencia
la encuesta también es fácil y rápida de hacer haciendo que su uso sea eficiente y sencillo 

2. Sistema de historial y seguimiento
Toda rutina que usted termine se guardará y se añadirá a un historial de entrenamiento donde podrá ver su progreso y verificarlo de forma visual gracias a la gráfica de peso, rutinas y tiempo de ejercicio, así como también una lista de características de la rutina

3. Sistema de alarmas
El aplicativo tiene consigo un sistema de alarmas que se ejecutan a diario, por lo que si usted quiere poner un recordatorio para empezar su rutina diaria puede darle a la aplicación una hora específica para comenzar

4. Chat IA
Una vez preparado el programa podrá ejecutar un chat IA local que cuenta con el único fin de ayudarle con sus entrenamientos y darle rutinas extra en caso de que usted busque eso, así como incluso ayudar a practicar conceptos de los cuatro deportes principales con los que trabaja la aplicación

# 🖋️ Requisitos para usar SportPro

Primero que nada, si usted quiere utilizar el aplicativo usted debe de tener visual studio con python 3.0 o superior, contar con pip para descargar las múltiples librerías a usar y tener LM studio para que la IA funcione

# 🪡 ¿Qué se usó para crearlo?

Se uso:
-Python - Lenguaje de programación
-Flask - Lenguaje de comunicación entre python y HTML
-HTML - Lengua de etiquetado para los visuales
-Css - Lenguaje de diseño para HTML
-Firebase - Servidores de datos

# 🧑‍💻 Instalación del aplicativo

Descargue todos los archivos, descomprima la base de datos y pegue su dirección en él .env, después instale un modelo IA local y configúrelo para que el programa lo reconozca adecuadamente, si usted busca una explicación más detalla de como configurar instalar y preparar completamente los archivos, esta se encuentra dentro del manual de Backend

# 💻 Estructura del proyecto

SportPro/

│

├── Main.py

├── .env

├── Basedatos.rar

│
├── models/

│   ├── __init__.py

│   ├── firebase.py

│   ├── rutina_base.py

│   ├── rutinas.py

│   ├── rutinas_futbol.py

│   ├── rutinas_baloncesto.py

│   ├── rutinas_tenis.py

│   ├── rutinas_nadacion.py

│   └── usuario.py

│
├── static/

│   ├── css/

│   │   └── style.css
│   │
│   └── img/

│       ├── logo.png

│       ├── imagenes_ejercicios.py

│       └── ejercicios/

│           └── (imágenes de ejercicios)

│
├── templates/

│   ├── base.html

│   ├── Encuesta.html

│   ├── Rutina.html

│   ├── Historial.html

│   ├── Usuario.html

│   ├── Ejercicios.html

│   └── Alarmas.html

│
└── viewmodels/

    └── rutinas_vm.py
    

# Licencia

Este proyecto es de uso público y cualquiera puede modificarlo o usarlo de base para un proyecto propio

Autores: Juan Sebastian Corredor Saenz, Sergio Alejandro Vazques Pineda, Diego Armando Perez Solano
Fecha de creacion: 4 de diciembre del 2025
Nombre del proyecto: SportPro
