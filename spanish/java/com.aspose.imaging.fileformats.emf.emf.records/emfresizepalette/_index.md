---
title: "EmfResizePalette"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_RESIZEPALETTE aumenta o disminuye el tamaño de un objeto LogPalette existente sección 2.2.17."
type: docs
weight: 108
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfresizepalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfResizePalette extends EmfObjectManipulationRecordType
```

El registro EMR\_RESIZEPALETTE aumenta o disminuye el tamaño de un objeto LogPalette existente (sección 2.2.17).

El nuevo tamaño del objeto LogPalette DEBE reflejarse en el campo NumberOfEntries de esa estructura.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfResizePalette(EmfRecord source)](#EmfResizePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfResizePalette`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getIhPal()](#getIhPal--) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto de paleta en la tabla de objetos EMF (sección 3.1.1.1). |
| [setIhPal(int value)](#setIhPal-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto de paleta en la tabla de objetos EMF (sección 3.1.1.1). |
### EmfResizePalette(EmfRecord source) {#EmfResizePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfResizePalette(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfResizePalette`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto de paleta en la tabla de objetos EMF (sección 3.1.1.1).

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto de paleta en la tabla de objetos EMF (sección 3.1.1.1).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

