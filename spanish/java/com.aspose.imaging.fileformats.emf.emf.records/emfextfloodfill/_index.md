---
title: "EmfExtFloodFill"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_EXTFLOODFILL rellena un área de la superficie de visualización con el pincel actual."
type: docs
weight: 54
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfExtFloodFill extends EmfDrawingRecordType
```

El registro EMR\_EXTFLOODFILL rellena un área de la superficie de visualización con el pincel actual
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfExtFloodFill(EmfRecord source)](#EmfExtFloodFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfExtFloodFill`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getStart()](#getStart--) | Obtiene o establece un objeto WMF PointL ([MS-WMF] sección 2.2.2.15), que especifica las coordenadas, en unidades lógicas, donde comienza el relleno. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Obtiene o establece un objeto WMF PointL ([MS-WMF] sección 2.2.2.15), que especifica las coordenadas, en unidades lógicas, donde comienza el relleno. |
| [getArgb32Color()](#getArgb32Color--) | Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8), que se usa con FloodFillMode para determinar el área a rellenar. |
| [setArgb32Color(int value)](#setArgb32Color-int-) | Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8), que se usa con FloodFillMode para determinar el área a rellenar. |
| [getFloodFillMode()](#getFloodFillMode--) | Obtiene o establece un entero sin signo de 32 bits que especifica cómo usar el valor Color para determinar el área de la operación de relleno por inundación. |
| [setFloodFillMode(int value)](#setFloodFillMode-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica cómo usar el valor Color para determinar el área de la operación de relleno por inundación. |
### EmfExtFloodFill(EmfRecord source) {#EmfExtFloodFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtFloodFill(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfExtFloodFill`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### getStart() {#getStart--}
```
public Point getStart()
```


Obtiene o establece un objeto WMF PointL ([MS-WMF] sección 2.2.2.15), que especifica las coordenadas, en unidades lógicas, donde comienza el relleno.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Obtiene o establece un objeto WMF PointL ([MS-WMF] sección 2.2.2.15), que especifica las coordenadas, en unidades lógicas, donde comienza el relleno.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getArgb32Color() {#getArgb32Color--}
```
public int getArgb32Color()
```


Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8), que se usa con FloodFillMode para determinar el área a rellenar.

**Returns:**
int
### setArgb32Color(int value) {#setArgb32Color-int-}
```
public void setArgb32Color(int value)
```


Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8), que se usa con FloodFillMode para determinar el área a rellenar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getFloodFillMode() {#getFloodFillMode--}
```
public int getFloodFillMode()
```


Obtiene o establece un entero sin signo de 32 bits que especifica cómo usar el valor Color para determinar el área de la operación de relleno por inundación. El valor DEBE estar en la enumeración FloodFill (sección 2.1.13).

**Returns:**
int
### setFloodFillMode(int value) {#setFloodFillMode-int-}
```
public void setFloodFillMode(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica cómo usar el valor Color para determinar el área de la operación de relleno por inundación. El valor DEBE estar en la enumeración FloodFill (sección 2.1.13).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

