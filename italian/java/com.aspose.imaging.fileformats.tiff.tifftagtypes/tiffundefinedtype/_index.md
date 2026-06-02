---
title: "TiffUndefinedType"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il tipo tiff undefined."
type: docs
weight: 26
url: /it/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffundefinedtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype)
```
public class TiffUndefinedType extends TiffDataType
```

Il tipo tiff undefined.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TiffUndefinedType(int tagId)](#TiffUndefinedType-int-) | Inizializza una nuova istanza della classe `TiffUndefinedType`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getData()](#getData--) | Ottiene o imposta i dati. |
| [setData(byte[] value)](#setData-byte---) | Ottiene o imposta i dati. |
| [getCount()](#getCount--) | Ottiene il conteggio degli elementi. |
| [getTagType()](#getTagType--) | Ottiene il tipo del tag. |
| [getValue()](#getValue--) | Ottiene o imposta il valore che questo tipo di dati contiene. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Ottiene o imposta il valore che questo tipo di dati contiene. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Scrive i dati aggiuntivi del tag. |
### TiffUndefinedType(int tagId) {#TiffUndefinedType-int-}
```
public TiffUndefinedType(int tagId)
```


Inizializza una nuova istanza della classe `TiffUndefinedType`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tagId | int | L'ID del tag. |

### getData() {#getData--}
```
public byte[] getData()
```


Ottiene o imposta i dati.

Valore: I dati.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Ottiene o imposta i dati.

Valore: I dati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### getCount() {#getCount--}
```
public long getCount()
```


Ottiene il conteggio degli elementi.

Valore: il conteggio degli elementi.

**Returns:**
long
### getTagType() {#getTagType--}
```
public int getTagType()
```


Ottiene il tipo del tag.

Valore: Il tipo di tag.

**Returns:**
int
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
