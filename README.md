# Prediccion-de-artritis-reumatoide
En este proyecto se realiza un análisis exploratorio a un dataset medico relacionado con el artritis reumatoide identificando características vitales para determinar posibles pacientes de esta enfermedad.

# Datos del dataset
Los Siguientes campos pertenecen al dataset medico de artritis reumatoide definiendo el contenido que posee y su importancia relacionada a la identificacion de esta enfermedad.

## Nombre
Incluye el nombre del paciente recolectado en la toma de datos de los pacientes al ingresar al hospital para una revision medica.

## Edad
Incluye la edad del paciente recolectado en la toma de datos de los pacientes al ingresar al hospital para una revision medica.

## Genero
Identifica el genero del paciente ingresado. En el dataset es clasificado como "Hombre" y "Mujer".

## Historial familiar
Identifica si el paciente posee familiares que han sufrido artritis remanoide. En el dataset es clasificado como "0" = no y "1" = si.

## IMC
El Indice de Masa Corporal (IMC) es la relacion entre la altura y el peso del paciente.

• Bajo peso: menor a 18.5

• Peso normal: 18.5 a 24.9

• Sobrepeso: 25.0 a 29.9

• Obeso: 30.0 o mas

## Tabaquismo

Identifica si el paciente actualmente (o anteriormente) es fumador activo. En el dataset es clasificado como "0" = no y "1" = si.


## Actividad fisica

Identifica si el paciente se ejercita constantemente. En el dataset es clasificado como "0" = no y "1" = si.

## Exposicion Contaminante

Identifica si el paciente esta expuesto a areas contaminadas constantemente. En el dataset es clasificado como "0" = no y "1" = si.


## Anti-pcc (Péptidos anticíclicos citrulinados)

Esta prueba busca un anticuerpo específico llamado anti-PCC, que está presente en un aproximado de 60 por ciento a 80 por ciento de las personas con artritis reumatoide, según la Fundación de la Artritis. su identificacion relacionada a la Artritis se nivela de la siguiente forma:

• Negativo: menos de 20 UI/ml

• positivo debil: 20 UI/ml a 39 UI/ml

• positivo moderado: 40 UI/ml a 59 UI/ml

• positivo fuerte: mayor a 60 UI/ml

## ANA (Anticuerpos antinucleares)

Esta prueba busca niveles altos de anticuerpos antinucleares, que son compuestos que pueden atacar el núcleo de la célula, lo que la destruye. En el dataset es clasificado como "0" = no hay niveles altos y "1" = hay niveles altos.

## PCR (Proteína C reactiva)

Esta prueba detecta la presencia de PCR, que produce el hígado en respuesta a la inflamación en el cuerpo (el exceso de esta proteina puede indicar artritis). sus medidas son las siguientes:

• Normal: menor a 5mg/l

• ligeremente elevado: 5 a 10mg/l

• moderadamente elevado: 10 a 40mg/l

• Altamente elevado: mayor a 40mg/l

## VSG (Velocidad de sedimentación globular)

Esta prueba dura 1 hora y mide la velocidad en la que los glóbulos rojos en una muestra de sangre se asientan en la probeta. El exceso de VSG puede indicar la exsistencia de artritis en el paciente.

◦ Hombres menores a 50 años: menor a 15mm/h

◦ hombres mayores a 50 años: menor a 20mm/h

◦ mujeres menores a 50 años: menor a 20mm/h

◦ mujeres mayores a 50 años: menor a 30mm/h

## HLA (Tipificación tisular para HLA)

Esta prueba detecta la presencia de un marcador genético llamado HLA-B27 en la sangre. En el dataset es clasificado como "0" = no y "1" = si.

## FR (Factor reumatoide): 

Esta prueba mide el nivel de FR, que actúa como un anticuerpo contra las gammaglobulinas.

## Acido Urico: 

El ácido úrico es un producto de desecho que tiende a estar presente en grandes cantidades cuando una persona tiene gota, que es otra forma de artritis inflamatoria. La
presencia de altos niveles de ácido úrico indica que una persona tiene más probabilidades de tener gota que artritis reumatoide. En el dataset es clasificado como "0" = no y "1" = si.

## Serologia-Lyme: 

La presencia de los factores inmunológicos de la serología de Lyme pueden indicar que una persona tiene la enfermedad de Lyme en lugar de artritis reumatoide. En el dataset es clasificado como "0" = no y "1" = si.

## Enfermo: 

indica si la persona posee o no artritis reumatoide. En el dataset es clasificado como "0" = no y "1" = si.
