# pd-dmtools
Surtido de herramientas básicas de audio y de control, desarrolladas en Pure Data.  
  
Incluye las siguientes abstracciones:
- `[3band~]`: Ecualizador de tres bandas.
- `[dbgain~]`: Control de ganancia en dB.
- `[del4~]`: Herramienta para manipular los objetos [delwrite~] y [delread~].
- `[lrtoms~]`: Conversor de estéreo izquierda-derecha a mid-side.
- `[master~]`: Pensada para utilizar con la señal al final de la cadena, esta abstracción cuenta con: control de ganancia, vúmetro, conversión de estéreo a mono y clipeo de la señal a -1 1.
- `[mstolr~]`: Conversor de estéreo mid-side a izquierda-derecha.
- `[pan~]`: Herramienta para panear una señal estéreo.
- `[probs~]`: Generador de bangs en base a una probabilidad de 0-100%.
- `[pw~]`: Generador de pulsos u oscilador con forma de onda rectangular.
- `[stom~]`: Herramienta para reducir la imagen estéreo.
