---
title: "WmfLogColorSpaceW"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto LogColorSpaceW especifica un espacio de color lógico que puede definirse mediante un archivo de perfil de color con un nombre compuesto por caracteres Unicode de 16 bits."
type: docs
weight: 45
url: /es/java/com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfLogColorSpaceW extends MetaObject
```

El objeto LogColorSpaceW especifica un espacio de color lógico, que puede definirse mediante un archivo de perfil de color con un nombre compuesto por caracteres Unicode de 16 bits.

Consulte el objeto `WmfLogColorSpace` (sección 2.2.2.11) para obtener detalles adicionales sobre la interpretación de los valores de los campos de este objeto.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WmfLogColorSpaceW()](#WmfLogColorSpaceW--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getSignature()](#getSignature--) | Obtiene o establece un entero sin signo de 32 bits que especifica la `signature` de los objetos de espacio de color; DEBE establecerse al valor 0x50534F43, que es la codificación ASCII de la cadena "PSOC". |
| [setSignature(int value)](#setSignature-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica la `signature` de los objetos de espacio de color; DEBE establecerse al valor 0x50534F43, que es la codificación ASCII de la cadena "PSOC". |
| [getVersion()](#getVersion--) | Obtiene o establece un entero sin signo de 32 bits que define un número de `version`; DEBE ser 0x00000400. |
| [setVersion(int value)](#setVersion-int-) | Obtiene o establece un entero sin signo de 32 bits que define un número de `version`; DEBE ser 0x00000400. |
| [getSize()](#getSize--) | Obtiene o establece un entero sin signo de 32 bits que define el `size` de este objeto, en bytes. |
| [setSize(int value)](#setSize-int-) | Obtiene o establece un entero sin signo de 32 bits que define el `size` de este objeto, en bytes. |
| [getColorSpaceType()](#getColorSpaceType--) | Obtiene o establece un entero con signo de 32 bits que especifica el tipo de espacio de color. |
| [setColorSpaceType(int value)](#setColorSpaceType-int-) | Obtiene o establece un entero con signo de 32 bits que especifica el tipo de espacio de color. |
| [getIntent()](#getIntent--) | Obtiene o establece un entero con signo de 32 bits que define la intención de mapeo de gamut. |
| [setIntent(int value)](#setIntent-int-) | Obtiene o establece un entero con signo de 32 bits que define la intención de mapeo de gamut. |
| [getEndpoints()](#getEndpoints--) | Obtiene o establece un objeto CIEXYZTriple (sección 2.2.2.7) que define las coordenadas de cromaticidad CIE x, y y z de los tres colores que corresponden a los `endpoints` RGB para el espacio de color lógico asociado con el mapa de bits. |
| [setEndpoints(WmfCieXyzTriple value)](#setEndpoints-com.aspose.imaging.fileformats.wmf.objects.WmfCieXyzTriple-) | Obtiene o establece un objeto CIEXYZTriple (sección 2.2.2.7) que define las coordenadas de cromaticidad CIE x, y y z de los tres colores que corresponden a los `endpoints` RGB para el espacio de color lógico asociado con el mapa de bits. |
| [getGammaRed()](#getGammaRed--) | Obtiene o establece un valor de punto fijo de 32 bits que define la curva de respuesta tonal para el rojo. |
| [setGammaRed(int value)](#setGammaRed-int-) | Obtiene o establece un valor de punto fijo de 32 bits que define la curva de respuesta tonal para el rojo. |
| [getGammaGreen()](#getGammaGreen--) | Obtiene o establece un valor de punto fijo de 32 bits que define la curva de respuesta tonal para el verde. |
| [setGammaGreen(int value)](#setGammaGreen-int-) | Obtiene o establece un valor de punto fijo de 32 bits que define la curva de respuesta tonal para el verde. |
| [getGammaBlue()](#getGammaBlue--) | Obtiene o establece un valor de punto fijo de 32 bits que define la curva de respuesta tonal para el azul. |
| [setGammaBlue(int value)](#setGammaBlue-int-) | Obtiene o establece un valor de punto fijo de 32 bits que define la curva de respuesta tonal para el azul. |
| [getFilename()](#getFilename--) | Obtiene o establece una cadena de caracteres Unicode UTF16-LE opcional, terminada en nulo, que especifica el nombre de un archivo que contiene un perfil de color. |
| [setFilename(String value)](#setFilename-java.lang.String-) | Obtiene o establece una cadena de caracteres Unicode UTF16-LE opcional, terminada en nulo, que especifica el nombre de un archivo que contiene un perfil de color. |
### WmfLogColorSpaceW() {#WmfLogColorSpaceW--}
```
public WmfLogColorSpaceW()
```


### getSignature() {#getSignature--}
```
public int getSignature()
```


Obtiene o establece un entero sin signo de 32 bits que especifica la `signature` de los objetos de espacio de color; DEBE establecerse al valor 0x50534F43, que es la codificación ASCII de la cadena "PSOC".

**Returns:**
int
### setSignature(int value) {#setSignature-int-}
```
public void setSignature(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica la `signature` de los objetos de espacio de color; DEBE establecerse al valor 0x50534F43, que es la codificación ASCII de la cadena "PSOC".

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Obtiene o establece un entero sin signo de 32 bits que define un número de `version`; DEBE ser 0x00000400.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Obtiene o establece un entero sin signo de 32 bits que define un número de `version`; DEBE ser 0x00000400.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getSize() {#getSize--}
```
public int getSize()
```


Obtiene o establece un entero sin signo de 32 bits que define el `size` de este objeto, en bytes.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Obtiene o establece un entero sin signo de 32 bits que define el `size` de este objeto, en bytes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getColorSpaceType() {#getColorSpaceType--}
```
public int getColorSpaceType()
```


Obtiene o establece un entero con signo de 32 bits que especifica el tipo de espacio de color. DEBE estar definido en la enumeración LogicalColorSpace (sección 2.1.1.14). Si este valor es LCS\_sRGB o LCS\_WINDOWS\_COLOR\_SPACE, se DEBE usar el espacio de color sRGB.

**Returns:**
int
### setColorSpaceType(int value) {#setColorSpaceType-int-}
```
public void setColorSpaceType(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica el tipo de espacio de color. DEBE estar definido en la enumeración LogicalColorSpace (sección 2.1.1.14). Si este valor es LCS\_sRGB o LCS\_WINDOWS\_COLOR\_SPACE, se DEBE usar el espacio de color sRGB.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getIntent() {#getIntent--}
```
public int getIntent()
```


Obtiene o establece un entero con signo de 32 bits que define la intención de mapeo de gamut. DEBE estar definido en la enumeración GamutMappingIntent (sección 2.1.1.11).

**Returns:**
int
### setIntent(int value) {#setIntent-int-}
```
public void setIntent(int value)
```


Obtiene o establece un entero con signo de 32 bits que define la intención de mapeo de gamut. DEBE estar definido en la enumeración GamutMappingIntent (sección 2.1.1.11).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getEndpoints() {#getEndpoints--}
```
public WmfCieXyzTriple getEndpoints()
```


Obtiene o establece un objeto CIEXYZTriple (sección 2.2.2.7) que define las coordenadas de cromaticidad CIE x, y y z de los tres colores que corresponden a los `endpoints` RGB para el espacio de color lógico asociado con el mapa de bits. Si el campo `ColorSpaceType` no especifica LCS\_CALIBRATED\_RGB, este campo DEBE ser ignorado.

**Returns:**
[WmfCieXyzTriple](../../com.aspose.imaging.fileformats.wmf.objects/wmfciexyztriple)
### setEndpoints(WmfCieXyzTriple value) {#setEndpoints-com.aspose.imaging.fileformats.wmf.objects.WmfCieXyzTriple-}
```
public void setEndpoints(WmfCieXyzTriple value)
```


Obtiene o establece un objeto CIEXYZTriple (sección 2.2.2.7) que define las coordenadas de cromaticidad CIE x, y y z de los tres colores que corresponden a los `endpoints` RGB para el espacio de color lógico asociado con el mapa de bits. Si el campo `ColorSpaceType` no especifica LCS\_CALIBRATED\_RGB, este campo DEBE ser ignorado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WmfCieXyzTriple](../../com.aspose.imaging.fileformats.wmf.objects/wmfciexyztriple) |  |

### getGammaRed() {#getGammaRed--}
```
public int getGammaRed()
```


Obtiene o establece un valor de punto fijo de 32 bits que define la curva de respuesta tonal para el rojo. Si el campo `ColorSpaceType` no especifica LCS\_CALIBRATED\_RGB, este campo DEBE ser ignorado.

**Returns:**
int
### setGammaRed(int value) {#setGammaRed-int-}
```
public void setGammaRed(int value)
```


Obtiene o establece un valor de punto fijo de 32 bits que define la curva de respuesta tonal para el rojo. Si el campo `ColorSpaceType` no especifica LCS\_CALIBRATED\_RGB, este campo DEBE ser ignorado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getGammaGreen() {#getGammaGreen--}
```
public int getGammaGreen()
```


Obtiene o establece un valor de punto fijo de 32 bits que define la curva de respuesta tonal para el verde. Si el campo `ColorSpaceType` no especifica LCS\_CALIBRATED\_RGB, este campo DEBE ser ignorado.

**Returns:**
int
### setGammaGreen(int value) {#setGammaGreen-int-}
```
public void setGammaGreen(int value)
```


Obtiene o establece un valor de punto fijo de 32 bits que define la curva de respuesta tonal para el verde. Si el campo `ColorSpaceType` no especifica LCS\_CALIBRATED\_RGB, este campo DEBE ser ignorado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getGammaBlue() {#getGammaBlue--}
```
public int getGammaBlue()
```


Obtiene o establece un valor de punto fijo de 32 bits que define la curva de respuesta tonal para el azul. Si el campo `ColorSpaceType` no especifica LCS\_CALIBRATED\_RGB, este campo DEBE ser ignorado.

**Returns:**
int
### setGammaBlue(int value) {#setGammaBlue-int-}
```
public void setGammaBlue(int value)
```


Obtiene o establece un valor de punto fijo de 32 bits que define la curva de respuesta tonal para el azul. Si el campo `ColorSpaceType` no especifica LCS\_CALIBRATED\_RGB, este campo DEBE ser ignorado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getFilename() {#getFilename--}
```
public String getFilename()
```


Obtiene o establece una cadena de caracteres Unicode UTF16-LE opcional, terminada en nulo, que especifica el nombre de un archivo que contiene un perfil de color. Si se especifica un nombre de archivo y el campo `ColorSpaceType` está configurado a LCS\_CALIBRATED\_RGB, los demás campos de esta estructura DEBERÁN ser ignorados.

**Returns:**
java.lang.String
### setFilename(String value) {#setFilename-java.lang.String-}
```
public void setFilename(String value)
```


Obtiene o establece una cadena de caracteres Unicode UTF16-LE opcional, terminada en nulo, que especifica el nombre de un archivo que contiene un perfil de color. Si se especifica un nombre de archivo y el campo `ColorSpaceType` está configurado a LCS\_CALIBRATED\_RGB, los demás campos de esta estructura DEBERÁN ser ignorados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

