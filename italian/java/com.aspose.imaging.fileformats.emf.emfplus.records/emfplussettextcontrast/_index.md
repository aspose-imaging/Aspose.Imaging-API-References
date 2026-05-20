---
title: "EmfPlusSetTextContrast"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusSetTextContrast specifica il contrasto del testo in base al valore di correzione gamma."
type: docs
weight: 64
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussettextcontrast/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusPropertyRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluspropertyrecordtype)
```
public final class EmfPlusSetTextContrast extends EmfPlusPropertyRecordType
```

Il record EmfPlusSetTextContrast specifica il contrasto del testo in base al valore di correzione gamma.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusSetTextContrast(EmfPlusRecord source)](#EmfPlusSetTextContrast-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusSetTextContrast`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTextContrast()](#getTextContrast--) | Ottiene o imposta il valore di correzione gamma X 1000, che sarà applicato alle successive operazioni di rendering del testo. |
| [setTextContrast(short value)](#setTextContrast-short-) | Ottiene o imposta il valore di correzione gamma X 1000, che sarà applicato alle successive operazioni di rendering del testo. |
### EmfPlusSetTextContrast(EmfPlusRecord source) {#EmfPlusSetTextContrast-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetTextContrast(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusSetTextContrast`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getTextContrast() {#getTextContrast--}
```
public short getTextContrast()
```


Ottiene o imposta il valore di correzione gamma X 1000, che sarà applicato alle successive operazioni di rendering del testo. L'intervallo consentito è da 1000 a 2200, rappresentando valori gamma del testo da 1.0 a 2.2.

**Returns:**
short
### setTextContrast(short value) {#setTextContrast-short-}
```
public void setTextContrast(short value)
```


Ottiene o imposta il valore di correzione gamma X 1000, che sarà applicato alle successive operazioni di rendering del testo. L'intervallo consentito è da 1000 a 2200, rappresentando valori gamma del testo da 1.0 a 2.2.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

