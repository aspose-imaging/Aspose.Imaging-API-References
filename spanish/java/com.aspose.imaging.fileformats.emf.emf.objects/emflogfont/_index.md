---
title: "EmfLogFont"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto LogFont especifica los atributos básicos de una fuente lógica."
type: docs
weight: 22
url: /es/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogfont/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public class EmfLogFont extends EmfObject
```

El objeto LogFont especifica los atributos básicos de una fuente lógica.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfLogFont()](#EmfLogFont--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getHeight()](#getHeight--) | Obtiene o establece un entero con signo de 32 bits que especifica la altura, en unidades lógicas, de la celda de carácter o carácter de la fuente. |
| [setHeight(int value)](#setHeight-int-) | Obtiene o establece un entero con signo de 32 bits que especifica la altura, en unidades lógicas, de la celda de carácter o carácter de la fuente. |
| [getWidth()](#getWidth--) | Obtiene o establece un entero con signo de 32 bits que especifica el ancho promedio, en unidades lógicas, de los caracteres de la fuente. |
| [setWidth(int value)](#setWidth-int-) | Obtiene o establece un entero con signo de 32 bits que especifica el ancho promedio, en unidades lógicas, de los caracteres de la fuente. |
| [getEscapement()](#getEscapement--) | Obtiene o establece un entero con signo de 32 bits que especifica el ángulo, en décimas de grado, entre el vector de escapamiento y el eje x del dispositivo. |
| [setEscapement(int value)](#setEscapement-int-) | Obtiene o establece un entero con signo de 32 bits que especifica el ángulo, en décimas de grado, entre el vector de escapamiento y el eje x del dispositivo. |
| [getOrientation()](#getOrientation--) | Obtiene o establece un entero con signo de 32 bits que especifica el ángulo, en décimas de grado, entre la línea base de cada carácter y el eje x del dispositivo. |
| [setOrientation(int value)](#setOrientation-int-) | Obtiene o establece un entero con signo de 32 bits que especifica el ángulo, en décimas de grado, entre la línea base de cada carácter y el eje x del dispositivo. |
| [getWeight()](#getWeight--) | Obtiene o establece un entero con signo de 32 bits que especifica el peso de la fuente en el rango de cero a 1000. |
| [setWeight(int value)](#setWeight-int-) | Obtiene o establece un entero con signo de 32 bits que especifica el peso de la fuente en el rango de cero a 1000. |
| [getItalic()](#getItalic--) | Obtiene o establece un entero sin signo de 8 bits que especifica una fuente cursiva si se establece a 0x01; de lo contrario, DEBE establecerse a 0x00. |
| [setItalic(byte value)](#setItalic-byte-) | Obtiene o establece un entero sin signo de 8 bits que especifica una fuente cursiva si se establece a 0x01; de lo contrario, DEBE establecerse a 0x00. |
| [getUnderline()](#getUnderline--) | Obtiene o establece un entero sin signo de 8 bits que especifica una fuente subrayada si se establece a 0x01; de lo contrario, DEBE establecerse a 0x00. |
| [setUnderline(byte value)](#setUnderline-byte-) | Obtiene o establece un entero sin signo de 8 bits que especifica una fuente subrayada si se establece a 0x01; de lo contrario, DEBE establecerse a 0x00. |
| [getStrikeout()](#getStrikeout--) | Obtiene o establece un entero sin signo de 8 bits que especifica una fuente tachada si se establece a 0x01; de lo contrario, DEBE establecerse a 0x00. |
| [setStrikeout(byte value)](#setStrikeout-byte-) | Obtiene o establece un entero sin signo de 8 bits que especifica una fuente tachada si se establece a 0x01; de lo contrario, DEBE establecerse a 0x00. |
| [getCharSet()](#getCharSet--) | Obtiene o establece un entero sin signo de 8 bits que especifica el conjunto de glifos de caracteres. |
| [setCharSet(byte value)](#setCharSet-byte-) | Obtiene o establece un entero sin signo de 8 bits que especifica el conjunto de glifos de caracteres. |
| [getOutPrecision()](#getOutPrecision--) | Obtiene o establece un entero sin signo de 8 bits que especifica la precisión de salida. |
| [setOutPrecision(byte value)](#setOutPrecision-byte-) | Obtiene o establece un entero sin signo de 8 bits que especifica la precisión de salida. |
| [getClipPrecision()](#getClipPrecision--) | Obtiene o establece un entero sin signo de 8 bits que especifica la precisión de recorte. |
| [setClipPrecision(byte value)](#setClipPrecision-byte-) | Obtiene o establece un entero sin signo de 8 bits que especifica la precisión de recorte. |
| [getQuality()](#getQuality--) | Obtiene o establece un entero sin signo de 8 bits que especifica la calidad de salida. |
| [setQuality(byte value)](#setQuality-byte-) | Obtiene o establece un entero sin signo de 8 bits que especifica la calidad de salida. |
| [getPitchAndFamily()](#getPitchAndFamily--) | Obtiene o establece un objeto WMF PitchAndFamily ([MS-WMF] sección 2.2.2.14) que especifica el paso y la familia de la fuente. |
| [setPitchAndFamily(WmfPitchAndFamily value)](#setPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-) | Obtiene o establece un objeto WMF PitchAndFamily ([MS-WMF] sección 2.2.2.14) que especifica el paso y la familia de la fuente. |
| [getFacename()](#getFacename--) | Obtiene o establece un Facename (64 bytes): una cadena de no más de 32 caracteres Unicode que especifica el nombre de la tipografía de la fuente. |
| [setFacename(String value)](#setFacename-java.lang.String-) | Obtiene o establece un Facename (64 bytes): una cadena de no más de 32 caracteres Unicode que especifica el nombre de la tipografía de la fuente. |
### EmfLogFont() {#EmfLogFont--}
```
public EmfLogFont()
```


### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtiene o establece un entero con signo de 32 bits que especifica la altura, en unidades lógicas, de la celda de carácter o carácter de la fuente. El valor de altura del carácter, también conocido como el tamaño em, es el valor de altura de la celda de carácter menos el valor de interlínea interno. El asignador de fuentes DEBERÍA interpretar el valor especificado en el campo Height de la siguiente manera.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica la altura, en unidades lógicas, de la celda de carácter o carácter de la fuente. El valor de altura del carácter, también conocido como el tamaño em, es el valor de altura de la celda de carácter menos el valor de interlínea interno. El asignador de fuentes DEBERÍA interpretar el valor especificado en el campo Height de la siguiente manera.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtiene o establece un entero con signo de 32 bits que especifica el ancho promedio, en unidades lógicas, de los caracteres de la fuente. Si el valor del campo Width es cero, se DEBERÍA calcular un valor apropiado a partir de otros valores LogFont para encontrar una fuente que tenga la relación de aspecto prevista por el tipógrafo.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica el ancho promedio, en unidades lógicas, de los caracteres de la fuente. Si el valor del campo Width es cero, se DEBERÍA calcular un valor apropiado a partir de otros valores LogFont para encontrar una fuente que tenga la relación de aspecto prevista por el tipógrafo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getEscapement() {#getEscapement--}
```
public int getEscapement()
```


Obtiene o establece un entero con signo de 32 bits que especifica el ángulo, en décimas de grado, entre el vector de escapamiento y el eje x del dispositivo. El vector de escapamiento es paralelo a la línea base de una fila de texto.

**Returns:**
int
### setEscapement(int value) {#setEscapement-int-}
```
public void setEscapement(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica el ángulo, en décimas de grado, entre el vector de escapamiento y el eje x del dispositivo. El vector de escapamiento es paralelo a la línea base de una fila de texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Obtiene o establece un entero con signo de 32 bits que especifica el ángulo, en décimas de grado, entre la línea base de cada carácter y el eje x del dispositivo.

**Returns:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica el ángulo, en décimas de grado, entre la línea base de cada carácter y el eje x del dispositivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getWeight() {#getWeight--}
```
public int getWeight()
```


Obtiene o establece un entero con signo de 32 bits que especifica el grosor de la fuente en el rango de cero a 1000. Por ejemplo, 400 es normal y 700 es negrita. Si este valor es cero, se puede usar un grosor predeterminado.

**Returns:**
int
### setWeight(int value) {#setWeight-int-}
```
public void setWeight(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica el grosor de la fuente en el rango de cero a 1000. Por ejemplo, 400 es normal y 700 es negrita. Si este valor es cero, se puede usar un grosor predeterminado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getItalic() {#getItalic--}
```
public byte getItalic()
```


Obtiene o establece un entero sin signo de 8 bits que especifica una fuente cursiva si se establece a 0x01; de lo contrario, DEBE establecerse a 0x00.

**Returns:**
byte
### setItalic(byte value) {#setItalic-byte-}
```
public void setItalic(byte value)
```


Obtiene o establece un entero sin signo de 8 bits que especifica una fuente cursiva si se establece a 0x01; de lo contrario, DEBE establecerse a 0x00.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getUnderline() {#getUnderline--}
```
public byte getUnderline()
```


Obtiene o establece un entero sin signo de 8 bits que especifica una fuente subrayada si se establece a 0x01; de lo contrario, DEBE establecerse a 0x00.

**Returns:**
byte
### setUnderline(byte value) {#setUnderline-byte-}
```
public void setUnderline(byte value)
```


Obtiene o establece un entero sin signo de 8 bits que especifica una fuente subrayada si se establece a 0x01; de lo contrario, DEBE establecerse a 0x00.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getStrikeout() {#getStrikeout--}
```
public byte getStrikeout()
```


Obtiene o establece un entero sin signo de 8 bits que especifica una fuente tachada si se establece a 0x01; de lo contrario, DEBE establecerse a 0x00.

**Returns:**
byte
### setStrikeout(byte value) {#setStrikeout-byte-}
```
public void setStrikeout(byte value)
```


Obtiene o establece un entero sin signo de 8 bits que especifica una fuente tachada si se establece a 0x01; de lo contrario, DEBE establecerse a 0x00.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getCharSet() {#getCharSet--}
```
public byte getCharSet()
```


Obtiene o establece un entero sin signo de 8 bits que especifica el conjunto de glifos de caracteres. DEBE ser un valor en la enumeración WMF CharacterSet ([MS-WMF] sección 2.1.1.5). Si el conjunto de caracteres es desconocido, el procesamiento del metarchivo NO DEBERÍA intentar traducir o interpretar cadenas que se renderizan con esa fuente.

**Returns:**
byte
### setCharSet(byte value) {#setCharSet-byte-}
```
public void setCharSet(byte value)
```


Obtiene o establece un entero sin signo de 8 bits que especifica el conjunto de glifos de caracteres. DEBE ser un valor en la enumeración WMF CharacterSet ([MS-WMF] sección 2.1.1.5). Si el conjunto de caracteres es desconocido, el procesamiento del metarchivo NO DEBERÍA intentar traducir o interpretar cadenas que se renderizan con esa fuente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getOutPrecision() {#getOutPrecision--}
```
public byte getOutPrecision()
```


Obtiene o establece un entero sin signo de 8 bits que especifica la precisión de salida. La precisión de salida define cuán estrechamente se requiere que la fuente coincida con la altura, anchura, orientación de caracteres, escapamiento, paso y tipo de fuente solicitados. DEBE ser un valor de la enumeración WMF OutPrecision.

**Returns:**
byte
### setOutPrecision(byte value) {#setOutPrecision-byte-}
```
public void setOutPrecision(byte value)
```


Obtiene o establece un entero sin signo de 8 bits que especifica la precisión de salida. La precisión de salida define cuán estrechamente se requiere que la fuente coincida con la altura, anchura, orientación de caracteres, escapamiento, paso y tipo de fuente solicitados. DEBE ser un valor de la enumeración WMF OutPrecision.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getClipPrecision() {#getClipPrecision--}
```
public byte getClipPrecision()
```


Obtiene o establece un entero sin signo de 8 bits que especifica la precisión de recorte. La precisión de recorte define cómo recortar los caracteres que están parcialmente fuera de la región de recorte. Puede ser uno o más de los indicadores WMF ClipPrecision.

**Returns:**
byte
### setClipPrecision(byte value) {#setClipPrecision-byte-}
```
public void setClipPrecision(byte value)
```


Obtiene o establece un entero sin signo de 8 bits que especifica la precisión de recorte. La precisión de recorte define cómo recortar los caracteres que están parcialmente fuera de la región de recorte. Puede ser uno o más de los indicadores WMF ClipPrecision.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getQuality() {#getQuality--}
```
public byte getQuality()
```


Obtiene o establece un entero sin signo de 8 bits que especifica la calidad de salida. La calidad de salida define cuán estrechamente se debe intentar que los atributos de fuente lógica coincidan con los de una fuente física real. DEBE ser uno de los valores de la enumeración WMF FontQuality ([MS-WMF] sección 2.1.1.10).

**Returns:**
byte
### setQuality(byte value) {#setQuality-byte-}
```
public void setQuality(byte value)
```


Obtiene o establece un entero sin signo de 8 bits que especifica la calidad de salida. La calidad de salida define cuán estrechamente se debe intentar que los atributos de fuente lógica coincidan con los de una fuente física real. DEBE ser uno de los valores de la enumeración WMF FontQuality ([MS-WMF] sección 2.1.1.10).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getPitchAndFamily() {#getPitchAndFamily--}
```
public WmfPitchAndFamily getPitchAndFamily()
```


Obtiene o establece un objeto WMF PitchAndFamily ([MS-WMF] sección 2.2.2.14) que especifica el paso y la familia de la fuente. Las familias de fuentes describen el aspecto de una fuente de manera general. Se utilizan para especificar una fuente cuando el tipo de letra especificado no está disponible.

**Returns:**
[WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily)
### setPitchAndFamily(WmfPitchAndFamily value) {#setPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-}
```
public void setPitchAndFamily(WmfPitchAndFamily value)
```


Obtiene o establece un objeto WMF PitchAndFamily ([MS-WMF] sección 2.2.2.14) que especifica el paso y la familia de la fuente. Las familias de fuentes describen el aspecto de una fuente de manera general. Se utilizan para especificar una fuente cuando el tipo de letra especificado no está disponible.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |

### getFacename() {#getFacename--}
```
public String getFacename()
```


Obtiene o establece un Facename (64 bytes): una cadena de no más de 32 caracteres Unicode que especifica el nombre del tipo de letra de la fuente. Si la longitud de esta cadena es inferior a 32 caracteres, DEBE estar presente un NULL terminador, después del cual el resto de este campo DEBE ser ignorado.

**Returns:**
java.lang.String
### setFacename(String value) {#setFacename-java.lang.String-}
```
public void setFacename(String value)
```


Obtiene o establece un Facename (64 bytes): una cadena de no más de 32 caracteres Unicode que especifica el nombre del tipo de letra de la fuente. Si la longitud de esta cadena es inferior a 32 caracteres, DEBE estar presente un NULL terminador, después del cual el resto de este campo DEBE ser ignorado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

