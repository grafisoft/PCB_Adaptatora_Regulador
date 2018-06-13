![Banner](https://i.imgur.com/cfQgf7Ph.jpg)

# PCB_Adaptatora_Regulador
Archivos para la fabricación de una PCB adaptadora con el fin de cambiar el regulador que llevan las placas tipo NodeMCU y asi lograr reducir drasticamente su consumo en periodos de deepsleep. Para proyectos IoT donde el consumo es crítico, necesitamos reducirlo tanto como podamos. Si ademas queremos usar hardware tipo NodeMCU, con un simple cambio logramos grandes resultados. Recordar que esto se puede aplicar a cualquier tipo de placa que lleve un ergulador LM1117.

Se trata de una PCB que adapta un regulador LDO para ser usado en placas que integren un ESP8266, ESP32 o similares y cuyo regulador sea un LM1117. El caso es cambiar este regulador para obtener consumos en modo deepsleep mucho mas bajos, pues pasariamos de tener unos mA a consumos menores de 40uA.

La PCB facilitada es para usar con reguladores cuyo encapsulado es SOT-89. En caso de necesitar usar otro tipo, podeis pedir los nuevos diseños, se hacen rápido. 

Podeis seguir el post escrito con la documentación necesaria, y realizar cualquier tipo de consulta,  en el foro Maker SpainLabs:
https://www.spainlabs.com/foros/tema-APORTE-SpainLabsIoT2018-ESP8266-NodeMCU-Ajustando-su-consumo-hack

Saludos y a disfrutar del bajo consumo :)
