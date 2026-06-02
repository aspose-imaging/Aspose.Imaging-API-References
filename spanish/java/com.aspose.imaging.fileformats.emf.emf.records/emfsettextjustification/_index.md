---
title: "EmfSetTextJustification"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_SETTEXTJUSTIFICATION especifica la cantidad de espacio adicional que se debe agregar a los caracteres de separación para la justificación del texto."
type: docs
weight: 141
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfsettextjustification/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetTextJustification extends EmfStateRecordType
```

El registro EMR\_SETTEXTJUSTIFICATION especifica la cantidad de espacio adicional que se debe añadir a los caracteres de separación para la justificación del texto.

En lugar de usar un registro EMR\_SETTEXTJUSTIFICATION, una implementación DEBERÍA usar un registro EMR\_EXTTEXTOUTW (sección 2.3.5.8) para realizar esta función.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfSetTextJustification(EmfRecord source)](#EmfSetTextJustification-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfSetTextJustification`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getNBreakExtra()](#getNBreakExtra--) | Obtiene o establece un entero con signo de 32 bits que especifica la cantidad total de espacio adicional, en unidades lógicas, a agregar. |
| [setNBreakExtra(int value)](#setNBreakExtra-int-) | Obtiene o establece un entero con signo de 32 bits que especifica la cantidad total de espacio adicional, en unidades lógicas, a agregar. |
| [getNBreakCount()](#getNBreakCount--) | Obtiene o establece un entero con signo de 32 bits que especifica el número de caracteres de interrupción. |
| [setNBreakCount(int value)](#setNBreakCount-int-) | Obtiene o establece un entero con signo de 32 bits que especifica el número de caracteres de interrupción. |
### EmfSetTextJustification(EmfRecord source) {#EmfSetTextJustification-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetTextJustification(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfSetTextJustification`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### getNBreakExtra() {#getNBreakExtra--}
```
public int getNBreakExtra()
```


Obtiene o establece un entero con signo de 32 bits que especifica la cantidad total de espacio adicional, en unidades lógicas, a agregar.

**Returns:**
int
### setNBreakExtra(int value) {#setNBreakExtra-int-}
```
public void setNBreakExtra(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica la cantidad total de espacio adicional, en unidades lógicas, a agregar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getNBreakCount() {#getNBreakCount--}
```
public int getNBreakCount()
```


Obtiene o establece un entero con signo de 32 bits que especifica el número de caracteres de interrupción.

**Returns:**
int
### setNBreakCount(int value) {#setNBreakCount-int-}
```
public void setNBreakCount(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica el número de caracteres de interrupción.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

