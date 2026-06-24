**7.ACTORES, REQUERIMIENTOS FUNCIONALES Y NO FUNCIONALES, HISTORIA DE USUARIOS**

. Identificación de Actores

Actor Principal

Conductor de vehículo particular

Persona que utiliza automóvil, motocicleta o camioneta y desea conocer la calidad del aire, evitar zonas contaminadas y reducir el impacto ambiental de sus recorridos.

Actores Secundarios

Usuario Registrado

Persona que crea una cuenta para consultar su historial de viajes, puntos ecológicos y estadísticas personales.

Administrador del Sistema

Responsable de gestionar contenidos educativos, supervisar el funcionamiento de la aplicación y administrar la información mostrada a los usuarios.

IQAir

Sistema externo que proporciona información sobre calidad del aire en tiempo real.

WAQI (World Air Quality Index)

Sistema externo que suministra datos sobre contaminación atmosférica.

IDEAM

Entidad externa que proporciona información ambiental utilizada por la aplicación.

Servicio de Geolocalización y Mapas

Sistema externo encargado de proporcionar mapas, ubicaciones y rutas para la navegación dentro de la aplicación.

2\. Requerimientos Funcionales

RF01. El sistema deberá permitir al usuario consultar la calidad del aire de cualquier zona dentro del Valle de Aburrá.

RF02. El sistema deberá mostrar los niveles de contaminación presentes en la ubicación actual del usuario.

RF03. El sistema deberá calcular una estimación de la contaminación generada por un viaje.

RF04. El sistema deberá permitir ingresar un punto de origen y un punto de destino para realizar consultas de recorrido.

RF05. El sistema deberá identificar zonas con altos niveles de contaminación atmosférica.

RF06. El sistema deberá generar alertas cuando el usuario se dirija hacia una zona altamente contaminada.

RF07. El sistema deberá sugerir rutas ecológicas que eviten sectores con altos índices de contaminación.

RF08. El sistema deberá mostrar información comparativa entre la ruta seleccionada y las rutas ecológicas sugeridas.

RF09. El sistema deberá asignar puntos virtuales cuando el usuario seleccione rutas con menor impacto ambiental.

RF10. El sistema deberá almacenar el historial de viajes realizados por el usuario.

RF11. El sistema deberá permitir consultar el historial de contaminación estimada de los recorridos realizados.

RF12. El sistema deberá mostrar estadísticas relacionadas con la contaminación generada por el usuario.

RF13. El sistema deberá permitir consultar contenidos educativos sobre calidad del aire, contaminación atmosférica, PM2.5, PM10 y huella de carbono.

RF14. El sistema deberá mostrar recomendaciones para disminuir la contaminación generada durante los desplazamientos.

RF15. El sistema deberá permitir el registro e inicio de sesión de usuarios.

3\. Requerimientos No Funcionales

Requerimientos del Producto

RNF01. Disponibilidad: La aplicación deberá estar disponible para consulta de información ambiental cuando el usuario la requiera.

RNF02. Usabilidad: La interfaz deberá ser sencilla, intuitiva y comprensible para cualquier ciudadano.

RNF03. Rendimiento: La información de calidad del aire deberá mostrarse en tiempos adecuados para apoyar la toma de decisiones del usuario.

RNF04. Confiabilidad: Los datos ambientales deberán provenir de fuentes confiables y reconocidas.

RNF05. Compatibilidad: La aplicación deberá funcionar en dispositivos móviles inteligentes.

RNF06. Precisión: Las estimaciones de contaminación deberán estar basadas en los datos ambientales disponibles.

Requerimientos Organizacionales

RNF07. El desarrollo deberá respetar el alcance definido para el prototipo EcoRuta Itagüí.

RNF08. La aplicación deberá utilizar información proveniente de IQAir, WAQI e IDEAM como fuentes de referencia ambiental.

RNF09. La aplicación deberá operar únicamente dentro del Valle de Aburrá.

Requerimientos Externos

RNF10. Seguridad: La aplicación deberá proteger la información personal de los usuarios registrados.

RNF11. La aplicación no deberá utilizar dispositivos físicos conectados a los vehículos para medir emisiones.

RNF12. La aplicación no deberá conectarse con sistemas de fotomultas ni con plataformas de la Secretaría de Tránsito.

RNF13. La aplicación deberá utilizar únicamente fuentes públicas y autorizadas de información ambiental.

4\. Historias de Usuario

HU01. Consultar contaminación de una zona

Como conductor de vehículo particular

