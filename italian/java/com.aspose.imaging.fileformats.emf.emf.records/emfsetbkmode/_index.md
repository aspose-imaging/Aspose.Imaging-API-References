---
title: "EmfSetBkMode"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_SETBKMODE specifica la modalità di miscelazione dello sfondo del contesto del dispositivo di riproduzione."
type: docs
weight: 120
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetBkMode extends EmfStateRecordType
```

Il record EMR\_SETBKMODE specifica la modalità di miscelazione dello sfondo del contesto del dispositivo di riproduzione. La modalità di miscelazione dello sfondo è usata con testo, pennelli tratteggiati e stili di penna che non sono linee solide.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfSetBkMode(EmfRecord source)](#EmfSetBkMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfSetBkMode`. |
| [EmfSetBkMode()](#EmfSetBkMode--) | Inizializza una nuova istanza della classe `EmfSetBkMode`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBackgroundMode()](#getBackgroundMode--) | Ottiene o imposta un intero senza segno a 32 bit che specifica la modalità di sfondo e DEVE appartenere all'enumerazione BackgroundMode (sezione 2.1.4). |
| [setBackgroundMode(int value)](#setBackgroundMode-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica la modalità di sfondo e DEVE appartenere all'enumerazione BackgroundMode (sezione 2.1.4). |
### EmfSetBkMode(EmfRecord source) {#EmfSetBkMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetBkMode(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfSetBkMode`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfSetBkMode() {#EmfSetBkMode--}
```
public EmfSetBkMode()
```


Inizializza una nuova istanza della classe `EmfSetBkMode`.

### getBackgroundMode() {#getBackgroundMode--}
```
public int getBackgroundMode()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la modalità di sfondo e DEVE appartenere all'enumerazione BackgroundMode (sezione 2.1.4).

**Returns:**
int
### setBackgroundMode(int value) {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la modalità di sfondo e DEVE appartenere all'enumerazione BackgroundMode (sezione 2.1.4).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

