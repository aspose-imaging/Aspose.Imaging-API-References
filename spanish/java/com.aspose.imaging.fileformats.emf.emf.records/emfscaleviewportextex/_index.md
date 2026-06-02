---
title: "EmfScaleViewportExtex"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_SCALEVIEWPORTEXTEX vuelve a especificar la ventana gráfica para un contexto de dispositivo usando las proporciones formadas por los multiplicadores y divisores especificados."
type: docs
weight: 113
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfScaleViewportExtex extends EmfStateRecordType
```

El registro EMR\_SCALEVIEWPORTEXTEX vuelve a especificar el viewport para un contexto de dispositivo usando las proporciones formadas por los multiplicadores y divisores especificados.

La extensión no puede cambiarse si el contexto de dispositivo está usando un modo de mapeo de escala fija. Sólo MM\_ISOTROPIC y MM\_ANISOTROPIC no son de escala fija. Las extensiones de la ventana gráfica se modifican de la siguiente manera. xNewWE = (xOldWE \* xNum) / xDenom yNewWE = (yOldWE \* yNum) / yDenom
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfScaleViewportExtex(EmfRecord source)](#EmfScaleViewportExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfScaleViewportExtex`. |
| [EmfScaleViewportExtex()](#EmfScaleViewportExtex--) | Inicializa una nueva instancia de la clase [EmfScaleViewportExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getXNum()](#getXNum--) | Obtiene o establece un entero con signo de 32 bits que especifica el multiplicando horizontal. |
| [setXNum(int value)](#setXNum-int-) | Obtiene o establece un entero con signo de 32 bits que especifica el multiplicando horizontal. |
| [getXDenom()](#getXDenom--) | Obtiene o establece un entero con signo de 32 bits que especifica el divisor horizontal. |
| [setXDenom(int value)](#setXDenom-int-) | Obtiene o establece un entero con signo de 32 bits que especifica el divisor horizontal. |
| [getYNum()](#getYNum--) | Obtiene o establece un entero con signo de 32 bits que especifica el multiplicando vertical. |
| [setYNum(int value)](#setYNum-int-) | Obtiene o establece un entero con signo de 32 bits que especifica el multiplicando vertical. |
| [getYDenom()](#getYDenom--) | Obtiene o establece un entero con signo de 32 bits que especifica el divisor vertical. |
| [setYDenom(int value)](#setYDenom-int-) | Obtiene o establece un entero con signo de 32 bits que especifica el divisor vertical. |
### EmfScaleViewportExtex(EmfRecord source) {#EmfScaleViewportExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfScaleViewportExtex(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfScaleViewportExtex`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfScaleViewportExtex() {#EmfScaleViewportExtex--}
```
public EmfScaleViewportExtex()
```


Inicializa una nueva instancia de la clase [EmfScaleViewportExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex).

### getXNum() {#getXNum--}
```
public int getXNum()
```


Obtiene o establece un entero con signo de 32 bits que especifica el multiplicando horizontal. No puede ser cero.

**Returns:**
int
### setXNum(int value) {#setXNum-int-}
```
public void setXNum(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica el multiplicando horizontal. No puede ser cero.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getXDenom() {#getXDenom--}
```
public int getXDenom()
```


Obtiene o establece un entero con signo de 32 bits que especifica el divisor horizontal. No puede ser cero.

**Returns:**
int
### setXDenom(int value) {#setXDenom-int-}
```
public void setXDenom(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica el divisor horizontal. No puede ser cero.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getYNum() {#getYNum--}
```
public int getYNum()
```


Obtiene o establece un entero con signo de 32 bits que especifica el multiplicando vertical. No puede ser cero.

**Returns:**
int
### setYNum(int value) {#setYNum-int-}
```
public void setYNum(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica el multiplicando vertical. No puede ser cero.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getYDenom() {#getYDenom--}
```
public int getYDenom()
```


Obtiene o establece un entero con signo de 32 bits que especifica el divisor vertical. No puede ser cero.

**Returns:**
int
### setYDenom(int value) {#setYDenom-int-}
```
public void setYDenom(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica el divisor vertical. No puede ser cero.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

