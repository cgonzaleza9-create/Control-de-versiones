# Resumen Técnico y General del Caso 

La documentación analizada abarca el ciclo de vida de desarrollo de software, específicamente centrado en un Sistema de Pedidos para una Cafetería Universitaria (SPCU), así como una investigación técnica sobre herramientas de documentación. Los archivos presentan una visión integral que va desde la definición de requisitos y pruebas de calidad hasta propuestas de mantenimiento y el uso de lenguajes de marcado para la gestión del código y la documentación.

### Definición de Requisitos del Sistema
El núcleo del proyecto se detalla en el Documento de Requisitos de Software (DRS). Este sistema tiene como propósito automatizar y optimizar la gestión de pedidos para reducir tiempos de espera y mejorar la organización entre estudiantes, personal administrativo y cocina. El documento establece roles claros: administradores que gestionan el menú e inventario, personal de cocina que actualiza estados de preparación y clientes que realizan pedidos.

Los requisitos funcionales incluyen la gestión de altas y bajas de productos, el registro de pedidos con especificaciones de cantidad y pago, el control de estados (pendiente, listo, entregado) y la generación de comprobantes digitales. Por otro lado, los requisitos no funcionales priorizan la usabilidad, exigiendo flujos de compra en menos de tres pasos, una disponibilidad del servicio del 99% y tiempos de procesamiento inferiores a tres segundos, además de garantizar la seguridad de los datos.

### Estrategia de Pruebas y Aseguramiento de Calidad
Para validar el cumplimiento de los requisitos, se presenta una estructura de pruebas dividida en pruebas unitarias y de validación. Las pruebas unitarias se centran en verificar módulos específicos, como la correcta inserción de un producto en la base de datos, la generación de un número de orden único y la actualización de estados en el flujo de trabajo.

Las pruebas de validación se enfocan en la experiencia integral, confirmando que el sistema genera comprobantes con los montos correctos y que la interfaz es lo suficientemente intuitiva para que un usuario nuevo complete una transacción sin errores. La reflexión final sobre esta etapa subraya que las pruebas no solo detectan fallos técnicos, sino que aseguran que el producto final se alinee con las expectativas reales del usuario.

### Propuesta de Mantenimiento y Evolución
El análisis se extiende a la fase de post-implementación mediante una propuesta de mantenimiento elaborada por un equipo de estudiantes. Se identifican riesgos operativos como la saturación de pedidos y la desincronización de inventarios. Para mitigar esto, se proponen cuatro tipos de mantenimiento:
* **Correctivo:** Solución de errores en cálculos de precios y fallos de interfaz.
* **Adaptativo:** Integración de pasarelas de pago en línea y ajustes fiscales.
* **Perfectivo:** Rediseño de la interfaz para mejorar la usabilidad.
* **Preventivo:** Implementación de un módulo de calificación para obtener retroalimentación constante y prevenir la insatisfacción del usuario.

### Herramientas de Documentación Técnica
Finalmente, se incluye una investigación sobre el lenguaje Markdown y su relevancia en el desarrollo de software moderno. Se destaca su integración con plataformas como GitHub, permitiendo que la documentación resida junto al código fuente en formato de texto plano. Esto facilita el control de versiones, ya que permite detectar cambios específicos en la documentación de la misma manera que en el código. Aunque se reconocen limitaciones en cuanto a diseño gráfico y estandarización, se valora su ligereza, portabilidad y capacidad para el resaltado de sintaxis técnica.

