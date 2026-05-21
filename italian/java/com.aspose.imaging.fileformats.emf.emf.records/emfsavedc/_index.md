---
title: "EmfSaveDc"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Salva lo stato corrente del contesto del dispositivo di riproduzione su una pila di stati salvati da record EMR_SAVEDC precedenti, se presenti."
type: docs
weight: 112
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfsavedc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSaveDc extends EmfStateRecordType
```

Salva lo stato corrente del contesto del dispositivo di riproduzione su una pila di stati salvati da record EMR\_SAVEDC precedenti, se presenti. Lo stato è composto da proprietà grafiche e oggetti, inclusi la bitmap, il pennello, la tavolozza, il carattere, la penna e la regione attualmente selezionati. Un record EMR\_RESTOREDC è usato per ripristinare lo stato. Questo record EMF non specifica parametri.

La pila può contenere informazioni di stato per più istanze del contesto del dispositivo di riproduzione. Quando uno stato viene ripristinato, tutte le istanze di stato salvate più recentemente DEVONO essere scartate.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfSaveDc(EmfRecord source)](#EmfSaveDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfSaveDc`. |
| [EmfSaveDc()](#EmfSaveDc--) | Inizializza una nuova istanza della classe `EmfSaveDc`. |
### EmfSaveDc(EmfRecord source) {#EmfSaveDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSaveDc(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfSaveDc`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfSaveDc() {#EmfSaveDc--}
```
public EmfSaveDc()
```


Inizializza una nuova istanza della classe `EmfSaveDc`.

