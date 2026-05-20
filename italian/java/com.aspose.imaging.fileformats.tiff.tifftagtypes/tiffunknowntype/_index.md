---
title: "TiffUnknownType"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il tipo tiff sconosciuto."
type: docs
weight: 27
url: /it/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype)
```
public final class TiffUnknownType extends TiffDataType
```

Il tipo tiff sconosciuto. Nel caso in cui il tag tiff non possa essere riconosciuto, questo tipo viene istanziato.

Nota che `TiffUnknownType` non viene serializzato nuovamente nello stream.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TiffUnknownType(TiffStreamReader stream, int tagType, int tagId, long count, long offsetOrValue)](#TiffUnknownType-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-int-int-long-long-) | Inizializza una nuova istanza della classe `TiffUnknownType`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCount()](#getCount--) | Ottiene il conteggio degli elementi. |
| [getOffsetOrValue()](#getOffsetOrValue--) | Ottiene il valore di offset per dati aggiuntivi o per il valore stesso nel caso in cui il conteggio sia 1. |
| [getStream()](#getStream--) | Ottiene lo stream da cui leggere i dati aggiuntivi. |
| [getTagType()](#getTagType--) | Ottiene il tipo del tag. |
| [getAdditionalDataSize(byte sizeOfTagValue)](#getAdditionalDataSize-byte-) | Ottiene la dimensione aggiuntiva del valore del tag in byte (nel caso in cui il tag non possa contenere l'intero valore del tag). |
| [getValue()](#getValue--) | Ottiene o imposta il valore che questo tipo di dati contiene. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Ottiene o imposta il valore che questo tipo di dati contiene. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Scrive i dati aggiuntivi del tag. |
| [toString()](#toString--) | Restituisce una `System.String` che rappresenta questa istanza. |
### TiffUnknownType(TiffStreamReader stream, int tagType, int tagId, long count, long offsetOrValue) {#TiffUnknownType-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-int-int-long-long-}
```
public TiffUnknownType(TiffStreamReader stream, int tagType, int tagId, long count, long offsetOrValue)
```


Inizializza una nuova istanza della classe `TiffUnknownType`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) | Lo stream da cui leggere. |
| tagType | int | Tipo del tag. |
| tagId | int | L'ID del tag. |
| count | long | Il valore del conteggio. |
| offsetOrValue | long | L'offset o il valore. |

### getCount() {#getCount--}
```
public long getCount()
```


Ottiene il conteggio degli elementi.

Valore: il conteggio degli elementi.

**Returns:**
long
### getOffsetOrValue() {#getOffsetOrValue--}
```
public long getOffsetOrValue()
```


Ottiene il valore di offset per dati aggiuntivi o per il valore stesso nel caso in cui il conteggio sia 1.

Valore: L'offset o il valore.

**Returns:**
long
### getStream() {#getStream--}
```
public TiffStreamReader getStream()
```


Ottiene lo stream da cui leggere i dati aggiuntivi.

Valore: Lo stream da cui leggere i dati.

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader)
### getTagType() {#getTagType--}
```
public int getTagType()
```


Ottiene il tipo del tag.

Valore: Il tipo di tag.

**Returns:**
int
### getAdditionalDataSize(byte sizeOfTagValue) {#getAdditionalDataSize-byte-}
```
public long getAdditionalDataSize(byte sizeOfTagValue)
```


Ottiene la dimensione aggiuntiva del valore del tag in byte (nel caso in cui il tag non possa contenere l'intero valore del tag).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sizeOfTagValue | byte | Dimensione del valore del tag: 4 o 8 per BigTiff. |

**Returns:**
long - La dimensione dei dati aggiuntivi in byte.
### getValue() {#getValue--}
```
public Object getValue()
```


Ottiene o imposta il valore che questo tipo di dati contiene.

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Ottiene o imposta il valore che questo tipo di dati contiene.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object |  |

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public long writeAdditionalData(TiffStreamWriter dataStream)
```


Scrive i dati aggiuntivi del tag.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) | Il flusso di dati. |

**Returns:**
long - I byte effettivamente scritti.
### toString() {#toString--}
```
public String toString()
```


Restituisce una `System.String` che rappresenta questa istanza.

**Returns:**
java.lang.String - Una `System.String` che rappresenta questa istanza.
