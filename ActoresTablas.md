**Historias de usuarios**

**1.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | HU-01 |
| Título | Consultar contaminación de una zona |
| Como | Conductor de vehículo particular |
| Quiero | Visualizar el nivel de contaminación del aire de una zona específica |
| Para | Decidir si debo circular por allí o buscar una alternativa |

**2.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | HU-02 |
| Título | Recibir alertas de contaminación |
| Como | Conductor de vehículo particular |
| Quiero | Recibir alertas cuando me acerque a una zona altamente contaminada |
| Para | Evitar exponerme a aire perjudicial para mi salud |

**3.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | HU-03 |
| Título | Obtener rutas ecológicas |
| Como | Conductor de vehículo particular |
| Quiero | Recibir rutas alternativas con menor contaminación ambiental |
| Para | Reducir mi exposición al material particulado |

**4.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | HU-04 |
| Título | Conocer la contaminación generada por mi viaje |
| Como | Conductor de vehículo particular |
| Quiero | Conocer una estimación de la contaminación que genera mi recorrido |
| Para | Comprender mi impacto ambiental |

**5.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | HU-05 |
| Título | Comparar rutas según contaminación |
| Como | Conductor de vehículo particular |
| Quiero | Comparar diferentes rutas según su nivel de contaminación |
| Para | Elegir la alternativa más saludable |

**6.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | HU-06 |
| Título | Consultar historial ambiental |
| Como | Usuario registrado |
| Quiero | Consultar el historial de contaminación estimada de mis viajes |
| Para | Evaluar mis hábitos de conducción |

**7.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | HU-07 |
| Título | Acumular puntos ecológicos |
| Como | Conductor de vehículo particular |
| Quiero | Recibir puntos cuando utilice rutas con menor impacto ambiental |
| Para | Sentirme motivado a contaminar menos |

Por cada viaje completado exitosamente (por la ruta menos contaminada) se le agregan 1 punto. llegados a los 5 puntos puede participar en una rifa o guardarlos para reclamar cupones como: 50%OFF en cualquier tienda de mayorca con 30 puntos, 1 helado pequeño gratis en Mcdonals con 10 puntos entre otras más.
Si te despazas en un vehiculo que usa Diésel o gasolina, unicamente serán 1 punto por recorrido, si usas gas natural(GNV) se te otorga 1.5 puntos.
Si es electrico,vas a pié o en bicicleta SIN asistencia, son 3.5 puntos.

**8.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | HU-08 |
| Título | Visualizar zonas críticas de contaminación |
| Como | Conductor de vehículo particular |
| Quiero | Identificar en el mapa las zonas con mayores niveles de contaminación |
| Para | Evitar transitar por ellas |

**9.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | HU-09 |
| Título | Acceder a contenido educativo |
| Como | Ciudadano interesado en el medio ambiente |
| Quiero | Acceder a información sobre contaminación atmosférica, PM2.5 y calidad del aire |
| Para | Comprender los riesgos para mi salud |

**10.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | HU-10 |
| Título | Consultar calidad del aire en tiempo real |
| Como | Conductor de vehículo particular |
| Quiero | Conocer la calidad del aire de mi ubicación actual |
| Para | Tomar decisiones antes de iniciar mi recorrido |

Requisito Funcional (RF)

**1.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | RF-01 |
| HU Relacionada | HU-01, HU-10 |
| Descripción | El sistema debe permitir consultar la calidad del aire de cualquier en itagüí. |

**2.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | RF-02 |
| HU Relacionada | HU-01, HU-10 |
| Descripción | El sistema debe mostrar los niveles de contaminación de la ubicación actual del usuario. |

**3.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | RF-03 |
| HU Relacionada | HU-04 |
| Descripción | El sistema debe calcular una estimación de la contaminación generada por un viaje. |

**4.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | RF-04 |
| HU Relacionada | HU-03 |
| Descripción | El sistema debe permitir ingresar origen y destino para consultar recorridos. |

**5.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | RF-05 |
| HU Relacionada | HU-02, HU-08 |
| Descripción | El sistema debe identificar zonas con altos niveles de contaminación atmosférica en las zonas urbanas y rurales. |

**6.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | RF-06 |
| HU Relacionada | HU-02 |
| Descripción | El sistema debe generar alertas al acercarse a zonas altamente contaminadas con un semáforo ambiental que indique el nivel de calidad del aire mediante colores: verde (buena), amarillo (moderada) y rojo (mala).. |

**7.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | RF-07 |
| HU Relacionada | HU-03, HU-05 |
| Descripción | El sistema debe sugerir rutas ecológicas con menor exposición a contaminación. |

**8.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | RF-08 |
| HU Relacionada | HU-05 |
| Descripción | El sistema debe comparar rutas según su nivel de contaminación y mostrar que tipo de vehiculos circulan más por dicha ruta. |

