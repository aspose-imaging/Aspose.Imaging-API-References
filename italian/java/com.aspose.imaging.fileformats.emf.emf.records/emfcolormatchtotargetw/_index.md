---
title: "EmfColorMatchToTargetW"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_COLORMATCHTOTargetW specifica se eseguire l'abbinamento colore con un profilo colore specificato in un file il cui nome è composto da caratteri Unicode."
type: docs
weight: 24
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfColorMatchToTargetW extends EmfStateRecordType
```

Il record EMR\_COLORMATCHTOTargetW specifica se eseguire l'abbinamento colore con un profilo colore specificato in un file il cui nome è composto da caratteri Unicode.

Un record EMR\_COLORMATCHTOTargetW può essere usato per controllare se applicare la trasformazione colore corrente nel contesto del dispositivo di riproduzione. Se il valore dwAction è CS\_ENABLE, la mappatura colore è abilitata e la trasformazione colore corrente DEVE essere applicata alle operazioni grafiche successive. Se dwAction è impostato a CS\_DISABLE, la trasformazione colore NON DEVE essere applicata. Mentre la mappatura colore verso il bersaglio è abilitata da un valore dwAction di CS\_ENABLE, le modifiche allo spazio colore o alla mappatura del gamut colore non vengono applicate. Tuttavia, tali modifiche DEVONO avere effetto quando la mappatura colore verso il bersaglio è disabilitata. Il campo dwAction NON DEVE essere impostato a CS\_DELETE\_TRANSFORM a meno che la gestione del colore non sia già stata abilitata con un record EMR\_SETICMMODE (sezione 2.3.11.14).
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfColorMatchToTargetW(EmfRecord source)](#EmfColorMatchToTargetW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfColorMatchToTargetW`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDwAction()](#getDwAction--) | Ottiene o imposta un intero senza segno a 32 bit che specifica un valore dell'enumerazione ColorSpace (sezione 2.1.7). |
| [setDwAction(int value)](#setDwAction-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica un valore dell'enumerazione ColorSpace (sezione 2.1.7). |
| [getDwFlags()](#getDwFlags--) | Ottiene o imposta un intero senza segno a 32 bit che specifica un valore dell'enumerazione ColorMatchToTarget (sezione 2.1.6). |
| [setDwFlags(int value)](#setDwFlags-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica un valore dell'enumerazione ColorMatchToTarget (sezione 2.1.6). |
| [getCbName()](#getCbName--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di byte nel nome Unicode UTF16-LE del profilo colore desiderato. |
| [setCbName(int value)](#setCbName-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di byte nel nome Unicode UTF16-LE del profilo colore desiderato. |
| [getCbData()](#getCbData--) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione dei dati grezzi del profilo colore di destinazione, se contenuti nel campo Data. |
| [setCbData(int value)](#setCbData-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione dei dati grezzi del profilo colore di destinazione, se contenuti nel campo Data. |
| [getData()](#getData--) | Ottiene o imposta un array di dimensione (cbName + cbData) in byte, che specifica il nome UTF16-LE e i dati grezzi del profilo colore desiderato. |
| [setData(byte[] value)](#setData-byte---) | Ottiene o imposta un array di dimensione (cbName + cbData) in byte, che specifica il nome UTF16-LE e i dati grezzi del profilo colore desiderato. |
| [getName()](#getName--) | Ottiene il nome |
| [getRawData()](#getRawData--) | Ottiene i dati grezzi |
### EmfColorMatchToTargetW(EmfRecord source) {#EmfColorMatchToTargetW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfColorMatchToTargetW(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfColorMatchToTargetW`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### getDwAction() {#getDwAction--}
```
public int getDwAction()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica un valore dell'enumerazione ColorSpace (sezione 2.1.7).

**Returns:**
int
### setDwAction(int value) {#setDwAction-int-}
```
public void setDwAction(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica un valore dell'enumerazione ColorSpace (sezione 2.1.7).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica un valore dell'enumerazione ColorMatchToTarget (sezione 2.1.6).

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica un valore dell'enumerazione ColorMatchToTarget (sezione 2.1.6).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCbName() {#getCbName--}
```
public int getCbName()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di byte nel nome Unicode UTF16-LE del profilo colore desiderato.

**Returns:**
int
### setCbName(int value) {#setCbName-int-}
```
public void setCbName(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di byte nel nome Unicode UTF16-LE del profilo colore desiderato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione dei dati grezzi del profilo colore di destinazione, se contenuti nel campo Data.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione dei dati grezzi del profilo colore di destinazione, se contenuti nel campo Data.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Ottiene o imposta un array di dimensione (cbName + cbData) in byte, che specifica il nome UTF16-LE e i dati grezzi del profilo colore desiderato.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Ottiene o imposta un array di dimensione (cbName + cbData) in byte, che specifica il nome UTF16-LE e i dati grezzi del profilo colore desiderato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### getName() {#getName--}
```
public String getName()
```


Ottiene il nome

**Returns:**
java.lang.String
### getRawData() {#getRawData--}
```
public byte[] getRawData()
```


Ottiene i dati grezzi

**Returns:**
byte[]
