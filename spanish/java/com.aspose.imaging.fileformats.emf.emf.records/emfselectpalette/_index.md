---
title: "EmfSelectPalette"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_SELECTPALETTE especifica una paleta lógica para el contexto del dispositivo de reproducción."
type: docs
weight: 117
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfselectpalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfSelectPalette extends EmfObjectManipulationRecordType
```

El registro EMR\_SELECTPALETTE especifica una paleta lógica para el contexto de dispositivo de reproducción.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfSelectPalette(EmfRecord source)](#EmfSelectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfSelectPalette`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getIhPal()](#getIhPal--) | Obtiene o establece un entero sin signo de 32 bits que especifica ya sea el índice de un objeto LogPalette (sección 2.2.17) en la tabla de objetos EMF o el valor DEFAULT\_PALETTE, que es el índice de una paleta de objetos predeterminados de la enumeración StockObject (sección 2.1.31). |
| [setIhPal(int value)](#setIhPal-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica ya sea el índice de un objeto LogPalette (sección 2.2.17) en la tabla de objetos EMF o el valor DEFAULT\_PALETTE, que es el índice de una paleta de objetos predeterminados de la enumeración StockObject (sección 2.1.31). |
### EmfSelectPalette(EmfRecord source) {#EmfSelectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSelectPalette(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfSelectPalette`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


Obtiene o establece un entero sin signo de 32 bits que especifica ya sea el índice de un objeto LogPalette (sección 2.2.17) en la tabla de objetos EMF o el valor DEFAULT\_PALETTE, que es el índice de una paleta de objetos predeterminados de la enumeración StockObject (sección 2.1.31).

Este valor NO DEBE ser cero ni el índice de ningún otro objeto predeterminado.

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica ya sea el índice de un objeto LogPalette (sección 2.2.17) en la tabla de objetos EMF o el valor DEFAULT\_PALETTE, que es el índice de una paleta de objetos predeterminados de la enumeración StockObject (sección 2.1.31).

Este valor NO DEBE ser cero ni el índice de ningún otro objeto predeterminado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

