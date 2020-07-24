# Learning Lounge Portal Revamp 
## (Internal - Avature)

[TEG Case](https://teg.avature.net/#Case/482253)

### El problema

Luego de un rediseño del portal se detectaron muchísimos problemas de usabilidad, patrones y categorización de contenidos, con lo cual se genero la hipótesis de que los usuarios estaban teniendo una experiencia adversa y poco engagement.

### Hipótesis a validar en el estudio previo y la recopilación de datos

En un kickoff, Internal Training definió problemas a validar. Esto dio lugar a los siguientes planteos por parte de Studio:

- Los usuarios se pierden en la navegación por criterios poco claros de categorizacion
- Los usuarios no conocen el contenido del portal
- Los patrones poco consistentes generan una mala experiencia
- La falta de motivadores atentan contra el engagement con el portal

### Preguntas a analizar previo al estudio del sitio

- Cuál es el objetivo de Training con respecto al portal?
- Cuáles son los equipos que más deberían usarlo?
- Cuáles son los que realmente lo usan?
- Lo usan más empleados nuevos o con experiencia?

### Se optó por realizar tres tipos de estudios para recopilar datos de usuarios, con sus correspondientes objetivos

- [Entrevistas](https://github.com/jmmorena/Studio-Process-Framework/tree/Internal-Training-Portal-Revamp/User%20Testing/Interviews)
- [Pruebas de Usabilidad](https://github.com/jmmorena/Studio-Process-Framework/tree/Internal-Training-Portal-Revamp/User%20Testing/Usability%20Testing)
- [Tree Testing](https://github.com/jmmorena/Studio-Process-Framework/tree/Internal-Training-Portal-Revamp/User%20Testing/Tree%20Testing)

__Objetivo:__ Entender cómo ven los usuarios el portal de Internal Training y detectar pain points en su uso diario




### Entrevistas

__Se realizaron 9 entrevistas a diversos perfiles__

A nivel macro, se dividio en dos grupos:
- Onboarders
- Non-Onboarders

Se entrevistaron miembros de varios equipos, para tener una visión holística del caso:
- Engineering
- Studio
- Tech Support
- Product Marketing
- Talent Acquistion
- Consulting

Todo el contenido se encuentra disponible en la sección Entrevistas de este repo.

### Pruebas de usabilidad

Se hicieron 8 prueba de usabilidad a los dos grupos macro que cubrieron las entrevistas, con dos tareas simples predefinidas (tres en el caso de los onboarders), enfocadas en el análisis de la organización de contenidos y los pain points que podían surgir en la navegación y uso.

Todos los datos se encuentras disponibles en la sección Usability Testing presente en este repo.

Tree testing

Se optó por un Tree Testing para validar la estructura de contenidos del sitio y de esta manera poder identificar si los problemas que se detectaron durante las pruebas de usabilidad respondian a complicaciones netamente de la interface o si la organizacion de la informacion tambien jugaba un papel importante en estos pain point

Todo el estudio se puede encontrar en la seccion Tree Testing de este proyecto. 

### Benchmarking

Se realizó un benchmarking de 5 sites de e-learning para entender cómo le hablan a sus usuarios y de qué manera presentan y filtran los contenidos.

Los ejes de análisis fueron el dashboard, la forma de categorizar los contenidos, la claridad con la que se presentan una vez dentro del curso y si hay conceptos de gamification.

Los sitios analizados fueron __Google Digital Garage, Skillshare, Domestika, Udemy e IDF.__ Como punto extra se analizó el hub de __Google AI Developers__ por su muy interesante patrón de filtros y su wording.

Para la carga de datos se creó un Google Forms por su facilidad para generar reportes.

Todos los datos están disponibles en la seccion Benchmarking de este repo.

### User Research Findings

Se detectaron en total 7 ejes problemáticos a encarar, ordenados en esta lista de mayor a menor según su impacto en el producto

1. __Definition:__ Los usuarios consideran que el Portal de Training caduca después del primer mes
2. __Engagement:__ Los usuarios que conocen el Portal no vuelven a entrar o no encuentran motivos para hacerlo regularmente
3. __Discoverability:__ Los usuarios no encuentran el contenido o se frustran buscándolo
4. __Predictability:__ Los filtros no se comportan como los usuarios esperan o dan resultados poco intuitivos
5. __Content Friendliness:__ Las sesiones no tienen descripciones claras o indicadores de los temas que se van a tocar y en qué momento del video
6. __Content Flow:__ No hay una correlación lineal entre el contenido presentado
7. __Branding:__ El Portal no responde a los nuevos lineamientos de Branding de Talent Brand

## Process & Status Meetings

Todas las presentaciones y documentos nombrados en este apartado se encuentran disponibles en la carpeta Presentations del presente repositorio

### Status Meeting 1: Presentación de findings y definición de Scope

Se presentaron todos los findings de user research al team de Internal Training y se presentaron dos posibles scopes de trabajo:

#### __Scope 1__
Ataca los problemas de __Engagement, Discoverability y Predictability__ . 
Los tasks a cumplir son:
- Replanteo de la arquitectura de la información
- Rediseño del Portal con foco en la usabilidad
- Testeo de usabilidad de prototipo
 
#### __Scope 2__
Ataca los problemas de __Engagement (con un fuerte foco en la ludificación), Discoverability, Predictability__ . 
Los tasks a cumplir son:
- Replanteo de la arquitectura de la información
- Rediseño del Portal con foco en la usabilidad
- Testeo de usabilidad de prototipo
- Planteo de un modelo de Gamification

Independientemente del scope seleccionado, todas las estrategias deberían atacar __Definition, Content Flow, y Branding__

El eje de __Content Friendliness__ depende del contenido del área de Internal Training

El scope elegido por los stakeholders fue el __1__

Posteriormente se elaboró una aproximación de Gantt para desarrollar este portal. El mismo, lógicamente, sufrió muchas modificaciones.

### Status Meeting 2: Technical meeting

En este punto se sumó un nuevo stakeholder, __Internal Comms__, que se unió al proyecto con el fin de nuclear todos los proyectos de aplicación del nuevo branding de Avature.

Sobre los aportes y comunicaciones con Internal Comms nos explayamos en el Anexo A: Working with Internal Comms (WIP) y sobre la aplicación de branding, ya sea Corporate o Talent Brand, lo hacemos en el documento Talent and Corporate Brand for Internal Portals (WIP)

Esta presentación tuvo como fin la definición de elementos de UI particulares para atacar las problemáticas relevadas. A la misma se sumó Manu Migone para dar su feedback técnico de cada uno de los módulos.

- Feature 1: Lists
Contenido personalizado. Permite al usuario tener en su home una vista de las cards presentes en listas personalizadas - __Recommended for you__ (llamado Assigned Sessions en la versión final) presenta contenido curado especialmente para el usuario; __What's new__ releva en orden cronológico las sesiones de training más recientes; __Saved sessions__ muestra las sesiones que el usuario decidió guardar en su lista personal para referencia futura.

- Feature 2: Progress Bar
Con el fin de dar previsibilidad al onboarder, se sumó una barra de progreso en el home de onboarding


