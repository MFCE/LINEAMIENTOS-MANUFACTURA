# LINEAMIENTOS-MANUFACTURA
Introducción
El problema que se está presentando en estos tiempos de COVID-19 es la falta de recurso médico. Uno de los más vitales si el número de infectados sigue incrementando son los ventiladores/respiradores mecánicos que ayudan al paciente a respirar, al sustituir la función de los pulmones.. 
“La capacidad de los ventiladores se ha convertido en una preocupación creciente en todo el mundo, especialmente cuando COVID-19 abrumó la oferta en Italia y España, obligando a los médicos a elegir a quién salvar y a quién dejar morir.” (Fry, 2020)
Teniendo lo anterior en cuenta, el equipo DINAMITA considera que es muy importante atacar esta problemática desde el punto de vista ingenieril e industrial. Otros países ya pasaron por esto y es necesario prevenir lo más posible la escasez cuando los casos de infectados aumentan. Estamos conscientes de que vivimos en una sociedad con muchos ingenieros e industrias con la mejor disposición de ayudar a crear respiradores de último recurso. El problema, es que se ignoran los requerimientos médicos y solo se toman en cuenta los componentes ingenieriles pudiendo posiblemente poner en riesgo al paciente de ser utilizado puesto que hay muchas más variables a considerar que solamente llevar a cabo la acción de comprimir la bolsa.
Por lo anterior, se desarrolló una guía rápida dirigida a ingenieros e industrias en donde se podrán encontrar los componentes de manufactura para fabricar un ventilador de último recurso próximo a ser aprobado, para que los ingenieros con intenciones de ayudar sin conocimientos médicos, puedan colaborar de manera efectiva al producir estas piezas y en caso de querer ejecutar el ventilador, los lineamientos a tener en cuenta para que pueda ser candidato a respirador de último recurso. Además de fungir como una pauta para todas las empresas que actualmente se encuentran en pausa debido a la contingencia puedan unir esfuerzos y de ser posible, reajustar sus líneas de producción para fabricar alguna de las piezas o materiales que se mencionan.

El sector salud (hospitales) necesitan abastecimiento de equipo médico: ventiladores específicamente, debido a lo indispensable que son ante la pandemia y propagación de COVID-19.

Componentes para la manufactura del ventilador.
Desglosamos los materiales y componentes de manufactura de un ventilador de último recurso, nos basaremos en el prototipo de ventilador mecánico “E-VENT” del Massachusetts Institute of Technology (MIT) debido a que tras investigar, se llegó a la conclusión de que la opción más viable en caso de una emergencia, donde no haya manera de acceder al paciente a un ventilador de manera inmediata sería esta debido a que ha logrado casi por completo el control de las variables mínimas necesarias a monitorear. El prototipo cuesta aproximadamente 200 USD manufacturar. Se espera que sea aprobado y de ser así, que se use como prototipo base.
herramientas: cortadora laser

AMBU BAGS: (silicona)
Acrílico  (12.55mm) 
perillas de entrada
Motor eléctrico, alimentado de una batería 14.8 VDC
tarjetas de programación arduino (duemilanove microcontroller board)
motorreductor PK51 DC
torque de ahogo de 2.8 Nm
circuitos puente H 
pantalla LCD 
tapas de aluminio de 63.5 mm de radio en forma de media luna 
Ejes de aluminio de 8mm 
bujes de nylon
potenciómetro 
sensor de presión 
(Husseini, A and A, Saukonnen, J, 2010)


Requerimientos mínimos para ventilación
Agregando que todo tipo de práctica de ventilación asistida, debe efectuarse bajo la responsabilidad de un profesional capacitado en el área y solo en situaciones donde la utilización del dispositivo es el último recurso disponible, estos son los lineamientos a considerar según el área de ciencias de la salud del MIT y el gobierno federal de los Estados Unidos Mexicanos:
1- Los mínimos parámetros que deben ser controlables son:
 Frecuencia Respiratoria (respiros por minuto) 8-150
Volumen corriente (volumen del aire que se manda al pulmón): 200-800 ml dependiendo el paciente
Tiempos inspiratorios y espiratorios: .1-10 segundos respectivamente 
relación de inhalación y expiración: 1;1; (mejor si puede ser ajustado)
Ventilación controlable, para empezar a ejecutar el respirador y para desactivarlo en cuanto el paciente pueda retomar su propia respiración
2- Se debe poder monitorear la presión del aire
3- En caso de que la ventilación asistida falle en algún momento, se debe poder convertir a asistencia manual de forma inmediata
4- Se deben utilizar filtros HEPA para proteger tanto al paciente de utilizar un tubo con bacterias y para evitar contagiar al personal médico
5- Deben ser desechables, de un solo uso todos los componentes que tengan contacto con el paciente
6- En caso de que el paciente genere fluidos deben poder ser limpiados 
7- En caso de alguna falla (ya sea con la máquina o el paciente) debe existir algún sistema de alarma para avisar.
Dentro de las alarmas que debe de incluir el sistema se encuentran las siguientes:
Presión inspiratoria alta.
PEEP bajo o desconexión del paciente.
Apnea.
Volumen minuto o corriente alto y bajo.
Frecuencia respiratoria alta y baja.
FiO2 alta y baja.
Baja presión del suministro de gases.
Batería baja.
Falta de alimentación eléctrica.
Ventilador inoperable o falla del ventilador o indicador de no usar el aparato.
SIlencio de alarma.
8- En caso de falla con la red eléctrica, debe poder trabajar por sí solo al menos 20 minutos
9- Contar con una batería externa de 7 horas por lo menos
	(CFPRS,2020), (MIT, 2020)
Recomendaciones
Debe de ser especificada la vida útil del dispositivo.
Debe ser lo suficientemente intuitivo para que el personal calificado lo pueda usar sin problemas. 
Debe de haber un instructivo explicando su funcionamiento y potenciales fallas (en un idioma local o inglés).
De ser necesario brindar capacitación (puede darse de forma virtual). (CFPRS, 2020)

Referencias:
-MIT E-VENT. (2020). MIT Emergency Ventilator (E-Vent) Project. Abril 7 del 2020, de MIT E-Vent | MIT Emergency Ventilator Sitio web: https://e-vent.mit.edu/

-Comisión Federal para la Protección contra Riesgos Sanitarios (2020). Disposiciones para la adquisición y fabricación de ventiladores, durante la emergencia de salud pública por coronavirus 2019 (COVID-19). Recuperado de https://www.gob.mx/cofepris/articulos/disposiciones-para-la-adquisicion-y-fabricacion-de-ventiladores-durante-la-emergencia-de-salud-publica-por-coronavirus-2019-covid-19?idiom=es&fbclid=IwAR2z-UMAfxPa7FOn90D7VTBIDFCSoKXjkmWv_V8kUUG_rOFn7El8GbVCcas

-MIT E-VENT. (2020). Key Ventilation Specifications. Abril 7 del 2020, de Emergency ventilator design toolbox Sitio web: https://e-vent.mit.edu/clinical/key-ventilation-specifications/

-(Husseini, A and A, Saukonnen, J, 2010). (2010). Design and Prototyping of a Low-cost Portable Mechanical Ventilator. May 3 2020, de Proceedings of the 2010 Design of Medical Devices Conference Sitio web: https://e-vent.mit.edu/wp-content/uploads/2020/03/DMD-2010-MIT-E-Vent.pdf
