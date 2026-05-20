---
title: "EmfCreateColorSpaceW"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_CREATECOLORSPACEW crea un oggetto spazio colore logico da un profilo colore con un nome costituito da caratteri Unicode."
type: docs
weight: 37
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateColorSpaceW extends EmfObjectCreationRecordType
```

Il record EMR\_CREATECOLORSPACEW crea un oggetto spazio colore logico da un profilo colore con un nome costituito da caratteri Unicode.

L'oggetto spazio colore logico definito da questo record può essere selezionato nel contesto del dispositivo di riproduzione da un record EMR\_SETCOLORSPACE (sezione 2.3.8.7), che definisce lo spazio colore logico da utilizzare nelle successive operazioni grafiche.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfCreateColorSpaceW(EmfRecord source)](#EmfCreateColorSpaceW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfCreateColorSpaceW`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getIhCS()](#getIhCS--) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto spazio colore logico nella tabella degli oggetti EMF (sezione 3.1.1.1). |
| [setIhCS(int value)](#setIhCS-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto spazio colore logico nella tabella degli oggetti EMF (sezione 3.1.1.1). |
| [getLcs()](#getLcs--) | Ottiene o imposta un oggetto WMF LogColorSpaceW ([MS-WMF] sezione 2.2.2.12) che può specificare il nome di un profilo colore in caratteri Unicode UTF16-LE |
| [setLcs(WmfLogColorSpaceW value)](#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpaceW-) | Ottiene o imposta un oggetto WMF LogColorSpaceW ([MS-WMF] sezione 2.2.2.12) che può specificare il nome di un profilo colore in caratteri Unicode UTF16-LE |
| [getDwFlags()](#getDwFlags--) | Ottiene o imposta un intero senza segno a 32 bit che fornisce informazioni sui dati in questo record. |
| [setDwFlags(int value)](#setDwFlags-int-) | Ottiene o imposta un intero senza segno a 32 bit che fornisce informazioni sui dati in questo record. |
| [getCbData()](#getCbData--) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione, in byte, del campo Data. |
| [setCbData(int value)](#setCbData-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione, in byte, del campo Data. |
| [getData()](#getData--) | Ottiene o imposta un array opzionale di byte che specifica i dati del profilo colore. |
| [setData(byte[] value)](#setData-byte---) | Ottiene o imposta un array opzionale di byte che specifica i dati del profilo colore. |
### EmfCreateColorSpaceW(EmfRecord source) {#EmfCreateColorSpaceW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateColorSpaceW(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfCreateColorSpaceW`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### getIhCS() {#getIhCS--}
```
public int getIhCS()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto spazio colore logico nella tabella degli oggetti EMF (sezione 3.1.1.1). Questo indice DEVE essere salvato affinché l'oggetto possa essere riutilizzato o modificato.

**Returns:**
int
### setIhCS(int value) {#setIhCS-int-}
```
public void setIhCS(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto spazio colore logico nella tabella degli oggetti EMF (sezione 3.1.1.1). Questo indice DEVE essere salvato affinché l'oggetto possa essere riutilizzato o modificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getLcs() {#getLcs--}
```
public WmfLogColorSpaceW getLcs()
```


Ottiene o imposta un oggetto WMF LogColorSpaceW ([MS-WMF] sezione 2.2.2.12) che può specificare il nome di un profilo colore in caratteri Unicode UTF16-LE

**Returns:**
[WmfLogColorSpaceW](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew)
### setLcs(WmfLogColorSpaceW value) {#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpaceW-}
```
public void setLcs(WmfLogColorSpaceW value)
```


Ottiene o imposta un oggetto WMF LogColorSpaceW ([MS-WMF] sezione 2.2.2.12) che può specificare il nome di un profilo colore in caratteri Unicode UTF16-LE

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WmfLogColorSpaceW](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew) |  |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


Ottiene o imposta un intero senza segno a 32 bit che fornisce informazioni sui dati in questo record.

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che fornisce informazioni sui dati in questo record.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione, in byte, del campo Data.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione, in byte, del campo Data.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Ottiene o imposta un array opzionale di byte che specifica i dati del profilo colore.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Ottiene o imposta un array opzionale di byte che specifica i dati del profilo colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

