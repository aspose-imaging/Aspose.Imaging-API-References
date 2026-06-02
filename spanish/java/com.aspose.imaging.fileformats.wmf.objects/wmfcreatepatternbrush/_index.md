---
title: "WmfCreatePatternBrush"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro META_CREATEPATTERNBRUSH crea un objeto pincel con un patrón especificado por un mapa de bits."
type: docs
weight: 23
url: /es/java/com.aspose.imaging.fileformats.wmf.objects/wmfcreatepatternbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject)
```
public class WmfCreatePatternBrush extends WmfGraphicObject
```

El registro META\_CREATEPATTERNBRUSH crea un objeto pincel con un patrón especificado por un bitmap.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WmfCreatePatternBrush()](#WmfCreatePatternBrush--) | WMFs el registro. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBitmap()](#getBitmap--) | Obtiene o establece el mapa de bits. |
| [setBitmap(WmfBitmap16 value)](#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-) | Obtiene o establece el mapa de bits. |
| [getReserved()](#getReserved--) | Obtiene o establece el reservado. |
| [setReserved(byte[] value)](#setReserved-byte---) | Obtiene o establece el reservado. |
| [getPattern()](#getPattern--) | Obtiene o establece el patrón. |
| [setPattern(byte[] value)](#setPattern-byte---) | Obtiene o establece el patrón. |
### WmfCreatePatternBrush() {#WmfCreatePatternBrush--}
```
public WmfCreatePatternBrush()
```


WMFs el registro.

### getBitmap() {#getBitmap--}
```
public WmfBitmap16 getBitmap()
```


Obtiene o establece el mapa de bits.

Valor: El mapa de bits que especifica el patrón para el pincel.

**Returns:**
[WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16)
### setBitmap(WmfBitmap16 value) {#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-}
```
public void setBitmap(WmfBitmap16 value)
```


Obtiene o establece el mapa de bits.

Valor: El mapa de bits que especifica el patrón para el pincel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16) |  |

### getReserved() {#getReserved--}
```
public byte[] getReserved()
```


Obtiene o establece el reservado.

Valor: Reservado. Este campo DEBE ser ignorado.

**Returns:**
byte[]
### setReserved(byte[] value) {#setReserved-byte---}
```
public void setReserved(byte[] value)
```


Obtiene o establece el reservado.

Valor: Reservado. Este campo DEBE ser ignorado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### getPattern() {#getPattern--}
```
public byte[] getPattern()
```


Obtiene o establece el patrón.

Valor: Una matriz de bytes de longitud variable que define los datos de píxeles del mapa de bits que componen el patrón del pincel. La longitud de este campo, en bytes, puede calcularse a partir de los parámetros del mapa de bits de la siguiente manera.

**Returns:**
byte[]
### setPattern(byte[] value) {#setPattern-byte---}
```
public void setPattern(byte[] value)
```


Obtiene o establece el patrón.

Valor: Una matriz de bytes de longitud variable que define los datos de píxeles del mapa de bits que componen el patrón del pincel. La longitud de este campo, en bytes, puede calcularse a partir de los parámetros del mapa de bits de la siguiente manera.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

