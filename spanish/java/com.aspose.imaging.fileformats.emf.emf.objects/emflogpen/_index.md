---
title: "EmfLogPen"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto LogPen define el estilo, ancho y color de un lápiz lógico."
type: docs
weight: 27
url: /es/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogpen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfBasePen](../../com.aspose.imaging.fileformats.emf.emf.objects/emfbasepen)
```
public final class EmfLogPen extends EmfBasePen
```

El objeto LogPen define el estilo, ancho y color de una pluma lógica.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfLogPen()](#EmfLogPen--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPenStyle()](#getPenStyle--) | Obtiene o establece un entero sin signo de 32 bits que especifica el PenStyle. |
| [setPenStyle(int value)](#setPenStyle-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el PenStyle. |
| [getWidth()](#getWidth--) | Obtiene o establece un objeto WMF PointL ([MS-WMF] sección 2.2.2.15) que especifica el ancho del lápiz mediante el valor de su campo x. |
| [setWidth(Point value)](#setWidth-com.aspose.imaging.Point-) | Obtiene o establece un objeto WMF PointL ([MS-WMF] sección 2.2.2.15) que especifica el ancho del lápiz mediante el valor de su campo x. |
| [getAffectWidth()](#getAffectWidth--) | Obtiene o establece el ancho del efecto. |
| [setAffectWidth(int value)](#setAffectWidth-int-) | Obtiene o establece el ancho del efecto. |
| [getArgb32ColorRef()](#getArgb32ColorRef--) | Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8) que especifica el valor del color del lápiz. |
| [setArgb32ColorRef(int value)](#setArgb32ColorRef-int-) | Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8) que especifica el valor del color del lápiz. |
### EmfLogPen() {#EmfLogPen--}
```
public EmfLogPen()
```


### getPenStyle() {#getPenStyle--}
```
public int getPenStyle()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el PenStyle. El valor DEBE estar definido en la tabla de enumeración PenStyle, especificada en la sección 2.1.25.

**Returns:**
int
### setPenStyle(int value) {#setPenStyle-int-}
```
public void setPenStyle(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el PenStyle. El valor DEBE estar definido en la tabla de enumeración PenStyle, especificada en la sección 2.1.25.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getWidth() {#getWidth--}
```
public Point getWidth()
```


Obtiene o establece un objeto WMF PointL ([MS-WMF] sección 2.2.2.15) que especifica el ancho del lápiz mediante el valor de su campo x. El valor de su campo y DEBE ser ignorado.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setWidth(Point value) {#setWidth-com.aspose.imaging.Point-}
```
public void setWidth(Point value)
```


Obtiene o establece un objeto WMF PointL ([MS-WMF] sección 2.2.2.15) que especifica el ancho del lápiz mediante el valor de su campo x. El valor de su campo y DEBE ser ignorado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getAffectWidth() {#getAffectWidth--}
```
public int getAffectWidth()
```


Obtiene o establece el ancho del efecto.

Valor: El ancho del efecto.

**Returns:**
int
### setAffectWidth(int value) {#setAffectWidth-int-}
```
public void setAffectWidth(int value)
```


Obtiene o establece el ancho del efecto.

Valor: El ancho del efecto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getArgb32ColorRef() {#getArgb32ColorRef--}
```
public int getArgb32ColorRef()
```


Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8) que especifica el valor del color del lápiz.

Valor: El color ARGB de 32 bits

**Returns:**
int
### setArgb32ColorRef(int value) {#setArgb32ColorRef-int-}
```
public void setArgb32ColorRef(int value)
```


Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8) que especifica el valor del color del lápiz.

Valor: El color ARGB de 32 bits

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

