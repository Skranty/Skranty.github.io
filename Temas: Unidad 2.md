---
layout: post
title: Unidad 2
---

### Ciclo de Vida de un Software:

![_config.yml]({{ site.baseurl }}/images/64.jpg)

ESPECIFICACIONES:
Formalizamos los requerimientos; el documento obtenido en la etapa anterior se tomará como punto de partida para esta etapa.

#### ANÁLISIS:
Determinamos los elementos que intervienen en el sistema a desarrollar, su estructura, relaciones, evolución temporal, funcionalidades, tendremos una descripción clara de qué producto vamos a construir, qué funcionalidades aportará y qué comportamiento tendrá.
#### DISEÑO:
Ya sabemos qué hacer, ahora tenemos que determinar cómo debemos hacerlo (¿cómo debe ser construido el sistema en cuestion?; definimos en detalle entidades y relaciones de las bases de datos, seleccionamos el lenguaje que vamos a utilizar, el Sistema Gestor de Bases de Datos, etc.).
#### IMPLEMENTACIÓN:
Empezamos a codificar algoritmos y estructuras de datos, de- finidos en las etapas anteriores, en el correspondiente lenguaje de programación o para un determinado sistema gestor de bases de datos. En muchos proyectos se pasa directamente a esta etapa; son proyectos muy arriesgados que adoptan un modelo de ciclo de vida de code & fix (codificar y corregir) donde se eliminan las etapas de especificaciones, análisis y diseño con la consiguiente pérdida de control sobre la gestión del proyecto.
#### DEBUGGING:
El objetivo de esta etapa es garantizar que nuestro programa no contiene errores de diseño o codificación. En esta etapa no deseamos saber si nuestro programa realiza lo que solicitó el usuario, esa tarea le corresponde a la etapa de implementación. En ésta deseamos encontrar la mayor cantidad de errores. Todas los programas contienen errores: encontrarlos es cuestión de tiempo. Lo ideal es encontrar la mayoría, si no todos, en esta etapa. También se pueden agregar testeos de performance.
#### VALIDACIÓN:
Esta etapa tiene como objetivo la verificación de que el sistema desarrollado cumple con los requerimientos expresados inicialmente por el cliente y que han dado lugar al presente proyecto. En muchos proyectos las etapas de validación y debugging se realizan en paralelo por la estrecha relación que llevan. Sin embargo, tenemos que evitar la confusión: podemos realizarlos en paralelo, pero no como una única etapa.
#### EVOLUCIÓN:
En la mayoría de los proyectos se considera esta etapa como Mantenimiento y evolución, y se le asigna, no sólo el agregado de nuevas funcionalidades (evolución); sino la corrección de errores que surgen (mantenimiento). En la práctica esta denominación no es del todo errónea, ya que es posible que aun luego de una etapa de debugging y validación exhaustiva, se filtren errores.

### El Proceso de desarrollo de Software:

![_config.yml]({{ site.baseurl }}/images/jeje.jpg)

Un proceso de desarrollo de software tiene como propósito la producción eficaz y eficiente de un producto software que reúna los requisitos del cliente. Dicho proceso, en términos globales se muestra en la Figura 2 . Este proceso es intensamente intelectual, afectado por la creatividad y juicio de las personas involucradas. Aunque un proyecto de desarrollo de software es equiparable en muchos aspectos a cualquier otro proyecto de ingeniería, en el desarrollo de software hay una serie de desafíos adicionales, relativos esencialmente a la naturaleza del producto obtenido. A continuación se explican algunas particularidades asociadas al desarrollo de software y que influyen en su proceso de construcción.

Un producto software en sí es complejo, es prácticamente inviable conseguir un 100% de confiabilidad de un programa por pequeño que sea. Existe una inmensa combinación de factores que impiden una verificación exhaustiva de las todas posibles situaciones de ejecución que se puedan presentar (entradas, valores de variables, datos almacenados, software del sistema, otras aplicaciones que intervienen, el hardware sobre el cual se ejecuta, etc.). Un producto software es intangible y por lo general muy abstracto, esto dificulta la definición del producto y sus requisitos, sobre todo cuando no se tiene precedentes en productos software similares. Esto hace que los requisitos sean difíciles de consolidar tempranamente. Así, los cambios en los requisitos son inevitables, no sólo después de entregado en producto sino también durante el proceso de desarrollo.

Además, de las dos anteriores, siempre puede señalarse la inmadurez de la ingeniería del software como disciplina, justificada por su corta vida comparada con otras disciplinas de la ingeniería. Sin embargo, esto no es más que un inútil consuelo.
El proceso de desarrollo de software no es único. No existe un proceso de software universal que sea efectivo para todos los contextos de proyectos de desarrollo. Debido a esta diversidad, es difícil automatizar todo un proceso de desarrollo de software.
A pesar de la variedad de propuestas de proceso de software, existe un conjunto de actividades fundamentales que se encuentran presentes en todos ellos:

•	Especificación de software: Se debe definir la funcionalidad y restricciones operacionales que debe cumplir el software.
•	Diseño e Implementación: Se diseña y construye el software de acuerdo a la especificación.
•	Validación: El software debe validarse, para asegurar que cumpla con lo que quiere el cliente.
•	Evolución: El software debe evolucionar, para adaptarse a las necesidades del cliente.
•	Además de estas actividades fundamentales, Pressman menciona un conjunto de “actividades protectoras”, que se aplican a lo largo de todo el proceso del software. Ellas se señalan a continuación:
•	Seguimiento y control de proyecto de software.
•	Revisiones técnicas formales.
•	Garantía de calidad del software.
•	Gestión de configuración del software.
•	Preparación y producción de documentos.
•	Gestión de reutilización.
•	Mediciones.
•	Gestión de riesgos.
Pressman caracteriza un proceso de desarrollo de software como se muestra en la Figura 3. Los elementos involucrados se describen a continuación:
•	Un marco común del proceso, definiendo un pequeño número de actividades del marco de trabajo que son aplicables a todos los proyectos de software, con independencia del tamaño o complejidad.
•	Un conjunto de tareas, cada uno es una colección de tareas de ingeniería del software, hitos de proyectos, entregas y productos de trabajo del software, y puntos de garantía de calidad, que permiten que las actividades del marco de trabajo se adapten a las características del proyecto de software y los requisitos del equipo del proyecto.
•	Las actividades de protección, tales como garantía de calidad del software, gestión de configuración del software y medición, abarcan el modelo del proceso. Las actividades de protección son independientes de cualquier actividad del marco de trabajo y aparecen durante todo el proceso.

