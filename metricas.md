El presente documento es un referente teórico para la discusión respecto a la 
forma de medir la producción de software.


Métricas de Proceso y Proyecto

* MEDIDA:  Valor asignado a un atributo de una entidad mediante una medición.
	   Ejemplo: 35000 líneas de código

* MEDICION: Es el acto de determinar una medida.
	    Ejemplo: Ana será la encvargada de medir las LDC de cada módulo del
                     sistema.

* Métrica: Medida cuantitativa del grado en que un sistema, componente o proceso
           posee un atributo dado. Incluye el método de medición.
	   Ejemplo: La productividad de este proyecto fue de 500 líneas 
	   (LDC/personas-mes)

* Indicador: Es una métrica o combinación de métricas que proporcionan una visión 
	     profunda del proceso de software.
	     Ejemplo: La productividad media de nuestra empresa es de 500 (LDC/pm)

nota: hasta aquí podemos percibir indicadores cuantitativos que serviran como medida 
      numerico estadistico, frío y sin análisis, debemos entonces considerar que el 
      desempeño de los equipos de desarrollo no puede ser comprendido en su amplitud
      sin considerar el impacto en las dimensiones humanas (tan necesarias para el 
      análisis crítico de las condiciones objetivas y materiales que lo componen), es 
      decir este referente teorico-cientifico-numérico debe ser solapado con las 
      dimensiones de impacto político, económico, comunicacional y orgánico, tan necesarios
      para no deshumanizar la tarea de creación misma.

      Esto se nota ya que las métricas sirven para entender los procesos técnicos para el 
      desarrollo de un producto, pero sin tomar en cuenta el impacto del producto mismo sobre
      los hombres que lo crean y más aún hacia la orgánica a quien beneficia el mismo.

      Tanto es así que las métricas mismas están sometidas a la interpretación de un grupo de 
      personas que por especialicimas condiciones se convierten en los gestores del software.

Existen métricas para el proyecto y para los procesos:

      En este esntendido se calculan unas estimaciones iniciales que dimensionan el proyecto
de forma cronológica y de recursos por lo general se da está etapa durante el proceso de estimación
y debe ser lo suficientemente holgado y flexible a las futuras modificaciones. La estimación de 
métricas estáticas y pocos variables es la negación a la dinámica de la naturaleza misma.

      Por esto conforme el proyecto avanza las medidas de esfuerzo y tiempo utilizados, se comparan
con las estimaciones iniciales y se replantean (planificación y re organización de metas, es aquí
donde debemos incluir el análisis reflexivo y de dimensiones arriba expuesto).

      Para las métricas del proyecto se miden los índices de producción representados en términos de 
modelos creados, horas de revisión, puntos de función y líneas fuentes entregadas.

La finalidad de las métricas del proceso:

      Se emplean para minimizar el tiempo de desarrollo.

MEDICION DEL SOFTWARE:

	1.) Medidas directas del proceso de software (costo/esfuerzo) y del producto (Líneas de 
	    código producidas, rapidez de ejecución y efectos reportados)

	2.) Medidas indirectas del producto que incluyen: funcionalidad, calidad, complejidad, 
	    eficiencia, confiabilidad, facilidad de mantenimiento, documentación.

METRICAS ORIENTADAS AL TAMAÑO:

	Son aceptadas universalmente como la mejor forma de medir el tamaño del proceso.

METRICAS ORIENTADAS A LA FUNCION:

	Se emplean como valor de normalización una medida de la funcionalidad que entrega la 
	aplicación.

METRICAS ORIENTADAS A OBJETOS:

	No proporcionan suficiente granularidad para la planificación y los ajustes de esfuerzos
	Las siguientas métricas sugeridas para proyectos OO:

		1.) Número de guiones de escenario.
		2.) Número de clases nuevas.
		3.) Número de clases de apoyo.
		4.) Número promedio de clases de apoyo por clase clave.
		5.) Número de Subsistemas.

METRICAS ORIENTADAS A CASOS DE USOS:

	Se defienen etapas tempranas del proceso de software, lo que permite emplearlo en la 
	estimación antes de iniciar actividades significativas de modelado construcción.

METRICAS DE PROYECTOS DE INGENIERIA WEB:

	Se usan cuando los proyectos están orientados a construir una aplicación web.
	Métricas sugeridas:

		1.) Número de páginas web estáticas.
		2.) Número de páginas web dinámicas.
		3.) Número de vínculos internos de la página.
		4.) Número de objetos de datos persistentes.
		5.) Número de sistemas externos de interfaz.
		6.) Número de objetos de contenido estático.
		7.) Número de objetos de contenido dinámico.
		8.) Número de funciones ejecutables.

METRICAS PARA LA CALIDAD DE SOFTWARE:

	Satisfacción de las necesidades iniciales planteadas, aquí necesario es añadir la 
