# Universidad Estatal de Milagro (UNEMI)

## Sistema de Pedidos para Cafetería Universitaria (SPCU)

**Información General**
El presente informe corresponde a la asignatura de Introducción a la Ingeniería de Software de la carrera de Ingeniería de Software. El trabajo fue realizado por los estudiantes Roger Escalante, Tyron Bayas, Carolina Gonzales, Milton Higuera y Holger Vera. El tema central es el análisis y mantenimiento del Sistema SPCU (web), diseñado para optimizar el servicio de alimentos, gestionar inventarios y puntos de venta en la universidad.

**Marco Teórico: Mantenimiento de Software**
El documento define el mantenimiento como la acción de asegurar que el software no se deteriore tras su construcción. Se describen cuatro tipos:

* **Correctivo:** Minimiza errores y fallas (ej. precios mal calculados o congelamientos).
* **Adaptativo:** Ajusta el sistema a cambios del entorno externo, como nuevas leyes fiscales o nuevos dispositivos.
* **Perfectivo:** Mejora la experiencia del usuario y la eficiencia (ej. mayor velocidad o usabilidad).
* **Preventivo:** Mantenimiento interno para evitar fallas futuras (refactorización o limpieza de código).

**Análisis de Situaciones Problemáticas**
Durante el análisis del caso SPCU, se identificaron varias áreas de mejora y riesgos:

* **Riesgo de saturación:** El sistema permitía pedidos básicos pero no limitaba la cantidad según la capacidad de la cocina, lo que podía frustrar el objetivo de reducir tiempos de espera.
* **Falta de medición de calidad:** Ausencia de herramientas para que los clientes califiquen el servicio, impidiendo a la administración evaluar la satisfacción real.
* **Información incompleta:** El menú carecía de datos críticos como listas de ingredientes, información nutricional o alérgenos.
* **Problemas operativos:** Desfase entre pedidos e inventario (productos agotados aparecían disponibles) e interfaz poco intuitiva para nuevos usuarios.

**Aplicación de Fases de Mantenimiento**
El equipo propuso acciones específicas para cada tipo de mantenimiento:

* **Correctivo:** Corrección de errores en la visualización de precios, fallos en la interfaz y lógica de disponibilidad de productos.
* **Adaptativo:** Implementación de pagos en línea para facilitar transacciones y ajuste del IVA.
* **Perfectivo:** Rediseño de la interfaz para optimizar el flujo de pedidos y mejorar la usabilidad.
* **Preventivo:** Implementación de un sistema de calificación de servicio y pruebas automáticas para análisis de riesgos.

**Cambio Funcional Propuesto: Módulo de Calificación**
Como mejora principal, se propuso integrar un **Módulo de Calificación de Servicio y Producto**.

* **Funcionamiento:** Tras recoger el pedido, el sistema solicita al usuario una retroalimentación (estrellas y comentarios).
* **Objetivo:** Pasar de suposiciones a datos reales sobre qué platos gustan y cómo es el servicio.
* **Impacto:** Fomenta la responsabilidad del personal y convierte la plataforma en un medio de comunicación bidireccional, fortaleciendo el mantenimiento preventivo basado en datos reales.

**Conclusiones y Reflexión Final**
El mantenimiento del software representa un costo sustancial y es un proceso continuo y estratégico, no solo técnico. El desarrollo del caso permitió a los estudiantes identificar errores, aplicar teoría en un entorno práctico y justificar mejoras que optimizan la experiencia del usuario, adaptan el sistema a nuevas tecnologías y previenen problemas futuros.

