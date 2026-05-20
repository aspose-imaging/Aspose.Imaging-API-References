---
title: "TiffDataType"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il tipo di dati TIFF."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.fileformats.tiff/tiffdatatype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public abstract class TiffDataType implements Comparable<TiffDataType>
```

Il tipo di dati TIFF.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getElementSize()](#getElementSize--) | Ottiene la dimensione dell'elemento in byte. |
| [getDataSize()](#getDataSize--) | Ottiene la dimensione del valore del tag. |
| [getCount()](#getCount--) | Ottiene il conteggio degli elementi. |
| [getId()](#getId--) | Ottiene l'ID del tag come numero. |
| [getTagId()](#getTagId--) | Ottiene l'ID del tag. |
| [getTagType()](#getTagType--) | Ottiene il tipo del tag. |
| [getAlignedDataSize(byte sizeOfTagValue)](#getAlignedDataSize-byte-) | Ottiene la dimensione dei dati allineata a un confine di 4 byte (int) o 8 byte (long). |
| [getAdditionalDataSize(byte sizeOfTagValue)](#getAdditionalDataSize-byte-) | Ottiene la dimensione aggiuntiva del valore del tag in byte (nel caso in cui il tag non possa contenere l'intero valore del tag). |
| [getValue()](#getValue--) | Ottiene il valore contenuto da questo tipo di dati. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Imposta il valore contenuto da questo tipo di dati. |
| [isValid()](#isValid--) | Ottiene un valore che indica se i dati del tag sono validi. |
| [readTag(TiffStreamReader dataStream, long position)](#readTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-long-) | Legge i dati del tag. |
| [compareTo(TiffDataType obj)](#compareTo-com.aspose.imaging.fileformats.tiff.TiffDataType-) | Confronta l'istanza corrente con un altro oggetto dello stesso tipo e restituisce un intero che indica se l'istanza corrente precede, segue o si trova nella stessa posizione nell'ordine di ordinamento rispetto all'altro oggetto. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [deepClone()](#deepClone--) | Esegue una clonazione profonda di questa istanza. |
| [writeTag(TiffStreamWriter dataStream, long additionalDataOffset)](#writeTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-long-) | Scrive i dati del tag. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Scrive i dati aggiuntivi del tag. |
| [toString()](#toString--) | Restituisce una `System.String` che rappresenta questa istanza. |
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Ottiene la dimensione dell'elemento in byte.

**Returns:**
byte - la dimensione dell'elemento in byte.
### getDataSize() {#getDataSize--}
```
public long getDataSize()
```


Ottiene la dimensione del valore del tag.

**Returns:**
long - la dimensione del valore del tag.
### getCount() {#getCount--}
```
public abstract long getCount()
```


Ottiene il conteggio degli elementi.

Valore: il conteggio degli elementi.

**Returns:**
long - il conteggio degli elementi.
### getId() {#getId--}
```
public final int getId()
```


Ottiene l'ID del tag come numero.

**Returns:**
int - ID del tag come numero.
### getTagId() {#getTagId--}
```
public int getTagId()
```


Ottiene l'ID del tag.

**Returns:**
int - L'ID del tag.
### getTagType() {#getTagType--}
```
public abstract int getTagType()
```


Ottiene il tipo del tag.

**Returns:**
int - Il tipo di tag.
### getAlignedDataSize(byte sizeOfTagValue) {#getAlignedDataSize-byte-}
```
public final long getAlignedDataSize(byte sizeOfTagValue)
```


Ottiene la dimensione dei dati allineata a un confine di 4 byte (int) o 8 byte (long).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sizeOfTagValue | byte | Dimensione del valore del tag. |

**Returns:**
long - La dimensione dei dati allineati in byte.
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
public abstract Object getValue()
```


Ottiene il valore contenuto da questo tipo di dati.

**Returns:**
java.lang.Object - Il valore.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Imposta il valore contenuto da questo tipo di dati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object | Il valore. |

### isValid() {#isValid--}
```
public boolean isValid()
```


Ottiene un valore che indica se i dati del tag sono validi. Il tag valido contiene dati che possono essere conservati. Il tag non valido non può essere memorizzato.

**Returns:**
boolean - `true` se i dati del tag sono validi; altrimenti, `false`.
### readTag(TiffStreamReader dataStream, long position) {#readTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-long-}
```
public static TiffDataType readTag(TiffStreamReader dataStream, long position)
```


Legge i dati del tag.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dataStream | [TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) | Il flusso di dati. |
| position | long | La posizione del tag. |

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - The read tag.
### compareTo(TiffDataType obj) {#compareTo-com.aspose.imaging.fileformats.tiff.TiffDataType-}
```
public int compareTo(TiffDataType obj)
```


Confronta l'istanza corrente con un altro oggetto dello stesso tipo e restituisce un intero che indica se l'istanza corrente precede, segue o si trova nella stessa posizione nell'ordine di ordinamento rispetto all'altro oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | [TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Un oggetto da confrontare con questa istanza. |

**Returns:**
int - Un intero con segno a 32 bit che indica l'ordine relativo degli oggetti confrontati. Il valore restituito ha questi significati: Valore Significato Meno di zero Questa istanza è minore di `obj`. Zero Questa istanza è uguale a `obj`. Maggiore di zero Questa istanza è maggiore di `obj`.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### deepClone() {#deepClone--}
```
public TiffDataType deepClone()
```


Esegue una clonazione profonda di questa istanza.

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - A deep clone of the current instance.
### writeTag(TiffStreamWriter dataStream, long additionalDataOffset) {#writeTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-long-}
```
public void writeTag(TiffStreamWriter dataStream, long additionalDataOffset)
```


Scrive i dati del tag.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) | Il flusso di dati. |
| additionalDataOffset | long | L'offset a cui scrivere i dati aggiuntivi. |

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public abstract long writeAdditionalData(TiffStreamWriter dataStream)
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