tecnologías en uso, disponibilidad, escalabilidad y documentación.

	Medición de la calidad:
		1.) Corrección.
			grado en que el software desempeña la función para la que fue creado donde
			los defectos se definen como una falta de concordancia con los requisitos. 
		2.) Facilidad de mantenimiento.
			Sencillez con la que un programa puede corregirse si se cuenta con un error,
			adaptarse si su entorno cambia, o mejorar si el cliente desea un cambio.
			Medida: Tiempo medio de cambio (análisis, diseño, implementación, prueba, 
			distribución).
		3.) Integridad.
			mide la habilidad de un sistema para resistir a ataques ya sea accidentales 
			o intencionales a su seguridad.
			seguridad es la probabilidad de que se repela la amenaza:
				integridad= 1 - (amenaza x (1 - seguridad))
		4.) Facilidad de uso.
			intento de cuantificar el uso de la palicación se puede medir en términos de 
			diseño de la interfaz de usuario.

ARGUMENTOS PARA LAS MÉTRICAS DEL SOFTWARE:

	* Si no se mide no existe una forma real de determinar si se está mejorando. Y si no se 
	  mejora, se está perdido.
	* Si el proceso se puede mejorar producirá un impacto directo en los sustancial.
	* Establecer objetivos de mejora dentro del proceso actual de desarrollo de s/w.
	* La recopilación de métricas de calidad permite que una organización centralice
	  su proceso de s/w para renovar las causas de los defectos que tienen mayor impacto 
	  sobre el desarrollo de software.

	* <INSERT HERE> Agreguen aquí los argumentos desde el punto de vista social y político </INSERT> 

Existen una serie de modelos para la referenciación de métricas el modelo MCCAL [1] (modelo de factores/
criterios/ métricas). Identifica atributos (llamados factores de calidad). Define tres vistas:

	1.) vista de usuario: clasifica los factrores de calidad.
	2.) vista de la dirección: clasifica los criterios de calidad.
	3.) vista del desarrollador: clasifica las métricas de calidad.

Modelo DROMEY [2]: resalta que la calidad del producto es altamente determinada por los componentes del 
	       mismo (documentos, guías de usuario, diseño, código). Sugiere el uso de 3 categorias 
	       correctitud, Internas, Contextuales y descriptivas.

Modelo FURPS [3]: basado en el modelo MCCAL. Se usa para establecer métricas de la calidad para todas las 
	      actividades de proceso de desarrollo de un software, inclusive de un sistema de información.

Modelo Paradigma GQM (Goal-Question-Metric) [4]: Paradigma que permite evaluar la calidad del producto y
					     del proceso en tres etapas:

						1.) Lista de objetivos principales en el desarrollo 
						    y mantenimiento del proyecto.
						2.) Para cada objetivo obtener las preguntas que deben 
						    contestarse para saber si se están cumpliendo los
						    objetivos.
						3.) Decidir qué medir para poder contestar las preguntas
						    de manera apropiada.
Modelo CMM (Capability Madurity Model) [5].


CONCLUSION: Aunque podemos adoptar un modelo para obtener métricas iniciales para los proyectos a 
	    desarrollar, necesario es entender que estos no pueden pasar de ser un referente teórico
	    ya que los mismos miden un conjunto de variables cuantificables y la mayoría van enfocada
	    hacia el producto final y no a la gente.
	    
	    Está demás decir que los mismos fueron pensados para realidades distintas a las de nuestros
	    entornos, culturas y políticas.

	    Necesario es entonces que podamos desde el análisis y la participación colectiva adaptar
	    estas mediciones, para dimensionar la participación los aportes, pero también el impacto
	    de las unidades productivas desde la realidad de sus pertinencias territoriales y 
	    culturales la separación des estás realidades propias es la deshumanización del proyecto,
	    la división por especialicimas condiciones y la segmentacióin de la sinergia tan necesaria
	    para la apropiación de la tarea.

	    Se propone entonces la identificación de las dimensiones propias que permitan darle un 
	    espacio desde el entendimiento orgánico, vivo y cambiante a la intención de una métrica
	    popular de la mano con nuestra realidad política y social actual.

   
   
FUENTES CONSULTADAS:
http://es.slideshare.net/loreknelamorena/mtricas-de-proceso-y-proyecto-de-software
https://prezi.com/8xgg-08nncwl/medidasmetricas-e-indicadores-de-la-calidad-del-software/
http://evaluaciondesoftware2013.blogspot.com


REFERENCIAS
[1] http://vanevargas.jimdo.com/módulos/modelos/modelo-de-mccall/
[2] https://prezi.com/u0es3ti5uekp/modelo-de-calidad-dromey/
[3] https://es.wikipedia.org/wiki/FURPS
[4] https://en.wikipedia.org/wiki/GQM
[5] https://es.wikipedia.org/wiki/Modelo_de_Capacidad_y_Madurez