Quiero visualizar el nivel de contaminación del aire de una zona específica

Para decidir si debo circular por allí o buscar una alternativa.

Criterios de aceptación

Dado que consulto una zona del mapa, cuando solicite la información, entonces debo visualizar su nivel de contaminación.

Dado que la zona posee un nivel de contaminación determinado, cuando la información sea mostrada, entonces deberá indicarse si es baja, media o alta.

HU02. Recibir alertas de contaminación

Como conductor de vehículo particular

Quiero recibir alertas cuando me acerque a una zona altamente contaminada

Para evitar exponerme a aire perjudicial para mi salud.

Criterios de aceptación

Dado que me dirijo hacia una zona contaminada, cuando la aplicación detecte el recorrido, entonces deberá generar una alerta.

Dado que recibo una alerta, cuando la visualice, entonces deberá mostrar el nivel de contaminación detectado.

HU03. Obtener rutas ecológicas

Como conductor de vehículo particular

Quiero recibir rutas alternativas con menor contaminación ambiental

Para reducir mi exposición al material particulado.

Criterios de aceptación

Dado que ingreso origen y destino, cuando solicite una ruta, entonces la aplicación deberá mostrar una alternativa ecológica.

Dado que exista una ruta menos contaminada, cuando se realice el cálculo, entonces deberá destacarse como recomendada.

HU04. Conocer la contaminación generada por mi viaje

Como conductor de vehículo particular

Quiero conocer una estimación de la contaminación que genera mi recorrido

Para comprender mi impacto ambiental.

Criterios de aceptación

Dado que selecciono un recorrido, cuando solicite la estimación, entonces la aplicación deberá mostrar la contaminación generada.

Dado que finalice un viaje, cuando consulte los resultados, entonces deberá visualizarse la estimación correspondiente.

HU05. Comparar rutas según contaminación

Como conductor de vehículo particular

Quiero comparar diferentes rutas según su nivel de contaminación

Para elegir la alternativa más saludable.

Criterios de aceptación

Dado que existen varias rutas disponibles, cuando las consulte, entonces deberá mostrarse el nivel de contaminación de cada una.

Dado que visualizo varias opciones, cuando las compare, entonces podré identificar la menos contaminante.

HU06. Consultar historial ambiental

Como usuario registrado

Quiero consultar el historial de contaminación estimada de mis viajes

Para evaluar mis hábitos de conducción.

Criterios de aceptación

Dado que he realizado viajes anteriormente, cuando consulte el historial, entonces deberán mostrarse los registros almacenados.

Dado que existen registros históricos, cuando los visualice, entonces deberán aparecer organizados cronológicamente.

HU07. Acumular puntos ecológicos

Como conductor de vehículo particular

Quiero recibir puntos cuando utilice rutas con menor impacto ambiental

Para sentirme motivado a contaminar menos.

Criterios de aceptación

Dado que utilizo una ruta ecológica, cuando finalice el recorrido, entonces deberán asignarse puntos.

Dado que obtengo puntos, cuando consulte mi perfil, entonces deberá mostrarse el total acumulado.

HU08. Visualizar zonas críticas de contaminación

Como conductor de vehículo particular

Quiero identificar en el mapa las zonas con mayores niveles de contaminación

Para evitar transitar por ellas.

Criterios de aceptación

Dado que accedo al mapa, cuando se cargue la información ambiental, entonces deberán resaltarse las zonas críticas.

Dado que una zona presente alta contaminación, cuando la visualice, entonces deberá diferenciarse de las demás.

HU09. Acceder a contenido educativo

Como ciudadano interesado en el medio ambiente

Quiero acceder a información sobre contaminación atmosférica, PM2.5 y calidad del aire

Para comprender los riesgos para mi salud.

Criterios de aceptación

Dado que ingreso al módulo educativo, cuando seleccione un tema, entonces deberá mostrarse la información correspondiente.

Dado que existan varios contenidos, cuando navegue entre ellos, entonces podré acceder a diferentes temas ambientales.

HU10. Consultar calidad del aire en tiempo real

Como conductor de vehículo particular

Quiero conocer la calidad del aire de mi ubicación actual

Para tomar decisiones antes de iniciar mi recorrido.

Criterios de aceptación

Dado que abro la aplicación, cuando consulte mi ubicación actual, entonces deberá mostrarse la calidad del aire correspondiente.

Dado que la calidad del aire cambie, cuando actualice la consulta, entonces deberá visualizarse la información más reciente.