### Metodologías ágiles en el desarrollo de software:

![_config.yml]({{ site.baseurl }}/images/15.jpg)

Históricamente, el desarrollo de software ha sido una tarea tediosa y compleja, donde muchas veces la rentabilidad de la misma estaba muy por debajo de su coste. Eran épocas de desarrollos interminables, de infinidad de líneas de código donde cualquier cambio en el proyecto inicial suponía un auténtico quebradero de cabeza para el desarrollador. La poca (o nula) tolerancia y/o previsión a cambios, los métodos arcaicos de programación, etc. no contribuían a generar un ecosistema adecuado para el correcto desarrollo de software.
Con el paso de los años, fueron surgiendo nuevos lenguajes de programación (en teoría más sencillos…), entornos más amigables, frameworks que facilitaban muchas tareas, conceptos que las empresas dedicadas al desarrollo de software acogieron rápidamente para mejorar la calidad y los plazos de entrega de sus proyectos. Pero, ¿es esto suficiente en la actualidad?
Obviamente, ¡NO!
En un mundo tan cambiante, donde predominan los tiempos y la rentabilidad, muchas veces las empresas olvidan el tercer factor fundamental… la calidad. Pero, ¿es posible meter estas tres variables en la ecuación y obtener un resultado positivo?
Obviamente, ¡SÍ!

### 12 Principios Del Manifiesto Ágil:

1.	Nuestra mayor prioridad es satisfacer al cliente mediante la entrega temprana y continua de software con valor.
2.	Aceptamos que los requisitos cambien, incluso en etapas tardías del desarrollo. Los procesos Ágiles aprovechan el cambio para proporcionar ventaja competitiva al cliente.
3.	Entregamos software funcional frecuentemente, entre dos semanas y dos meses, con preferencia al periodo de tiempo más corto posible.
4.	Los responsables de negocio y los desarrolladores trabajamos juntos de forma cotidiana durante todo el proyecto.
5.	Los proyectos se desarrollan en torno a individuos motivados. Hay que darles el entorno y el apoyo que necesitan, y confiarles la ejecución del trabajo.
6.	El método más eficiente y efectivo de comunicar información al equipo de desarrollo y entre sus miembros es la conversación cara a cara.
7.	El software funcionando es la medida principal de progreso.
8.	Los procesos Ágiles promueven el desarrollo sostenible. Los promotores, desarrolladores y usuarios debemos ser capaces de mantener un ritmo constante de forma indefinida.
9.	La atención continua a la excelencia técnica y al buen diseño mejora la Agilidad.
10.	La simplicidad, o el arte de maximizar la cantidad de trabajo no realizado, es esencial.
11.	Las mejores arquitecturas, requisitos y diseños emergen de equipos auto-organizados.
12.	A intervalos regulares el equipo reflexiona sobre cómo ser más efectivo para a continuación ajustar y perfeccionar su comportamiento en consecuencia.
Por tanto, las tres variables se asocian perfectamente en la ecuación “metodologías ágiles”, lo que significa que una empresa dedicada al desarrollo de software que no opte por una metodología ágil difícilmente podrá sobrevivir al entorno actual pero, sobre todo, a los nuevos tiempos que se avecinan.
Es decir, la duda no debería ser ¿es necesario utilizar una metodología ágil para desarrollar software? La duda, más bien, debería ser ¿qué metodología ágil escojo para desarrollar software?
Algunas de las principales opciones, a día de hoy, son:
1.	Scrum: “Scrum es un marco de trabajo para desarrollar, entregar y mantener productos complejos”.
2.	eXtreme Programming (XP): “Extreme Programming (XP) es un marco de desarrollo de software ágil que tiene como objetivo producir software de mayor calidad y una mejor calidad de vida para el equipo de desarrollo.”
3.	Kanban: “Sistema de información que controla de modo armónico la fabricación de los productos necesarios en la cantidad y tiempo necesarios en cada uno de los procesos.”
4.	Scrumban: metodología que utiliza lo mejor de scrum y de kanban.
5.	Lean: “Originado en el Sistema de Producción de Toyota, este método ofrece todo un marco teórico sólido y basado en la experiencia, para las prácticas ágiles de gestión.”
6.	Feature-Driven Development (FDD): “Feature-Driven Development (FDD) es una metodología ágil basada en la calidad y el monitoreo constante del proyecto.”
7.	Test-Driven Development (TDD): “Test-Driven Development es un proceso de desarrollo de software que se basa en la repetición de un ciclo de desarrollo muy corto: los requisitos se convierten en casos de prueba muy específicos, luego se mejora el software para pasar las nuevas pruebas.”

Un proceso de software ágil debe adaptarse incrementalmente. Para lograr la adaptación incremental, un equipo ágil requiere retroalimentación con el cliente (de modo que sea posible hacer las adaptaciones apropiadas). Un catalizador eficaz para la retroalimentación con el cliente es un prototipo operativo o una porción de un sistema operativo. 