**9.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | RF-09 |
| HU Relacionada | HU-07 |
| Descripción | El sistema debe asignar puntos virtuales por utilizar rutas ecológicas. |

**10.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | RF-10 |
| HU Relacionada | HU-06 |
| Descripción | El sistema debe almacenar el historial de viajes realizados. |

**11.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | RF-11 |
| HU Relacionada | HU-06 |
| Descripción | El sistema debe permitir consultar el historial de contaminación estimada. |

**12.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | RF-12 |
| HU Relacionada | HU-06 |
| Descripción | El sistema debe mostrar estadísticas diarias ambientales del usuario. |

**13.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | RF-13 |
| HU Relacionada | HU-09 |
| Descripción | El sistema debe ofrecer contenido educativo sobre calidad del aire y contaminación. |

**14.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | RF-14 |
| HU Relacionada | HU-09 |
| Descripción | El sistema debe mostrar recomendaciones para disminuir la contaminación. |

**15.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | RF-15 |
| HU Relacionada | HU-06, HU-07 |
| Descripción | El sistema debe permitir el registro, inicio de sesión de usuarios, consultarlos y modificarlos. |

**16**

| ID    | Requerimiento Funcional    | Descripción                                                                                                                                 |
| ----- | -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| RF-15 | Registro de rutas alternas | El sistema permitirá a los ciudadanos registrar y compartir rutas alternas que eviten zonas con altos niveles de contaminación atmosférica. |

**17**

| ID    | Requerimiento Funcional | Descripción                                                                                                                                            |
| ----- | ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| RF-17 | Semáforo ambiental      | El sistema mostrará un semáforo ambiental que indique el nivel de calidad del aire mediante colores: verde (buena), amarillo (moderada) y rojo (mala). |

**18**

| ID    | Requerimiento Funcional     | Descripción                                                                                                                                                                                                              |
| ----- | --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| RF-18 | Estimación de contaminación | El sistema calculará una estimación del nivel de contaminación generado por un recorrido, considerando el tipo de vehículo (Diésel, Gasolina, Gas Natural Vehicular o Eléctrico) y la cantidad de kilómetros recorridos. |




Requerimientos No Funcionales (RNF)

**1.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | RNF-01 |
| Categoría | Disponibilidad |
| Descripción | La aplicación debe estar disponible 24/7 los 365 dias del año para consulta de información ambiental. |
| Métrica | 95% del tiempo |

**2.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | RNF-02 |
| Categoría | Usabilidad |
| Descripción | La interfaz debe permitir una interacción clara y sencilla para cualquier ciudadano. |
| Métrica | 80% de usuarios completan tareas sin ayuda |

**3.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | RNF-03 |
| Categoría | Rendimiento |
| Descripción | La información ambiental debe cargarse rápidamente. |
| Métrica | Menos de 5 segundos |

**4.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | RNF-04 |
| Categoría | Confiabilidad |
| Descripción | Los datos deben provenir de fuentes confiables. |
| Métrica | 100% de datos desde IQAir, WAQI o IDEAM |



**5.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | RNF-05 |
| Categoría | Portabilidad |
| Descripción | La aplicación debe de ser visible para cuál quier dispositivo en cualquier sistema operativo. |
| Métrica | Compatible con todos los sistemas operativos |

**6.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | RNF-06 |
| Categoría | Precisión |
| Descripción | Las estimaciones deben basarse en datos ambientales actuales. |
| Métrica | Actualización periódica de datos |

**7.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | RNF-07 |
| Categoría | Restricción Organizacional |
| Descripción | Debe respetar el alcance del prototipo EcoRuta. |
| Métrica | Solo funciones definidas en el alcance |

**8.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | RNF-08 |
| Categoría | Disponibilidad |
| Descripción | Debe utilizar IQAir, WAQI e IDEAM. |
| Métrica | 100% consultas desde fuentes definidas |

**9.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | RNF-09 |
| Categoría | Portabilidad |
| Descripción | Debe operar únicamente en itagüí. |
| Métrica | Cobertura limitada a la región |

**10.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | RNF-10 |
| Categoría | Seguridad |
| Descripción | El sistema deberá contar con un nivel de seguridad medio que garantice la protección de los datos de los usuarios y evite accesos no autorizados.. |
| Métrica | Acceso solo mediante autenticación |

**11.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | RNF-11 |
| Categoría | Restricción Externa |
| Descripción | No debe usar sensores físicos en vehículos. |
| Métrica | 0 sensores físicos |

**12.**

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | RNF-12 |
| Categoría | Restricción Externa |
| Descripción | No debe conectarse a fotomultas ni tránsito. |
| Métrica | 0 integraciones con dichos sistemas |
