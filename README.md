# Integración práctica. UML.

### Integrantes
- Gonzalez Lucas
- Picon Matias
- Ragusa Octavio
- Garay Franco

### Consignas

##### Ejercicio 1
Una figura puede estar compuesta por otras figuras básicas, como por ejemplo: triángulos, elipses y cuadriláteros. Se sabe además que un tipo particular de elipse es 
el círculo, mientras que un tipo particular de cuadrilátero es el rectángulo. A su vez un tipo particular de rectángulo es el cuadrado. 
Por otra parte, los cuadriláteros y triángulos son tipos de polígonos. Los polígonos tienen un número de lados, y dichos lados están definidos por 2 puntos. 
Un punto está definido por una coordenada en el eje de las x, y otra en el eje de las y.

##### Ejercicio 2
Un país tiene provincias, una capital, limita con otros países y se localiza en un continente. Las provincias de un país limitan con otras provincias del mismo país y 
a su vez pueden limitar con otros países. Las provincias tienen ciudades y una de ellas es su capital.

##### Ejercicio 3
Un país tiene que controlar el gasto público de las ciudades con más de 100.000 habitantes. Para ello, tiene información del monto recaudado por cada ciudad a través 
de cinco diferentes tipos de impuestos (denominados, aquí, de imp1, imp2, imp3, imp4 e imp5) e información acerca de gastos realizados en mantenimiento de la ciudad. 
Este país necesita un sistema que le informe cuales son las ciudades que gastan mas de lo que recaudan, y las provincias 
que tienen mas de la mitad de las ciudades en condición de déficit.

##### Ejercicio 4
Una cooperativa de agricultores requiere de un sistema que le aconseje cual es el cereal que puede sembrar en un determinado lote. Los lotes son clasificados como especiales cuando contienen ciertos minerales de interés primario para la cooperativa y comunes cuando contienen sólo minerales secundarios en la composición de la tierra.
Para poder sembrar un cereal en un lote, éste debe contener determinados minerales. Los cereales se clasifican en granos de cosecha gruesa (como girasol, maíz,...), granos de cosecha fina (como trigo, avena,..) y pasturas (como alfalfa, trébol subterráneo,..). Un lote satisface los requerimientos de un cereal si contiene todos de los minerales que requiere ese cereal. Además, para el caso de las pasturas no se puede haber sembrado previamente otra pastura.

##### Ejercicio 5
En una ciudad existen diferentes restaurantes, algunos de ellos con varias sucursales. 
Los restaurantes ofrecen diferentes platos (de comida), pero no más de 20, 
a las personas que concurren a ellos. En general, a las personas les gustan 
diferentes platos, frecuentan varios restaurantes y ocasionalmente pueden 
concurrir a otros aunque no sean de los que frecuenta habitualmente. En particular, 
a las personas no les gusta un plato por sí mismo, sino cómo lo sirven 
en determinados restaurantes, aunque puede que para un plato particular 
no le guste cómo lo sirven en ninguno de los restaurantes. A su vez, un plato 
servido en un restaurante puede no gustarle a ninguna persona.

##### Ejercicio 6
Por cada comunidad autónoma (CA) se guarda su nombre, sus parques y el organismo responsable de estos. Hay parques que se extienden por varias CAs. De un parque se almacena su nombre (no habrá dos de igual nombre), la fecha en la que fue declarado PN, sus diferentes áreas y los km2 de cada una. No hay dos áreas del mismo PN que se llamen igual. En cada área de un parque residen varias especies. Cada especie tiene sus nombres científico y vulgar y se conoce el nº de individuos en cada área. Por cada especie vegetal desean conocer si tiene floración y, en ese caso, en qué periodo florece. De las especies animales se guardará cuál es su periodo de celo. Según su alimentación, las especies animales se clasifican en herbívoras, carnívoras y omnívoras. También hay registrar qué animales o vegetales sirven de alimento a los animales de los parques.
Por cada visitante a PNs se recoge su DNI, nombre, dirección y profesión. Los PN tienen alojamientos propios que organizan excursiones. No hay dos alojamientos de un parque con igual nombre. Además se guarda su capacidad, categoría, visitantes que lo utilizaron y en qué habitación y fechas de inicio y fin.
Cada excursión tiene un código que la identifica. Además se registra el día, la hora y los alojamientos que la organizan. También se almacenan los visitantes que se inscriben en cada excursión. El personal que trabaja en cada parque puede ser: celador, investigador y guarda. Una persona puede desempeñar varios cargos al mismo tiempo (por ejemplo, guarda e investigador). Para todos ellos se guarda su DNI, nombre, dirección, teléfono, sueldo, nº de seguridad social y el parque donde trabaja. Cada parque tiene una o varias entradas. Éstas se numeran del uno al nº de entradas al mismo. Cada celador está destinado en una de ellas y se encarga de registrar quién visita el parque y en qué fecha. Cada guarda tiene asignada un área de su parque y la recorre en un vehículo, del que se almacena su tipo y matrícula. Se pueden asignar varios guardas a un área del parque y varios celadores a una entrada.
Por cada investigador se recoge su titulación, los proyectos de investigación en los que ha intervenido junto a las especies investigadas por él en cada proyecto. De cada proyecto se registra su nombre, presupuesto y período de realización (fechas de inicio y fin).

