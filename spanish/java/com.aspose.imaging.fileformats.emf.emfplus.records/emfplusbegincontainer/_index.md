---
title: "EmfPlusBeginContainer"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusBeginContainer abre un nuevo contenedor de estado gráfico y especifica una transformación para él."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusBeginContainer extends EmfPlusStateRecordType
```

El registro EmfPlusBeginContainer abre un nuevo contenedor de estado gráfico y especifica una transformación para él.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusBeginContainer(EmfPlusRecord source)](#EmfPlusBeginContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusBeginContainer`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPageUnit()](#getPageUnit--) | Obtiene la unidad de página. |
| [getDestRect()](#getDestRect--) | Obtiene o establece un objeto EmfPlusRectF (sección 2.2.2.39) que, junto con SrcRect, especifica una transformación para el contenedor. |
| [setDestRect(RectangleF value)](#setDestRect-com.aspose.imaging.RectangleF-) | Obtiene o establece un objeto EmfPlusRectF (sección 2.2.2.39) que, junto con SrcRect, especifica una transformación para el contenedor. |
| [getSrcRect()](#getSrcRect--) | Obtiene o establece un rectángulo EmfPlusRectF que, junto con DestRect, especifica una transformación para el contenedor. |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | Obtiene o establece un rectángulo EmfPlusRectF que, junto con DestRect, especifica una transformación para el contenedor. |
| [getStackIndex()](#getStackIndex--) | Obtiene o establece un entero sin signo de 32 bits que especifica un índice para asociar con el contenedor de estado gráfico. |
| [setStackIndex(int value)](#setStackIndex-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica un índice para asociar con el contenedor de estado gráfico. |
### EmfPlusBeginContainer(EmfPlusRecord source) {#EmfPlusBeginContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusBeginContainer(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusBeginContainer`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


Obtiene la unidad de página.

Valor: La unidad de página.

**Returns:**
int
### getDestRect() {#getDestRect--}
```
public RectangleF getDestRect()
```


Obtiene o establece un objeto EmfPlusRectF (sección 2.2.2.39) que, junto con SrcRect, especifica una transformación para el contenedor. Esta transformación produce SrcRect cuando se aplica a DestRect.

Valor: El rectángulo de destino.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setDestRect(RectangleF value) {#setDestRect-com.aspose.imaging.RectangleF-}
```
public void setDestRect(RectangleF value)
```


Obtiene o establece un objeto EmfPlusRectF (sección 2.2.2.39) que, junto con SrcRect, especifica una transformación para el contenedor. Esta transformación produce SrcRect cuando se aplica a DestRect.

Valor: El rectángulo de destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


Obtiene o establece un rectángulo EmfPlusRectF que, junto con DestRect, especifica una transformación para el contenedor. Esta transformación produce SrcRect cuando se aplica a DestRect.

Valor: el rectángulo de origen.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


Obtiene o establece un rectángulo EmfPlusRectF que, junto con DestRect, especifica una transformación para el contenedor. Esta transformación produce SrcRect cuando se aplica a DestRect.

Valor: el rectángulo de origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Obtiene o establece un entero sin signo de 32 bits que especifica un índice para asociar con el contenedor de estado gráfico. El índice DEBE ser referenciado por un registro EmfPlusEndContainer posterior (sección 2.3.7.3) para cerrar el contenedor de estado gráfico.

Valor: El índice de la pila.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica un índice para asociar con el contenedor de estado gráfico. El índice DEBE ser referenciado por un registro EmfPlusEndContainer posterior (sección 2.3.7.3) para cerrar el contenedor de estado gráfico.

Valor: El índice de la pila.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

