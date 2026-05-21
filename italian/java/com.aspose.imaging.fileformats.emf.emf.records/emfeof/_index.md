---
title: "EmfEof"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_EOF indica la fine del metafile e specifica una tavolozza."
type: docs
weight: 48
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfeof/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfControlRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcontrolrecordtype)
```
public final class EmfEof extends EmfControlRecordType
```

Il record EMR\_EOF indica la fine del metafile e specifica una tavolozza.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfEof(EmfRecord record)](#EmfEof-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfEof`. |
| [EmfEof()](#EmfEof--) | Inizializza una nuova istanza della classe `EmfEof`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPaletteArgb32Entries()](#getPaletteArgb32Entries--) | Ottiene un buffer opzionale che contiene i dati della tavolozza, che non è necessario sia contiguo con la parte fissa del record EMR\_EOF. |
| [setPaletteArgb32Entries(int[] value)](#setPaletteArgb32Entries-int---) | Imposta un buffer opzionale che contiene i dati della tavolozza, che non è necessario sia contiguo con la parte fissa del record EMR\_EOF. |
| [getSizeLast()](#getSizeLast--) | Ottiene un intero senza segno a 32 bit che DEVE essere uguale a Size e DEVE essere l'ultimo campo del record e quindi del metafile. |
| [setSizeLast(int value)](#setSizeLast-int-) | Imposta un intero senza segno a 32 bit che DEVE essere uguale a Size e DEVE essere l'ultimo campo del record e quindi del metafile. |
### EmfEof(EmfRecord record) {#EmfEof-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfEof(EmfRecord record)
```


Inizializza una nuova istanza della classe `EmfEof`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Il record. |

### EmfEof() {#EmfEof--}
```
public EmfEof()
```


Inizializza una nuova istanza della classe `EmfEof`.

### getPaletteArgb32Entries() {#getPaletteArgb32Entries--}
```
public int[] getPaletteArgb32Entries()
```


Ottiene un buffer opzionale che contiene i dati della tavolozza, che non è necessario sia contiguo con la parte fissa del record EMR\_EOF. Di conseguenza, i campi in questo buffer etichettati "UndefinedSpace" sono opzionali e DEVE essere ignorati. La dimensione di questo campo DEVE essere un multiplo di 4 byte.

**Returns:**
int[]
### setPaletteArgb32Entries(int[] value) {#setPaletteArgb32Entries-int---}
```
public void setPaletteArgb32Entries(int[] value)
```


Imposta un buffer opzionale che contiene i dati della tavolozza, che non è necessario sia contiguo con la parte fissa del record EMR\_EOF. Di conseguenza, i campi in questo buffer etichettati "UndefinedSpace" sono opzionali e DEVE essere ignorati. La dimensione di questo campo DEVE essere un multiplo di 4 byte.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] |  |

### getSizeLast() {#getSizeLast--}
```
public int getSizeLast()
```


Ottiene un intero senza segno a 32 bit che DEVE essere uguale a Size e DEVE essere l'ultimo campo del record e quindi del metafile. Gli oggetti LogPaletteEntry, se esistono, DEVONO precedere questo campo.

**Returns:**
int
### setSizeLast(int value) {#setSizeLast-int-}
```
public void setSizeLast(int value)
```


Imposta un intero senza segno a 32 bit che DEVE essere uguale a Size e DEVE essere l'ultimo campo del record e quindi del metafile. Gli oggetti LogPaletteEntry, se esistono, DEVONO precedere questo campo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