##### Ejercicio 7
Dadas las siguientes especificaciones de un “Campeonato de esqui”.
El campeonato consta de una serie de pruebas. En cada una se inscribe un conjunto de participantes. Hay pruebas individuales y por equipos. Un esquiador puede participar en varias pruebas a título individual o sino formando parte de un equipo (pero NO unas veces individualmente y otras en equipo).
Por cada esquiador se desea guardar su DNI, nombre, fecha de nacimiento y edad. A cada participante en una prueba (equipo, para pruebas por equipos o esquiador si es individual) se le asigna un código formado por el nombre de la prueba y un dorsal. Por cada equipo se tiene su código, entrenador, sus esquiadores y cuántos son. No todos los esquiadores de un equipo deben participar en cada prueba donde se ha inscrito. Hay varias federaciones de esquí. De cada una se conoce su nombre y nº de federados. Cada esquiador pertenece a una única federación. No se admite la participación de esquiadores no federados.
Cada federación puede administrar estaciones de esquí. Toda estación se administra al menos por una federación, aunque puede serlo por varias. Cada estación de esquí dispone de un código identificativo. Tiene un nombre, personas de contacto, dirección, teléfono, nº total de kilómetros esquiables y nº de pistas. Cada pista se identifica por el código de la estación a la que pertenece y un número correlativo. Se guarda su longitud en kilómetros y su nivel de dificultad (según un código de colores).
Algunas pruebas de largo recorrido utilizan varias pistas de una misma estación como si fuesen una sola pista compuesta de varias subpistas. Cada prueba se realizará en las pistas de una única estación. Puede durar varios días. Se almacenan las fechas en las que tiene lugar.
Los participantes podrán competir en diferentes pruebas y en diferentes pistas. Se registrará la fecha o fechas en las que cada participante compite en cada prueba así como el tiempo empleado y la posición obtenida. Cada prueba se identifica por un nombre, será de un tipo (fondo, slalom, salto, ...) tendrá unas fechas previstas de realización y se registrará el vencedor y el tiempo empleado por éste.

##### Ejercicio 8
Dadas las siguientes especificaciones de un “Aeródromo”.
Cada avión tiene un nº de matrícula, es de un tipo y se guarda en un hangar. Cada tipo de avión tiene un nº de modelo y cierta capacidad y peso. Cada hangar tiene un número, capacidad y una ubicación. La BD también lleva el control del propietario(s) de cada avión así como de los mecánicos que han llevado su mantenimiento. También se guarda la fecha de adquisición de cada avión por su propietario
actual. También se almacenan los servicios realizados por cada mecánico a cada avión. Cada registro de servicio incluye la fecha en la que se realizó, el número de horas invertidas y el tipo de trabajo. No puede haber dos servicios realizados al mismo avión en la misma fecha con el mismo tipo de trabajo.
Por cada persona se guarda su nº de seguridad social, nombre, dirección y teléfono. Para los mecánicos se guarda también su salario y turno. Para los pilotos su nº de licencia y restricciones.
También se guarda el tipo de aviones en los que está autorizado a volar cada piloto y los tipos de avión en los que puede dar mantenimiento cada mecánico.

