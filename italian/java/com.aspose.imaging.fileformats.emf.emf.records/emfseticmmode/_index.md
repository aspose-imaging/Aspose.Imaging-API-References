---
title: "EmfSetIcmMode"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_SETICMMODE specifica la modalità di Image Color Management (ICM) per le operazioni grafiche."
type: docs
weight: 125
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfseticmmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetIcmMode extends EmfStateRecordType
```

Il record EMR\_SETICMMODE specifica la modalità di Image Color Management (ICM) per le operazioni grafiche.

Quando la modalità ICM è abilitata, i colori specificati nei record EMF DEVONO essere abbinati a un profilo colore, mentre il profilo colore predefinito nel contesto del dispositivo di riproduzione DEVE essere utilizzato quando viene eseguito un trasferimento bit‑block. Se il profilo colore predefinito non è desiderato, la modalità ICM DEVE essere disattivata prima di eseguire il trasferimento bit‑block.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfSetIcmMode(EmfRecord source)](#EmfSetIcmMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfSetIcmMode`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getIcmMode()](#getIcmMode--) | Ottiene o imposta un intero senza segno a 32 bit che specifica se abilitare o disabilitare ICM, dall'enumerazione ICMMode (sezione 2.1.18). |
| [setIcmMode(int value)](#setIcmMode-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica se abilitare o disabilitare ICM, dall'enumerazione ICMMode (sezione 2.1.18). |
### EmfSetIcmMode(EmfRecord source) {#EmfSetIcmMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetIcmMode(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfSetIcmMode`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### getIcmMode() {#getIcmMode--}
```
public int getIcmMode()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica se abilitare o disabilitare ICM, dall'enumerazione ICMMode (sezione 2.1.18). Questo valore fa parte dello stato del contesto del dispositivo di riproduzione.

**Returns:**
int
### setIcmMode(int value) {#setIcmMode-int-}
```
public void setIcmMode(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica se abilitare o disabilitare ICM, dall'enumerazione ICMMode (sezione 2.1.18). Questo valore fa parte dello stato del contesto del dispositivo di riproduzione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

