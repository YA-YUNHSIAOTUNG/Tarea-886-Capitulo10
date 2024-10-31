**Checksum**

_Descripción:_ Método simple que suma todos los valores de los datos.

_Funcionamiento:_ Se calculan la suma de los bytes (o palabras) de datos.
El resultado (checksum) se envía junto con los datos.
El receptor recalcula la suma y compara con el checksum recibido.

_Detección:_ Eficaz para detectar errores de transmisión, pero puede fallar en casos de errores que cancelan la suma.
