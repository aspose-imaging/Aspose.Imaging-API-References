---
title: "EmfPlusSetCompositingMode"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusSetCompositingMode specifica come i colori di origine vengono combinati con i colori di sfondo."
type: docs
weight: 58
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetcompositingmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusPropertyRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluspropertyrecordtype)
```
public final class EmfPlusSetCompositingMode extends EmfPlusPropertyRecordType
```

Il record EmfPlusSetCompositingMode specifica come i colori di origine vengono combinati con i colori di sfondo.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusSetCompositingMode(EmfPlusRecord source)](#EmfPlusSetCompositingMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusSetCompositingMode`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCompositingMode()](#getCompositingMode--) | Ottiene o imposta il valore della modalità di composizione, dall'enumerazione CompositingMode (sezione 2.1.1.5). |
| [setCompositingMode(byte value)](#setCompositingMode-byte-) | Ottiene o imposta il valore della modalità di composizione, dall'enumerazione CompositingMode (sezione 2.1.1.5). |
### EmfPlusSetCompositingMode(EmfPlusRecord source) {#EmfPlusSetCompositingMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetCompositingMode(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusSetCompositingMode`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getCompositingMode() {#getCompositingMode--}
```
public byte getCompositingMode()
```


Ottiene o imposta il valore della modalità di composizione, dall'enumerazione CompositingMode (sezione 2.1.1.5). La composizione può essere espressa come lo stato del blending alfa, che può essere attivo o inattivo.

Valore: La modalità di composizione.

**Returns:**
byte
### setCompositingMode(byte value) {#setCompositingMode-byte-}
```
public void setCompositingMode(byte value)
```


Ottiene o imposta il valore della modalità di composizione, dall'enumerazione CompositingMode (sezione 2.1.1.5). La composizione può essere espressa come lo stato del blending alfa, che può essere attivo o inattivo.

Valore: La modalità di composizione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

