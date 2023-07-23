# Introduccion
Los controladores MPPT deben sus siglas a (Maximum Power Point Tracking) lo que significa que hacen trabajar al panel en su punto de maxima potencia, por lo que no tenemos la desventaja de los PWM en los que se iguala la tension de bateria a la del panel, perdiendo eficiencia.
El principal problema resuelto por el algoritmo de MPPT es que se encuentra de manera automatica el voltaje de operacion del panel para el cual permite la mayor potencia de salida.
Las curvas de salida de un panel solar tipico son mostradas en la siguiente figura. La tension a circuito abierto es obviamente la maxima tension que puede entregar el panel pero sin drenar potencia. La corriente de cortocircuito es otro parametro importante porque es la maxima corriente absoluta que puede entregar el panel.

La maxima potencia que le podemos extraer al panel depende principalmente de tres factores: irradiacion, temperatura y carga. La temperatura principalmente cambia el valor de tension de operacion del panel mientras que la irradiacion cambia la corriente de operacion del panel. En el primer grafico vemos las distintas curvas de corriente segun la irradiacion del panel.
Adaptando las impedancias del panel con la carga con un convertidor DC-DC tiene sentido. 

