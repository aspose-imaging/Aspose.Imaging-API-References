---
title: "EmfPixelFormatDescriptor"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto PixelFormatDescriptor puede usarse en los registros EMR_HEADER sección 2.3.4.2 para especificar el formato de píxel de la superficie de salida para el contexto del dispositivo de reproducción."
type: docs
weight: 31
url: /es/java/com.aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfPixelFormatDescriptor extends EmfObject
```

El objeto PixelFormatDescriptor puede usarse en registros EMR\_HEADER (sección 2.3.4.2) para especificar el formato de píxel de la superficie de salida para el contexto del dispositivo de reproducción.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPixelFormatDescriptor()](#EmfPixelFormatDescriptor--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getNSize()](#getNSize--) | Obtiene o establece un entero de 16 bits que especifica el tamaño, en bytes, de esta estructura de datos. |
| [setNSize(short value)](#setNSize-short-) | Obtiene o establece un entero de 16 bits que especifica el tamaño, en bytes, de esta estructura de datos. |
| [getNVersion()](#getNVersion--) | Obtiene o establece un entero de 16 bits que DEBE establecerse en 0x0001. |
| [setNVersion(short value)](#setNVersion-short-) | Obtiene o establece un entero de 16 bits que DEBE establecerse en 0x0001. |
| [getDwFlags()](#getDwFlags--) | Obtiene o establece banderas de bits que especifican propiedades del búfer de píxeles que se usa para la salida a la superficie de dibujo. |
| [setDwFlags(int value)](#setDwFlags-int-) | Obtiene o establece banderas de bits que especifican propiedades del búfer de píxeles que se usa para la salida a la superficie de dibujo. |
| [getIPixelType()](#getIPixelType--) | Obtiene o establece el tipo de datos de píxel PFD\_TYPE\_RGBA 0x00 El formato de píxel es RGBA. |
| [setIPixelType(byte value)](#setIPixelType-byte-) | Obtiene o establece el tipo de datos de píxel PFD\_TYPE\_RGBA 0x00 El formato de píxel es RGBA. |
| [getCColorBits()](#getCColorBits--) | Obtiene o establece el número de bits por píxel para tipos de píxel RGBA, excluyendo los planos de bits alfa. |
| [setCColorBits(byte value)](#setCColorBits-byte-) | Obtiene o establece el número de bits por píxel para tipos de píxel RGBA, excluyendo los planos de bits alfa. |
| [getCRedBits()](#getCRedBits--) | Obtiene o establece el número de planos de bits rojos en cada búfer de color RGBA. |
| [setCRedBits(byte value)](#setCRedBits-byte-) | Obtiene o establece el número de planos de bits rojos en cada búfer de color RGBA. |
| [getCRedShift()](#getCRedShift--) | Obtiene o establece la cantidad de desplazamiento en bits para los planos de bits rojos en cada búfer de color RGBA. |
| [setCRedShift(byte value)](#setCRedShift-byte-) | Obtiene o establece la cantidad de desplazamiento en bits para los planos de bits rojos en cada búfer de color RGBA. |
| [getCGreenBits()](#getCGreenBits--) | Obtiene o establece el número de planos de bits verdes en cada búfer de color RGBA. |
| [setCGreenBits(byte value)](#setCGreenBits-byte-) | Obtiene o establece el número de planos de bits verdes en cada búfer de color RGBA. |
| [getCGreenShift()](#getCGreenShift--) | Obtiene o establece la cantidad de desplazamiento para los planos de bits verdes en cada búfer de color RGBA. |
| [setCGreenShift(byte value)](#setCGreenShift-byte-) | Obtiene o establece la cantidad de desplazamiento para los planos de bits verdes en cada búfer de color RGBA. |
| [getCBlueBits()](#getCBlueBits--) | Obtiene o establece el número de planos de bits azules en cada búfer de color RGBA. |
| [setCBlueBits(byte value)](#setCBlueBits-byte-) | Obtiene o establece el número de planos de bits azules en cada búfer de color RGBA. |
| [getCBlueShift()](#getCBlueShift--) | Obtiene o establece la cantidad de desplazamiento para los planos de bits azules en cada búfer de color RGBA. |
| [setCBlueShift(byte value)](#setCBlueShift-byte-) | Obtiene o establece la cantidad de desplazamiento para los planos de bits azules en cada búfer de color RGBA. |
| [getCAlphaBits()](#getCAlphaBits--) | Obtiene o establece el número de planos de bits alfa en cada búfer de color RGBA. |
| [setCAlphaBits(byte value)](#setCAlphaBits-byte-) | Obtiene o establece el número de planos de bits alfa en cada búfer de color RGBA. |
| [getCAlphaShift()](#getCAlphaShift--) | Obtiene o establece la cantidad de desplazamiento para los planos de bits alfa en cada búfer de color RGBA. |
| [setCAlphaShift(byte value)](#setCAlphaShift-byte-) | Obtiene o establece la cantidad de desplazamiento para los planos de bits alfa en cada búfer de color RGBA. |
| [getCAccumBits()](#getCAccumBits--) | Obtiene o establece el número total de planos de bits en el búfer de acumulación. |
| [setCAccumBits(byte value)](#setCAccumBits-byte-) | Obtiene o establece el número total de planos de bits en el búfer de acumulación. |
| [getCAccumRedBits()](#getCAccumRedBits--) | Obtiene o establece el número de planos de bits rojos en el búfer de acumulación. |
| [setCAccumRedBits(byte value)](#setCAccumRedBits-byte-) | Obtiene o establece el número de planos de bits rojos en el búfer de acumulación. |
| [getCAccumGreenBits()](#getCAccumGreenBits--) | Obtiene o establece el número de planos de bits verdes en la acumulación. |
| [setCAccumGreenBits(byte value)](#setCAccumGreenBits-byte-) | Obtiene o establece el número de planos de bits verdes en la acumulación. |
| [getCAccumBlueBits()](#getCAccumBlueBits--) | Obtiene o establece el número de planos de bits azules en el búfer de acumulación. |
| [setCAccumBlueBits(byte value)](#setCAccumBlueBits-byte-) | Obtiene o establece el número de planos de bits azules en el búfer de acumulación. |
| [getCAccumAlphaBits()](#getCAccumAlphaBits--) | Obtiene o establece el número de planos de bits alfa en el búfer de acumulación. |
| [setCAccumAlphaBits(byte value)](#setCAccumAlphaBits-byte-) | Obtiene o establece el número de planos de bits alfa en el búfer de acumulación. |
| [getCDepthBits()](#getCDepthBits--) | Obtiene o establece la profundidad del búfer de profundidad (eje z). |
| [setCDepthBits(byte value)](#setCDepthBits-byte-) | Obtiene o establece la profundidad del búfer de profundidad (eje z). |
| [getCStencilBits()](#getCStencilBits--) | Obtiene o establece la profundidad del búfer de plantilla. |
| [setCStencilBits(byte value)](#setCStencilBits-byte-) | Obtiene o establece la profundidad del búfer de plantilla. |
| [getCAuxBuffers()](#getCAuxBuffers--) | Obtiene o establece el número de búferes auxiliares. |
| [setCAuxBuffers(byte value)](#setCAuxBuffers-byte-) | Obtiene o establece el número de búferes auxiliares. |
| [getILayerType()](#getILayerType--) | Obtiene o establece Este campo PUEDE ser ignorado |
| [setILayerType(byte value)](#setILayerType-byte-) | Obtiene o establece Este campo PUEDE ser ignorado |
| [getBReserved()](#getBReserved--) | Obtiene o establece especifica el número de planos de superposición y subyacentes. |
| [setBReserved(byte value)](#setBReserved-byte-) | Obtiene o establece especifica el número de planos de superposición y subyacentes. |
| [getDwLayerMask()](#getDwLayerMask--) | Obtiene o establece Este campo PUEDE ser ignorado. |
| [setDwLayerMask(int value)](#setDwLayerMask-int-) | Obtiene o establece Este campo PUEDE ser ignorado. |
| [getDwVisibleMask()](#getDwVisibleMask--) | Obtiene o establece especifica el color transparente o el índice de un plano subyacente. |
| [setDwVisibleMask(int value)](#setDwVisibleMask-int-) | Obtiene o establece especifica el color transparente o el índice de un plano subyacente. |
| [getDwDamageMask()](#getDwDamageMask--) | Obtiene o establece Este campo PUEDE ser ignorado |
| [setDwDamageMask(int value)](#setDwDamageMask-int-) | Obtiene o establece Este campo PUEDE ser ignorado |
### EmfPixelFormatDescriptor() {#EmfPixelFormatDescriptor--}
```
public EmfPixelFormatDescriptor()
```


### getNSize() {#getNSize--}
```
public short getNSize()
```


Obtiene o establece un entero de 16 bits que especifica el tamaño, en bytes, de esta estructura de datos.

**Returns:**
short
### setNSize(short value) {#setNSize-short-}
```
public void setNSize(short value)
```


Obtiene o establece un entero de 16 bits que especifica el tamaño, en bytes, de esta estructura de datos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getNVersion() {#getNVersion--}
```
public short getNVersion()
```


Obtiene o establece un entero de 16 bits que DEBE establecerse en 0x0001.

**Returns:**
short
### setNVersion(short value) {#setNVersion-short-}
```
public void setNVersion(short value)
```


Obtiene o establece un entero de 16 bits que DEBE establecerse en 0x0001.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


Obtiene o establece banderas de bits que especifican propiedades del búfer de píxeles que se usa para la salida a la superficie de dibujo. Estas propiedades no son todas mutuamente excluyentes; se permiten combinaciones de banderas, excepto donde se indique lo contrario.

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


Obtiene o establece banderas de bits que especifican propiedades del búfer de píxeles que se usa para la salida a la superficie de dibujo. Estas propiedades no son todas mutuamente excluyentes; se permiten combinaciones de banderas, excepto donde se indique lo contrario.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getIPixelType() {#getIPixelType--}
```
public byte getIPixelType()
```


Obtiene o establece el tipo de datos de píxel PFD\_TYPE\_RGBA 0x00 El formato de píxel es RGBA. PFD\_TYPE\_COLORINDEX 0x01 Cada píxel es un índice en una tabla de colores.

**Returns:**
byte
### setIPixelType(byte value) {#setIPixelType-byte-}
```
public void setIPixelType(byte value)
```


Obtiene o establece el tipo de datos de píxel PFD\_TYPE\_RGBA 0x00 El formato de píxel es RGBA. PFD\_TYPE\_COLORINDEX 0x01 Cada píxel es un índice en una tabla de colores.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getCColorBits() {#getCColorBits--}
```
public byte getCColorBits()
```


Obtiene o establece el número de bits por píxel para tipos de píxel RGBA, excluyendo los planos de bits alfa. Para píxeles de tabla de colores, es el tamaño de cada índice de la tabla de colores.

**Returns:**
byte
### setCColorBits(byte value) {#setCColorBits-byte-}
```
public void setCColorBits(byte value)
```


Obtiene o establece el número de bits por píxel para tipos de píxel RGBA, excluyendo los planos de bits alfa. Para píxeles de tabla de colores, es el tamaño de cada índice de la tabla de colores.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getCRedBits() {#getCRedBits--}
```
public byte getCRedBits()
```


Obtiene o establece el número de planos de bits rojos en cada búfer de color RGBA.

**Returns:**
byte
### setCRedBits(byte value) {#setCRedBits-byte-}
```
public void setCRedBits(byte value)
```


Obtiene o establece el número de planos de bits rojos en cada búfer de color RGBA.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getCRedShift() {#getCRedShift--}
```
public byte getCRedShift()
```


Obtiene o establece la cantidad de desplazamiento en bits para los planos de bits rojos en cada búfer de color RGBA.

**Returns:**
byte
### setCRedShift(byte value) {#setCRedShift-byte-}
```
public void setCRedShift(byte value)
```


Obtiene o establece la cantidad de desplazamiento en bits para los planos de bits rojos en cada búfer de color RGBA.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getCGreenBits() {#getCGreenBits--}
```
public byte getCGreenBits()
```


Obtiene o establece el número de planos de bits verdes en cada búfer de color RGBA.

**Returns:**
byte
### setCGreenBits(byte value) {#setCGreenBits-byte-}
```
public void setCGreenBits(byte value)
```


Obtiene o establece el número de planos de bits verdes en cada búfer de color RGBA.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getCGreenShift() {#getCGreenShift--}
```
public byte getCGreenShift()
```


Obtiene o establece la cantidad de desplazamiento para los planos de bits verdes en cada búfer de color RGBA.

**Returns:**
byte
### setCGreenShift(byte value) {#setCGreenShift-byte-}
```
public void setCGreenShift(byte value)
```


Obtiene o establece la cantidad de desplazamiento para los planos de bits verdes en cada búfer de color RGBA.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getCBlueBits() {#getCBlueBits--}
```
public byte getCBlueBits()
```


Obtiene o establece el número de planos de bits azules en cada búfer de color RGBA.

**Returns:**
byte
### setCBlueBits(byte value) {#setCBlueBits-byte-}
```
public void setCBlueBits(byte value)
```


Obtiene o establece el número de planos de bits azules en cada búfer de color RGBA.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getCBlueShift() {#getCBlueShift--}
```
public byte getCBlueShift()
```


Obtiene o establece la cantidad de desplazamiento para los planos de bits azules en cada búfer de color RGBA.

**Returns:**
byte
### setCBlueShift(byte value) {#setCBlueShift-byte-}
```
public void setCBlueShift(byte value)
```


Obtiene o establece la cantidad de desplazamiento para los planos de bits azules en cada búfer de color RGBA.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getCAlphaBits() {#getCAlphaBits--}
```
public byte getCAlphaBits()
```


Obtiene o establece el número de planos de bits alfa en cada búfer de color RGBA.

**Returns:**
byte
### setCAlphaBits(byte value) {#setCAlphaBits-byte-}
```
public void setCAlphaBits(byte value)
```


Obtiene o establece el número de planos de bits alfa en cada búfer de color RGBA.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getCAlphaShift() {#getCAlphaShift--}
```
public byte getCAlphaShift()
```


Obtiene o establece la cantidad de desplazamiento para los planos de bits alfa en cada búfer de color RGBA.

**Returns:**
byte
### setCAlphaShift(byte value) {#setCAlphaShift-byte-}
```
public void setCAlphaShift(byte value)
```


Obtiene o establece la cantidad de desplazamiento para los planos de bits alfa en cada búfer de color RGBA.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getCAccumBits() {#getCAccumBits--}
```
public byte getCAccumBits()
```


Obtiene o establece el número total de planos de bits en el búfer de acumulación.

**Returns:**
byte
### setCAccumBits(byte value) {#setCAccumBits-byte-}
```
public void setCAccumBits(byte value)
```


Obtiene o establece el número total de planos de bits en el búfer de acumulación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getCAccumRedBits() {#getCAccumRedBits--}
```
public byte getCAccumRedBits()
```


Obtiene o establece el número de planos de bits rojos en el búfer de acumulación.

**Returns:**
byte
### setCAccumRedBits(byte value) {#setCAccumRedBits-byte-}
```
public void setCAccumRedBits(byte value)
```


Obtiene o establece el número de planos de bits rojos en el búfer de acumulación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getCAccumGreenBits() {#getCAccumGreenBits--}
```
public byte getCAccumGreenBits()
```


Obtiene o establece el número de planos de bits verdes en la acumulación.

**Returns:**
byte
### setCAccumGreenBits(byte value) {#setCAccumGreenBits-byte-}
```
public void setCAccumGreenBits(byte value)
```


Obtiene o establece el número de planos de bits verdes en la acumulación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getCAccumBlueBits() {#getCAccumBlueBits--}
```
public byte getCAccumBlueBits()
```


Obtiene o establece el número de planos de bits azules en el búfer de acumulación.

**Returns:**
byte
### setCAccumBlueBits(byte value) {#setCAccumBlueBits-byte-}
```
public void setCAccumBlueBits(byte value)
```


Obtiene o establece el número de planos de bits azules en el búfer de acumulación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getCAccumAlphaBits() {#getCAccumAlphaBits--}
```
public byte getCAccumAlphaBits()
```


Obtiene o establece el número de planos de bits alfa en el búfer de acumulación.

**Returns:**
byte
### setCAccumAlphaBits(byte value) {#setCAccumAlphaBits-byte-}
```
public void setCAccumAlphaBits(byte value)
```


Obtiene o establece el número de planos de bits alfa en el búfer de acumulación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getCDepthBits() {#getCDepthBits--}
```
public byte getCDepthBits()
```


Obtiene o establece la profundidad del búfer de profundidad (eje z).

**Returns:**
byte
### setCDepthBits(byte value) {#setCDepthBits-byte-}
```
public void setCDepthBits(byte value)
```


Obtiene o establece la profundidad del búfer de profundidad (eje z).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getCStencilBits() {#getCStencilBits--}
```
public byte getCStencilBits()
```


Obtiene o establece la profundidad del búfer de plantilla.

**Returns:**
byte
### setCStencilBits(byte value) {#setCStencilBits-byte-}
```
public void setCStencilBits(byte value)
```


Obtiene o establece la profundidad del búfer de plantilla.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getCAuxBuffers() {#getCAuxBuffers--}
```
public byte getCAuxBuffers()
```


Obtiene o establece especifica el número de búferes auxiliares. Los búferes auxiliares no son compatibles.

**Returns:**
byte
### setCAuxBuffers(byte value) {#setCAuxBuffers-byte-}
```
public void setCAuxBuffers(byte value)
```


Obtiene o establece especifica el número de búferes auxiliares. Los búferes auxiliares no son compatibles.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getILayerType() {#getILayerType--}
```
public byte getILayerType()
```


Obtiene o establece Este campo PUEDE ser ignorado

**Returns:**
byte
### setILayerType(byte value) {#setILayerType-byte-}
```
public void setILayerType(byte value)
```


Obtiene o establece Este campo PUEDE ser ignorado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getBReserved() {#getBReserved--}
```
public byte getBReserved()
```


Obtiene o establece especifica el número de planos de superposición y subyacentes. Los bits 0 a 3 especifican hasta 15 planos de superposición y los bits 4 a 7 especifican hasta 15 planos subyacentes.

**Returns:**
byte
### setBReserved(byte value) {#setBReserved-byte-}
```
public void setBReserved(byte value)
```


Obtiene o establece especifica el número de planos de superposición y subyacentes. Los bits 0 a 3 especifican hasta 15 planos de superposición y los bits 4 a 7 especifican hasta 15 planos subyacentes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getDwLayerMask() {#getDwLayerMask--}
```
public int getDwLayerMask()
```


Obtiene o establece Este campo PUEDE ser ignorado.

**Returns:**
int
### setDwLayerMask(int value) {#setDwLayerMask-int-}
```
public void setDwLayerMask(int value)
```


Obtiene o establece Este campo PUEDE ser ignorado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getDwVisibleMask() {#getDwVisibleMask--}
```
public int getDwVisibleMask()
```


Obtiene o establece especifica el color transparente o el índice de un plano subyacente. Cuando el tipo de píxel es RGBA, dwVisibleMask es un valor de color RGB transparente. Cuando el tipo de píxel es índice de color, es un valor de índice transparente.

**Returns:**
int
### setDwVisibleMask(int value) {#setDwVisibleMask-int-}
```
public void setDwVisibleMask(int value)
```


Obtiene o establece especifica el color transparente o el índice de un plano subyacente. Cuando el tipo de píxel es RGBA, dwVisibleMask es un valor de color RGB transparente. Cuando el tipo de píxel es índice de color, es un valor de índice transparente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getDwDamageMask() {#getDwDamageMask--}
```
public int getDwDamageMask()
```


Obtiene o establece Este campo PUEDE ser ignorado

**Returns:**
int
### setDwDamageMask(int value) {#setDwDamageMask-int-}
```
public void setDwDamageMask(int value)
```


Obtiene o establece Este campo PUEDE ser ignorado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

