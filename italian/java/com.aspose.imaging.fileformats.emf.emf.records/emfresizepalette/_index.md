---
title: "EmfResizePalette"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_RESIZEPALETTE aumenta o diminuisce la dimensione di un oggetto LogPalette esistente sezione 2.2.17."
type: docs
weight: 108
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfresizepalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfResizePalette extends EmfObjectManipulationRecordType
```

Il record EMR\_RESIZEPALETTE aumenta o diminuisce le dimensioni di un oggetto LogPalette esistente (sezione 2.2.17).

La nuova dimensione dell'oggetto LogPalette DEVE essere riflessa nel campo NumberOfEntries di quella struttura.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfResizePalette(EmfRecord source)](#EmfResizePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfResizePalette`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getIhPal()](#getIhPal--) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto palette nella EMF Object Table (sezione 3.1.1.1). |
| [setIhPal(int value)](#setIhPal-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto palette nella EMF Object Table (sezione 3.1.1.1). |
### EmfResizePalette(EmfRecord source) {#EmfResizePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfResizePalette(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfResizePalette`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto palette nella EMF Object Table (sezione 3.1.1.1).

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto palette nella EMF Object Table (sezione 3.1.1.1).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

