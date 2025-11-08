**Parte 1: Análisis comparativo de modelos de desarrollo de software**


Completa la siguiente tabla comparativa. Deberás investigar y extraer la información directamente de los materiales del curso, citando las fuentes para cada punto relevante.


| Característica/Aspecto          | Modelos Clásicos (Predictivos)                                                                                                                                                                        | Modelos Evolutivos o Incrementales                                                                                                                                                                                        | Metodologías Ágiles (Adaptativas)                                                                                                                                                                                                                 |
|:---------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Definición Principal            | Los modelos clásicos son rígidos, secuenciales y planificados de antemano. Por ejemplo, el Modelo en Cascada plantea que cada fase debe completarse antes de pasar a la siguiente.                   | Modelos más modernos que tienen en cuenta la naturaleza cambiante y evolutiva del software que plantean desarrollar una implementación inicial, someterla a comentarios del usuario y refinarla en sucesivas versiones. | Las metodologías ágiles se basan en el desarrollo iterativo e incremental, la colaboración, la adaptación al cambio y entregas frecuentes.                                                                                                      |
| Características Clave / Enfoque | • Enfoque lineal y documentado.<br>• Definición completa de requisitos al inicio.<br>• Fases bien definidas: preanálisis, análisis, diseño, desarrollo, pruebas, implantación y mantenimiento. | • Enfoque iterativo e incremental.<br>• Se repiten actividades de especificación, desarrollo y pruebas.<br>• Permite realimentación del usuario de forma relativamente temprana.                                     | • Individuos e interacciones sobre procesos y herramientas.<br>• Software funcionando sobre documentación extensiva.<br>• Colaboración con el cliente sobre negociación contractual.<br>• Respuesta ante el cambio sobre seguir un plan.<br> |
| Ventajas (Pros)                  | • Buena previsibilidad cuando los requisitos son estables.<br>• Documentación detallada.<br>• Estructura clara y control del proceso.                                                              | • Reduce riesgos al entregar partes funcionales tempranamente.<br>• Permite validación de incrementos con usuarios.<br>• Más flexible frente a cambios que el modelo predictivo.                                     | • Alta capacidad de respuesta al cambio.<br>• Entregas frecuentes generan valor más rápidamente.<br>• Mejor implicación del cliente y del equipo.<br>• Mejora continua del producto.                                                         |
| Desventajas (Contras)            | • Muy baja adaptabilidad al cambio.<br>• Los errores descubiertos tarde son muy caros.<br>                                                                                                           | • Puede requerir mayor gestión de versiones e integración.<br>• Riesgo de fragmentación funcional o arquitectónica si no se coordina bien.<br>                                                                      | • Puede faltar documentación formal detallada.<br>• Requiere equipo disciplinado y comunicación frecuente.<br>                                                                                                                                  |
| Aportación en la Actualidad     | En la actualidad solo se aplica a pequeños desarrollos, debido a que en las etapas se pasa de una a otra sin retorno posible.                                                                         | En la actualidad, estos modelos se aplican mucho en combinación con metodologías ágiles donde el desarrollo evolutivo e incremental permite adaptarse a cambios frecuentes.                                            | Actualmente es el enfoque predominante en la industria del software, gracias a su adaptabilidad, entrega continua de valor y enfoque centrado en el cliente.                                                                                        |






**Parte 2: Reflexión sobre la detección y corrección de fallos y cambios**


Basándote en las fases del ciclo de vida del software y en los diferentes modelos de desarrollo estudiados, responde y reflexiona sobre las siguientes cuestiones:


1. Corrección de cambios y fallos en diferentes modelos: Explica cómo los distintos tipos de modelos de desarrollo (clásicos, evolutivos, ágiles) manejan la corrección de fallos y la incorporación de cambios una vez que el proyecto ha avanzado:




+ ¿Cómo aborda la realimentación y la posibilidad de "volver atrás" el Modelo en Cascada con Realimentación?


El Modelo en Cascada con Realimentación es una variante del modelo clásico predictivo. La realimentación significa que las fases posteriores alimentan a las anteriores.


