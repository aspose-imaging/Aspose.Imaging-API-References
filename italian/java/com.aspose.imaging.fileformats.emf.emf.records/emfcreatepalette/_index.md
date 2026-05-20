---
title: "EmfCreatePalette"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_CREATEPALETTE definisce una palette logica per le operazioni grafiche."
type: docs
weight: 40
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreatePalette extends EmfObjectCreationRecordType
```

Il record EMR\_CREATEPALETTE definisce una tavolozza logica per operazioni grafiche.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfCreatePalette(EmfRecord source)](#EmfCreatePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfCreatePalette`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getIhPal()](#getIhPal--) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto palette logica nella EMF Object Table (sezione 3.1.1.1). |
| [setIhPal(int value)](#setIhPal-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto palette logica nella EMF Object Table (sezione 3.1.1.1). |
| [getLogPalette()](#getLogPalette--) | Ottiene o imposta un oggetto LogPalette (sezione 2.2.17). |
| [setLogPalette(EmfLogPalette value)](#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-) | Ottiene o imposta un oggetto LogPalette (sezione 2.2.17). |
### EmfCreatePalette(EmfRecord source) {#EmfCreatePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreatePalette(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfCreatePalette`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto palette logica nella EMF Object Table (sezione 3.1.1.1). Questo indice DEVE essere salvato affinché l'oggetto possa essere riutilizzato o modificato.

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto palette logica nella EMF Object Table (sezione 3.1.1.1). Questo indice DEVE essere salvato affinché l'oggetto possa essere riutilizzato o modificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getLogPalette() {#getLogPalette--}
```
public EmfLogPalette getLogPalette()
```


Ottiene o imposta un oggetto LogPalette (sezione 2.2.17). Il campo Version di questo oggetto DEVE essere impostato a 0x0300. Se il valore NumberOfEntries in questo oggetto è zero, l'elaborazione di questo record DEVE fallire.

**Returns:**
[EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette)
### setLogPalette(EmfLogPalette value) {#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-}
```
public void setLogPalette(EmfLogPalette value)
```


Ottiene o imposta un oggetto LogPalette (sezione 2.2.17). Il campo Version di questo oggetto DEVE essere impostato a 0x0300. Se il valore NumberOfEntries in questo oggetto è zero, l'elaborazione di questo record DEVE fallire.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette) |  |

