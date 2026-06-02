---
title: "TiffLong8Type"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il tipo TIFF senza segno a 64 bit."
type: docs
weight: 17
url: /it/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tifflong8type/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public class TiffLong8Type extends TiffCommonArrayType
```

Il tipo TIFF senza segno a 64 bit.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TiffLong8Type(int tagId)](#TiffLong8Type-int-) | Inizializza una nuova istanza della classe [TiffLong8Type](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tifflong8type). |
| [TiffLong8Type(int tagId, long[] values)](#TiffLong8Type-int-long---) | Inizializza una nuova istanza della classe [TiffLong8Type](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tifflong8type). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getValues()](#getValues--) | Ottiene i valori. |
| [setValues(long[] value)](#setValues-long---) | Imposta i valori. |
| [getValuesContainer()](#getValuesContainer--) | Ottiene il contenitore dei valori. |
| [getTagType()](#getTagType--) | Ottiene il tipo del tag. |
| [getValue()](#getValue--) | Ottiene il valore contenuto da questo tipo di dati. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Imposta il valore contenuto da questo tipo di dati. |
| [getElementSize()](#getElementSize--) | Ottiene la dimensione dell'elemento. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Scrive i dati aggiuntivi del tag. |
### TiffLong8Type(int tagId) {#TiffLong8Type-int-}
```
public TiffLong8Type(int tagId)
```


Inizializza una nuova istanza della classe [TiffLong8Type](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tifflong8type).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tagId | int | L'ID del tag. |

### TiffLong8Type(int tagId, long[] values) {#TiffLong8Type-int-long---}
```
public TiffLong8Type(int tagId, long[] values)
```


Inizializza una nuova istanza della classe [TiffLong8Type](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tifflong8type).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tagId | int | L'ID del tag. |
| valori | long[] |  |

### getValues() {#getValues--}
```
public final long[] getValues()
```


Ottiene i valori.

Valore: I valori del tag.

**Returns:**
long[] - i valori.
### setValues(long[] value) {#setValues-long---}
```
public final void setValues(long[] value)
```


Imposta i valori.

Valore: I valori del tag.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long[] | i valori. |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Ottiene il contenitore dei valori.

**Returns:**
com.aspose.ms.System.Array - contenitore dei valori.
### getTagType() {#getTagType--}
```
public int getTagType()
```


Ottiene il tipo del tag.

Valore: Il tipo di tag.

**Returns:**
int - il tipo di tag.
### getValue() {#getValue--}
```
public Object getValue()
```


Ottiene il valore contenuto da questo tipo di dati.

**Returns:**
java.lang.Object - il valore che questo tipo di dati contiene.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Imposta il valore contenuto da questo tipo di dati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object | il valore che questo tipo di dati contiene. |

### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Ottiene la dimensione dell'elemento.

**Returns:**
byte - dimensione dell'elemento.
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