La posibilidad de "volver atrás" permite que, una vez que se ha iniciado un desarrollo secuencial (preanálisis → análisis → diseño → desarrollo → pruebas → implantación → mantenimiento), se pueda retroceder desde una fase posterior a una anterior para corregir o ajustar lo que se hizo. Por ejemplo, si en la fase de pruebas aparece un error o un requisito mal interpretado, se puede regresar a diseño o incluso a análisis para modificar lo detectado, en lugar de esperar al final.




Sin embargo, este “volver atrás” no es tan ágil como en modelos más flexibles. Sigue habiendo costosos replanteamientos, documentación a modificar, fases ya cerradas que requieren reabrirse, etc. Por lo tanto, aunque permite realimentación, lo hace a cambio de tiempo, coste y esfuerzo.




+ ¿Cómo permiten los Modelos Evolutivos o Incrementales "refinar en sucesivas versiones" el sistema y la "rápida realimentación del usuario"?


Los Modelos Evolutivos o Incrementales tienen mecanismos que favorecen la "rápida realimentación del usuario" y permiten "refinar en sucesivas versiones". En estos modelos se lanza una versión inicial del sistema que permite al usuario o cliente interactuar con una parte real del producto. Luego, en versiones sucesivas, se añade funcionalidad, se mejora la existente o se corrigen fallos.


La "rápida realimentación del usuario", surge porque estos ven versiones funcionales temprano y pueden comentar o sugerir mejoras, lo que reduce el riesgo de acabar con un producto que no cumple bien sus expectativas. Esta estrategia permite refinar el sistema incorporando los aprendizajes del anterior, los errores detectados, los feedbacks del cliente y los requisitos emergentes. Así, el ciclo desarrollo–prueba–retroalimentación se acorta, lo que mejora la capacidad de adaptación del proyecto.




+ ¿Cómo las Metodologías Ágiles, con su enfoque en la "respuesta ante el cambio", las "iteraciones (sprint)" y las "pequeñas mejoras continuas" (XP), facilitan la adaptación y la corrección?


Las metodologías ágiles están diseñadas precisamente para manejar entornos cambiantes, corregir errores rápidamente y adaptarse a nuevas necesidades.


Estas relacionan “respuesta ante el cambio” con seguir un plan rígido. Esto significa que están preparadas para incorporar cambios de requisitos o correcciones en cualquier momento, lo que favorece la adaptabilidad.


Se organizan en "iteraciones cortas o sprints", ciclos de trabajo breves y repetitivos en los cuales se entrega algo funcional. Esa entrega permite obtener feedback temprano, detectar fallos, corregirlos y ajustar prioridades.


En enfoques como XP se habla de “pequeñas mejoras continuas” que refactorizan el código, realizan una integración continua, pruebas automáticas y una colaboración constante. Estas prácticas reducen el coste de corrección y mantenimiento, y facilitan que los cambios se incorporen frecuentemente.


Debido a esto, la adaptación y corrección de errores se convierten en parte normal del desarrollo, no algo que ocurre solo al final.




+ Finalmente, describe el papel fundamental de la Fase de Mantenimiento en la corrección de defectos ("mantenimiento correctivo") y la adaptación a nuevas situaciones ("mantenimiento evolutivo y adaptativo") a lo largo de la vida útil del software.


La fase de mantenimiento es fundamental en el ciclo de vida del software porque es la que permite que el sistema siga siendo útil, fiable y adaptado a lo largo del tiempo.


El "mantenimiento correctivo" se ocupa de la corrección de defectos o fallos detectados una vez que el software está en operación. No todos los errores se detectan antes de la puesta en marcha, por lo que el "mantenimiento correctivo" es clave para restaurar el funcionamiento esperado.


Por otro lado, el "mantenimiento evolutivo", se centra en añadir mejoras, nuevas funcionalidades o incrementar la calidad del software en respuesta a nuevas necesidades del usuario.


Por último, el "mantenimiento adaptativo" trata de ajustar el software a nuevos entornos tecnológicos o de negocio.


Esta fase no es solo arreglar lo que está mal, sino también mantener lo que funciona y adaptarlo al cambio. El software no se desgasta en el sentido físico pero sí en su contexto; por ello, el mantenimiento se convierte en la fase más prolongada y activa de su ciclo de vida. Además, invertir en este permite que el sistema tenga una mayor vida útil, que se reduzcan los riesgos de obsolescencia, que se mejore la satisfacción del cliente, y que se adapten cambios externos sin tener que desarrollar un sistema completamente nuevo.
