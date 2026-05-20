---
title: "EmfNamedEscape"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record MR_NAMEDESCAPE passa informazioni arbitrarie a un driver di stampa specificato."
type: docs
weight: 75
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfnamedescape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfEscapeRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype)
```
public final class EmfNamedEscape extends EmfEscapeRecordType
```

Il record MR\_NAMEDESCAPE trasmette informazioni arbitrarie a un driver di stampante specificato.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfNamedEscape(EmfRecord source)](#EmfNamedEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfNamedEscape`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCjDriver()](#getCjDriver--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di byte nel campo DriverName. |
| [setCjDriver(int value)](#setCjDriver-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di byte nel campo DriverName. |
| [getCjIn()](#getCjIn--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di byte da passare al driver di stampa. |
| [setCjIn(int value)](#setCjIn-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di byte da passare al driver di stampa. |
| [getDriverName()](#getDriverName--) | Ottiene o imposta una stringa di caratteri Unicode a 16 bit che specifica il nome del driver di stampa che riceverà i dati. |
| [setDriverName(String value)](#setDriverName-java.lang.String-) | Ottiene o imposta una stringa di caratteri Unicode a 16 bit che specifica il nome del driver di stampa che riceverà i dati. |
| [getData()](#getData--) | Ottiene o imposta i dati da passare al driver di stampa. |
| [setData(byte[] value)](#setData-byte---) | Ottiene o imposta i dati da passare al driver di stampa. |
### EmfNamedEscape(EmfRecord source) {#EmfNamedEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfNamedEscape(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfNamedEscape`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### getCjDriver() {#getCjDriver--}
```
public int getCjDriver()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di byte nel campo DriverName. Questo valore DEVE essere un numero pari.

**Returns:**
int
### setCjDriver(int value) {#setCjDriver-int-}
```
public void setCjDriver(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di byte nel campo DriverName. Questo valore DEVE essere un numero pari.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCjIn() {#getCjIn--}
```
public int getCjIn()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di byte da passare al driver di stampa.

**Returns:**
int
### setCjIn(int value) {#setCjIn-int-}
```
public void setCjIn(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di byte da passare al driver di stampa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getDriverName() {#getDriverName--}
```
public String getDriverName()
```


Ottiene o imposta una stringa di caratteri Unicode a 16 bit che specifica il nome del driver di stampa che riceverà i dati. Questo valore DEVE essere lungo cjDriver byte e DEVE essere terminato con un carattere nullo.

**Returns:**
java.lang.String
### setDriverName(String value) {#setDriverName-java.lang.String-}
```
public void setDriverName(String value)
```


Ottiene o imposta una stringa di caratteri Unicode a 16 bit che specifica il nome del driver di stampa che riceverà i dati. Questo valore DEVE essere lungo cjDriver byte e DEVE essere terminato con un carattere nullo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getData() {#getData--}
```
public byte[] getData()
```


Ottiene o imposta i dati da passare al driver di stampa. Devono essere disponibili cjIn byte.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Ottiene o imposta i dati da passare al driver di stampa. Devono essere disponibili cjIn byte.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

