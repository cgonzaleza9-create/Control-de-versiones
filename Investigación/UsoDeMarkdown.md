# Investigación sobre el lenguaje Mark Down y su integración en GitHub para el desarrollo

## Que es MarkDown y su origen

Markdown es un lenguaje de marcado ligero creado originalmente por John Gruber y Aaron Swartz en el 2004. La idea detrás de esto era permitir a las personas escribir usando un formato de texto plano que fuera fácil de leer y fácil de escribir, y que luego pudiera convertirse en XHTML o HTML valido. A diferencia de los procesadores de texto como Word que ocultan el formato detras de una interfaz grafica, en markdown tu escribes los símbolos directamente. Por ejemplo usas asteriscos para poner algo en negrita o guiones para hacer listas. Es muy popular porque no pesa nada y se abre en cualquier lado.

## Por que se usa tanto en proyectos de software

En el mundo del desarrollo de software el uso de markdown es casi obligatorio hoy en dia. La razon principal es que los desarrolladores trabajan con codigo fuente que es texto plano y markdown también es texto plano. Esto permite que la documentación viva junto al código en el mismo repositorio.

Además esta el tema del control de versiones. Herramientas como Git funcionan comparando líneas de texto para ver que cambio. Si escribieras la documentación en un PDF o un .docx, git no podría decirte que párrafo modificaste, pero con markdown te marca exacto la diferencia (diff). Esto facilita mucho el trabajo en equipo cuando varias personas editan la documentación al mismo tiempo. También ayuda a que no se pierda tiempo dando formato visual y el programador se concentre en el contenido técnico que es lo importante.

## Ventajas del uso de Markdown junto a Github

Cuando combinas markdown con la plataforma de github existen beneficios claros.

Primero esta la visualización inmediata. Github toma tus archivos con extensión .md y los muestra como si fueran una pagina web bien formateada. El archivo README.md es el ejemplo mas claro, es la cara del proyecto y github lo muestra abajo de los archivos automáticamente.

Segunda ventaja es el resaltado de sintaxis. Github usa una versión propia llamada Github Flavored Markdown (GFM) que permite poner bloques de código especificando el lenguaje, por ejemplo JavaScript o python, y github le pone colores a las variables y funciones lo cual es vital para que otros entiendan el código que compartes.

También es ligero y portátil, no necesitas instalar nada para leerlo, el navegador lo interpreta solo dentro de la interfaz de github.

## Desventajas y problemas comunes

Aunque es muy util tambien tiene sus cosas malas. La principal desventaja es la falta de estandarización total. Aunque existe una base común, github tiene su "sabor", gitlab tiene otro, y otros editores tienen el suyo. A veces escribes algo que se ve bien en tu computadora pero cuando lo subes a github se rompe la tabla o la lista no se indenta bien.

Otra limitante es el diseño. Markdown es para estructura no para diseño grafico. Si quieres centrar un texto, cambiar el color de la letra a rojo o poner una imagen flotando a la derecha, en markdown puro no se puede. Tienes que empezar a mezclar etiquetas de HTML dentro del archivo lo cual lo hace mas difícil de leer y mantener, perdiendo el propósito original de que fuera simple. Además para documentaciones muy extensas un solo archivo se vuelve eterno y difícil de navegar sin un índice generado automáticamente.

