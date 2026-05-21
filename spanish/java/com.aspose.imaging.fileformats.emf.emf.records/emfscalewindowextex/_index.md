---
title: "EmfScaleWindowExtex"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_SCALEWINDOWEXTEX vuelve a especificar la ventana para un contexto de dispositivo de reproducción utilizando las proporciones formadas por los multiplicadores y divisores especificados."
type: docs
weight: 114
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfScaleWindowExtex extends EmfStateRecordType
```

El registro EMR\_SCALEWINDOWEXTEX vuelve a especificar la ventana para un contexto de dispositivo de reproducción usando las proporciones formadas por los multiplicadores y divisores especificados.

La extensión no puede cambiarse si el contexto del dispositivo está usando un modo de mapeo de escala fija. Sólo MM\\_ISOTROPIC y MM\\_ANISOTROPIC no son de escala fija. Las extensiones de la ventana se modifican de la siguiente manera. xNewWE = (xOldWE \\* xNum) / xDenom yNewWE = (yOldWE \\* yNum) / xDenom
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfScaleWindowExtex(EmfRecord source)](#EmfScaleWindowExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfScaleWindowExtex`. |
| [EmfScaleWindowExtex()](#EmfScaleWindowExtex--) | Inicializa una nueva instancia de la clase [EmfScaleWindowExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex). |
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
### EmfScaleWindowExtex(EmfRecord source) {#EmfScaleWindowExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfScaleWindowExtex(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfScaleWindowExtex`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfScaleWindowExtex() {#EmfScaleWindowExtex--}
```
public EmfScaleWindowExtex()
```


Inicializa una nueva instancia de la clase [EmfScaleWindowExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex).

### getXNum() {#getXNum--}
```
public int getXNum()
```


Obtiene o establece un entero con signo de 32 bits que especifica el multiplicador horizontal. NO DEBE ser cero.

**Returns:**
int
### setXNum(int value) {#setXNum-int-}
```
public void setXNum(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica el multiplicador horizontal. NO DEBE ser cero.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getXDenom() {#getXDenom--}
```
public int getXDenom()
```


Obtiene o establece un entero con signo de 32 bits que especifica el divisor horizontal. NO DEBE ser cero.

**Returns:**
int
### setXDenom(int value) {#setXDenom-int-}
```
public void setXDenom(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica el divisor horizontal. NO DEBE ser cero.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getYNum() {#getYNum--}
```
public int getYNum()
```


Obtiene o establece un entero con signo de 32 bits que especifica el multiplicador vertical. NO DEBE ser cero.

**Returns:**
int
### setYNum(int value) {#setYNum-int-}
```
public void setYNum(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica el multiplicador vertical. NO DEBE ser cero.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getYDenom() {#getYDenom--}
```
public int getYDenom()
```


Obtiene o establece un entero con signo de 32 bits que especifica el divisor vertical. NO DEBE ser cero.

**Returns:**
int
### setYDenom(int value) {#setYDenom-int-}
```
public void setYDenom(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica el divisor vertical. NO DEBE ser cero.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

