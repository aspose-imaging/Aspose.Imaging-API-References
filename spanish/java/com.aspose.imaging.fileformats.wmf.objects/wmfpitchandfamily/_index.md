---
title: "WmfPitchAndFamily"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto PitchAndFamily especifica las propiedades de paso y familia de un objeto Font sección 2.2.1.2."
type: docs
weight: 54
url: /es/java/com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class WmfPitchAndFamily extends Struct<WmfPitchAndFamily>
```

El objeto PitchAndFamily especifica las propiedades de paso y familia de un objeto Font (sección 2.2.1.2). El paso se refiere al ancho de los caracteres, y la familia se refiere a la apariencia general de una fuente.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WmfPitchAndFamily()](#WmfPitchAndFamily--) |  |
| [WmfPitchAndFamily(byte byteData)](#WmfPitchAndFamily-byte-) | Inicializa una nueva instancia de la estructura `WmfPitchAndFamily`. |
| [WmfPitchAndFamily(byte pitch, byte family)](#WmfPitchAndFamily-byte-byte-) | Inicializa una nueva instancia de la estructura `WmfPitchAndFamily`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFamily()](#getFamily--) | Obtiene una propiedad de una fuente que describe su apariencia general. |
| [getPitch()](#getPitch--) | Obtiene una propiedad de una fuente que describe el paso de los caracteres. |
| [getByteData()](#getByteData--) | Establece los datos ``. |
| [setByteData(byte value)](#setByteData-byte-) | Establece los datos ``. |
| [toByte()](#toByte--) | Al byte. |
| [CloneTo(WmfPitchAndFamily that)](#CloneTo-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-) |  |
| [Clone()](#Clone--) |  |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isEquals(WmfPitchAndFamily obj1, WmfPitchAndFamily obj2)](#isEquals-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-) |  |
### WmfPitchAndFamily() {#WmfPitchAndFamily--}
```
public WmfPitchAndFamily()
```


### WmfPitchAndFamily(byte byteData) {#WmfPitchAndFamily-byte-}
```
public WmfPitchAndFamily(byte byteData)
```


Inicializa una nueva instancia de la estructura `WmfPitchAndFamily`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| byteData | byte | Los datos ``. |

### WmfPitchAndFamily(byte pitch, byte family) {#WmfPitchAndFamily-byte-byte-}
```
public WmfPitchAndFamily(byte pitch, byte family)
```


Inicializa una nueva instancia de la estructura `WmfPitchAndFamily`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pitch | byte | El paso. |
| familia | byte | La familia. |

### getFamily() {#getFamily--}
```
public byte getFamily()
```


Obtiene una propiedad de una fuente que describe su apariencia general. Esto DEBE ser un valor en la enumeración FamilyFont.

Valor: La familia.

**Returns:**
byte
### getPitch() {#getPitch--}
```
public byte getPitch()
```


Obtiene una propiedad de una fuente que describe el tono de los caracteres. Esto DEBE ser un valor en la enumeración PitchFont.

Valor: El tono.

**Returns:**
byte
### getByteData() {#getByteData--}
```
public byte getByteData()
```


Establece los datos ``.

Valor: Los `` data ``.

**Returns:**
byte
### setByteData(byte value) {#setByteData-byte-}
```
public void setByteData(byte value)
```


Establece los datos ``.

Valor: Los `` data ``.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### toByte() {#toByte--}
```
public byte toByte()
```


Al byte.

**Returns:**
byte - El valor del byte.
### CloneTo(WmfPitchAndFamily that) {#CloneTo-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-}
```
public void CloneTo(WmfPitchAndFamily that)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| that | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |

### Clone() {#Clone--}
```
public WmfPitchAndFamily Clone()
```




**Returns:**
[WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily)
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### isEquals(WmfPitchAndFamily obj1, WmfPitchAndFamily obj2) {#isEquals-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-}
```
public static boolean isEquals(WmfPitchAndFamily obj1, WmfPitchAndFamily obj2)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj1 | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |
| obj2 | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |

**Returns:**
boolean
