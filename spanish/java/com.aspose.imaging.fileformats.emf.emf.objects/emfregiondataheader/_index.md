---
title: "EmfRegionDataHeader"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto RegionDataHeader describe las propiedades de un objeto RegionData."
type: docs
weight: 34
url: /es/java/com.aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfRegionDataHeader extends EmfObject
```

El objeto RegionDataHeader describe las propiedades de un objeto RegionData.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfRegionDataHeader()](#EmfRegionDataHeader--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getSize()](#getSize--) | Obtiene un entero sin signo de 32 bits que especifica el tamaño de este objeto en bytes. |
| [setSize(int value)](#setSize-int-) | Establece un entero sin signo de 32 bits que especifica el tamaño de este objeto en bytes. |
| [getType()](#getType--) | Obtiene un entero sin signo de 32 bits que especifica el tipo de región. |
| [setType(int value)](#setType-int-) | Establece un entero sin signo de 32 bits que especifica el tipo de región. |
| [getCountRects()](#getCountRects--) | Obtiene un entero sin signo de 32 bits que especifica el número de rectángulos en esta región. |
| [setCountRects(int value)](#setCountRects-int-) | Establece un entero sin signo de 32 bits que especifica el número de rectángulos en esta región. |
| [getRgnSize()](#getRgnSize--) | Obtiene un entero sin signo de 32 bits que especifica el tamaño del búfer de rectángulos en bytes. |
| [setRgnSize(int value)](#setRgnSize-int-) | Establece un entero sin signo de 32 bits que especifica el tamaño del búfer de rectángulos en bytes. |
| [getBounds()](#getBounds--) | Obtiene un objeto WMF RectL de 128 bits ([MS-WMF] sección 2.2.2.19), que especifica los límites de la región. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Establece un objeto WMF RectL de 128 bits ([MS-WMF] sección 2.2.2.19), que especifica los límites de la región. |
### EmfRegionDataHeader() {#EmfRegionDataHeader--}
```
public EmfRegionDataHeader()
```


### getSize() {#getSize--}
```
public int getSize()
```


Obtiene un entero sin signo de 32 bits que especifica el tamaño de este objeto en bytes. Esto DEBE ser 0x00000020.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Establece un entero sin signo de 32 bits que especifica el tamaño de este objeto en bytes. Esto DEBE ser 0x00000020.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getType() {#getType--}
```
public int getType()
```


Obtiene un entero sin signo de 32 bits que especifica el tipo de región. Esto DEBERÍA ser RDH\_RECTANGLES (0x00000001).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Establece un entero sin signo de 32 bits que especifica el tipo de región. Esto DEBERÍA ser RDH\_RECTANGLES (0x00000001).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getCountRects() {#getCountRects--}
```
public int getCountRects()
```


Obtiene un entero sin signo de 32 bits que especifica el número de rectángulos en esta región.

**Returns:**
int
### setCountRects(int value) {#setCountRects-int-}
```
public void setCountRects(int value)
```


Establece un entero sin signo de 32 bits que especifica el número de rectángulos en esta región.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getRgnSize() {#getRgnSize--}
```
public int getRgnSize()
```


Obtiene un entero sin signo de 32 bits que especifica el tamaño del búfer de rectángulos en bytes.

**Returns:**
int
### setRgnSize(int value) {#setRgnSize-int-}
```
public void setRgnSize(int value)
```


Establece un entero sin signo de 32 bits que especifica el tamaño del búfer de rectángulos en bytes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Obtiene un objeto WMF RectL de 128 bits ([MS-WMF] sección 2.2.2.19), que especifica los límites de la región.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Establece un objeto WMF RectL de 128 bits ([MS-WMF] sección 2.2.2.19), que especifica los límites de la región.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

