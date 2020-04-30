# Hamming_CRC
Receptor
El programa consiste en  una interfaz en donde el usuario ingresa la trama que ya viene con CRC y Hamming, proporciona si la paridad 
es par o impar y por ultimo, el divisor.
Si la trama no contenia errores, se mostrara un mensaje con "No se encontraron errores" y en esa misma ventana abajo aparecera
el caracter que se encontro.
Si al contrario, la trama es incorrecta, se quitan los bits de crc y se realiza hamming. Si el error es detectado, aparece
un mensaje con "Error encontrado en el bit #.." para que usted sepa que bit esta mal. Entonces se detecta y el error es corregido. Para
verificar esto se vuelve a hacer CRC ya con la trama "arreglada". Si vuelve a salir que se encontro un error es porque hay mas de un error.
