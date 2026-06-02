---
title: "EmfCreateColorSpace"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_CREATECOLORSPACE crea un oggetto spazio colore logico da un profilo colore con un nome costituito da caratteri ASCII."
type: docs
weight: 36
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateColorSpace extends EmfObjectCreationRecordType
```

Il record EMR\_CREATECOLORSPACE crea un oggetto spazio colore logico da un profilo colore con un nome costituito da caratteri ASCII.

L'oggetto spazio colore logico definito da questo record può essere selezionato nel contesto del dispositivo di riproduzione da un record EMR\_SETCOLORSPACE (sezione 2.3.8.7), che definisce lo spazio colore logico da utilizzare nelle successive operazioni grafiche.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfCreateColorSpace(EmfRecord source)](#EmfCreateColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfCreateColorSpace`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getIhCS()](#getIhCS--) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto spazio colore logico nella tabella degli oggetti EMF (sezione 3.1.1.1). |
| [setIhCS(int value)](#setIhCS-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto spazio colore logico nella tabella degli oggetti EMF (sezione 3.1.1.1). |
| [getLcs()](#getLcs--) | Ottiene o imposta un oggetto WMF LogColorSpace ([MS-WMF] sezione 2.2.2.11), che può specificare il nome di un profilo colore in caratteri ASCII. |
| [setLcs(WmfLogColorSpace value)](#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpace-) | Ottiene o imposta un oggetto WMF LogColorSpace ([MS-WMF] sezione 2.2.2.11), che può specificare il nome di un profilo colore in caratteri ASCII. |
### EmfCreateColorSpace(EmfRecord source) {#EmfCreateColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateColorSpace(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfCreateColorSpace`.

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
public WmfLogColorSpace getLcs()
```


Ottiene o imposta un oggetto WMF LogColorSpace ([MS-WMF] sezione 2.2.2.11), che può specificare il nome di un profilo colore in caratteri ASCII.

**Returns:**
[WmfLogColorSpace](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspace)
### setLcs(WmfLogColorSpace value) {#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpace-}
```
public void setLcs(WmfLogColorSpace value)
```


Ottiene o imposta un oggetto WMF LogColorSpace ([MS-WMF] sezione 2.2.2.11), che può specificare il nome di un profilo colore in caratteri ASCII.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WmfLogColorSpace](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspace) |  |

