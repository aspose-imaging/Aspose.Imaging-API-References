---
title: "EmfRestoreDc"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_RESTOREDC ripristina il contesto del dispositivo di riproduzione allo stato specificato."
type: docs
weight: 109
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfrestoredc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfRestoreDc extends EmfStateRecordType
```

Il record EMR\_RESTOREDC ripristina il contesto del dispositivo di riproduzione allo stato specificato. Il contesto del dispositivo di riproduzione viene ripristinato rimuovendo le informazioni di stato da una pila creata dai precedenti record EMR\_SAVEDC (sezione 2.3.11).

La pila può contenere informazioni di stato per più istanze del contesto del dispositivo di riproduzione. Quando uno stato viene ripristinato, tutte le istanze di stato salvate più recentemente DEVONO essere scartate.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfRestoreDc(EmfRecord source)](#EmfRestoreDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfRestoreDc`. |
| [EmfRestoreDc()](#EmfRestoreDc--) | Inizializza una nuova istanza della classe `EmfRestoreDc`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSavedDc()](#getSavedDc--) | Ottiene o imposta un intero con segno a 32 bit che specifica lo stato salvato da ripristinare rispetto allo stato corrente. |
| [setSavedDc(int value)](#setSavedDc-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica lo stato salvato da ripristinare rispetto allo stato corrente. |
### EmfRestoreDc(EmfRecord source) {#EmfRestoreDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRestoreDc(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfRestoreDc`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfRestoreDc() {#EmfRestoreDc--}
```
public EmfRestoreDc()
```


Inizializza una nuova istanza della classe `EmfRestoreDc`.

### getSavedDc() {#getSavedDc--}
```
public int getSavedDc()
```


Ottiene o imposta un intero con segno a 32 bit che specifica lo stato salvato da ripristinare rispetto allo stato corrente. Questo valore DEVE essere negativo; \\u20131 rappresenta lo stato più recentemente salvato sulla pila, \\u20132 quello precedente, ecc.

**Returns:**
int
### setSavedDc(int value) {#setSavedDc-int-}
```
public void setSavedDc(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica lo stato salvato da ripristinare rispetto allo stato corrente. Questo valore DEVE essere negativo; \\u20131 rappresenta lo stato più recentemente salvato sulla pila, \\u20132 quello precedente, ecc.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

