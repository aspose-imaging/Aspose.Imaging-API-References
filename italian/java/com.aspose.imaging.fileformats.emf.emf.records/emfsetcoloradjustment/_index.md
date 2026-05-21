---
title: "EmfSetColorAdjustment"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_SETCOLORADJUSTMENT specifica le proprietà di regolazione del colore nel contesto del dispositivo di riproduzione."
type: docs
weight: 122
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetcoloradjustment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetColorAdjustment extends EmfStateRecordType
```

Il record EMR\_SETCOLORADJUSTMENT specifica le proprietà di regolazione del colore nel contesto di dispositivo di riproduzione.

I valori di regolazione del colore sono usati per regolare il colore di ingresso del bitmap di origine per le operazioni grafiche eseguite dai record EMR\_STRETCHBLT e EMR\_STRETCHDIBITS quando la modalità STRETCH\_HALFTONE è impostata dall'enumerazione StretchMode (sezione 2.1.32). L'oggetto ColorAdjustment specificato da questo record DEVE essere utilizzato nelle operazioni grafiche che richiedono un oggetto ColorAdjustment, fino a quando non venga specificato un diverso oggetto ColorAdjustment da un altro record EMR\_SETCOLORADJUSTMENT, o fino a quando l'oggetto non venga rimosso da un record EMR\_DELETEOBJECT.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfSetColorAdjustment(EmfRecord source)](#EmfSetColorAdjustment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfSetColorAdjustment`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getColorAdjustment()](#getColorAdjustment--) | Ottiene o imposta un oggetto ColorAdjustment (sezione 2.2.2) che specifica i valori di regolazione del colore. |
| [setColorAdjustment(EmfColorAdjustment value)](#setColorAdjustment-com.aspose.imaging.fileformats.emf.emf.objects.EmfColorAdjustment-) | Ottiene o imposta un oggetto ColorAdjustment (sezione 2.2.2) che specifica i valori di regolazione del colore. |
### EmfSetColorAdjustment(EmfRecord source) {#EmfSetColorAdjustment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetColorAdjustment(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfSetColorAdjustment`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### getColorAdjustment() {#getColorAdjustment--}
```
public EmfColorAdjustment getColorAdjustment()
```


Ottiene o imposta un oggetto ColorAdjustment (sezione 2.2.2) che specifica i valori di regolazione del colore.

**Returns:**
[EmfColorAdjustment](../../com.aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment)
### setColorAdjustment(EmfColorAdjustment value) {#setColorAdjustment-com.aspose.imaging.fileformats.emf.emf.objects.EmfColorAdjustment-}
```
public void setColorAdjustment(EmfColorAdjustment value)
```


Ottiene o imposta un oggetto ColorAdjustment (sezione 2.2.2) che specifica i valori di regolazione del colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfColorAdjustment](../../com.aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment) |  |

