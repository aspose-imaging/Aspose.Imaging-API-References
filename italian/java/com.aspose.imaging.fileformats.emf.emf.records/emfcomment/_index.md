---
title: "EmfComment"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_COMMENT contiene dati privati arbitrari."
type: docs
weight: 25
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfcomment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public final class EmfComment extends EmfCommentRecordType
```

Il record EMR\_COMMENT contiene dati privati arbitrari. Nota: i campi non descritti in questa sezione sono specificati nella sezione 2.3.3.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfComment(EmfRecord source)](#EmfComment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfComment`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPrivateData()](#getPrivateData--) | Ottiene o imposta un array opzionale di byte che specifica i dati privati. |
| [setPrivateData(byte[] value)](#setPrivateData-byte---) | Ottiene o imposta un array opzionale di byte che specifica i dati privati. |
| [getCommentIdentifier()](#getCommentIdentifier--) | Ottiene o imposta l'identificatore del commento. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Ottiene o imposta l'identificatore del commento. |
### EmfComment(EmfRecord source) {#EmfComment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfComment(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfComment`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### getPrivateData() {#getPrivateData--}
```
public byte[] getPrivateData()
```


Ottiene o imposta un array opzionale di byte che specifica i dati privati. Il primo DWORD di questi dati NON DEVE essere uno dei valori predefiniti dell'identificatore del commento specificati nella sezione 2.3.3. I dati privati sono sconosciuti a EMF; hanno senso solo per le applicazioni che conoscono il formato dei dati e come usarli. I record di dati privati EMR\_COMMENT POSSONO essere ignorati.

**Returns:**
byte[]
### setPrivateData(byte[] value) {#setPrivateData-byte---}
```
public void setPrivateData(byte[] value)
```


Ottiene o imposta un array opzionale di byte che specifica i dati privati. Il primo DWORD di questi dati NON DEVE essere uno dei valori predefiniti dell'identificatore del commento specificati nella sezione 2.3.3. I dati privati sono sconosciuti a EMF; hanno senso solo per le applicazioni che conoscono il formato dei dati e come usarli. I record di dati privati EMR\_COMMENT POSSONO essere ignorati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Ottiene o imposta l'identificatore del commento.

Valore: l'identificatore del commento.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Ottiene o imposta l'identificatore del commento.

Valore: l'identificatore del commento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

