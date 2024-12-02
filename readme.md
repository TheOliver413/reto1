
## Simulador de Viajes Espaciales 🚀

### Descripción

El Simulador de Viajes Espaciales es una aplicación de consola en Java que permite a los usuarios seleccionar un planeta de destino, elegir una nave espacial y calcular los recursos necesarios para realizar un viaje interplanetario. Además, incluye una simulación interactiva que presenta eventos aleatorios durante el trayecto, como encuentros con asteroides o fallos del sistema.

Este proyecto es ideal para aprender conceptos básicos de programación en Java, como:

* Estructuras de control.
* Métodos y clases estáticas.
* Uso de arreglos y manipulación de datos.
* Simulación de eventos aleatorios.

### Características principales

* Selección de planetas: Opción para elegir entre varios planetas del sistema solar y obtener su distancia desde la Tierra.
* Selección de naves espaciales: Cinco naves famosas del cine con características únicas.
* Cálculo de recursos: Determina el combustible y el oxígeno necesario según la distancia y la cantidad de pasajeros.
* Simulación interactiva: Representación visual del progreso del viaje con eventos aleatorios.
* Interfaz mejorada: Uso de colores ANSI para hacer la experiencia en consola más atractiva.


### Requisitos del sistema
* Java Development Kit (JDK): versión 8 o superior.
* Sistema operativo: Windows, macOS, Linux.
* Editor recomendado: IntelliJ IDEA, Eclipse, o cualquier editor con soporte para Java.


### Instalación

* Clona el repositorio:

```bash
  git clone https://github.com/TheOliver413/reto1.git
```

* Navega al directorio del proyecto:

```bash
  cd reto1
```

* Compila el programa:

```bash
  javac main.java
```

* Ejecuta la aplicación:

```bash
  java main
```

### Uso

* Ejecuta el programa en la consola.
* Sigue las opciones del menú principal:
  * 1 Selecciona un planeta de destino.
  * 2 Elige una nave espacial.
  * 3 Calcula la distancia, el tiempo y los recursos necesarios.
  * 4 Muestra los datos seleccionados (planeta y nave).
  * 5 Lista todos los planetas y naves disponibles.
  * 6 Inicia la simulación del viaje.

### Detalles técnicos
#### Naves espaciales
Cada nave tiene un nombre y una velocidad específica. Aquí están las naves incluidas:

* Millennium Falcon (Star Wars)
* USS Enterprise (Star Trek)
* Nostromo (Alien)
* Serenity (Firefly)
* Discovery One (2001: A Space Odyssey)

#### Planetas disponibles
Los planetas seleccionables incluyen:

* Mercurio. 
* Venus. 
* Tierra. 
* Marte. 
* Júpiter. 
* Saturno.  
* Urano. 
* Neptuno.
* Plutón.

#### Cálculo de recursos
* Combustible necesario: 𝑑𝑖𝑠𝑡𝑎𝑛𝑐𝑖𝑎 × 0.1 distancia × 0.1 toneladas por kilómetro.

* Oxígeno necesario: 𝑝𝑎𝑠𝑎𝑗𝑒𝑟𝑜𝑠 × 0.5 pasajeros × 0.5 kg por hora de viaje.

* Eventos aleatorios en la simulación
  * Asteroides detectados.
  * Fallos en el sistema.
  * Progresos sin inconvenientes.


## Contacto

### Desarrollador: Oliver Sebastián Borda Mahecha
### Correo electrónico: oliverborda04@outlook.com