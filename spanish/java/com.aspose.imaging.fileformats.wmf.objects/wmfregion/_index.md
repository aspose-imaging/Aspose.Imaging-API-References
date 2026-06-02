---
title: "WmfRegion"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto Region define una forma potencialmente no rectilínea definida por una matriz de líneas de escaneo."
type: docs
weight: 62
url: /es/java/com.aspose.imaging.fileformats.wmf.objects/wmfregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfRegion extends MetaObject
```

El objeto Region define una forma potencialmente no rectilínea definida por una matriz de líneas de escaneo.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WmfRegion()](#WmfRegion--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getNextInChain()](#getNextInChain--) | Obtiene o establece el siguiente en la cadena. |
| [setNextInChain(short value)](#setNextInChain-short-) | Obtiene o establece el siguiente en la cadena. |
| [getObjectType()](#getObjectType--) | Obtiene o establece el tipo del objeto. |
| [setObjectType(short value)](#setObjectType-short-) | Obtiene o establece el tipo del objeto. |
| [getObjectCount()](#getObjectCount--) | Obtiene o establece el recuento de objetos. |
| [setObjectCount(int value)](#setObjectCount-int-) | Obtiene o establece el recuento de objetos. |
| [getRegionSize()](#getRegionSize--) | Obtiene o establece el tamaño de la región. |
| [setRegionSize(short value)](#setRegionSize-short-) | Obtiene o establece el tamaño de la región. |
| [getScanCount()](#getScanCount--) | Obtiene o establece el recuento de escaneos. |
| [setScanCount(short value)](#setScanCount-short-) | Obtiene o establece el recuento de escaneos. |
| [getMaxScan()](#getMaxScan--) | Obtiene o establece el escaneo máximo. |
| [setMaxScan(short value)](#setMaxScan-short-) | Obtiene o establece el escaneo máximo. |
| [getBoundingRectangle()](#getBoundingRectangle--) | Obtiene o establece el rectángulo delimitador. |
| [setBoundingRectangle(Rectangle value)](#setBoundingRectangle-com.aspose.imaging.Rectangle-) | Obtiene o establece el rectángulo delimitador. |
| [getAScans()](#getAScans--) | Obtiene o establece los escaneos. |
| [setAScans(WmfScanObject[] value)](#setAScans-com.aspose.imaging.fileformats.wmf.objects.WmfScanObject---) | Obtiene o establece los escaneos. |
### WmfRegion() {#WmfRegion--}
```
public WmfRegion()
```


### getNextInChain() {#getNextInChain--}
```
public short getNextInChain()
```


Obtiene o establece el siguiente en la cadena.

Valor: Un valor que DEBE ser ignorado.

**Returns:**
short
### setNextInChain(short value) {#setNextInChain-short-}
```
public void setNextInChain(short value)
```


Obtiene o establece el siguiente en la cadena.

Valor: Un valor que DEBE ser ignorado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getObjectType() {#getObjectType--}
```
public short getObjectType()
```


Obtiene o establece el tipo del objeto.

Valor: El identificador de la región. DEBE ser 0x0006.

**Returns:**
short
### setObjectType(short value) {#setObjectType-short-}
```
public void setObjectType(short value)
```


Obtiene o establece el tipo del objeto.

Valor: El identificador de la región. DEBE ser 0x0006.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getObjectCount() {#getObjectCount--}
```
public int getObjectCount()
```


Obtiene o establece el recuento de objetos.

Valor: Un valor que DEBE ser ignorado.

**Returns:**
int
### setObjectCount(int value) {#setObjectCount-int-}
```
public void setObjectCount(int value)
```


Obtiene o establece el recuento de objetos.

Valor: Un valor que DEBE ser ignorado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getRegionSize() {#getRegionSize--}
```
public short getRegionSize()
```


Obtiene o establece el tamaño de la región.

Valor: El tamaño de la región en bytes más el tamaño de aScans en bytes.

**Returns:**
short
### setRegionSize(short value) {#setRegionSize-short-}
```
public void setRegionSize(short value)
```


Obtiene o establece el tamaño de la región.

Valor: El tamaño de la región en bytes más el tamaño de aScans en bytes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getScanCount() {#getScanCount--}
```
public short getScanCount()
```


Obtiene o establece el recuento de escaneos.

Valor: El número de líneas de escaneo que componen la región.

**Returns:**
short
### setScanCount(short value) {#setScanCount-short-}
```
public void setScanCount(short value)
```


Obtiene o establece el recuento de escaneos.

Valor: El número de líneas de escaneo que componen la región.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getMaxScan() {#getMaxScan--}
```
public short getMaxScan()
```


Obtiene o establece el escaneo máximo.

Valor: El número máximo de puntos en cualquier escaneo de esta región.

**Returns:**
short
### setMaxScan(short value) {#setMaxScan-short-}
```
public void setMaxScan(short value)
```


Obtiene o establece el escaneo máximo.

Valor: El número máximo de puntos en cualquier escaneo de esta región.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rectangle getBoundingRectangle()
```


Obtiene o establece el rectángulo delimitador.

Valor: Un objeto Rect (sección 2.2.2.18) que define el rectángulo delimitador.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBoundingRectangle(Rectangle value) {#setBoundingRectangle-com.aspose.imaging.Rectangle-}
```
public void setBoundingRectangle(Rectangle value)
```


Obtiene o establece el rectángulo delimitador.

Valor: Un objeto Rect (sección 2.2.2.18) que define el rectángulo delimitador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAScans() {#getAScans--}
```
public WmfScanObject[] getAScans()
```


Obtiene o establece los escaneos.

Valor: Una matriz de objetos Scan (sección 2.2.2.21) que define las líneas de escaneo en la región.

**Returns:**
com.aspose.imaging.fileformats.wmf.objects.WmfScanObject[]
### setAScans(WmfScanObject[] value) {#setAScans-com.aspose.imaging.fileformats.wmf.objects.WmfScanObject---}
```
public void setAScans(WmfScanObject[] value)
```


Obtiene o establece los escaneos.

Valor: Una matriz de objetos Scan (sección 2.2.2.21) que define las líneas de escaneo en la región.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WmfScanObject\[\]](../../com.aspose.imaging.fileformats.wmf.objects/wmfscanobject) |  |