##### Ejercicio 9
Dadas las siguientes especificaciones de un “Museo”.
El museo tiene una colección de objetos de arte. Cada uno tiene su nº de identificación, artista y año de creación (si se conocen), título y una descripción. Los objetos de arte se clasifican en varias categorías: – Basándose en su tipo se distinguen pinturas, esculturas y otros. Las pinturas incluyen el tipo de pintura (óleo, acuarela, ...), soporte (lienzo, papel,...) y estilo (impresionista, abstracto, etc.). Para las esculturas se almacena el material (mármol, bronce,...), altura, peso y estilo. Basándose en su pertenencia al museo se distinguen objetos en préstamo u objetos de la colección permanente. Para estos últimos se guarda la fecha de adquisición y coste además de si está en exposición o en almacén. Para las obras en préstamo se incluye el nombre de la colección a la que pertenece, la fecha en la que se recibió en préstamo y la fecha de devolución.
Por cada objeto de arte se tiene también información sobre su origen mediante información de su país y cultura (romano, egipcio, maya, etc.) y su época (renacimiento, neoclásico, etc.) También se guarda información de los artistas: su nombre (se supone que único), fecha de nacimiento y en su caso de defunción, país de origen, época, estilo principal y descripción.
En el museo se celebran diferentes exposiciones, cada una de ellas tiene un nombre que la identifica, tiene una fecha de comienzo y de finalización e incluye el conjunto de objetos de arte exhibidos. Sobre las colecciones de obras de arte con las que el museo intercambia obras es útil guardar su nombre (único), tipo (museo, colección privada, etc.), descripción, dirección, teléfono y el nombre de la persona de contacto.

##### Ejercicio 10
Dadas las siguientes especificaciones de los juegos olímpicos:
Las sedes olímpicas se dividen en complejos deportivos. Los complejos deportivos se subdividen en aquellos en los que se desarrolla un único deporte y los polideportivos. Ambos tipos manejan diferente tipo de información. Por cada sede se almacena el número de complejos que tiene y su presupuesto aproximado.
Los complejos tienen áreas designadas para cada deporte con un indicador de su situación (ejemplo: centro, esquina N-E, etc.).
Un complejo tiene una localización, un jefe de organización y el área ocupada. Cada complejo celebra una serie de eventos (ejemplo: la pista del estadio puede celebrar muchas carreras distintas)
Cada evento tiene prevista una fecha, duración, número de participantes y número de comisarios. Para cada comisario se almacena la lista de eventos en los que está involucrado. Para cada evento se guarda el material necesario para su desarrollo (porterías, pértigas, barras paralelas).

##### Ejercicio 11
Cosmética Natural, una empresa de venta directa, solicitó implementar parte de su funcionamiento en forma inmediata, con vistas a sistematizar todos sus procesos a corto plazo. Con este fin aportó la siguiente información:
La empresa fabrica en su laboratorio diversos productos, los cuales distribuye exclusivamente a través de sus representantes de ventas. Identifica a cada producto por su nombre y ha fijado un único precio para cada uno de ellos, el de venta al público.
La estructura de ventas se organiza en equipos coordinados por líderes. De cada líder se registra su nombre, dirección, teléfono, fecha de nacimiento, CUIT o CUIL, la fecha de su incorporación a la empresa y la fecha de su promoción a la categoría de líder, así como su equipo de vendedores. De cada vendedor se asienta la misma información, excepto la fecha de promoción a la categoría de líder, la cual se registra oportunamente, dado el caso.
Todos los representantes de ventas, vendedores y líderes, poseen su propia cartera de clientes, de los cuales se registra el nombre, dirección, teléfono y fecha de nacimiento, así como la fecha de ingreso a la empresa en calidad de cliente, con fines promocionales y de seguimiento.
Los vendedores y líderes adquieren cada producto en forma directa a la empresa, el  cual abonan contra entrega de un ticket de venta por unidad que registra la fecha, el producto y el precio. Los tickets se emiten por triplicado con el fin de que, una vez efectuada la venta final, el representante complete una de las copias con el nombre del cliente y la remita a la empresa para que se registre este dato.
Una vez por mes la empresa lleva a cabo una reunión general con toda su fuerza de ventas, en la cual informa la fecha de la próxima reunión, manteniendo el registro tanto de la última como de la próxima reunión, y brinda información de seguimiento de ventas. 
En la oportunidad, la empresa rinde a cada representante un importe en concepto de  comisión, el cual calcula a partir de un porcentaje fijo para toda la fuerza de ventas,  según el siguiente criterio:
A cada vendedor se le reintegra el porcentaje de comisión sobre el monto total de sus ventas registradas desde la fecha de la última reunión general.
A cada líder se le reintegra, además, el mismo porcentaje de comisión sobre el monto total de las ventas registradas de sus vendedores en el mismo período.









