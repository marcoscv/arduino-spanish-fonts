# Arduino Spanish fonts
## Fuentes Arduino en español

![Acentos](https://raw.githubusercontent.com/marcoscv/arduino-spanish-fonts/main/Spanish_Fonts.jpg)

Fuentes con Ñ, ñ, Á, á, É, é, Í, í, Ó, ó, Ú, ú para tu arduino. fáciles de usar con TFT eSPI y Adafruit GFX Library.
Están en el directorio "Fuentes".

## Ejemplo para TFT_eSPI:

Copiar fuentes .h a directorio:
`/Arduino/libraries/TFT_eSPI/Fonts/GFXFF`
Y añadir referencias a estas fuentes en el archivo `gfxfont.h`. Ejemplo:

```
  #include <Fonts/GFXFF/FreeMono12.h>
  #include <Fonts/GFXFF/FreeMono14.h>
```
No olvides tener `#define LOAD_GFXFF` descomentado en tu TFT eSPI User_Setup.h

## Ejemplo en Adafruit GFX Library

Copiar fuentes .h a directorio:
```/Arduino/libraries/Adafruit_GFX_Library/Fonts```
 y en tu archivo incluyes la fuente.
 ```#include <Fonts/customFreeFont.h>```

Luego la añades a tu proyecto:
```#include "customFreeFont.h"```


