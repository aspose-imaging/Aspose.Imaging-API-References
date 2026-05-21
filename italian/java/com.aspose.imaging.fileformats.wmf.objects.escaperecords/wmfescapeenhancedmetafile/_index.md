---
title: "WmfEscapeEnhancedMetafile"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record Escape Enhanced Meta file."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.fileformats.wmf.objects.escaperecords/wmfescapeenhancedmetafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.escaperecords.WmfEscapeRecordBase](../../com.aspose.imaging.fileformats.wmf.objects.escaperecords/wmfescaperecordbase)
```
public class WmfEscapeEnhancedMetafile extends WmfEscapeRecordBase
```

Il record Escape Enhanced Meta file.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WmfEscapeEnhancedMetafile()](#WmfEscapeEnhancedMetafile--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Ottiene o imposta l'identificatore del commento. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Ottiene o imposta l'identificatore del commento. |
| [getCommentType()](#getCommentType--) | Ottiene o imposta il tipo del commento. |
| [setCommentType(int value)](#setCommentType-int-) | Ottiene o imposta il tipo del commento. |
| [getVersion()](#getVersion--) | Ottiene o imposta la versione. |
| [setVersion(int value)](#setVersion-int-) | Ottiene o imposta la versione. |
| [getChecksum()](#getChecksum--) | Ottiene o imposta il checksum. |
| [setChecksum(int value)](#setChecksum-int-) | Ottiene o imposta il checksum. |
| [getFlags()](#getFlags--) | Ottiene o imposta le flag. |
| [setFlags(int value)](#setFlags-int-) | Ottiene o imposta le flag. |
| [getCommentRecordCount()](#getCommentRecordCount--) | Ottiene o imposta il conteggio dei record di commento. |
| [setCommentRecordCount(int value)](#setCommentRecordCount-int-) | Ottiene o imposta il conteggio dei record di commento. |
| [getCurrentRecordSize()](#getCurrentRecordSize--) | Ottiene o imposta la dimensione del record corrente. |
| [setCurrentRecordSize(int value)](#setCurrentRecordSize-int-) | Ottiene o imposta la dimensione del record corrente. |
| [getRemainingBytes()](#getRemainingBytes--) | Ottiene o imposta i byte rimanenti. |
| [setRemainingBytes(int value)](#setRemainingBytes-int-) | Ottiene o imposta i byte rimanenti. |
| [getEnhancedMetafileDataSize()](#getEnhancedMetafileDataSize--) | Ottiene o imposta la dimensione dei dati del metafile migliorato. |
| [setEnhancedMetafileDataSize(int value)](#setEnhancedMetafileDataSize-int-) | Ottiene o imposta la dimensione dei dati del metafile migliorato. |
| [getEnhancedMetafileData()](#getEnhancedMetafileData--) | Ottiene o imposta i dati del metafile migliorato. |
| [setEnhancedMetafileData(byte[] value)](#setEnhancedMetafileData-byte---) | Ottiene o imposta i dati del metafile migliorato. |
### WmfEscapeEnhancedMetafile() {#WmfEscapeEnhancedMetafile--}
```
public WmfEscapeEnhancedMetafile()
```


### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Ottiene o imposta l'identificatore del commento.

Valore: Un intero senza segno a 32 bit che definisce questo record come un record di commento WMF. Questo valore DEVE essere 0x43464D57.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Ottiene o imposta l'identificatore del commento.

Valore: Un intero senza segno a 32 bit che definisce questo record come un record di commento WMF. Questo valore DEVE essere 0x43464D57.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCommentType() {#getCommentType--}
```
public int getCommentType()
```


Ottiene o imposta il tipo del commento.

Valore: Un intero senza segno a 32 bit che identifica il tipo di commento in questo record. Questo valore DEVE essere 0x00000001.

**Returns:**
int
### setCommentType(int value) {#setCommentType-int-}
```
public void setCommentType(int value)
```


Ottiene o imposta il tipo del commento.

Valore: Un intero senza segno a 32 bit che identifica il tipo di commento in questo record. Questo valore DEVE essere 0x00000001.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Ottiene o imposta la versione.

Valore: Un intero senza segno a 32 bit che specifica l'interoperabilità del metafile EMF. Questo DOVREBBE essere 0x00010000.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Ottiene o imposta la versione.

Valore: Un intero senza segno a 32 bit che specifica l'interoperabilità del metafile EMF. Questo DOVREBBE essere 0x00010000.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getChecksum() {#getChecksum--}
```
public int getChecksum()
```


Ottiene o imposta il checksum.

Valore: Un intero senza segno a 16 bit usato per convalidare la correttezza del flusso EMF incorporato. Questo valore DEVE essere il complemento a uno del risultato dell'applicazione di un'operazione XOR a tutte le WORD nel flusso EMF.

**Returns:**
int
### setChecksum(int value) {#setChecksum-int-}
```
public void setChecksum(int value)
```


Ottiene o imposta il checksum.

Valore: Un intero senza segno a 16 bit usato per convalidare la correttezza del flusso EMF incorporato. Questo valore DEVE essere il complemento a uno del risultato dell'applicazione di un'operazione XOR a tutte le WORD nel flusso EMF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getFlags() {#getFlags--}
```
public int getFlags()
```


Ottiene o imposta le flag.

Valore: Questo intero senza segno a 32 bit non è utilizzato e DEVE essere impostato a zero.

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Ottiene o imposta le flag.

Valore: Questo intero senza segno a 32 bit non è utilizzato e DEVE essere impostato a zero.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCommentRecordCount() {#getCommentRecordCount--}
```
public int getCommentRecordCount()
```


Ottiene o imposta il conteggio dei record di commento.

Valore: Un intero senza segno a 32 bit che specifica il numero totale di record consecutivi META\_ESCAPE\_ENHANCED\_METAFILE che contengono il metafile EMF incorporato.

**Returns:**
int
### setCommentRecordCount(int value) {#setCommentRecordCount-int-}
```
public void setCommentRecordCount(int value)
```


Ottiene o imposta il conteggio dei record di commento.

Valore: Un intero senza segno a 32 bit che specifica il numero totale di record consecutivi META\_ESCAPE\_ENHANCED\_METAFILE che contengono il metafile EMF incorporato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCurrentRecordSize() {#getCurrentRecordSize--}
```
public int getCurrentRecordSize()
```


Ottiene o imposta la dimensione del record corrente.

Valore: Un intero senza segno a 32 bit che specifica la dimensione, in byte, del campo EnhancedMetafileData. Questo valore DEVE essere minore o uguale a 8.192.

**Returns:**
int
### setCurrentRecordSize(int value) {#setCurrentRecordSize-int-}
```
public void setCurrentRecordSize(int value)
```


Ottiene o imposta la dimensione del record corrente.

Valore: Un intero senza segno a 32 bit che specifica la dimensione, in byte, del campo EnhancedMetafileData. Questo valore DEVE essere minore o uguale a 8.192.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getRemainingBytes() {#getRemainingBytes--}
```
public int getRemainingBytes()
```


Ottiene o imposta i byte rimanenti.

Valore: Un intero senza segno a 32 bit che specifica il numero di byte nel flusso EMF che rimangono da elaborare dopo questo record. Quei byte EMF aggiuntivi DEVONO seguire nei campi EnhancedMetafileData dei successivi record di escape META\_ESCAPE\_ENHANDED\_METAFILE.

**Returns:**
int
### setRemainingBytes(int value) {#setRemainingBytes-int-}
```
public void setRemainingBytes(int value)
```


Ottiene o imposta i byte rimanenti.

Valore: Un intero senza segno a 32 bit che specifica il numero di byte nel flusso EMF che rimangono da elaborare dopo questo record. Quei byte EMF aggiuntivi DEVONO seguire nei campi EnhancedMetafileData dei successivi record di escape META\_ESCAPE\_ENHANDED\_METAFILE.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getEnhancedMetafileDataSize() {#getEnhancedMetafileDataSize--}
```
public int getEnhancedMetafileDataSize()
```


Ottiene o imposta la dimensione dei dati del metafile migliorato.

Valore: Un intero senza segno a 32 bit che specifica la dimensione totale del flusso EMF incorporato in questa sequenza di record META\_ESCAPE\_ENHANCED\_METAFILE.

**Returns:**
int
### setEnhancedMetafileDataSize(int value) {#setEnhancedMetafileDataSize-int-}
```
public void setEnhancedMetafileDataSize(int value)
```


Ottiene o imposta la dimensione dei dati del metafile migliorato.

Valore: Un intero senza segno a 32 bit che specifica la dimensione totale del flusso EMF incorporato in questa sequenza di record META\_ESCAPE\_ENHANCED\_METAFILE.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getEnhancedMetafileData() {#getEnhancedMetafileData--}
```
public byte[] getEnhancedMetafileData()
```


Ottiene o imposta i dati del metafile migliorato.

Valore: Un segmento di un file EMF. I byte nei record consecutivi META\_ESCAPE\_ENHANCED\_METAFILE DEVONO essere concatenati per rappresentare l'intero file EMF incorporato.

**Returns:**
byte[]
### setEnhancedMetafileData(byte[] value) {#setEnhancedMetafileData-byte---}
```
public void setEnhancedMetafileData(byte[] value)
```


Ottiene o imposta i dati del metafile migliorato.

Valore: Un segmento di un file EMF. I byte nei record consecutivi META\_ESCAPE\_ENHANCED\_METAFILE DEVONO essere concatenati per rappresentare l'intero file EMF incorporato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

