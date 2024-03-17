# Bill of Materials (BOM) - Componentes Electrónicos

## Descripción General
Este documento lista los componentes necesarios para el desarrollo de la parte electrónica del proyecto LecturaColectiva.org, incluyendo lockers de libros con control de acceso y gestión via NFC.

## Lista de Materiales

| ID | Componente                     | Cantidad | Descripción                                  | Proveedor / Notas                       |
|----|--------------------------------|----------|----------------------------------------------|-----------------------------------------|
| 1  | Microcontrolador               | 1        | Ej: ESP32, para control y conectividad WiFi  | Seleccionar según requisitos de I/O y memoria |
| 2  | Módulo NFC/RFID                | 1        | Para la identificación y gestión de libros   | Asegurar compatibilidad con etiquetas NFC de libros |
| 3  | Pantalla LCD/TFT               | 1        | Interfaz de usuario para interacciones       | Seleccionar tamaño según el diseño del locker |
| 4  | Teclado Matricial o Touchpad   | 1        | Para la interacción del usuario              | Elegir basado en la experiencia de usuario deseada |
| 5  | Cerradura Electrónica/Solenoide| 1        | Para el mecanismo de bloqueo/desbloqueo      | Evaluar fuerza y voltaje requeridos |
| 6  | Fuente de Alimentación         | 1        | Para suministrar energía a los componentes   | Seleccionar según los requerimientos de potencia del sistema |
| 7  | Batería con Sistema de Carga   | 1        | Para operación autónoma                      | Considerar duración y tamaño según el uso |
| 8  | Sensor de Puerta               | 1        | Para detectar el estado de la puerta (abierta/cerrada) | |
| 9  | LEDs                           | Varios   | Para indicadores de estado                   | Seleccionar colores según las señales a indicar |
| 10 | Resistencias                   | Varios   | Para pull-ups/downs y divisores de voltaje   | Calcular valores según el circuito |
| 11 | Condensadores                  | Varios   | Para filtrado de alimentación y desacoplo    | Seleccionar valores comunes (100nF, 10µF, etc.) |
| 12 | Cables y Conectores            | Varios   | Para interconexión de componentes            | Incluir variedad para prototipado y montaje final |
| 13 | Caja o Enclosure               | 1        | Para alojar los componentes electrónicos     | Diseñar o seleccionar según dimensiones de componentes |
| 14 | Placa de Circuito Impreso (PCB)| 1        | Para el montaje definitivo de los componentes| Diseñar según el esquema electrónico final |
