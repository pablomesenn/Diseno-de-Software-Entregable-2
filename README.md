# Diseño de Software Entregegable 2
Documentación requerida sobre el proceso de desarrollo para el entregable #2 de Diseño de Software
## Primeros avances
En relación a los primeros 4 pasos explicados en las instrucciones del trabajo se han concretado los siguientes avances:

### Primer intento de diagramación del "Goal Diagram"

![image](https://github.com/user-attachments/assets/9cf6bdae-9899-4991-b662-f8f3646e41ce)

Este primer diagrama realizado tiene varios problemas que se lograron identificar a través de principalmente consultas al profesor, y
los cuales se listan a continuación: 

  1- Falta de entidades de cobro o de servicios tales como por ejemplos: La municipalidad, el ICE, el AyA, entre otros..
  
  2- Falta de pasos o "sub-objetivos" en relación a las entidades del punto 1, tales como: verificación de convenio o verificación de acceso a la API
  
  3- Falta de parelelismo entre los pasos que se relacionan a la configuración del pago

### Segundo intento de diagramación

En el caso del segundo intento de diagramación se tuvo el siguiente resultado:

![image](https://github.com/user-attachments/assets/af5d838f-6da7-4544-bd7f-7efc84d3a51d)

Donde los errores antes mencionados han sido corregidos. Por último, en este primer avance se ha logrado determinar cuales son los estados más importantes
y que aportan cierta garantía de éxito, esto gracias a las relaciones entre entidades y metas vistas en el diagrama. Estos se listan a continuación.

  1- Seleccionar método de pago

  2- Autenticación de usuario

## Desarollo de wireframes

Como continuación del desarollo del entregable se han desarrollado los wireframes de los dos estados (listados previamente) considerados como fundamentales para la garantía de éxito
del proyecto. A continuación los wireframes y una breve explicación de estos.

-> Seleccionar método de pago

![image](https://github.com/user-attachments/assets/532bad59-4423-41b4-94e1-b86a8392af33) 

Para este wireframe se ha tomado en cuenta el reconomiento de voz con implementación de IA, por lo que a este estado se llegaría después del procesamiento de las directrices por voz,
en donde su función es reflejar el método de pago dicho con anterioridad y confirmar su selección.

-> Autenticación de usuario

![image](https://github.com/user-attachments/assets/13b143de-cce4-466e-a8a3-61b666c48e56)

En el caso de la autenticación se usuario se ha supuesto que en base al método de pago se deberá de recibir un código por los mecanismos de la entidad bancaria o pasarela de pago seleccionada,
por lo que el usuario deberá de confirmar su identidad mediante este código para poder confirmar la información y realizar futuras transacciones automáticas.

