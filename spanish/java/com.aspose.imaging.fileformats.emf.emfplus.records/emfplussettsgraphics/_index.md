---
title: "EmfPlusSetTsGraphics"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusSetTSGraphics especifica el estado de un contexto de dispositivo gráfico para un servidor de terminales."
type: docs
weight: 67
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetTsGraphics extends EmfPlusTerminalServerRecordType
```

El registro EmfPlusSetTSGraphics especifica el estado de un contexto de dispositivo gráfico para un servidor de terminales.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusSetTsGraphics(EmfPlusRecord source)](#EmfPlusSetTsGraphics-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusSetTsGraphics`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBasicVgaColors()](#getBasicVgaColors--) | Obtiene un valor que indica si [colores VGA básicos]. |
| [getHavePalette()](#getHavePalette--) | Obtiene un valor que indica si [tiene paleta]. |
| [getAntiAliasMode()](#getAntiAliasMode--) | Obtiene o establece un entero sin signo de 8 bits que especifica la calidad del renderizado de líneas, incluido el tipo de antialiasing de líneas. |
| [setAntiAliasMode(byte value)](#setAntiAliasMode-byte-) | Obtiene o establece un entero sin signo de 8 bits que especifica la calidad del renderizado de líneas, incluido el tipo de antialiasing de líneas. |
| [getTextRenderHint()](#getTextRenderHint--) | Obtiene o establece un entero sin signo de 8 bits que especifica la calidad del renderizado de texto, incluido el tipo de antialiasing de texto. |
| [setTextRenderHint(byte value)](#setTextRenderHint-byte-) | Obtiene o establece un entero sin signo de 8 bits que especifica la calidad del renderizado de texto, incluido el tipo de antialiasing de texto. |
| [getCompositingMode()](#getCompositingMode--) | Obtiene o establece un entero sin signo de 8 bits que especifica cómo se combinan los colores de origen con los colores de fondo. |
| [setCompositingMode(byte value)](#setCompositingMode-byte-) | Obtiene o establece un entero sin signo de 8 bits que especifica cómo se combinan los colores de origen con los colores de fondo. |
| [getCompositingQuality()](#getCompositingQuality--) | Obtiene o establece un entero sin signo de 8 bits que especifica el grado de suavizado a aplicar a líneas, curvas y los bordes de áreas rellenas para que parezcan más continuas o definidas con nitidez. |
| [setCompositingQuality(byte value)](#setCompositingQuality-byte-) | Obtiene o establece un entero sin signo de 8 bits que especifica el grado de suavizado a aplicar a líneas, curvas y los bordes de áreas rellenas para que parezcan más continuas o definidas con nitidez. |
| [getRenderOriginX()](#getRenderOriginX--) | Obtiene o establece un entero con signo de 16 bits, que es la coordenada horizontal del origen para renderizar matrices de semitonos y dithering. |
| [setRenderOriginX(short value)](#setRenderOriginX-short-) | Obtiene o establece un entero con signo de 16 bits, que es la coordenada horizontal del origen para renderizar matrices de semitonos y dithering. |
| [getRenderOriginY()](#getRenderOriginY--) | Obtiene o establece un entero con signo de 16 bits, que es la coordenada vertical del origen para renderizar matrices de semitonos y dithering. |
| [setRenderOriginY(short value)](#setRenderOriginY-short-) | Obtiene o establece un entero con signo de 16 bits, que es la coordenada vertical del origen para renderizar matrices de semitonos y dithering. |
| [getTextContrast()](#getTextContrast--) | Obtiene o establece un entero sin signo de 16 bits que especifica el valor de corrección gamma utilizado para renderizar texto anti-alias y ClearType. |
| [setTextContrast(short value)](#setTextContrast-short-) | Obtiene o establece un entero sin signo de 16 bits que especifica el valor de corrección gamma utilizado para renderizar texto anti-alias y ClearType. |
| [getFilterType()](#getFilterType--) | Obtiene o establece un entero sin signo de 8 bits que especifica cómo se realiza el escalado, incluido el estiramiento y la reducción. |
| [setFilterType(byte value)](#setFilterType-byte-) | Obtiene o establece un entero sin signo de 8 bits que especifica cómo se realiza el escalado, incluido el estiramiento y la reducción. |
| [getPixelOffset()](#getPixelOffset--) | Obtiene o establece un entero sin signo de 8 bits que especifica la calidad general de la imagen y del proceso de renderizado de texto. |
| [setPixelOffset(byte value)](#setPixelOffset-byte-) | Obtiene o establece un entero sin signo de 8 bits que especifica la calidad general de la imagen y del proceso de renderizado de texto. |
| [getWorldToDevice()](#getWorldToDevice--) | Obtiene o establece un objeto EmfPlusTransformMatrix de 192 bits (sección 2.2.2.47) que especifica las transformaciones del espacio mundial al espacio del dispositivo. |
| [setWorldToDevice(Matrix value)](#setWorldToDevice-com.aspose.imaging.Matrix-) | Obtiene o establece un objeto EmfPlusTransformMatrix de 192 bits (sección 2.2.2.47) que especifica las transformaciones del espacio mundial al espacio del dispositivo. |
| [getPalette()](#getPalette--) | Obtiene o establece un objeto EmfPlusPalette opcional. |
| [setPalette(EmfPlusPalette value)](#setPalette-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-) | Obtiene o establece un objeto EmfPlusPalette opcional. |
### EmfPlusSetTsGraphics(EmfPlusRecord source) {#EmfPlusSetTsGraphics-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetTsGraphics(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusSetTsGraphics`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### getBasicVgaColors() {#getBasicVgaColors--}
```
public boolean getBasicVgaColors()
```


Obtiene un valor que indica si [basic vga colors]. Si está establecido, la paleta contiene solo los colores VGA básicos.

Valor: `true` si [basic vga colors]; de lo contrario, `false`.

**Returns:**
boolean
### getHavePalette() {#getHavePalette--}
```
public boolean getHavePalette()
```


Obtiene un valor que indica si [have palette]. Si está establecido, este registro contiene un objeto EmfPlusPalette (sección 2.2.2.28) en el campo Palette después de los datos del estado gráfico.

Valor: `true` si [have palette]; de lo contrario, `false`.

**Returns:**
boolean
### getAntiAliasMode() {#getAntiAliasMode--}
```
public byte getAntiAliasMode()
```


Obtiene o establece un entero sin signo de 8 bits que especifica la calidad del renderizado de líneas, incluido el tipo de antialiasing de línea. DEBE estar definido en la enumeración SmoothingMode (sección 2.1.1.28).

Valor: El modo de antialiasing.

**Returns:**
byte
### setAntiAliasMode(byte value) {#setAntiAliasMode-byte-}
```
public void setAntiAliasMode(byte value)
```


Obtiene o establece un entero sin signo de 8 bits que especifica la calidad del renderizado de líneas, incluido el tipo de antialiasing de línea. DEBE estar definido en la enumeración SmoothingMode (sección 2.1.1.28).

Valor: El modo de antialiasing.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getTextRenderHint() {#getTextRenderHint--}
```
public byte getTextRenderHint()
```


Obtiene o establece un entero sin signo de 8 bits que especifica la calidad del renderizado de texto, incluido el tipo de antialiasing de texto. DEBE estar definido en la enumeración TextRenderingHint (sección 2.1.1.32).

Valor: La sugerencia de renderizado de texto.

**Returns:**
byte
### setTextRenderHint(byte value) {#setTextRenderHint-byte-}
```
public void setTextRenderHint(byte value)
```


Obtiene o establece un entero sin signo de 8 bits que especifica la calidad del renderizado de texto, incluido el tipo de antialiasing de texto. DEBE estar definido en la enumeración TextRenderingHint (sección 2.1.1.32).

Valor: La sugerencia de renderizado de texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getCompositingMode() {#getCompositingMode--}
```
public byte getCompositingMode()
```


Obtiene o establece un entero sin signo de 8 bits que especifica cómo se combinan los colores de origen con los colores de fondo. DEBE ser un valor de la enumeración CompositingMode (sección 2.1.1.5).

Valor: El modo de composición.

**Returns:**
byte
### setCompositingMode(byte value) {#setCompositingMode-byte-}
```
public void setCompositingMode(byte value)
```


Obtiene o establece un entero sin signo de 8 bits que especifica cómo se combinan los colores de origen con los colores de fondo. DEBE ser un valor de la enumeración CompositingMode (sección 2.1.1.5).

Valor: El modo de composición.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getCompositingQuality() {#getCompositingQuality--}
```
public byte getCompositingQuality()
```


Obtiene o establece un entero sin signo de 8 bits que especifica el grado de suavizado a aplicar a líneas, curvas y los bordes de áreas rellenas para que aparezcan más continuas o bien definidas. DEBE ser un valor de la enumeración CompositingQuality (sección 2.1.1.6).

Valor: La calidad de composición.

**Returns:**
byte
### setCompositingQuality(byte value) {#setCompositingQuality-byte-}
```
public void setCompositingQuality(byte value)
```


Obtiene o establece un entero sin signo de 8 bits que especifica el grado de suavizado a aplicar a líneas, curvas y los bordes de áreas rellenas para que aparezcan más continuas o bien definidas. DEBE ser un valor de la enumeración CompositingQuality (sección 2.1.1.6).

Valor: La calidad de composición.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getRenderOriginX() {#getRenderOriginX--}
```
public short getRenderOriginX()
```


Obtiene o establece un entero con signo de 16 bits, que es la coordenada horizontal del origen para renderizar matrices de semitonos y dithering.

Valor: El origen de renderizado x.

**Returns:**
short
### setRenderOriginX(short value) {#setRenderOriginX-short-}
```
public void setRenderOriginX(short value)
```


Obtiene o establece un entero con signo de 16 bits, que es la coordenada horizontal del origen para renderizar matrices de semitonos y dithering.

Valor: El origen de renderizado x.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getRenderOriginY() {#getRenderOriginY--}
```
public short getRenderOriginY()
```


Obtiene o establece un entero con signo de 16 bits, que es la coordenada vertical del origen para renderizar matrices de semitonos y dithering.

Valor: El origen de renderizado y.

**Returns:**
short
### setRenderOriginY(short value) {#setRenderOriginY-short-}
```
public void setRenderOriginY(short value)
```


Obtiene o establece un entero con signo de 16 bits, que es la coordenada vertical del origen para renderizar matrices de semitonos y dithering.

Valor: El origen de renderizado y.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getTextContrast() {#getTextContrast--}
```
public short getTextContrast()
```


Obtiene o establece un entero sin signo de 16 bits que especifica el valor de corrección gamma utilizado para renderizar texto antialias y ClearType. Este valor DEBE estar en el rango de 0 a 12, inclusive.

Valor: El contraste del texto.

**Returns:**
short
### setTextContrast(short value) {#setTextContrast-short-}
```
public void setTextContrast(short value)
```


Obtiene o establece un entero sin signo de 16 bits que especifica el valor de corrección gamma utilizado para renderizar texto antialias y ClearType. Este valor DEBE estar en el rango de 0 a 12, inclusive.

Valor: El contraste del texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getFilterType() {#getFilterType--}
```
public byte getFilterType()
```


Obtiene o establece un entero sin signo de 8 bits que especifica cómo se realiza el escalado, incluido el estiramiento y la reducción. DEBE ser un valor de la enumeración FilterType (sección 2.1.1.11).

Valor: El tipo de filtro.

**Returns:**
byte
### setFilterType(byte value) {#setFilterType-byte-}
```
public void setFilterType(byte value)
```


Obtiene o establece un entero sin signo de 8 bits que especifica cómo se realiza el escalado, incluido el estiramiento y la reducción. DEBE ser un valor de la enumeración FilterType (sección 2.1.1.11).

Valor: El tipo de filtro.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getPixelOffset() {#getPixelOffset--}
```
public byte getPixelOffset()
```


Obtiene o establece un entero sin signo de 8 bits que especifica la calidad general de la imagen y del proceso de renderizado de texto. DEBE ser un valor de la enumeración PixelOffsetMode (sección 2.1.1.26).

Valor: El desplazamiento de píxel.

**Returns:**
byte
### setPixelOffset(byte value) {#setPixelOffset-byte-}
```
public void setPixelOffset(byte value)
```


Obtiene o establece un entero sin signo de 8 bits que especifica la calidad general de la imagen y del proceso de renderizado de texto. DEBE ser un valor de la enumeración PixelOffsetMode (sección 2.1.1.26).

Valor: El desplazamiento de píxel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getWorldToDevice() {#getWorldToDevice--}
```
public Matrix getWorldToDevice()
```


Obtiene o establece un objeto EmfPlusTransformMatrix de 192 bits (sección 2.2.2.47) que especifica las transformaciones del espacio mundial al espacio del dispositivo.

Valor: De mundo a dispositivo.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setWorldToDevice(Matrix value) {#setWorldToDevice-com.aspose.imaging.Matrix-}
```
public void setWorldToDevice(Matrix value)
```


Obtiene o establece un objeto EmfPlusTransformMatrix de 192 bits (sección 2.2.2.47) que especifica las transformaciones del espacio mundial al espacio del dispositivo.

Valor: De mundo a dispositivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getPalette() {#getPalette--}
```
public EmfPlusPalette getPalette()
```


Obtiene o establece un objeto EmfPlusPalette opcional.

Valor: La paleta.

**Returns:**
[EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette)
### setPalette(EmfPlusPalette value) {#setPalette-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-}
```
public void setPalette(EmfPlusPalette value)
```


Obtiene o establece un objeto EmfPlusPalette opcional.

Valor: La paleta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette) |  |

