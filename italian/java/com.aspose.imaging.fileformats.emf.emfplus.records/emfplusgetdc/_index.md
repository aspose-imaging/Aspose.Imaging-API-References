---
title: "EmfPlusGetDc"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusGetDC specifica che i record EMF successivi incontrati nel metafile DEVONO essere elaborati."
type: docs
weight: 39
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusgetdc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusControlRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluscontrolrecordtype)
```
public final class EmfPlusGetDc extends EmfPlusControlRecordType
```

Il record EmfPlusGetDC specifica che i record EMF successivi incontrati nel metafile DEVONO essere elaborati.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusGetDc(EmfPlusRecord source)](#EmfPlusGetDc-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusGetDc`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFlags()](#getFlags--) | Ottiene o imposta un intero senza segno a 16 bit che non è utilizzato. |
| [setFlags(short value)](#setFlags-short-) | Ottiene o imposta un intero senza segno a 16 bit che non è utilizzato. |
### EmfPlusGetDc(EmfPlusRecord source) {#EmfPlusGetDc-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusGetDc(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusGetDc`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getFlags() {#getFlags--}
```
public short getFlags()
```


Ottiene o imposta un intero senza segno a 16 bit che non è utilizzato. Questo campo DOVREBBE essere impostato a zero e DEVE essere ignorato al ricevimento.

**Returns:**
short
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


Ottiene o imposta un intero senza segno a 16 bit che non è utilizzato. Questo campo DOVREBBE essere impostato a zero e DEVE essere ignorato al ricevimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

