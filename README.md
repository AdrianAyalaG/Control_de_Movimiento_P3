# Sevomotores, Motores, Sensores y Drivers de Potencia en Control de movimiento
Los ingenieros emplean servomotores, motores, sensores y drivers de potencia en diversos sistemas electromecánicos, donde cada componente cumple una función específica para garantizar un control preciso y un rendimiento óptimo. Mientras que los motores convierten la energía eléctrica en movimiento, los servomotores permiten regular con exactitud su posición, velocidad y torque gracias a un sistema de retroalimentación. Los sensores, por su parte, miden variables clave como las anteriormente mencionadas, proporcionando información esencial para un control eficiente. Complementando estos elementos, los drivers de potencia regulan la energía suministrada a los motores, optimizando su desempeño y protegiéndolos de sobrecargas o fallos. Un uso inadecuado de estos dispositivos podría generar limitaciones mecánicas o forzar un elemento más allá de sus capacidades, afectando el funcionamiento del sistema. Por ello, es fundamental comprender los distintos tipos, características y aplicaciones de estos componentes para su correcta implementación.

# 1. Servomotores
> 🔑Definición: La palabra servomotor proviene del latín servus (Esclavo) haciendo referencia a un motor que que sirve para ejecutar movimientos con precisión. Un servomotor es un actuador electromecánico que combina un motor, un sistema de retroalimentación y un controlador para regular con exactitud su posición, velocidad y Torque. 

## 1.1 Variables a controlar de un servomotor

foto unu

## 1.2 Componentes 

foto unu

* El servomotor permite control mecánico ON - OFF

# 2. Motores

foto unu

## 2.1 Tipos de motores
### 2.1.1 Motor DC

foto unu

> 🔑Definición: Los motores DC están compuestos por un rotor (bobinado) y un estator, que genera un campo magnético mediante imanes. La interacción entre el campo magnético del estator y la corriente en el bobinado del rotor produce una fuerza electromagnética que genera el movimiento. Además, las escobillas permiten la transferencia de corriente al embobinado del rotor, asegurando una continuidad.

* Hay un consumo alto en este motor, Hay mucha potencia, pero a más potencia se necesita más tamaño del motor.
* Cuentan con un colector de delgas que Su función principal es actuar como un conmutador mecánico, permitiendo que la corriente cambie de dirección en las bobinas del rotor conforme este gira, manteniendo así un movimiento continuo. 

### 2.1.2 Motor AC
Existen dos tipos de motores de corriente alterna. Estos dos tipos son: 
#### 2.1.2.1 Motor Síncrono 

foto unu

* Está compuesto de multiples bobinas con imanes permanentes (Niodimio). Estos imanes pueden tardar demasiado en desigmantarse, por lo que son ideales para un motor que tendrá un uso constante. 
* No hay una conexión permanente con las escobillas.
* La velocidad de rotación está vinculada con la frecuencia de la red (AC), por lo tanto hay un movimiento simultaneo.
* Es el motor más ideal de todos los tipos de motores existentes para el control de movimiento.
* Es un motor que recibe corriente trifásica, pues las bobinas están divididas en tres partes.

#### 2.1.2.2 Motor aSíncrono 

  foto unu

> 🔑Definición del movimiento: El movimiento se produce cuando la corriente alterna en el estator genera un campo magnético giratorio. Este campo induce una corriente en el rotor, creando a su vez un campo magnético que intenta seguir al del estator. Como nunca lo puede alcanzar por la velocidad de este, se genera un efecto de arrastre.

* Tiene embobinados en el rotor y en el estator.
* El campo magnético generado por las bobinas del estator induce una corriente en el rotor.
* Torque grande = Motor más grande.


  


