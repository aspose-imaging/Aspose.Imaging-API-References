---
title: "EmfSetTextJustification"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_SETTEXTJUSTIFICATION specifica la quantità di spazio extra da aggiungere ai caratteri di interruzione per la giustificazione del testo."
type: docs
weight: 141
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfsettextjustification/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetTextJustification extends EmfStateRecordType
```

Il record EMR\_SETTEXTJUSTIFICATION specifica la quantità di spazio extra da aggiungere ai caratteri di interruzione per la giustificazione del testo.

Invece di utilizzare un record EMR\_SETTEXTJUSTIFICATION, un'implementazione DOVREBBE usare un record EMR\_EXTTEXTOUTW (sezione 2.3.5.8) per eseguire questa funzione.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfSetTextJustification(EmfRecord source)](#EmfSetTextJustification-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfSetTextJustification`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getNBreakExtra()](#getNBreakExtra--) | Ottiene o imposta un intero con segno a 32 bit che specifica la quantità totale di spazio aggiuntivo, in unità logiche, da aggiungere. |
| [setNBreakExtra(int value)](#setNBreakExtra-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la quantità totale di spazio aggiuntivo, in unità logiche, da aggiungere. |
| [getNBreakCount()](#getNBreakCount--) | Ottiene o imposta un intero con segno a 32 bit che specifica il numero di caratteri di interruzione. |
| [setNBreakCount(int value)](#setNBreakCount-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica il numero di caratteri di interruzione. |
### EmfSetTextJustification(EmfRecord source) {#EmfSetTextJustification-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetTextJustification(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfSetTextJustification`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### getNBreakExtra() {#getNBreakExtra--}
```
public int getNBreakExtra()
```


Ottiene o imposta un intero con segno a 32 bit che specifica la quantità totale di spazio aggiuntivo, in unità logiche, da aggiungere.

**Returns:**
int
### setNBreakExtra(int value) {#setNBreakExtra-int-}
```
public void setNBreakExtra(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica la quantità totale di spazio aggiuntivo, in unità logiche, da aggiungere.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getNBreakCount() {#getNBreakCount--}
```
public int getNBreakCount()
```


Ottiene o imposta un intero con segno a 32 bit che specifica il numero di caratteri di interruzione.

**Returns:**
int
### setNBreakCount(int value) {#setNBreakCount-int-}
```
public void setNBreakCount(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica il numero di caratteri di interruzione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

