---
title: "EmfSetArcDirection"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_SETARCDIRECTION specifica la direzione di disegno da utilizzare per l'output di archi e rettangoli."
type: docs
weight: 118
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetArcDirection extends EmfStateRecordType
```

Il record EMR\_SETARCDIRECTION specifica la direzione di disegno da utilizzare per l'output di archi e rettangoli.

Il record EMR\_SETARCDIRECTION influisce sulla direzione in cui i seguenti record disegnano: - EMR\_ARC (sezione 2.3.5.2) - EMR\_ARCTO (sezione 2.3.5.3) - EMR\_CHORD (sezione 2.3.5.4) - EMR\_ELLIPSE (sezione 2.3.5.5) - EMR\_PIE (sezione 2.3.5.15) - EMR\_RECTANGLE (sezione 2.3.5.34) - EMR\_ROUNDRECT (sezione 2.3.5.35)
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfSetArcDirection(EmfRecord source)](#EmfSetArcDirection-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfSetArcDirection`. |
| [EmfSetArcDirection()](#EmfSetArcDirection--) | Inizializza una nuova istanza della classe `EmfSetArcDirection`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getArcDirection()](#getArcDirection--) | Ottiene o imposta un intero senza segno a 32 bit che specifica la direzione dell'arco. |
| [setArcDirection(int value)](#setArcDirection-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica la direzione dell'arco. |
### EmfSetArcDirection(EmfRecord source) {#EmfSetArcDirection-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetArcDirection(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfSetArcDirection`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfSetArcDirection() {#EmfSetArcDirection--}
```
public EmfSetArcDirection()
```


Inizializza una nuova istanza della classe `EmfSetArcDirection`.

### getArcDirection() {#getArcDirection--}
```
public int getArcDirection()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la direzione dell'arco. Il valore DEVE appartenere all'enumerazione ArcDirection (sezione 2.1.2). La direzione predefinita è antioraria.

**Returns:**
int
### setArcDirection(int value) {#setArcDirection-int-}
```
public void setArcDirection(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la direzione dell'arco. Il valore DEVE appartenere all'enumerazione ArcDirection (sezione 2.1.2). La direzione predefinita è antioraria.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

