# Informe de solución.

## Área técnica

### Aplicación móvil

Se necesita desarrollar una aplicación móvil que sea capaz de interactuar con el API y permita al usuario visualizar distintos datos sobre su informacion personal, efectivo, etc.

La principal característica de ésta aplicación es que puede conectarse con la API con el objetivo de realizar operaciones tales como:

+Transacciones bancarias.
+Consultar información del usuario.
+Visualizar los movimientos del usuario.

### API (que será consumada por la aplicación móvil)

El objetivo de este componente de software es permitir la conexión del usuario con el resto de los componentes del sistema, por ejemplo la base de datos y los otros servicios que conjunto forman la infraestructura del sistema.

Al ser la API solo un intermediario entre el usuario (a través de la aplicación móvil) y el core, la API debe de ofrecer de las funciones tales como:

+Realizar una transacción.
+Realizar una petición a la base de datos pertinente para poder visualizar la información del usuario y poder retornar esta a la aplicación móvil.
+Realizar la verificación pertinente de los datos cuando se requiera realizar una operación.

### Servicios de clabes y transferencias

Este será un servicio proporcionado por el banco de México en conjunto con otros bancos que operan en la república mexicana. Ellos proporcionarán cierta API que de acuerdo a su infraestructura deberemos de adaptar el flujo de datos de la aplicación para que a través de la conexión a ella puedan
realizarse todas las transferencias interbancarias bajo la cual se sustentará la aplicación.

## Área comercial

Se desarrollará una aplicación la que ahora permitirá al usuario realizar todos sus movimientos directamente desde su móvil, permitiendo visualizar su información y su estado de cuenta.