---
title: "EmfColorCorrectPalette"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_COLORCORRECTPALETTE especifica cómo corregir las entradas de un objeto de paleta lógica usando valores WCS 1.0."
type: docs
weight: 23
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfcolorcorrectpalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfColorCorrectPalette extends EmfObjectManipulationRecordType
```

El registro EMR\_COLORCORRECTPALETTE especifica cómo corregir las entradas de un objeto de paleta lógica usando valores WCS 1.0.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfColorCorrectPalette(EmfRecord source)](#EmfColorCorrectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfColorCorrectPalette`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getIhPalette()](#getIhPalette--) | Obtiene un entero sin signo de 32 bits que especifica el índice de un objeto de paleta lógica (sección 2.2.17) en la Tabla de Objetos EMF (sección 3.1.1.1). |
| [setIhPalette(int value)](#setIhPalette-int-) | Establece un entero sin signo de 32 bits que especifica el índice de un objeto de paleta lógica (sección 2.2.17) en la Tabla de Objetos EMF (sección 3.1.1.1). |
| [getNFirstEntry()](#getNFirstEntry--) | Obtiene un entero sin signo de 32 bits que especifica el índice de la primera entrada a corregir. |
| [setNFirstEntry(int value)](#setNFirstEntry-int-) | Establece un entero sin signo de 32 bits que especifica el índice de la primera entrada a corregir. |
| [getNPalEntries()](#getNPalEntries--) | Obtiene un entero sin signo de 32 bits que especifica el número de entradas de la paleta a corregir. |
| [setNPalEntries(int value)](#setNPalEntries-int-) | Establece un entero sin signo de 32 bits que especifica el número de entradas de la paleta a corregir. |
### EmfColorCorrectPalette(EmfRecord source) {#EmfColorCorrectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfColorCorrectPalette(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfColorCorrectPalette`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### getIhPalette() {#getIhPalette--}
```
public int getIhPalette()
```


Obtiene un entero sin signo de 32 bits que especifica el índice de un objeto de paleta lógica (sección 2.2.17) en la Tabla de Objetos EMF (sección 3.1.1.1).

**Returns:**
int
### setIhPalette(int value) {#setIhPalette-int-}
```
public void setIhPalette(int value)
```


Establece un entero sin signo de 32 bits que especifica el índice de un objeto de paleta lógica (sección 2.2.17) en la Tabla de Objetos EMF (sección 3.1.1.1).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getNFirstEntry() {#getNFirstEntry--}
```
public int getNFirstEntry()
```


Obtiene un entero sin signo de 32 bits que especifica el índice de la primera entrada a corregir.

**Returns:**
int
### setNFirstEntry(int value) {#setNFirstEntry-int-}
```
public void setNFirstEntry(int value)
```


Establece un entero sin signo de 32 bits que especifica el índice de la primera entrada a corregir.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getNPalEntries() {#getNPalEntries--}
```
public int getNPalEntries()
```


Obtiene un entero sin signo de 32 bits que especifica el número de entradas de la paleta a corregir.

**Returns:**
int
### setNPalEntries(int value) {#setNPalEntries-int-}
```
public void setNPalEntries(int value)
```


Establece un entero sin signo de 32 bits que especifica el número de entradas de la paleta a corregir.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

