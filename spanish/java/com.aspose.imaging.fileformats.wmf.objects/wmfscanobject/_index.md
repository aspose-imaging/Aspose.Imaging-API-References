---
title: "WmfScanObject"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto Scan especifica una colección de líneas de escaneo."
type: docs
weight: 69
url: /es/java/com.aspose.imaging.fileformats.wmf.objects/wmfscanobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfScanObject extends MetaObject
```

El objeto Scan especifica una colección de líneas de escaneo.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WmfScanObject()](#WmfScanObject--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCount()](#getCount--) | Obtiene o establece el recuento. |
| [setCount(int value)](#setCount-int-) | Obtiene o establece el recuento. |
| [getTop()](#getTop--) | Obtiene o establece la parte superior. |
| [setTop(int value)](#setTop-int-) | Obtiene o establece la parte superior. |
| [getBottom()](#getBottom--) | Obtiene o establece la parte inferior. |
| [setBottom(int value)](#setBottom-int-) | Obtiene o establece la parte inferior. |
| [getScanLines()](#getScanLines--) | Obtiene o establece las líneas de escaneo. |
| [setScanLines(Point[] value)](#setScanLines-com.aspose.imaging.Point---) | Obtiene o establece las líneas de escaneo. |
| [getCount2()](#getCount2--) | Obtiene o establece el count2. |
| [setCount2(int value)](#setCount2-int-) | Obtiene o establece el count2. |
### WmfScanObject() {#WmfScanObject--}
```
public WmfScanObject()
```


### getCount() {#getCount--}
```
public int getCount()
```


Obtiene o establece el recuento.

Valor: El número de coordenadas horizontales (eje x) en la matriz `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.ScanLines`. Este valor DEBE ser múltiplo de 2, ya que se requieren los puntos finales izquierdo y derecho para especificar cada línea de escaneo.

**Returns:**
int
### setCount(int value) {#setCount-int-}
```
public void setCount(int value)
```


Obtiene o establece el recuento.

Valor: El número de coordenadas horizontales (eje x) en la matriz `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.ScanLines`. Este valor DEBE ser múltiplo de 2, ya que se requieren los puntos finales izquierdo y derecho para especificar cada línea de escaneo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getTop() {#getTop--}
```
public int getTop()
```


Obtiene o establece la parte superior.

Valor: La coordenada vertical (eje y), en unidades lógicas, de la línea de escaneo superior.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Obtiene o establece la parte superior.

Valor: La coordenada vertical (eje y), en unidades lógicas, de la línea de escaneo superior.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getBottom() {#getBottom--}
```
public int getBottom()
```


Obtiene o establece la parte inferior.

Valor: La coordenada vertical (eje y), en unidades lógicas, de la línea de escaneo inferior.

**Returns:**
int
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Obtiene o establece la parte inferior.

Valor: La coordenada vertical (eje y), en unidades lógicas, de la línea de escaneo inferior.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getScanLines() {#getScanLines--}
```
public Point[] getScanLines()
```


Obtiene o establece las líneas de escaneo.

Valor: Una matriz de líneas de escaneo, cada una especificada por coordenadas horizontales (eje x) izquierdas y derechas de sus puntos finales.

**Returns:**
com.aspose.imaging.Point[]
### setScanLines(Point[] value) {#setScanLines-com.aspose.imaging.Point---}
```
public void setScanLines(Point[] value)
```


Obtiene o establece las líneas de escaneo.

Valor: Una matriz de líneas de escaneo, cada una especificada por coordenadas horizontales (eje x) izquierdas y derechas de sus puntos finales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) |  |

### getCount2() {#getCount2--}
```
public int getCount2()
```


Obtiene o establece el count2.

Valor: El mismo que el valor del campo `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.Count`; está presente para permitir el desplazamiento ascendente en la estructura.

**Returns:**
int
### setCount2(int value) {#setCount2-int-}
```
public void setCount2(int value)
```


Obtiene o establece el count2.

Valor: El mismo que el valor del campo `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.Count`; está presente para permitir el desplazamiento ascendente en la estructura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

