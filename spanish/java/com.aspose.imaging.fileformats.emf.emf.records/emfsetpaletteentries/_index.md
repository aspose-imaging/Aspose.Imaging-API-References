---
title: "EmfSetPaletteEntries"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_SETPALETTEENTRIES define valores de color RGB en un rango de entradas para un objeto LogPalette existente, sección 2.2.17."
type: docs
weight: 134
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfSetPaletteEntries extends EmfObjectManipulationRecordType
```

El registro EMR\_SETPALETTEENTRIES define valores de color RGB en un rango de entradas para un objeto LogPalette existente (sección 2.2.17).
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfSetPaletteEntries(EmfRecord source)](#EmfSetPaletteEntries-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfSetPaletteEntries`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getIhPal()](#getIhPal--) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice de la tabla de objetos EMF de la paleta. |
| [setIhPal(int value)](#setIhPal-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice de la tabla de objetos EMF de la paleta. |
| [getStart()](#getStart--) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice de la primera entrada a establecer. |
| [setStart(int value)](#setStart-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice de la primera entrada a establecer. |
| [getNumberofEntries()](#getNumberofEntries--) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de entradas. |
| [setNumberofEntries(int value)](#setNumberofEntries-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de entradas. |
| [getArgb32PalEntries()](#getArgb32PalEntries--) | Obtiene o establece una matriz de objetos LogPaletteEntry (sección 2.2.18), de longitud NumberOfEntries, que especifica los datos de la entrada de la paleta. |
| [setArgb32PalEntries(int[] value)](#setArgb32PalEntries-int---) | Obtiene o establece una matriz de objetos LogPaletteEntry (sección 2.2.18), de longitud NumberOfEntries, que especifica los datos de la entrada de la paleta. |
### EmfSetPaletteEntries(EmfRecord source) {#EmfSetPaletteEntries-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetPaletteEntries(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfSetPaletteEntries`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el índice de la tabla de objetos EMF de la paleta.

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el índice de la tabla de objetos EMF de la paleta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getStart() {#getStart--}
```
public int getStart()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el índice de la primera entrada a establecer.

**Returns:**
int
### setStart(int value) {#setStart-int-}
```
public void setStart(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el índice de la primera entrada a establecer.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getNumberofEntries() {#getNumberofEntries--}
```
public int getNumberofEntries()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de entradas.

**Returns:**
int
### setNumberofEntries(int value) {#setNumberofEntries-int-}
```
public void setNumberofEntries(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de entradas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getArgb32PalEntries() {#getArgb32PalEntries--}
```
public int[] getArgb32PalEntries()
```


Obtiene o establece una matriz de objetos LogPaletteEntry (sección 2.2.18), de longitud NumberOfEntries, que especifica los datos de la entrada de la paleta. Los miembros Values no contienen ningún valor.

**Returns:**
int[]
### setArgb32PalEntries(int[] value) {#setArgb32PalEntries-int---}
```
public void setArgb32PalEntries(int[] value)
```


Obtiene o establece una matriz de objetos LogPaletteEntry (sección 2.2.18), de longitud NumberOfEntries, que especifica los datos de la entrada de la paleta. Los miembros Values no contienen ningún valor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] |  |

