# Limpieza de Datos - Conjunto de Datos de Solicitudes de Crédito
 ## Acerca del Conjunto de Datos
###  Contexto
Este conjunto de datos original contiene 1000 entradas, cada una con 10 atributos categóricos/simbólicos, y fue preparado por el profesor Hofmann. Cada entrada representa a una persona que solicita un crédito a un banco. La clasificación del riesgo crediticio de cada persona se encuentra registrada como "bueno" o "malo" en función de los atributos asociados.

## Proceso de Limpieza de Datos
 ### Eliminación de la variable innecesaria

Se eliminó la variable unnamed ya que no aportaba valor al análisis y su inclusión podría generar confusión.

### Manejo de valores nulos o faltantes

#### Se identificaron y gestionaron los valores faltantes en las siguientes variables:

Saving accounts: Se encontraron 183 valores faltantes en esta variable.
Checking account: Se encontraron 394 valores faltantes en esta variable.
Eliminación de valores nulos

#### Para asegurar la calidad de los datos, se eliminaron los valores nulos en las siguientes variables:

Saving accounts: Se eliminaron las filas con valores faltantes en esta variable.
Checking account: Se eliminaron las filas con valores faltantes en esta variable.
### Resultado Final
Una vez completada la limpieza de los datos, el conjunto de datos resultante contiene 522 observaciones y 9 variables.